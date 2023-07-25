# Прогнозирование заказов такси на следующий час
[ipynb](https://github.com/tkachuk45/portfolio/blob/main/taxi_orders/taxi_orders_project.ipynb)

## Описание проекта
Необходимо подготовить модель, которая спрогнозирует количество заказов такси на следующий час. Метрика качества - RMSE. Установленный порог RMSE для качественной модели - не более 48. Модель поможет привлекать больше водителей в период пикового потока заказов.

Для обучения модели заказчиком предоставлен датасет с временным рядом периодичность 10 минут и количеством заказов для каждого периода.

## Использованные библиотеки
- **pandas**
- **numpy**
- **matplotlib**
- statsmodels.tsa.seasonal.**seasonal_decompose**
- statsmodels.graphics.tsaplots.**plot_acf**
- statsmodels.graphics.tsaplots.**plot_pacf**
- sklearn.linear_model.**LinearRegression**
- sklearn.linear_model.**Ridge**
- sklearn.linear_model.**Lasso**
- sklearn.linear_model.**ElasticNet**
- sklearn.dummy.**DummyRegressor**
- sklearn.metrics.**mean_squared_error**
- sklearn.model_selection.**GridSearchCV**
- sklearn.model_selection.**TimeSeriesSplit**
- sklearn.model_selection.**train_test_split**
- sklearn.pipeline.**Pipeline**
- **warnings**


## Общий итог
Мы выполнили ресемплинг временного ряда, проанализировали данные и создали признаки. Затем обучили модели и выбрали лучшую из них. Модель показала адекватность и отличный результат по метрике RMSE.
