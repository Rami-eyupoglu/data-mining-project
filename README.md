# data-mining-project
Usage
Place the dataset file (dataSet.csv) in the appropriate directory.
Open the project.ipynb file in Jupyter Notebook or any compatible IDE.
Run the cells sequentially to preprocess the data, analyze it, and train machine learning models.
Data Preprocessing
The following steps are performed during data preprocessing:

Handling Missing Values:

Missing values in CREDIT_SCORE and ANNUAL_MILEAGE are filled with their respective means.
Outlier Detection:

Z-Score method is used to detect outliers in CREDIT_SCORE, ANNUAL_MILEAGE, and SPEEDING_VIOLATIONS.
IQR method is applied to cap outliers in numeric features.
Feature Encoding:

Categorical features like GENDER, VEHICLE_TYPE, VEHICLE_YEAR, AGE, RACE, DRIVING_EXPERIENCE, EDUCATION, and INCOME are encoded using mappings.
Machine Learning Models
The following machine learning models are trained and evaluated:

Logistic Regression
Extra Trees Classifier
Random Forest Classifier
Decision Tree Classifier
K-Nearest Neighbors
Gradient Boosting Classifier
AdaBoost Classifier
Bagging Classifier
XGBoost Classifier
Support Vector Machine (SVM)
Model Evaluation
Models are evaluated using accuracy scores.
A bar plot is generated to compare the accuracy of different models.
Feature importance is visualized for the Random Forest Classifier.
Results
The best-performing model is displayed with its accuracy score.
Classification reports are generated for each model to evaluate precision, recall, and F1-score.
