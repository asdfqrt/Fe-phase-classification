# Fe phase classification

Pytorch implementation of Phase classification of high carbon steel using pre-trained CNN model.
This project is still in progress, but still shows decent classification capabilites.

## Environmnet
- Python3
- Pytorch

## Getting stared
### Dataset
Place your Micrograph dataset in proper path

    Fe phase classification
    ├── data
    │    └── For Training
    │         ├── sample_train
    │         │    ├── xxx.png
    │         │    ├── yyy.png
    │         │    └── ...
    │         ├── sample_test
    │         │    ├── aaa.png
    │         │    ├── bbb.png
    │         │    └── ...
    │         └── metadata.csv
    └── Resnet_classification.py

metadata.csv must contain "path" and "primary_microconstituent" values of dataset

Or, you can just use sameple files in this repository for quick testing

## Train
Run

    $ python
    
## Test
Run

    $ python

## Result
Some fancy image descriptions

* The classification result will be recored in /data/results.csv

## References
- Dataset: [UHCSDB: UltraHigh Carbon Steel Micrograph DataBase](https://www.kaggle.com/datasets/safi842/highcarbon-micrographs)