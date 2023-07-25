# Определение негативных комментариев
[ipynb](https://github.com/tkachuk45/portfolio/blob/main/toxic_comments/toxic_comments_project.ipynb)

## Описание проекта
Необходимо подготовить модель, которая классифицирует комментарии пользователей на негативные и позитивные. Метрика качества - F1-мера. Установленный порог F1 для качественной модели - 0.75. Модель поможет искать токсичные комментарии и отправлять их на модерацию.

Для обучения модели заказчиком предоставлен размеченный корпус текстов с негативными и позитивными комментариями.

## Использованные библиотеки
- **pandas**
- **numpy**
- **re**
- **spacy**
- nltk.corpus.**stopwords**
- sklearn.feature_extraction.text.**TfidfVectorizer**
- sklearn.metrics.**f1_score**
- sklearn.model_selection.**GridSearchCV**
- sklearn.model_selection.**train_test_split**
- sklearn.linear_model.**LogisticRegression**
- sklearn.svm.**LinearSVC**
- sklearn.dummy.**DummyClassifier**
- sklearn.pipeline.**Pipeline**

## Общий итог
Мы обработали и подготовили корпус текстов, затем обучили модели и выбрали лучшую из них. Модель показала адекватность и хорошее качество по метрике F1.
