# House Price Prediction Using Machine Learning

## Project Overview

This project focuses on predicting house prices using machine learning regression algorithms.

The model uses property characteristics such as area, bedrooms, bathrooms, age, location and property type to estimate house prices.

The project was developed using Python, Pandas, NumPy, Matplotlib, Seaborn and Scikit-learn.

## Objectives

- Understand basic machine learning concepts.
- Perform exploratory data analysis.
- Prepare numerical and categorical data.
- Implement Linear Regression from scratch.
- Build regression models using Scikit-learn.
- Compare models using cross-validation.
- Evaluate predictions using regression metrics.
- Visualise actual and predicted house prices.
- Analyse feature importance.

## Dataset

The dataset contains 300 property records.

Features include:

- Area
- Bedrooms
- Bathrooms
- Age
- Location
- Property Type

Target variable: Price

## Algorithms Used

1. Linear Regression
2. Polynomial Regression
3. Decision Tree Regression
4. Random Forest Regression

## Model Evaluation

The Random Forest model was selected based on five-fold cross-validation performance.

Final test results:

| Metric | Result |
|---|---:|
| MAE | 1,599,658.06 |
| MSE | 4,662,030,179,060.63 |
| RMSE | 2,159,173.49 |
| R² Score | 0.9673 |

These results describe performance on the particular held-out test dataset.

## Feature Importance

Area and location were the most influential features in the selected Random Forest model.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Project Structure

```text
house-price-prediction/
│
├── house_price_prediction.ipynb
├── house_data.csv
├── model_evaluation_report.md
├── README.md
├── requirements.txt
├── predictions_vs_actual.png
│
├── visualization/
│   ├── 01_feature_distributions.png
│   ├── 02_price_by_categories.png
│   ├── 03_predictions_vs_actual.png
│   ├── 04_residual_plot.png
│   └── 05_feature_importance.png
│
├── test_predictions.csv
└── model_comparison_cv.csv
```

## Installation

Install the required libraries:

```bash
pip install -r requirements.txt
```

## Running the Project

1. Clone or download this repository.
2. Install the required Python libraries.
3. Open `house_price_prediction.ipynb` using Google Colab or Jupyter Notebook.
4. Ensure the dataset is available in the expected location.
5. Execute the notebook cells sequentially.

## Conclusion

This project demonstrates the application of machine learning regression techniques to a house price prediction problem, including data preparation, model comparison, evaluation and practical prediction.

## Limitations

The dataset is relatively small, and model performance may differ on new datasets. Predictions should not be treated as guaranteed market valuations.
