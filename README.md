# Breast Cancer Classification using Machine Learning

## Dataset Description
This project uses the Breast Cancer Wisconsin Dataset for binary classification. 
The goal is to classify breast tumors into two categories: Malignant (cancerous) 
and Benign (non-cancerous) based on medical features extracted from cell images.

## Dataset
Dataset file used:
- data.csv

## Features
The dataset contains different numerical features such as:
- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Concave Points
- Symmetry
- Fractal Dimension

## Target Variable
Target variable:
- Diagnosis

Classes:
- M = Malignant
- B = Benign

## Data Preprocessing
The following preprocessing steps were performed:
- Checked missing values
- Removed unnecessary columns
- Encoded target labels into numerical form
- Applied feature scaling
- Split dataset into training and testing sets

## Machine Learning Model
A Support Vector Machine (SVM) classification model was trained.

## Cross Validation
5-Fold Cross-Validation was applied to evaluate model performance and stability.

## Hyperparameter Tuning
The model was optimized using:
- GridSearchCV
- RandomizedSearchCV

## Model Evaluation
The optimized model was evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Tools and Libraries
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Conclusion
The optimized SVM model provides improved classification performance compared 
to the baseline model. Hyperparameter tuning helps in selecting better model 
parameters and improves prediction accuracy.
