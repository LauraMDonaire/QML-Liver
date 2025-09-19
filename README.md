# QML-Liver: Liver Disease Detection with Hybrid Quantum Machine Learning

This repository contains the resources used and generated during the development of the project on liver disease detection using a hybrid quantum-classical architecture.  

## Repository structure  

- `model-notebook/`  
  - `model_with_2_qubits.ipynb`: Jupyter Notebook with the training and evaluation.  
  - `model.h5`: Trained model.  
  - `weights.h5`: Model weights.  
- `data/`  
  - `preprocessed_dataset.csv`: Dataset already preprocessed and ready to use.
  - `Indian Liver Patient Dataset.csv`: Original dataset. 
- `results/`  
  - `roc_curve.pdf`: ROC curve of the model.
  - `confusion_matrix.pdf`: Confusion matrix.  
  - `architecture.pdf`: Neural network architecture.  

## Requirements  

- Python 3.9+  
- pandas == 2.2.4
- numpy == 1.23.5
- pennylane == 0.40.0
- tensorflow == 2.14.0
- keras-tuner == 1.4.7
- sklearn == 1.7.1
