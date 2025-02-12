# Прогноз количества заказов для сервиса такси
[ipynb](Time_model.ipynb)
## Описание проектов
Требуется спрогнозировать количество заказов такси на следующий час, чтобы привлекать больше водителей в период пиковой нагрузки.
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
Проведено исследование временного ряда на предмет трендовых и сезонных закономерностей, случайной составляющей. Проведено исследование трёх типов моделей, выбрана LightGBM.




