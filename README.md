# AUS_predict_rain
it's a `Kaggle` dataset that we try to predict will tomorrow being raining or not
https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package

the shape of dataset is (145460, 23). but it has too much missing values and outliers that I handled them in different ways.
And in the end I predict with two estimators (logestic reg and RainForrestClassifier) with almost 85% accuracy.
