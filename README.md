# Titanic

using machine learning to predict on the famous titanic csv


This project will be able to predict if a given passenger will survive the Titanic disaster (for us, we are fictioning).




# Data Description


|FEATURE | DESCRIPTION    |
|---------|---------------|
|Survived | Survival      |
|Pclass   | Ticket Class  |
|Name     |Name of Passenger|
|Sex      |Gender of Passenger|
|Age      | Age (Years)       |
|SibSp    |Number of Siblings/Spouses Aboard|
|Parch    |Number of Parents/Children Aboard|
|Ticket   |Ticket Number                    |
|Fare     | Passenger Fare                  |
|Cabin    | Cabin Number                    |
|Embarked | Port of Embarkation             |



# ON EDA 

1. 25% of the passengers are in the age lower than 21, while 50% are lower than 28 and 75% are lower than 39. Also often called the 25th percentile (or 1st quartile), the median, and the 75th percentile (or 3rd quartile). 
2. Feature engineering was also done on add further columns to the data. 

# On Modelling and Results

We employed the use of Machine Learning models for model training and prediction.
1. Random Forest Classifier.
2. LogisticRegression. 


# [Note]

The model is unlikely to be useful at all if the model doesn't match the training data closely enough (underfitting). So, on both the train and test sets, a model that underfits would have poor accuracy. To address this, by increasing model complexity, e.g. by engineering better functionality, enhancing the imputation of missing values, tuning model parameters, and even fully switching models, we need to enhance the model.

The model is unlikely to be useful on data that it has not seen before, e.g. the test set, if the model matches the training data too closely (overfitting). So, on the test set, a model that overfits would have much lower accuracy than the training set. To fix this, we can: I train with more data, use only the more important characteristics of the model, and prefer simpler models over complex models.

