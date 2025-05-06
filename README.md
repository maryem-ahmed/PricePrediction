# PricePrediction
Project Idea
This project predicts the next day's stock price using Linear Regression
it uses historical data from a CSV file
Linear Regression Algorithm

Read the prices from CSV.

Assign x values (days) starting from 1.

Calculate:

sumX = sum of all x

sumY = sum of all prices

sumXY = sum of x*y

sumX2 = sum of x*x

Use formula:

m = (n*sumXY - sumX*sumY) / (n*sumX2 - sumX^2)

b = (sumY - m*sumX)/n

Predict the next price: y = m*(n+1) + b

