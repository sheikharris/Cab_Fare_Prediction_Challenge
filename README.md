
# Cab Fare Prediction AI Challenge

The aim of the challenge is to predict the cab fare using the given dataset


## Dataset

- Train.csv
- test.csv

#### TRAIN.csv 
Consists of 9 attributes:

- index
- time_stamp - epoch time (in seconds) when the cab was booked
- cab_provider - company (Uber/Lyft)
- source - the starting point of the cab ride
- destination - the destination of the cab ride
- distance - the distance between source and destination
- surge_multiplier - multiplier by which price increased
- cab_type - the type of cab (Uber Pool, Uber XL, etc. )
- fare - cab fare in USD (Target Attribute)

#### TEST.csv 
Consists of the testing data required for prediction and consists of 8 attributes:

- index
- time_stamp - epoch time (in seconds) when the cab was booked
- cab_provider - company (Uber/Lyft)
- source - the starting point of the cab ride
- destination - the destination of the cab ride
- distance - the distance between source and destination
- surge_multiplier - multiplier by which price increased
- cab_type - the type of cab (Uber Pool, Uber XL, etc. )

## Feature engineering 

- Create a extra features like Days form time_stamp.
- One hot encoding for categorical data.
- final data had 41 columns 

## Model 

- Linear Regression 
- Polynomial Regression
- Random Forest [woked well]
- Nerual network 

## Result









  


![](https://github.com/sheikharris/Cab_Fare_Prediction_Challenge/blob/main/image/Annotation%202021-09-21%20214309.jpg)


  
