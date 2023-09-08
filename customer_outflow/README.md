# Прогнозирование оттока клиентов
[ipynb](https://github.com/tkachuk45/portfolio/blob/main/customer_outflow/customer_outflow_project.ipynb)

## Описание проекта
Оператор связи хочет научиться прогнозировать отток клиентов. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. Необходимо подготовить модель машинного обучения, которая предскажет расторжение договора клиентом. Метрика качества - AUC-ROC. Установленный порог AUC-ROC для качественной модели - 0.85.

Для обучения модели заказчик предоставил датасеты с персональными данными о некоторых клиентах, информацией о подключенных услугах, оплатах и договорах.

## Использованные библиотеки
- **pandas**
- **numpy**
- **matplotlib**
- **seaborn**
- **phik**
- lightgbm.**LGBMRegressor**
- lightgbm.**log_evaluation**
- catboost.**CatBoostRegressor**
- sklearn.compose.**make_column_transformer**
- sklearn.linear_model.**LogisticRegression**
- sklearn.ensemble.**RandomForestRegressor**
- sklearn.dummy.**DummyRegressor**
- sklearn.metrics.**roc_auc_score**
- sklearn.metrics.**accuracy_score**
- sklearn.metrics.**confusion_matrix**
- sklearn.metrics.**roc_curve**
- sklearn.model_selection.**GridSearchCV**
- sklearn.model_selection.**train_test_split**
- sklearn.pipeline.**make_pipeline**
- sklearn.impute.**SimpleImputer**
- sklearn.preprocessing.**StandardScaler**
- sklearn.preprocessing.**OneHotEncoder** 

## Общий итог
Мы исследовали данные и составили план работы. Затем подготовили и проанализировали признаки, обучили модели и выбрали лучшую. Далее протестировали лучшую модель и проанализировали важность признаков обученной модели. Модель показала адекватность и отличный результат по метрике AUC-ROC.
