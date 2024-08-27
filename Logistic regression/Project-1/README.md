# Breast Cancer Prediction using Logistic Regression

## Overview

This project aims to develop a predictive model for breast cancer diagnosis using logistic regression. The logistic regression model is trained to classify instances of breast cancer as malignant or benign based on various features extracted from the dataset. 

## Dataset

The dataset used in this project is the Breast Cancer Wisconsin dataset, which can be accessed [here](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data). It contains information about various attributes related to breast cancer, which will be used to train and evaluate the predictive model.

## Steps Involved

1. **Importing Libraries**: Essential libraries and modules are imported for data manipulation, visualization, and machine learning.

2. **Importing the Dataset**: The dataset is loaded into the environment using `pandas` from a CSV file.

3. **Data Cleaning**: Data is cleaned to handle missing values, remove duplicates, and ensure proper formatting.

4. **Preprocessing Data**: The dataset is divided into features (inputs) and the target variable (output). Features are then normalized using `StandardScaler` to improve model performance.

5. **Train-Test Split**: The dataset is split into training and testing sets to evaluate the model's performance.

6. **Training the Model**: A logistic regression model is trained using the training dataset.

7. **Evaluating the Model**: The model’s performance is assessed using accuracy and a classification report, which includes precision, recall, and F1-score.

## Conclusion

The logistic regression model has been trained and evaluated for predicting breast cancer. The evaluation metrics provide insights into the model’s performance and its ability to classify instances correctly. This project demonstrates the application of logistic regression in a practical scenario and highlights the importance of data preprocessing and model evaluation.

## Author

[Thota rahul]  
[rahulthota21@gmail.com] \
[27-08-2024]

## Requirements

- Python 3.x
- NumPy
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn

To install the necessary packages, you can use:

```bash
pip install numpy pandas seaborn matplotlib scikit-learn

