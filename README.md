# House Price Prediction

A Machine Learning regression project that predicts house sale prices using property features and Scikit-learn.

## Project Overview

This project explores house-price prediction using the Ames Housing dataset from OpenML.

The objective is to train regression models, evaluate their performance, and understand the complete Machine Learning workflow.

## Dataset

- Source: OpenML — House Prices
- Target variable: `SalePrice`
- Features: Property size, quality, neighborhood, garage details, and other house characteristics.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Google Colab

## Machine Learning Workflow

1. Dataset loading and exploration
2. Exploratory Data Analysis (EDA)
3. Missing-value handling
4. Numerical and categorical preprocessing
5. Train-test splitting
6. Linear Regression
7. Random Forest Regression
8. Model evaluation
9. Cross-validation
10. Hyperparameter tuning
11. Feature importance and error analysis
12. Model serialization using Joblib

## Models and Results

### Linear Regression

| Metric | Result |
|---|---:|
| MAE | 21,106.69 |
| RMSE | 65,334.54 |
| R² | 0.4435 |

### Random Forest Regression

| Metric | Result |
|---|---:|
| MAE | 17,541.82 |
| RMSE | 28,985.91 |
| R² | 0.8905 |

Random Forest performed better than Linear Regression on the test dataset.

*Note: These are baseline model results. Hyperparameter tuning and final validation are still to be completed.*

## Project Files

- `house_price_prediction.ipynb` — Complete project notebook.
- `house_price_model.pkl` — Saved baseline Random Forest pipeline.

## How to Run

1. Open the notebook using Google Colab.
2. Run the cells in order.
3. The dataset is fetched from OpenML.
4. Train the models and evaluate their predictions.

## Future Improvements

- Complete hyperparameter tuning.
- Perform additional cross-validation.
- Improve feature engineering.
- Explore additional regression algorithms.
- Improve model explainability.

## Author

GitHub: [Your GitHub Profile](https://github.com/)
