Name:C.Vani
Company:CODETECH IT SOLUTIONS
ID:CT6WDS798
Domain:Data Analytics
Duration:July to August 2024

Project Overview: Predicting Diabetes Progression using Simple Linear Regression

1. Introduction
Objective: Predict the progression of diabetes in a patient using Simple Linear Regression.
Dataset: Diabetes dataset from Scikit-Learn, which includes data on various medical features of patients.

2. Dataset Description
Source: Scikit-Learn’s datasets module.
Features: The dataset contains 10 features (e.g., age, sex, body mass index, average blood pressure, and six blood serum measurements).
Target: A continuous variable indicating the diabetes progression one year after baseline.

3. Project Steps
1. Load the Dataset

Import the necessary libraries.
Load the dataset using sklearn.datasets.load_diabetes().
Split the dataset into features (a) and target (b).

2. Preprocessing
Split the Data: Divide the dataset into training and testing sets using train_test_split from sklearn.model_selection.
Normalization: Depending on the features, consider scaling them using StandardScaler from sklearn.preprocessing.

3. Exploratory Data Analysis (EDA)
Visualize Data: Use libraries like matplotlib or seaborn to visualize relationships between features and the target variable.
Correlation Analysis: Analyze correlations between features and the target variable to understand their relationships.

4. Model Implementation
Initialize Model: Import and initialize the LinearRegression model from sklearn.linear_model.
Train Model: Fit the model to the training data using the fit method.
Predict: Make predictions on the test set using the predict method.

5. Evaluation
Performance Metrics: Evaluate the model’s performance using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared score from sklearn.metrics.
Visualize Predictions: Plot predicted values against actual values to visualize the model’s performance.
![Screenshot (44)](https://github.com/user-attachments/assets/c6d7b377-ddd7-452b-a750-bfe947a98883)
![Screenshot (45)](https://github.com/user-attachments/assets/c77da6bc-f9b2-464c-bfa5-ae88a7e88031)
![Screenshot (46)](https://github.com/user-attachments/assets/c7fc0e7f-5398-4ed3-85b4-b10462b6100d)


