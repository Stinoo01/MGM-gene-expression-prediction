# Multilayer Graph Model for Gene Expression Classification from Epigenomic Data

This repository contains the code for a multilayer graph-based framework to predict gene expression from histone modification data.

## System Requirements

### Operating System

The model was developed and tested on a machine running **Windows 11**.

Training was performed on a system equipped with a 12th Gen Intel(R) Core(TM) i7-12700H @ 2.30 GHz CPU and 16 GB of RAM.

To reproduce other pipelines, please refer to the respective system requirements.

### Python Packages

The model was trained and tested using **Python 3.12.3** with the following package versions:

- `numpy`: 1.26.4  
- `pandas`: 2.2.2  
- `matplotlib`: 3.9.2  
- `seaborn`: 0.13.2  
- `scikit-learn`: 1.5.1  
- `xgboost`: 3.0.0  
- `lightgbm`: 4.6.0  
- `torch`: 2.7.0+cpu  
- `statsmodels`: 0.14.2  
- `mygene`: 3.2.2

## Replicating the Experiments

Pre-processed data can be downloaded from the following [link](https://drive.google.com/drive/folders/1O4oE5gS5j4Jx9Y0D_gjBhJ2ppOAOoZy6).

The experiments reported in the manuscript can be replicated using the `demo.ipynb` notebook.

## Training from Scratch

The full training pipeline is available in the `pipeline.ipynb` notebook, which allows training the model from raw data and applying it to new datasets.
