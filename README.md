# Heart-Stroke-Prediction-with-Logistic-Regression-and-Gradient-Boosting-Classifier-

Project Overview
The project follows a standard machine learning workflow:

1. Load Data: Load the stroke prediction dataset (Heart_stroke.csv).
2. Explore Data: Perform initial data exploration to understand the dataset structure, identify missing values, and analyze basic statistics.
3. Clean Data: Handle missing values, outliers, and inconsistencies in the data.
4. Process Data: Encode categorical variables, scale numerical features, and split the data into training and testing sets.
5. Analyze and Visualize Data: Explore the relationships between features and the target variable (stroke) using visualizations and   statistical analysis. Identify important features.
6. Build Model: Train Logistic Regression and Gradient Boosting models.
7. Validate Model: Evaluate the models' performance using appropriate metrics (accuracy, precision, recall, F1-score, AUC).
8. Tune Model: Optimize model hyperparameters using GridSearchCV.

The dataset used in this project is Heart_stroke.csv. It contains information about patients, including:

id: Unique identifier
gender: Gender of the patient
age: Age of the patient
hypertension: 0 if the patient has no hypertension, 1 if the patient has hypertension
heart_disease: 0 if the patient has no heart disease, 1 if the patient has heart disease
ever_married: Whether the patient was ever married ('Yes' or 'No')
work_type: Type of work the patient does
Residence_type: Type of residence ('Rural' or 'Urban')
avg_glucose_level: Average glucose level in blood
bmi: Body Mass Index
smoking_status: Smoking status of the patient
stroke: 1 if the patient had a stroke, 0 if not (Target Variable)
Setup
To run this notebook, you will need to have Python and the following libraries installed:

pandas
numpy
scikit-learn
matplotlib
seaborn
You can install these libraries using pip:
