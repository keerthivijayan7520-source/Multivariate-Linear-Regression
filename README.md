# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
Import the required libraries such as NumPy and Scikit-learn.
### Step2
Load the dataset and separate the input features (X) and output variable (Y).
### Step3
Split the dataset into training and testing data.
### Step4
Train the Multivariate Linear Regression model using the training data.
### Step5
Predict the output using the testing data and display the predicted results.

## Program:
### Developed by: Keerthi.V
### Reference No: 26010139
### Import pandas as pd
### from sklearn import linear_model
### df = pd.read_csv("carsemission.csv")
### X = df[['Weight', 'Volume']]
### y = df['CO2']
### regr = linear_model.LinearRegression()
### regr.fit(X, y)
### print('Coefficients:', regr.coef_)
### print('Intercept:', regr.intercept_)
### input_data = pd.DataFrame({'Weight': [3300], 'Volume': [1300]})
### predictedCO2 = regr.predict(input_data)
### print('Predicted CO2 for the corresponding weight and volume:', predictedCO2)
## Output:
<img width="928" height="817" alt="WhatsApp Image 2026-11-25 at 4 20 16 PM" src="https://github.com/user-attachments/assets/66bca3f0-fe39-4134-8308-d971b6983420" />


## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
