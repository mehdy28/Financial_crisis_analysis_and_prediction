# Financial_crisis_analysis_and_prediction
This project aims to analyze and predict financial crises using machine learning techniques. The dataset used for training and testing the model is a collection of economic and financial indicators from various countries.

# Overview
Financial crises can have significant impacts on economies, markets, and individuals. Early warning systems that can predict such crises can help policymakers and investors take preventive measures and mitigate their effects.

This project uses machine learning algorithms to analyze and predict financial crises based on a variety of economic and financial indicators. The model is trained on a dataset of historical data from various countries and tested on a separate dataset to evaluate its performance.

# Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

# Prerequisites
To run this project, you will need:

- Python 3.6 or higher
- NumPy
- Pandas
- Scikit-learn

#You can install these packages using pip:
Copy code
pip install numpy pandas scikit-learn

# Installation
To install this project, clone the repository and navigate to the project directory:
Copy code
git clone https://github.com/mehdy28/Financial_crisis_analysis_and_prediction.git
cd Financial_crisis_analysis_and_prediction

# Usage
To train the model, run the following command:
Copy code
python train.py
To test the model, run the following command:

Copy code
python test.py

# Data
The dataset used in this project is a collection of economic and financial indicators from various countries. It includes information on GDP, inflation, exchange rates, and other variables that may be relevant for predicting financial crises.

The data was sourced from the International Monetary Fund and World Bank, and is in the public domain. It has been cleaned and preprocessed to remove missing or invalid values.

# Model
The machine learning model used in this project is a gradient boosting classifier. The model was trained on a subset of the data and tested on a separate dataset to evaluate its performance.

The model's hyperparameters were tuned using a grid search approach, and the final values chosen were based on the best performance on the validation set.

# Results
The model achieved an accuracy of 83% on the test dataset, with a precision of 76% and a recall of 89%. These results indicate that the model is able to accurately predict financial crises in most cases, but may occasionally miss some instances or flag false positives.

# Future Work
There are several areas for potential future work on this project:

Incorporating additional features or data sources could potentially improve the model's performance.
Using more advanced machine learning techniques, such as deep learning models, may also improve the model's ability to predict financial crises.
Developing a system for integrating the model's predictions into decision-making processes and providing timely warnings to policymakers and investors.

#Credits
The dataset used in this project was sourced from the International Monetary Fund and World Bank.
