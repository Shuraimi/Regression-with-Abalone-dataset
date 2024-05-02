# Regression-with-Abalone-dataset

This is a regression project on the Abalone dataset on kaggle. In this project, the goal is to predict the age of Abalone given features.

I used the features in dataset to predict number of rings in abalone because age equals rings + 1.5

This problem was a hosted playground competition on kaggle and I got 994th rank out of 2600 (a bit better than the previous competition).

Here's the link to competition 
(https://www.kaggle.com/competitions/playground-series-s4e4/)

<img src="https://github.com/Shuraimi/zero-to-mastery-ai-ml-course/blob/main/images/6-step-ml-framework.png" />

## Steps I followed:-

1. **Problem Definition** - Predicting whether the price of a bulldozer given the features.
2. **Data** - Downloaded and imported the data into a DataFrame from Kaggle.
3. **Evaluation** - The evalutaion metric is RMSLE ( root mean squared log error)
4. **Features** - Defined a data dictionary which defines what a feature means.

<img src='https://github.com/Shuraimi/zero-to-mastery-ai-ml-course/blob/main/images/sklearn-workflow.png' />

5. **Modelling** - This includes
   * Splitting data into features(X) and labels(y)
   * Splitting the features and labels into train and validation splits because test dataset is not available 
   * Choosing the right model/s
   * Instantiating a model
   * Fitting the model/s
   * Evaluating the model
   * Choosing the model with best performance
   * Hyperparameter tuning for better performance of model

After the features section, we import all the necessary libraries, get the data ready and perform Exploratory Data Analysis (EDA) to learn more about the data.

## What I learnt from this project?

* I learnt how to take part in ML competitions on kaggle.
* Learnt how to choose models to try and also select the best model based on its performance on the evaluation metric.
* Make a custom scorer using`make_scorer` because RMSLE is not available in `cross_val_score`
* Tune `RandomForestRegressor` and `XGBRegressor` using Optuna.
* At last, create a submission file with your predictions on the best trained model and submit to kaggle.
* I also learnt many more things while building this project.

This is my second project, and I've learned many things while building it. I'm still eager to learn more through building projects and competing in Kaggle competitions.

Here are scores I got on test data on kaggle for different models I tried.
<img src='https://raw.githubusercontent.com/Shuraimi/Regression-with-Abalone-dataset/main/images/IMG_20240501_104631.jpg'/>

