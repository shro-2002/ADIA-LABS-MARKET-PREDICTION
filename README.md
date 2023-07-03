# ADIA-LABS-MARKET-PREDICTION 
### Cross-Section Forecast Problem

This repository contains code and resources related to the cross-section forecast problem in finance. The goal of the problem is to predict the relative performance of a group of investments over time, using a pool of investment vehicles.

## Problem Overview

The cross-section forecast problem involves predicting the ranking of investments from best to worst at each given date. Instead of directly predicting the future price of a single asset, we aim to predict how different investments will perform relative to each other. The evaluation metric for this problem is Spearman's rank correlation, which measures the match between the predicted ranking and the actual ranking.

## Timeline

- Documentation Release: May 12th, 2023
- Start Date: May 16th, 2023, 05.00 PM CET
- End Date: November 16th, 2023, 11:59 PM CET
- Submission Deadline: August 16th, 2023, 04:59 PM CET

## Code Structure

- `main.ipynb`: Jupyter Notebook containing the code implementation for data loading, exploratory data analysis (EDA), feature engineering, model training, and prediction.
- `data/`: Directory containing the training and testing data in Parquet format.
- `model.pkl`: Saved trained model using XGBoost.
- `submission.csv`: CSV file containing the predictions on the test data.

## Setup and Dependencies

To run the code in this repository, you need the following dependencies:

- Python 3.x
- Numpy
- Matplotlib
- Pandas
- TensorFlow
- XGBoost
- Seaborn
- Scipy
- Statsmodels

Install the required dependencies using the following command:
pip install -r requirements.txt


## Usage

1. Clone the repository:

git clone https://github.com/shro-2002/ADIA-LABS-MARKET-PREDICTION.git


4. Follow the instructions in the notebook to load the data, perform EDA, train the model, and make predictions.


## License

This project is licensed under the [MIT License](LICENSE).

