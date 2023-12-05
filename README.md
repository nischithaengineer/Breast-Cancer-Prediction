# Breast-Cancer-Prediction

# Overview
* This project aims to predict breast cancer diagnosis using machine learning classifiers: logistic regression, decision tree, and random forest. The dataset used contains features extracted from breast mass images, aiming to classify tumors as malignant or benign.

1. Data Collection:
* Acquire the dataset containing features extracted from breast mass images.
* Verify data quality and ensure it includes the necessary information for analysis.
2. Exploratory Data Analysis (EDA):
* Load the dataset using Python (in this case, using pandas' read_csv function).
* Inspect the structure of the dataset (data.head(), data.info(), data.describe()) to understand its attributes, data types, and distributions.
* Handle missing data (data.isnull().sum()).
* Encode categorical variables into numerical format (LabelEncoder).
* Visualize the data distribution (sns.countplot, sns.pairplot, heatmaps) to identify patterns and correlations between features.
3. Data Preprocessing:
* Separate the dataset into independent variables (features) and the dependent variable (diagnosis).
* Split the data into training and testing sets using train_test_split.
* Standardize the feature data using StandardScaler to ensure all features are on the same scale.
4. Model Building:
* Implement machine learning models: Logistic Regression, Decision Tree Classifier, Random Forest Classifier using scikit-learn.
* Train the models using the training dataset (fit function).
5. Model Evaluation:
* Evaluate model performance using various metrics like accuracy scores (model.score), confusion matrices (confusion_matrix), and classification reports (classification_report).
* Compare the performance of each model on the test dataset.
6. Prediction and Analysis:
* Make predictions using the trained models on the test dataset.
* Analyze the predictions against actual values to assess model accuracy and effectiveness.
* Create a DataFrame to compare actual vs. predicted values. 
