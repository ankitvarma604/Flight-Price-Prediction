## Purpose of the Project
Main purpose of this project is to Predict the price of flight depending on the different features. From data cleaning, feature engineering, EDA to creating best model based on optimum features this project takes care of everything
### Feature Engineering
There were different feature which had to be manipulated for better analysis, for example taking care of Duration Feature and converting it into int type using for loop and other such instances
- Creating new features after manipulating departure, arrival and duration hours for better analysis.
- Converting necessary onject types into datetime.
- Removing unnecessary values from the list for better analysis etc
### EDA
After Data Cleaing and Feature Engineering, EDA has been done of the data generate better understanding from the Visulizations.
- Mean price of the flight depending on different aspects like Airlines, Flight Timing, Duration, Source etc
- All the major coorelated Matrixs which influences the price of a flight.
- Fligh count depending on Departure Hour
### Machine Learning Model Development.
In this step I have treid to Find the best Machine Learning Algoritihm that can be use for creating the model and then found there best paramenrets using Hyperparameter Tuning.
- Found the best model by using some Regression Models and Comparing there scores using R2_Score and accuracy score and other such criteria.
- Created a pickle file for later phase in the pipelines.
