# Copper Industry Machine Learning Models

## Problem Statement
The copper industry deals with less complex data related to sales and pricing. However, this data may suffer from issues such as skewness and noisy data, which can affect the accuracy of manual predictions. Dealing with these challenges manually can be time-consuming and may not result in optimal pricing decisions. A machine learning regression model can address these issues by utilizing advanced techniques such as data normalization, feature scaling, and outlier detection, and leveraging algorithms that are robust to skewed and noisy data. 

Another area where the copper industry faces challenges is in capturing the leads. A lead classification model is a system for evaluating and classifying leads based on how likely they are to become a customer. You can use the STATUS variable with WON being considered as Success and LOST being considered as Failure and remove data points other than WON, LOST STATUS values.

## Solution
The solution includes the following steps:
1. **Data Exploration**: Exploring skewness and outliers in the dataset.
2. **Data Preprocessing**: Transform the data into a suitable format and perform any necessary cleaning and pre-processing steps.
3. **Regression Model**: Develop a machine learning regression model which predicts continuous variable ‘Selling_Price’.
4. **Classification Model**: Develop a machine learning classification model which predicts Status: WON or LOST.
5. **Streamlit Application**: Create a streamlit page where you can insert each column value and you will get the Selling_Price predicted value or Status(Won/Lost)

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
What things you need to install the software and how to install them
```
python=3.7
pandas
numpy
scikit-learn
streamlit
```

### Installing
A step by step series of examples that tell you how to get a development env running

Clone the repo:
```
git clone https://github.com/piyushrgone/Industrial-Copper-Modeling.git
```
Install packages:
```
pip install -r requirements.txt
```

### Running the tests
Explain how to run the automated tests for this system

### Deployment
Add additional notes about how to deploy this on a live system
