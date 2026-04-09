# Student Performance Prediction (Machine Learning Project)
📌 Overview

This project focuses on predicting student academic performance using machine learning techniques. It demonstrates an end-to-end ML pipeline including data ingestion, data transformation, model training, and evaluation.

The goal is to analyze how different factors influence student scores and build models that can accurately predict performance.

🎯 Problem Statement

The dataset contains student-related attributes such as:

Gender
Race/Ethnicity
Parental Level of Education
Lunch Type
Test Preparation Course
Math Score
Reading Score

The objective is to build a machine learning model that predicts student performance based on these features.

⚙️ Project Workflow
1. Data Ingestion
Load dataset from source (CSV or other format)
Handle missing or inconsistent data
Split dataset into training and testing sets
2. Data Transformation
Encoding categorical features (e.g., gender, race)
Feature scaling and normalization
Pipeline creation for preprocessing
3. Model Training
Multiple machine learning algorithms implemented:
Linear Regression
Decision Tree
Random Forest
Support Vector Classifier (SVC)
XGBoost
CatBoost
Model comparison based on performance metrics
4. Model Evaluation
Evaluate models using metrics like:
R² Score
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Select the best-performing model
🧠 Key Features
Modular code structure
End-to-end ML pipeline
Multiple model experimentation
Clean separation of components
Logging and exception handling implemented
🛠️ Technologies Used
Python
NumPy
Pandas
Scikit-learn
XGBoost
CatBoost
📁 Project Structure
├── src/
│   ├── components/
│   │   ├── data_ingestion.py
│   │   ├── data_transformation.py
│   │   └── model_trainer.py
│   ├── exception.py
│   ├── logger.py
│
├── notebooks/
├── data/
├── requirements.txt
└── README.md
🚀 How to Run the Project
Clone the repository:
git clone <https://github.com/devzz-4807/project/tree/main>
Install dependencies:
pip install -r requirements.txt
Run the training pipeline:
python main.py