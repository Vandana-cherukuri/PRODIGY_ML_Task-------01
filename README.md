Project Overview

This project demonstrates:

Loading and exploring a dataset.

Preprocessing data for training.

Training a linear regression model.

Evaluating the model's performance.

Visualizing predictions.


Dataset

The dataset includes details of houses such as:

GrLivArea: Above-ground living area size (square feet).

BedroomAbvGr: Number of bedrooms.

FullBath: Number of full bathrooms.


Results

Mean Squared Error (MSE): 2,806,426,667.25

R-Squared Score: 0.6341


The model achieved moderate performance in predicting house prices.

Installation

1. Clone the repository:

git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction


2. Install required libraries:

pip install pandas scikit-learn matplotlib


3. Open the Jupyter Notebook:

jupyter notebook



Usage

1. Replace the placeholder dataset file (house.csv) with your dataset.


2. Run the cells step by step to train the model and evaluate its performance.



Visualizations

A scatter plot compares real house prices with predicted prices:

X-axis: Real prices.

Y-axis: Estimated prices.


Example Prediction

Predict the price of a house with:

Living area: 8,547 sqft

1 bedroom

3 bathrooms


The estimated price: $1,004,762.40.
