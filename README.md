# Bulldozer Sale Price Prediction (Regression problem)

This project uses structured bulldozer sales data to train a regression model that predicts future sale prices.

##  Project Overview
This project follows a complete end-to-end regression workflow using the Kaggle “Bluebook for Bulldozers” dataset.
It features:
- Problem framing and relevant evaluation metric (RMSLE)
- Data preprocessing and feature engineering
- Model training and hyperparameter tuning
- Prediction on test data and custom samples
- Feature importance analysis and model persistence

## Dataset  
- **Train.csv** (2011 data)  
- **Valid.csv** (January–April 2012)  
- **Test.csv** (May–November 2012; missing sale prices)  
- Data is sourced from the [Kaggle Bluebook for Bulldozers competition](https://www.kaggle.com/c/bluebook-for-bulldozers/data).  

## Evaluation Metric  
**Root Mean Squared Log Error (RMSLE)** is used for model evaluation — reflecting performance with penalization for large deviations.

## Requirements  
- Python 3.x  
- Jupyter Notebook / JupyterLab  
- Required data science libraries listed in `requirement.txt`

## Setup Instructions  
1. Clone the repository:
   ```bash
   git clone https://github.com/AJ-MH/bulldozer-salePrice-prediction.git
   cd bulldozer-salePrice-prediction
2. (Optional) Create and activate a virtual environment:
    ```bash
   python -m venv env
   source env/bin/activate    # On Windows use `env\Scripts\activate`
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
5. Usage Guide
   1. Launch Jupyter
   2. Open and run the notebook
   3. Execute step-by-step:
      * Data loading and preprocessing
      * Model training and tuning
      * Predictions and evaluation (RMSLE)
      * Optional: custom sample predictions and feature importance
    4. Save or reuse the trained model as needed.

 ## License
 This project is licensed under the MIT License — see the LICENSE file for details.
