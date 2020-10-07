![logo](logo.png)
![license](https://img.shields.io/badge/License-GPLV3-green)

## Dataset and results from "Evaluation of pre-trained and open-source deep convolutional neural networks suitable for player detection and motion analysis in squash"

This dataset contains labeled data of four videos for player feet in squash. Beside the hand labeled data, detections obtained from different deep convolutional neural networks are included.

### Folder Structure
```
- <DATA_NAME>
    - algorithms
        - arttrack   [ json-files for arttrack (A0) detections             ]
        - openpose
            - body25 [ json-files for body25 (A1F0) detections             ]
            - coco   [ json-files for coco (A1F1) detections               ]
            - mpi    [ json-files for mpii (A1F2) detections               ]
        - posenet    [ json-file for posenet (A2) detection                ]
    - annotation     [ annotation and events file, annotated labels        ]
    - npz            [ Numpy arrays for calibration, court definition, ... ]
    - results        [ Contains results discussed in the paper             ]
```

In general there is `dataset_description.json`, which contains links and
format specifier for every single element inside the dataset.

### Citation
Please cite in your publications if it helps your research:
    
    TBA: BibTeX Entry  

TBA: [link to paper]()