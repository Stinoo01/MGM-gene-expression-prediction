# Multilayer Graph Modeling of gene expression data

Repository for the Master Thesis 2024/2025 (Data Science, Sapienza University of Rome). 

This project contains the code for a multilayer graph-based framework to predict gene expression from histone modification data.

## System Requirements

### Operating system 

For the model it was used a `Windows 11`  operating systems.

The model was trained using a computer with 12th Gen Intel(R) Core(TM) i7-12700H @ 2.3 GHz CPU, 16,0 GB of RAM.

To replicate any other pipeline, please refer to the respective system requirements.

### Python packages

The model was trained and tested using `Python 3.12.3` with the following packages versions:

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

## Replicatig the experiment

You can download alrady pre-processed data at this [link](https://drive.google.com/drive/folders/1O4oE5gS5j4Jx9Y0D_gjBhJ2ppOAOoZy6?usp=sharing) and replicate the experiments using the `demo` notebook.

## Training from scratch 

You can train from scratch the model and apply to new data using the `pipeline` notebook available in this repository. 


