# Optical Digits Recognition Classifier

## Introduction
This project implements a classification model for recognizing handwritten digits using the **Optical Recognition of Handwritten Digits** dataset. The dataset consists of 8×8 images of digits (0-9), where each pixel has an integer value in the range of 0 to 16.

## Dataset
The dataset has the following characteristics:
- **Number of Instances:** 1797
- **Number of Attributes:** 64
- **Data Format:** 8×8 images with pixel values ranging from 0 to 16
- **Missing Values:** None

## Models Used
The following models are implemented and evaluated:
- **Support Vector Machine (SVM)**
- **Decision Tree (DT)**
- **Artificial Neural Network (ANN)**
- **K-Nearest Neighbors (KNN)**
- **Gaussian Naive Bayes (GNB)**
- **Random Forest (RF)**
- **Logistic Regression (LR)**

## Requirements
To run this project, install the required dependencies:
```bash
pip install -r requirements.txt
```

## How to Run
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook mnist-digit-classifier.ipynb
   ```
2. Execute the notebook cells to load the dataset, preprocess data, train models, and evaluate performance.

## Evaluation Metrics
The models are evaluated based on:
- Accuracy
- Precision
- Recall

## Results
The best-performing model is selected, and a comparison of different models is provided.

