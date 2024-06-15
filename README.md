# Bank Term Deposit Predictor

## Project Overview

This project aims to develop a predictive model to determine whether a customer will subscribe to a term deposit based on direct marketing phone calls made by a Portuguese banking institution. The goal is to optimize the bank's marketing strategy by identifying potential customers for term deposits.

## Features

- **Predictive Model**: Utilizes machine learning to predict customer subscription to term deposits.
- **Web UI Tool**: Allows bank employees to input customer data and get predictions.
- **Single Customer Prediction**: Input individual customer data for prediction.
- **Batch Prediction**: Upload a CSV file containing multiple customer records for batch predictions.
- **Analysis Charts**: Visual representation of customer trends and behaviors.
- **Recommendations**: Provides targeted customer recommendations based on predictions.

## Dataset

The dataset used for training the model is available on [Kaggle](https://www.kaggle.com/datasets/hariharanpavan/bank-marketing-dataset-analysis-classification).

## Folder Structure
  - `templates/`: HTML files for the web UI.
  - `static/`: Static files such as generated plots.
  - `test-dataset1.csv` & `test-dataset2.csv`: Sample test datasets.
  - `random_forest_model.joblib`: Pre-trained Random Forest model.
  - `app.py`: Main Flask application.

## Instructions

### Running the Application

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/yourusername/bank-term-deposit-predictor.git
   cd bank-term-deposit-predictor/src/phase3
