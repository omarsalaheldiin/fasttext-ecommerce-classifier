# E-Commerce Product Classification

## Overview
The goal of this project is to classify e-commerce product descriptions into predefined categories using FastText. The dataset contains product descriptions and corresponding categories. This project involves preprocessing text data, training a FastText model, and evaluating its performance.

## Dataset
- [The dataset](https://www.kaggle.com/datasets/saurabhshahane/ecommerce-text-classification)

The dataset is a classification based E-commerce text dataset for 4 categories - "Electronics", "Household", "Books" and "Clothing & Accessories", which almost cover 80% of any E-commerce website.

## Data Preprocessing
- Handled missing values.
- Added FastText label prefix to categories.
- Removed newline characters, punctuation, and extra spaces from descriptions.
- Converted text to lowercase.

## Model Building
- Trained a FastText supervised classification model 
- Optimizer: Built-in Adam optimizer with default settings
- Loss Function: Cross-entropy loss for classification tasks

## Evaluation
- The model's performance is evaluated using the classification report and confusion matrix.

## Libraries To run the notebook:
- pandas
- re
- scikit-learn
- fasttext