# Machine Learning Challenge

## Project Objective

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

The purpose of this project was to craete multiple machine learning models and compare them to identify the best model for classifying candidate exoplanets from the raw dataset.

## Methods Used

* Machine Learning
    

## Technologies

* Python
* Scikit-Learn
* Pandas, Jupyter
    

## Process

1. ### Preprocess the Data

    * Preprocessed the dataset prior to fitting the models.
    * Performed feature selection and removed unnecessary features.
    * Used `MinMaxScaler` to scale the numerical data.
    * Separated the data into training and testing data.          

2. ### Tune Model Parameters

    * Used GridSearch to tune model parameters.
    * Tuned and compared two different classifiers: `Linear Regression algorithm` and `Random Forest algorithm`
    

## Analysis

### Model-1 Linear Regression

* `Training Data Score = 0.84837`
* `Testing Data Score = 0.84439`
* Using GridSearchCV to tune the model's parameters `Score = 0.884796`

### Model-2 Random Forest

* `Training Data Score = 1.0`
* `Testing Data Score = 0.90217`
* Using GridSearchCV to tune the model's parameters `Score = 0.893568`  

    
## Conclusion

In conclusion, based on the results above, the Random Forest algorithm has a higher accuracy than the Linear Regression algorithm. The hyperparameters tuning did help to increase the efficiency in both the models. After hyperparameters tuning, Random Forest has a slightly higher performance than Linear Regression.