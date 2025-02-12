# Оптимизация производственных расходов, металлургического комбината 
[ipynb](Fin_model.ipynb)
## Описание проектов
Необходимо разработать модель, для контролирования температуры сплава
## Навыки и инструменты
* python
* pandas
* numpy
* matplotlib
* seaborn 
* sklearn
* sklearn.pipeline.Pipeline
* sklearn.linear_model.LinearRegression
* sklearn.neighbors.LGBMRegressor
* catboost.CatBoostRegressor
* sklearn.ensemble.RandomForestRegressor
* sklearn.model_selection.GridSearchCV
* sklearn.metrics.mean_absolute_error
* sklearn.metrics.r2_score


## Общий вывод
После проведенного исследования выяснилось, что для контроля температуры сплава необхадимо использовать модель `CatBoostRegressor`. Значение MAE на тестовых данных составила 6.34, что удовлетворяет условию и ниже значения 6.8.




