# Stock Price Prediction using Machine Learning

This repository contains a simple machine learning project to predict the stock prices of Tesla. The project is implemented in Python using a Jupyter Notebook.

## Dataset

The dataset `Tesla.csv` contains historical stock data. It includes the following columns:
- **Date**: The date of the record.
- **Open**: The opening price of the stock.
- **High**: The highest price of the stock on that day.
- **Low**: The lowest price of the stock on that day.
- **Close**: The closing price of the stock.
- **Volume**: The volume of stocks traded.
- **Adj Close**: The adjusted closing price of the stock.

## Libraries & Tools Used

The following libraries are used in this project:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn` (for data preprocessing, metrics, Support Vector Classifier, and Logistic Regression)
- `xgboost` (for the XGBClassifier model)

## Models Built

The notebook trains multiple machine learning models to analyze their performance. These typically include:
- Logistic Regression
- Support Vector Machine (SVC)
- XGBoost Classifier

## How to Run

1. Clone the repository or download the project files.
2. Ensure you have Jupyter Notebook or JupyterLab installed.
3. Install the required dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn xgboost
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook 1Stock_Price_Prediction_using_Machine_Learning_in_Python.ipynb
   ```
5. Note: Check the dataset path in the notebook. Since it was run on Google Colab (`/content/Tesla.csv`), you'll want to update the file path in the `pd.read_csv()` function to `Tesla.csv` to run it locally.
6. Run the cells in the notebook to view data preparation, exploratory data analysis, model training, and evaluation results.
