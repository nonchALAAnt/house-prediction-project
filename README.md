# house-prediction-project
a house prediction model using machine learning and gradient descent

A linear regression model built **from scratch** using NumPy to predict
house prices based on key property features.

## Overview
This project implements linear regression and gradient descent manually
without using any ML libraries like scikit-learn. The goal was to deeply
understand how the algorithm works under the hood rather than just calling
a function.

## Features used
- Number of bedrooms
- Living area (sqft)
- Number of floors
- Condition of the house

## How it works
1. Data is loaded and cleaned (NaN values removed)
2. Features are normalized using mean and standard deviation
3. Gradient descent runs for 100,000 iterations to minimize the cost function
4. The cost curve is plotted to visualize model convergence
5. User can input house features and get a price prediction

## Dataset
[House Price Dataset](https://www.kaggle.com/datasets/mohamedbakrey/housecsv)
by Mohamed Bakrey on Kaggle.

## How to run
1. Download `houses.csv` from the dataset link above and place it in the
same folder as the script
2. Install dependencies:
pip install numpy pandas matplotlib
3. Run the script:
python house_prediction.py
4. Enter the house features when prompted

## Results
The model converges steadily as shown in the generated `cost_curve.png`.

## What I learned
- Implementing linear regression and gradient descent from scratch
- Feature normalization and why it matters for gradient descent
- Using NumPy for efficient matrix operations
