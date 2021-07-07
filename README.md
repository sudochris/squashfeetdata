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
    
    @Article{Brumann2021,
        AUTHOR         = {Brumann, Christopher and Kukuk, Markus and Reinsberger, Claus},
        TITLE          = {Evaluation of Open-Source and Pre-Trained Deep Convolutional Neural Networks Suitable for Player Detection and Motion Analysis in Squash},
        JOURNAL        = {Sensors},
        VOLUME         = {21},
        YEAR           = {2021},
        NUMBER         = {13},
        ARTICLE-NUMBER = {4550},
        URL            = {https://www.mdpi.com/1424-8220/21/13/4550},
        ISSN           = {1424-8220},
        DOI            = {10.3390/s21134550}
    }
