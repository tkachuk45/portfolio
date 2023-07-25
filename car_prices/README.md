# Определение рыночной стоимости подержанного автомобиля
[ipynb](https://github.com/tkachuk45/portfolio/blob/main/car_prices/car_prices_project.ipynb)

## Описание проекта
Необходимо построить модель, которая определяет рыночную стоимость подержанного автомобиля. Метрика качества - RMSE. Установленный порог RMSE для качественной модели - не более 2500. Модель поможет привлечь новых клиентов за счет удобной функции расчета цены. Для заказчика важно не только качество предсказания модели, но и время обучения и время предсказания, поэтому необходимо выбрать оптимальную модель, учитывая эти пожелания.

Для обучения модели заказчиком предоставлен датасет с данными о конкретных автомобилях: их характеристики, информация о комплектации и рыночная цена.

## Использованные библиотеки
- **pandas**
- **numpy**
- **matplotlib**
- **seaborn**
- **time**
- lightgbm.**LGBMRegressor**
- catboost.**CatBoostRegressor**
- sklearn.compose.**make_column_transformer**
- sklearn.linear_model.**Ridge**
- sklearn.ensemble.**RandomForestRegressor**
- sklearn.dummy.**DummyRegressor**
- sklearn.metrics.**mean_squared_error**
- sklearn.model_selection.**GridSearchCV**
- sklearn.model_selection.**RandomizedSearchCV**
- sklearn.model_selection.**train_test_split**
- sklearn.pipeline.**make_pipeline**
- sklearn.preprocessing.**StandardScaler**
- sklearn.preprocessing.**OneHotEncoder** 
- sklearn.preprocessing.**OrdinalEncoder**
- **warnings**

## Общий итог
Мы проанализировали и обработали данные. Затем подготовили признаки, обучили модели и сравнили их по времени обучения, качеству и времени предсказания. Далее выбрали оптимальную модель с отличным качеством и высокой скоростью работы. Модель показала адекватность и прекрасный результат по метрике RMSE.
