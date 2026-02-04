# Flight Price Prediction ✈️

Machine Learning project to predict airline ticket prices using Linear Regression.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1xYZ_pPPH6kJ0-1kQ7vBtZGypb59Rs0AT?usp=sharing)

## Dataset
Airlines Flights Data from Kaggle (300,000+ flights)

## Features
- Duration, Days Left, Airline, Source City, Destination City, Class, Stops, Departure Time, Arrival Time, Flight Number

## Model Performance
- **R² Score**: 0.93 (Train & Test)
- **RMSE**: ~5,000-6,000 ₹
- **No overfitting** - consistent performance across train and test sets

## Key Insights
- Book flights 20+ days in advance for best prices
- Direct flights are generally cheapest
- Business class is 3-4x more expensive than Economy
- Last-minute bookings (1-5 days) are most expensive

## Tools Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Kagglehub

## How to Run
1. Click the Colab badge above to open the notebook
2. Or clone this repo and install requirements: `pip install -r requirements.txt`
3. Run all cells in order

## Pipeline
1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing & Encoding
4. Feature Scaling
5. Model Training
6. Evaluation
7. Model Saving
