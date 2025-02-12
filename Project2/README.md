# Персонализация предложений постоянным клиентам интернет-магазина
[ipynb](Personal_model.ipynb)
## Описание проектов
Необходимо разработать модель, которая позволит персонализировать предложения постоянным клиентам, чтобы увеличить их покупательскую активность.
## Навыки и инструменты
* python
* pandas
* numpy
* matplotlib
* sklearn
* statsmodels.tsa.seasonal.seasonal_decompose
* sklearn.linear_model.LinearRegression
* lightgbm.LGBMRegressor
* catboost.CatBoostRegressor
* sklearn.metrics.root_mean_squared_error
* klearn.model_selection.cross_val_score
* sklearn.model_selection.GridSearchCV
* sklearn.model_selection.TimeSeriesSplit 

## Общий вывод
После проведенного исследования выяснилось что для повышения покупательской активности, следует отпровлять специальные предложения тем пользователям, кто склонен покупать товары для детей по акциям. Наиболее точная модель стала SVC, её точность на тестовых данных состовляет 92%. 




