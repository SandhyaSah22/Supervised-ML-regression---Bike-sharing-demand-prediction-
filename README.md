# Supervised-ML(regression)-Bike-sharing-demand-prediction
**Introduction**

Currently, Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of the bike count required at each hour for the stable supply of rental bikes.

**Problem statement**

We are tasked with predicting the number of bikes rented each hour so as to make an approximate estimation of the number of bikes to be made available to the public given a particular hour of the day.

**Overview of data**

The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

**Attribute Information:**

Date: year-month-day

Rented Bike count - Count of bikes rented at each hour

Hour - Hour of the day

Temperature-Temperature in Celsius

Humidity - %

Windspeed - m/s

Visibility - 10m

Dew point temperature - Celsius

Solar radiation - MJ/m2

Rainfall - mm

Snowfall - cm

Seasons - Winter, Spring, Summer, Autumn

Holiday - Holiday/No holiday

Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

**Steps involved**

*I. Performing EDA (exploratory data analysis)

*II. Drawing conclusions from the data

*III. Training the model

*IV. Evaluating metrics of our model

**Models used**

LINEAR REGRESSION
LASSO REGRESSION
RIDGE REGRESSION
ELASTIC NET REGRESSION
DECISION TREE
RANDOM FOREST
GRADIENT BOOSTING
GRADIENT BOOSTING REGRESSION

**Challenges**

A huge amount of data needed to be dealt while doing the project which is quite an important task and also even small inferences need to be kept in mind. 
As dataset was quite big enough which led more computation time.

**CONCLUSION**

During the time of our analysis, we initially did EDA on all the features of our dataset. We first analysed our dependent variable, 'Rented Bike Count' and also transformed it.  Then we analysed categorical variable and dropped the variable who had majority of one class, we also analysed numerical variable, found out the correlation, distribution and their relationship with the dependent variable. We also   removed some numerical features which had mostly 0 values and hot encoded the categorical   variables.

Next we implemented 7 machine learning algorithms Linear Regression, lasso, ridge, elastic Net, decision tree, Random Forest and XG Boost. We did hyperparameter tuning  to improve our model performance. The results of our evaluation are:

    • No overfitting is seen.

    • Random forest Regressor and Gradient Boosting gridsearchcv give the highest R2 score of 99% and 95%              

       respectively  for the Train Set and 92% for the Test set.

    • Feature Importance value for Random Forest and Gradient Boost is different.

    • We can deploy this model

However, this is not the ultimate end. As this data is time dependent, the values for variables like temperature, windspeed, solar radiation etc., will not always be consistent. Therefore, there will be scenarios where the model might not perform well. As Machine learning is an exponentially evolving field, we will have to be prepared for all contingencies and also keep checking our model from time to time. Therefore, having a quality knowledge and keeping pace with the ever evolving ML field would surely help one to stay a step ahead in future.
