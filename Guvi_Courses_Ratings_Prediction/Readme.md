# RATINGS OF GUVI COURSES

## About:

This project is about the Guvi courses Rating, Each cource will get rating from the scholars. The data is given by the Guvi Officials for theEducation purpose, The given dataset has to be worked with the preprocessing and used the preprocessed data for the model building. The dataset is used to create a regression model which is used to predict the Rating of the guvi courses using the past data.

The following project is about Guvi Courses. The dataset for this project contains information
about Guvi courses in various categories, including course title, URL, price, number of
subscribers, number of reviews, number of lectures, course level, rating, content duration,
published timestamp, and subject. With this dataset, we can track the performance of courses
and uncover opportunities to generate revenue.

## Technologies used:
1. Python

2. Scikit Learn

3. Pandas

4. Matplotlib 

5. Seaborn

6. Pickle

7. Numpy

## Model Preperation and Predict the Rating:

The data is used to be preprocessed and dealt with null values, outliers and skewness. The whole process is done by python scripting. Pyhon libraries are used to do the most of work heare. First the data frame is created with the Pandas using the given csv file.

The data frame is checked for null values which can be dealt with the mean, meadian and mode based upon the data understanding. Then the skewnedd in reduced with the log transformation. Then the outliers has to be removed or modified using the methods like z-scores method, Robust method , IQR method and etc. I used IQR( Inter Quartile Range) method to remove the outliers.

Then the correlation between the features has to be checked before selecting the features for the model creation. The features and target values will be splitted as x and y and the the data will be splitted into training and testing data.

The model is builded with the training and testing data using multiple regressors, I selected Random forest Regressor for the model building and then used parameter grid search to tweek the model for better results.

Testing the model for the rating prediction. And then the model is saved with pickle file and then the model is loaded from the pickle file to check for the output.

## Conclution

The created model is used to predict the ratings of the future courses, The ratings would be more or less Assumptions only since the ratings can be affected by more outside features and with the each individual review and ratings. Even though the Maching learning Model will predict the rating as per the past data accurate as per the dataset.

I have shared the jupyter notebook and pickle files for the public usage use it to check yourself the ratings prediction.