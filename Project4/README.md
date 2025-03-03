# Определение стоимости автомобилей
[ipynb](Fin_model.ipynb)
## Описание проектов
Необходимо разработать модель, для определения рыночной стоимости автомобиля
## Навыки и инструменты
* python
* pandas
* numpy
* matplotlib
* seaborn 
* sklearn
* sklearn.linear_model.LinearRegression
* lightgbm.LGBMRegressor
* catboost.CatBoostRegressor
* sklearn.model_selection.GridSearchCV
* sklearn.metrics.root_mean_squared_error


## Общий вывод
После проведенного исследования выяснилось, что для определения стоимости автомобиля необхадимо использовать модель `LightGBM`. Значение RMSE на тестовых данных составила 1659, что удовлетворяет условию и ниже значения 2500.
