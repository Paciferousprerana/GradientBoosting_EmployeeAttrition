# Employee Attrition Prediction using Gradient Boosting Models

## Problem Statement

To predict employee attrition using CatBoost, XgBoost and LightGBM
(CatBoost, XGBoost, and LightGBM are widely used gradient boosting algorithms known for their high performance and ability to handle complex datasets.)

## Objectives

* explore the employee attrition dataset
* apply CatBoost and XgBoost on the dataset
* tune the model hyperparameters to improve accuracy
* evaluate the model using suitable metrics

## Dataset

The dataset used for this mini-project is [HR Employee Attrition dataset](https://data.world/aaizemberg/hr-employee-attrition). This dataset is synthetically created by IBM data scientists. There are 35 features and 1470 records.

## Project Setup
Follow the steps below to set up the project:

1. Clone the project repository or download the project files to your local machine.

2. Open it in Jupyter Notebook or Google Colab.

3. Download the dataset (link given in the notebook) and split it into training and testing datasets

## Usage
1. Open the ipynb file.

2. Load the employee attrition dataset into the notebook using the appropriate file reading function (e.g., pd.read_csv() in the case of a CSV file).

3. Preprocess the dataset by performing data cleaning, handling missing values, encoding categorical variables, and splitting the data into training and testing sets.

4. Implement the CatBoost, XGBoost, and LightGBM models using the respective libraries' modules. Set the appropriate hyperparameters (found using optuna) based on the dataset and problem requirements.

5. Train the models using the training data and evaluate their performance using suitable evaluation metrics (e.g., accuracy, precision, recall, F1 score, ROC-AUC).

6. Adjust the hyperparameters of the models (e.g., learning rate, maximum depth, number of estimators) if necessary to improve performance.

7. Make predictions on the test data using the trained models and assess the accuracy of the predictions.

8. Compare the performance of the three models and choose the best-performing one based on the evaluation metrics.

## Troubleshooting
* Ensure that the dataset file is correctly specified and placed in the same directory as the ipynb Notebook file.

* Check for any missing libraries or dependencies and install them using the pip install command if necessary.
