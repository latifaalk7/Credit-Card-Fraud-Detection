# Credit-Card-Fraud-Detection
This project applies supervised machine learning techniques to detect fraudulent credit card transactions. Due to the highly imbalanced nature of the dataset, the project compares model performance before and after applying random undersampling.

The workflow includes data preprocessing, exploratory data analysis, model training, performance evaluation, and a comparison of results using multiple classification metrics.

## Features
- Exploratory Data Analysis (EDA)
- Data preprocessing and feature scaling
- Random undersampling to address class imbalance
- Logistic Regression and Random Forest models

## Performance evaluation using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Precision-Recall Curve

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Results

The models were evaluated on both the original and undersampled datasets. While the original dataset produced higher overall accuracy, the undersampled dataset improved the detection of fraudulent transactions by increasing recall and F1-score. This demonstrates the importance of selecting evaluation metrics that reflect the objective of fraud detection rather than relying solely on accuracy.
