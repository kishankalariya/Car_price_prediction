# Aim

The aim of car price prediction is to create a model that can forecast the worth of a vehicle based on a collection of relevant data such as the brand, model, year, miles, and condition. Stakeholders in the automobile sector may make better informed decisions, avoid financial risk, and enhance overall profitability by properly anticipating car pricing.


![Car_img](https://kishankalariya.github.io/images/Car.jpg)

## Usecase 

Car price prediction is commonly used in the **automotive industry** and is used for a variety of purposes, including:

- Auto dealerships and individual buyers and sellers can utilise price prediction models to evaluate the fair market worth of a vehicle, which can aid in negotiating a better price.

- Insurance firms can utilise automobile price prediction models to estimate a vehicle's worth in the case of an accident, which can help them establish the proper amount of coverage and rates.

- Banks and other financial institutions can use car price prediction models to determine the value of a vehicle when issuing car loans, which can help them assess risk and determine interest rates.

- To discover market trends and customer preferences, vehicle manufacturers and dealerships can utilise car price prediction models. This can help them create specialised marketing and sales strategies.
--------


## Steps

![Steps](https://github.com/kishankalariya/Car_price_prediction/blob/master/Steps_img/car%20price%20predition.drawio.png?raw=true)




1. **EDA**

>Here are some techniques that may be used during the EDA stage of a car price prediction project:

- Data visualization: Techniques for visualisation, such as histograms, scatter plots, and box plots, can be used to identify trends and patterns in the data. For example, a scatter plot may be used to identify the relationship between car price and mileage.

- Correlation analysis: Correlation analysis can be used to identify the strength and direction of the relationship between different features in the data. This can aid in determining which features are most strongly related to car price.

- Outlier detection: Outliers in the data can have a significant impact on the performance of a car price prediction model.

- Missing value imputation: Missing values in the data can also have a significant impact on the performance of a car price prediction model. Techniques such as mean imputation, median imputation, and regression imputation can be used to impute missing values.

2. **Data preprocessing**

- Once understand the data by visualising it, it must be preprocessed to prepare it for modeling. I have applied techniques such as data normalization, feature scaling, and handling missing data.

3. **Feature selection and engineering** 

- Feature selection techniques applied to identify the most relevant features for predicting car prices.


4. **Model selection**

- There are many different types of models that can be used for car price prediction. However, in this project, I have only explored linear regression.Linear regression is a simple and widely-used technique for predicting a numeric target variable (in this case, the price of a car) based on one or more predictor variables (such as the car's mileage, make, model, year, etc.). Some advantages of linear regression for car price prediction include:

- Interpretability: Linear regression provides a simple and interpretable model that can help to identify which factors are most strongly associated with car prices.

- Ease of use: (FYI: this was my first data science project) Linear regression is a relatively simple and easy-to-understand model that can be trained quickly and does not require a lot of computational power.

5. **Model training and tuning** 

- I trained the model with 20% test data and 80% training data from the original data set. I haven't explored fine tuning which may help to improve model performance and prevent overfitting.(e.g. cross-validation, regularization, and hyperparameter tuning ), but I would like to in my next project.

6. **Model evaluation** 

- Finally, the model was evaluated using appropriate metrics. (e.g., mean absolute error (MAE))



## **Future Development**

> In the future, I am interested in using Streamlit as an open-source app framework to develop web applications for my car price prediction project. Streamlit is a powerful tool that can help me create beautiful and interactive web apps in a short amount of time, and it is well-suited for use in machine learning and data science projects.

> Note: linear regression has some limitations as well. For example, it assumes a linear relationship between the predictors and the target variable, which may not always be true. In addition, linear regression may be sensitive to outliers (e.g., Vintage car) and can be affected by multicollinearity (when predictor variables are highly correlated with each other). Other models, such as decision trees, random forests, or neural networks, may be more suitable for some car price prediction problems. As a result, it is worthwhile to investigate alternative algorithms for the same problem. 
