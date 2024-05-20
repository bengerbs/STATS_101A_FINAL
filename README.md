# STATS_101A_FINAL

## Problem Statement

A Chinese automobile company Geely Auto aspires to enter the US market by setting up their manufacturing unit there and producing cars locally to give competition to their US and European counterparts. They have contracted an automobile consulting company to understand the factors on which the pricing of cars depends. Specifically, they want to understand the factors affecting the pricing of cars in the American market, since those may be very different from the Chinese market. The company wants to know:

- Which variables are significant in predicting the price of a car.
- How well those variables describe the price of a car.
- Based on various market surveys, the consulting firm has gathered a large data set of different types of cars across the America market.

## Business Goal

We are required to model the price of cars with the available “independent” variables. It will be used by the management to understand how exactly the prices vary with the independent variables. They can accordingly manipulate the design of the cars, the business strategy etc. to meet certain price levels. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Data Description

The data at hand is divided into two data sets: Training and Testing. The training data set contains 1500 observations and has 23 predictors and the response variable PriceNew. 

The testing data set contains 500 observations and has 23 predictors and the response variable PriceNew.

The variables are described as follows:
- "Manufacturer"
- "Model"
- "Type"
- "MPG.highway"
- "AirBags"
- "DriveTrain"
- "Cylinders"
- "EngineSize"
- "Horsepower"
- "RPM"
- "Rev.per.mile"
- "Man.trans.avail"
- "Fuel.tank.capacity"
- "Passengers"
- "Length"
- "Wheelbase"
- "Width"
- "Turn.circle"
- "Rear.seat.room"
- "Luggage.room"
- "Weight"
- "Origin"
- "Make"
- "PriceNew"

## Project's Main Goals
- Use the training data to build a valid MLR.
- Check diagnostics
- Compete to make your MLR model the “best” it can be. (create new variables out of existing ones, transformations, checking leverages and outliers, …etc.)
- Your Task is to predict the prices of the cars in the testing data and create a solution file and submit it on kaggle to check your predictions accuracies.
- The Competition ranks students’ submissions based on their testing R2.
- Accurate, Valid and Simple are the best models.
- The submission file must have two columns with 500 rows: The first column named Ob and the second named “PriceNew” in a csv format only.
