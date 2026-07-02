# Housing Price Prediction

This project builds and evaluates regression models to predict residential property prices from structured housing data. The workflow includes exploratory data analysis, feature engineering, target transformation, and model comparison using several regression techniques.

## Project Objective

The goal is to estimate house sale prices more accurately by combining domain-informed features with machine learning models. This can support use cases such as:

- property valuation
- pricing strategy analysis
- investment screening
- real-estate decision support

## Dataset

The notebook expects a CSV file named `housing_price_data.csv` in the project root. A typical dataset includes columns such as:

- House ID
- City
- House Area (sqm)
- No. of Bedrooms
- No. of Toilets
- Stories
- Renovation Status
- Price ($)

## Project Structure

- `housing_price_prediction.ipynb` — end-to-end notebook for data loading, EDA, feature engineering, model training, and evaluation.
- `README.md` — project overview and usage instructions.
- `requirements.txt` — Python dependencies for running the notebook.

## Setup

1. Create and activate a virtual environment.
2. Install the dependencies.
3. Place `housing_price_data.csv` in the repository root.
4. Open and run the notebook cells in order.

### Environment Setup

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```

## Workflow

1. Data loading and inspection
2. Exploratory data analysis
3. Feature engineering
4. Target transformation for better regression stability
5. Training and evaluation of multiple models
6. Comparison of baseline and improved performance

## Models Explored

- Dummy Regressor (baseline)
- Linear Regression
- Lasso Regression
- Decision Tree Regressor
- Gradient Boosting Regressor

## Evaluation Metrics

The project evaluates model quality using:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R-squared ($R^2$)

## Notes for Reproducibility

- The notebook uses a fixed random seed where appropriate for repeatable results.
- The target variable is log-transformed to reduce skew and improve model stability.
- Feature engineering is documented in the notebook to make the reasoning behind each transformation explicit.

## Suggested Next Steps

- Add cross-validation summaries and experiment tracking
- Compare with Random Forest and XGBoost models
- Build a simple deployment API or streamlit app
- Add automated data validation checks

## License

This project is intended for educational and demonstration purposes.
