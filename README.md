# Heart Disease Prediction using Machine Learning with Python

## Overview
This project aims to predict the presence of heart disease using machine learning techniques. By analyzing medical data, we train a model to classify whether a patient is at risk or not.

## Dataset
The dataset used for this project is the Heart Disease dataset obtained from Kaggle. It consists of 14 features such as age, sex, chest pain type, blood pressure, cholesterol levels, and more.

## Features
Some key features in the dataset include:

- **Age**: Age of the patient
- **Sex**: Male or Female
- **Chest Pain Type (cp)**: Different types of chest pain
- **Resting Blood Pressure (trestbps)**
- **Cholesterol (chol)**
- **Fasting Blood Sugar (fbs)**
- **Resting Electrocardiographic Results (restecg)**
- **Maximum Heart Rate Achieved (thalach)**
- **Exercise Induced Angina (exang)**
- **Oldpeak**: ST depression induced by exercise
- **Slope**: Slope of the peak exercise ST segment
- **Number of Major Vessels (ca)**
- **Thalassemia (thal)**

## Machine Learning Models Used
The following models were implemented and evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Gradient Boosting Classifier

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Installation
To run this project on your local machine, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Heart-Disease-Prediction-using-Machine-Learning-with-Python.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Heart-Disease-Prediction-using-Machine-Learning-with-Python
   ```
3. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
5. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Usage
- Open the Jupyter Notebook and execute the cells to preprocess data, train models, and evaluate performance.
- Compare different machine learning models based on accuracy, precision, recall, and F1-score.
- Modify hyperparameters to optimize the models for better performance.

## Results
The models are evaluated using accuracy scores, confusion matrices, and ROC curves. The best-performing model is identified based on these metrics.

## Contribution
Feel free to contribute by:
- Improving model accuracy
- Adding new datasets
- Implementing additional machine learning techniques
- Enhancing data visualization

Created by Mathusayini Thayalanesan
