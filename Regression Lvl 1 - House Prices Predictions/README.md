# House Price Prediction using Machine Learning

## Project Overview

This project aims to predict house prices using machine learning models based on various features from the Ames housing dataset. The dataset includes a wide range of variables related to house characteristics such as size, location, and overall quality. The objective is to create a regression model that can accurately predict the sale price of homes.

## Key Features

- **Data Preprocessing**: Loads and preprocesses the data, including handling missing values and encoding categorical variables.
- **Feature Engineering**: Extracts key features from the dataset to improve model performance.
- **Model Training and Evaluation**: Trains multiple regression models (e.g., linear regression, decision trees, random forests) to predict house prices, and evaluates their performance using standard metrics like Mean Absolute Error (MAE).

## Requirements

To run the project, you’ll need the following packages:
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

Install the dependencies with:

pip install pandas numpy scikit-learn matplotlib seaborn

## Running the Project

1. Clone this repository:
   git clone https://github.com/bnikolaos21b/house-price-prediction
   cd house-price-prediction

2. Load the dataset files (`train.csv`, `test.csv`, `sample_submission.csv`) and the Jupyter notebook (`House_Price_Prediction.ipynb`).

3. Run the notebook to preprocess the data, train the models, and make predictions on the test set.

4. Use the notebook to generate predictions and submit the results as a CSV file for evaluation.

## Data Description

The dataset contains various features about the properties in the Ames housing market, including:
- **MSSubClass**: Type of dwelling involved in the sale.
- **OverallQual**: Rates the overall material and finish of the house.
- **YearBuilt**: Original construction date.
- **GrLivArea**: Above grade (ground) living area square feet.
- **SalePrice**: The property's sale price (target variable).

For a full description of the features, please refer to the `data_description.txt` file.

## Conclusion

This project demonstrates how machine learning models can be applied to predict house prices based on a rich set of features. With proper data preprocessing and feature engineering, predictive models can provide accurate price estimations, which can be useful in real estate markets.


