# Flight Price Prediction System

## Overview
This project implements a complete machine learning pipeline for predicting flight prices based on various features such as airline, journey date, source, destination, stops, and more. The workflow follows the standard data science lifecycle:

- Data collection
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model building and evaluation
- ML pipeline automation
- Hyperparameter tuning

## Project Structure

```
Flight-Prediction-System-main/
│
├── Model Implementation/
│   └── flight_Prediction_System.ipynb   # Main Jupyter Notebook with code and analysis
│
├── Training Data/
│   └── Data_Train.xlsx                  # Raw training dataset
│
└── README.md                            # Project documentation
```

## Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook or JupyterLab

### Required Python Packages
- pandas
- numpy
- matplotlib
- seaborn

You can install the required packages with:

```bash
pip install pandas numpy matplotlib seaborn
```

### Running the Notebook
1. Open `Model Implementation/flight_Prediction_System.ipynb` in Jupyter Notebook or JupyterLab.
2. Run the cells sequentially to:
   - Load and explore the dataset
   - Clean and preprocess the data
   - Perform EDA and feature engineering
   - Train and evaluate machine learning models
   - Tune hyperparameters

## Data
- The dataset (`Data_Train.xlsx`) contains flight details and prices.
- The notebook demonstrates how to load and preprocess this data for model training.

## Results
- The notebook provides visualizations, feature importance analysis, and model performance metrics.
- Final models and insights are documented within the notebook.

