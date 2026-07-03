# Housing Price Prediction

A machine learning project that predicts residential property prices using structured housing data. The project demonstrates an end-to-end regression workflow, including exploratory data analysis (EDA), feature engineering, target transformation, model training, and performance evaluation.


## Features

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Target transformation using log scaling
- Training and comparison of multiple regression models
- Performance evaluation using standard regression metrics

## Requirements

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook


## Dataset

The project uses a structured housing dataset (`housing_price_data.csv`) containing property characteristics such as:

- House ID
- City
- Floor Area (sqm)
- Number of Bedrooms
- Number of Toilets
- Number of Stories
- Renovation Status
- Sale Price

The dataset is expected to be placed in the project root directory before running the notebook.

## Project Structure

```
housing-price-prediction/
│
├── housing_price_prediction.ipynb
├── housing_price_data.csv
├── requirements.txt
├── README.md
└── .gitignore
```

## Machine Learning Workflow

1. Data loading and inspection
2. Data preprocessing
3. Exploratory Data Analysis
4. Feature engineering
5. Log transformation of the target variable
6. Model training
7. Model evaluation
8. Model comparison


## Models Evaluated

- Dummy Regressor (Baseline)
- Linear Regression
- Lasso Regression
- Decision Tree Regressor
- Gradient Boosting Regressor


## Evaluation Metrics

Model performance is evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics provide a balanced comparison between prediction accuracy and model generalization.


## Installation

Clone the repository:

```bash
git clone https://github.com/vvivsm/housing-price-prediction.git
```

Install the required packages:

```bash
pip install -r requirements.txt
```

## Running the Project

Launch Jupyter Notebook and open:

```
housing_price_prediction.ipynb
```

Run all notebook cells sequentially.


## Future Improvements

Potential extensions include:

- Cross-validation and hyperparameter tuning
- Random Forest and XGBoost regression models
- Interactive Streamlit web application
- Model serialization with Joblib
- Automated data validation
- MLflow experiment tracking

## Note

This project was originally completed as part of a machine learning coursework assignment and has since been refined with improved documentation and repository organization for portfolio purposes.
