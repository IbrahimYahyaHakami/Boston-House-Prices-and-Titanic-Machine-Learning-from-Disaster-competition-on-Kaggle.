## Predicting Boston House Prices and Titanic-Machine-Learning-from-Disaster competition on Kaggle.



###### Team:  Ibrahim Hakami - Mohammed Alqahtani - Sumaiah Alsadhan



### Core
#### Kaggle
 - Is a popular platform for machine learning competitions. It combines data, code and users in a way to allow for both collaboration and competition.
Accessing and Reading Data Sets
 - We will read and process the data using pandas
 - The training dataset includes 1,460 datapoints, 80 features, and 1 label., the test data contains 1,459 datapoints and 80 features for house prices
 - The training dataset includes 891 datapoints, 12 features, and 1 label., the test data contains 891 datapoints and 80 features for Titanic-Machine-Learning-from-Disaster
#### EDA
 - Data Exploration
  - by using .head(), .shape , .info()
 - Feature Engneering
  - Filling missing values:
   - catigorical : based on the discretion of the data Nan refers to inapplicability or availability of that feature hence it was filled with 'None'.
   - numerical : the lareger of missed numerics are filled with mode,  some are filled with 0, one feature filled with median, and numeric fetures that resemble dates or categories are changed to String.
 - Visualization
#### Modeling
 - Models used: 
  - LassoCV
  - RidgeCV
  - ElasticNetCV
  - RandomForestRegressor
  - GradientBoostingRegressor
  - others

#### Predict and Submit
 - [kaggle kernal for Predicting Boston House Prices](https://www.kaggle.com/mohammadqahtani/p2-kaggle-competition-house-prices) , with a score of 0.13571 / 0.
 - [Titanic-Machine-Learning-from-Disaster](https://www.kaggle.com/ibrahimhakami/titanic-machine-learning-from-disaster?scriptVersionId=23139133), with a score of 0.79425 / 1 .
### Target
Getting the highest score on kaggel for sale price prediction.

## Acknowledgments

* MISK academy
* General assembly
* special thanks to our instructors for all the help they provided.