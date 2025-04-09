# Banking Customer Churn Prediction
(View the full article [here](https://medium.com/@elijahobisesan01/predicting-bank-customer-churn-a-comprehensive-guide-52b2627405a4)).

## Project Overview

This project involves predicting customer churn in a banking dataset. The goal is to build a model that can predict whether a customer is likely to churn based on various features. The project includes exploratory data analysis (EDA), data preprocessing, model building, and evaluation.

## Contents

- **`dataset/`**: Contains the dataset used for the project.
- **`notebooks/`**: Jupyter notebook for exploratory data analysis and model building.
- **`README.md`**: This file.

## Project Details

### 1. Exploratory Data Analysis (EDA)

- Performed exploratory data analysis to understand the dataset and identify key features.
- Analyzed the distribution of numerical and categorical variables.
- Identified and handled missing values and outliers.

### 2. Data Preprocessing

- **Data Cleaning**: Handled missing values and outliers.
- **Feature Encoding**: Converted categorical variables to numerical using one-hot encoding.
- **Feature Scaling**: Standardized numerical features for model training.

### 3. Model Building

- **Model Selection**: Built and trained a Logistic Regression model to predict customer churn.
- **Evaluation**: Evaluated the model using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

### 4. Results

- Provided performance metrics of the trained model.
- Included a detailed classification report and ROC curve to visualize model performance.

## Getting Started

To run the code and reproduce the results:

1. Clone the repository:
    ```bash
    git clone https://github.com/etimexo/banking-customer-churn.git
    ```

2. Navigate to the project directory:
    ```bash
    cd banking-customer-churn
    ```

3. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the Jupyter notebooks for EDA and model building:
    ```bash
    jupyter notebook notebooks/
    ```
    
## Acknowledgements
- [Scikit-learn](https://scikit-learn.org/) for machine learning algorithms and tools.

## Contact

For any questions or feedback, please contact elijahobisesan@gmail.com

