Machine Learning Lab 5: KNN Classification and Regression
Student Details
Name: Harshit Uchasare
Section: A
Roll Number: 35
Batch: A3
Lab Number: 5
Aim

To implement the K-Nearest Neighbors (KNN) algorithm for classification and regression using Python and the Diabetes dataset.

Objectives
Understand the working of the KNN algorithm.
Perform data preprocessing and exploratory data analysis (EDA).
Implement KNN classification to predict diabetes outcomes.
Implement KNN regression to predict a continuous value.
Evaluate model performance using appropriate metrics.
Dataset

File name: diabetes.csv

The dataset contains medical attributes such as:

Pregnancies
Glucose
BloodPressure
SkinThickness
Insulin
BMI
DiabetesPedigreeFunction
Age
Outcome

The Outcome column is used for classification, while Glucose is used as the regression target in this project.

Technologies Used
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Project Workflow
Load the Diabetes dataset.
Inspect the dataset and perform EDA.
Handle duplicate rows and missing or invalid zero values.
Fill missing values using median imputation.
Split the data into training and testing sets.
Standardize features for KNN.
Train a KNN classifier with K = 3.
Train a KNN regressor with K = 3.
Evaluate and visualize the results.
Evaluation Metrics
Classification
Accuracy
Precision
Recall
F1-score
Confusion matrix
Regression
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R² score
How to Run
Download or clone this repository.
Keep diabetes.csv in the same folder as the notebook.
Open the notebook in Jupyter Notebook or Google Colab.
Run the notebook cells in order.
Files
Lab_5_Harshit_Uchasare_KNN_EDA.ipynb — Jupyter Notebook
diabetes.csv — Dataset
README.md — Project documentation
Conclusion

This practical demonstrates how KNN can be applied to both classification and regression problems. Feature standardization is important for KNN because the algorithm uses distances to identify neighboring observations. Model evaluation metrics help assess the performance of both approaches.

Note: Actual performance values should be taken from the executed notebook results.
