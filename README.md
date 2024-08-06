# Breast_Cancer_Classification

This project aims to build machine learning models to predict breast cancer using the Wisconsin Diagnostic Breast Cancer dataset.

# Project Overview:
This project involves:

1. Data preprocessing and exploration.
2. Training and evaluating different machine learning models.
3. Comparing model performance.

# Dataset:
The dataset contains features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. It includes the following:

569 instances
31 features (after removing id and an unnamed column)
Diagnosis labels (M for malignant, B for benign)

# Libraries Used:
1) numpy
2) pandas
3) seaborn
4) matplotlib
5) scikit-learn

# Steps: 

  # 1. Data Loading and Exploration
          - Load the dataset using pandas.
          - Inspect the data with functions like df.head(), df.info(), and df.describe().
          - Check for missing values and duplicates.
          - Data Preprocessing

  # 2. Drop unnecessary columns (id and unnamed column).
          - Encode diagnosis labels: M to 1 and B to 0.
          - Standardize the features.
          
  # 3. Data Visualization
          - Visualize the distribution of diagnosis labels using count plots and pie charts.

  # 4. Model Training and Evaluation
          - Split the data into training and test sets.
          - Train and evaluate the following models:
              + Logistic Regression
              + Decision Tree Classifier
              + Random Forest Classifier
              + K-Nearest Neighbors Classifier
          - Compare the models based on accuracy, confusion matrix, and classification report.
          
# Results:
- Logistic Regression achieved an accuracy of 98.2%.
- Decision Tree Classifier achieved an accuracy of 93.6%.
- Random Forest Classifier achieved an accuracy of 97.1%.
- K-Nearest Neighbors Classifier achieved an accuracy of 95.9%.

# Conclusion:
Logistic Regression performed the best among the evaluated models with an accuracy of 98.2%. Future work could include further tuning of hyperparameters and exploring other models or techniques.
