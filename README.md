# Indian Startup Funding Prediction Using SVR

## Overview
This project predicts the funding amount of Indian startups based on historical data, using Support Vector Regression (SVR) model. The dataset includes information like startup name, industry, location, and investment type.

## Dataset
The dataset used for this project is `startup_funding.csv`, which contains columns such as:
- `Startup Name`
- `Industry Vertical`
- `SubVertical`
- `City Location`
- `Investment Type`
- `Investors Name`
- `Amount in USD`
- `Date`

## Key Steps:
1. **Data Preprocessing:**
   - Handle missing values using KNN imputation.
   - Convert categorical columns into one-hot encoded format.
   - Apply log transformation to handle outliers in the 'Amount in USD'.
   - Normalize numeric features (Amount, Year, Month).

2. **Model Building:**
   - A Support Vector Regression (SVR) model is trained to predict funding amounts.
   - The model is evaluated using Mean Squared Error (MSE) and Mean Absolute Error (MAE).

3. **Results:**
   - The model achieved reasonable predictions of startup funding amounts with the following metrics:
     - Mean Squared Error (MSE): [value]
     - Mean Absolute Error (MAE): [value]

## Setup Instructions:

1. Clone the repository or download the code files.
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Load and preprocess the dataset using the provided code.
4. Train the SVR model using the cleaned and preprocessed data.
5. Evaluate the model's performance on the test set.

## Files:
- `startup_funding.csv`: The dataset containing startup funding details.
- `startup_funding_model.ipynb`: The Jupyter Notebook with the implementation of the project.
- `requirements.txt`: The list of Python dependencies required to run the code.

## License:
This project is licensed under the MIT License.

