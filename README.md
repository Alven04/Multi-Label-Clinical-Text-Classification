# Multi Label Clinical Text Classification
Overview
This project aims to perform multi-label classification on clinical text data from the MIMIC-III dataset, specifically focusing on Discharge Summary notes. The goal is to predict multiple medical codes (ICD-9 codes) associated with each clinical note.

## Dataset
- MIMIC-III: The Medical Information Mart for Intensive Care (MIMIC-III) is a publicly available dataset containing de-identified health-related data associated with over 40,000 patients who stayed in critical care units of the Beth Israel Deaconess Medical Center between 2001 and 2012.

## Approach
- Data Preprocessing: Discharge Summary notes are preprocessed to remove noise, tokenize the text, and convert it into a format suitable for modeling.

## Model Architecture: 
- Various deep learning architectures such as Convolutional Neural Networks (CNNs), Bidirectional LSTMs, or their combinations are explored to build a robust multi-label classification model.

## Evaluation: The model is evaluated based on metrics such as accuracy, precision, recall, F1-score, and Hamming loss.

## Limitations
- Large Computational Resources: Training deep learning models on large clinical datasets like MIMIC-III requires significant computational resources.
- Class Imbalance: Imbalanced distribution of medical codes in the dataset poses challenges for model training and evaluation.

## Requirements
- Python
- PyTorch
- scikit-learn
- Pandas
- NumPy
- Matplotlib
- NLP
