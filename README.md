## Purpose of the Project
Main purpose of this project is to Predict the price of flight depending on the different features. From data cleaning, feature engineering, EDA to creating best model based on optimum features this project takes care of everything.
## Data Overview
In this dataset price of different flights are mentioned depending on the other fearutes in the Datasets. Apart from that some of the other important variables are as below


![image](https://user-images.githubusercontent.com/66120808/213873435-11f5f9e9-ba9f-40d7-aad1-bf419063b93f.png)

## Feature Engineering
Feature engineering is the process of selecting, manipulating, and transforming raw data into features that can be used in supervised learning. In order to make machine learning work well on new tasks, it might be necessary to design and train better features. While developing a fine tuned model with desired output, it was very important to care of Feature Engineering and here also, I have taken all the necessary steps when it comes to features engineering which are below

### Convering Duration feature into desired data type
Here in below steps I have tried to convert duration of the journet into int type and created 2 features hours and minutes from it

- Earlier

![image](https://user-images.githubusercontent.com/66120808/213873892-6d230b2e-adcc-4b44-a42c-7b8bfbddd4e6.png)

Here some necessart impution were done below

![image](https://user-images.githubusercontent.com/66120808/213873924-d8f79656-5e41-4d8a-b46e-e8c52d2b40b2.png)

Final Output

![image](https://user-images.githubusercontent.com/66120808/213873936-ba429d29-7259-44ff-8a50-793e80e997f4.png)

### Categorical Values Imputation
- For the categorical features like "Airlines", "Source" etc one hot encoding was done while droping one of the columns
- Values for features like "Total Stop" was encoded to be converted into numerical formart
- 
## EDA
After Data Cleaing and Feature Engineering, EDA has been done of the data generate better understanding from the Visulizations.

- Mean price
  Mean price of the flight depending on different aspects like Airlines, Flight Timing, Duration, Source etc. Below pictures shows mean price depending on the features   mentioned below

![image](https://user-images.githubusercontent.com/66120808/213874295-400f4280-683c-492a-8779-e9786f923a30.png)
![image](https://user-images.githubusercontent.com/66120808/213874307-d6818677-8901-4d22-8e05-9dce451c5ff1.png)

- All the major coorelated Matrixs which influences the price of a flight.
  Coorelation has been findind between all the featues in the dataset in comparison with our dependent variable
- Feature Importance.
  Here in this step feature important of all the independent feaures were calculated and visulized below. It will tell us mode about the top features which highly imfulence the dependent variabels.
  ![image](https://user-images.githubusercontent.com/66120808/213874678-785a6f9f-42be-4a17-b4fc-3bec0d66b941.png)

## Machine Learning Model Development.
In this step I have treid to Find the best Machine Learning Algoritihm that can be use for creating the model and then found there best paramenrets using Hyperparameter Tuning.

Hyperparameter tuning is very critical to find the optimum hyperparameter to get the best results while developing the model. It not done correctly, it can give undesired values whihc will hamper the output of our model, hence our model will not be much credible.

![image](https://user-images.githubusercontent.com/66120808/213874892-c93e81ec-e8ac-4a91-a06c-ccd6b979f837.png)

After finding the optimum hyperparameter, model was fine tuned and some of the metrics which were coming were as below
MAE  :- 1167.80
MSE  :- 4065123.75
RMSE :- 2016.21
