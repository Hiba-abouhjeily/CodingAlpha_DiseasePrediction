# CodingAlpha_DiseasePrediction

## Project Overview
This project is developed as part of the **CodeAlpha Machine Learning Internship**. The objective is to build a machine learning classification pipeline to predict patient health risks (such as heart disease) using structured medical data.

## Technologies Used
* **Python**
* **Pandas & NumPy** (Data cleaning and manipulation)
* **Scikit-Learn** (Classification models and metrics evaluation)
* **Jupyter Notebook**

## Dataset
* **File:** `heart_disease_cleveland.csv`
* **Features Include:** Age, Sex, Chest Pain Type (cp), Resting Blood Pressure (trestbps), Cholesterol (chol), Maximum Heart Rate Achieved (thalach), and other clinical attributes.
* **Target Variable:** Binary classification column indicating the presence or absence of heart disease.

## Approach & Workflow
1. **Data Preprocessing:** Inspected the dataset for missing values, cleaned columns, and prepared features for modeling.
2. **Data Splitting:** Divided the clinical dataset into training and testing subsets.
3. **Feature Scaling:** Standardized numerical clinical features to ensure balanced model weights.
4. **Model Training & Evaluation:** Trained machine learning classification algorithms and evaluated performance using metrics like Accuracy, Precision, Recall, and F1-Score.

## How to Run
1. Clone this repository or download the files.
2. Ensure you have Python, Jupyter Notebook, and required libraries installed (`pandas`, `numpy`, `scikit-learn`)
3. Open `heart_disease.ipynb` in Jupyter Notebook and execute the code cells sequentially.
