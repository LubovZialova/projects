# Поиск токсичных комментариев
## Исходные данные: 
В вашем распоряжении набор данных с разметкой о токсичности правок описания товара Интернет-магазин «Викишоп». Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.

## Цель: Обучите модель классифицировать комментарии на позитивные и негативные, а также построить модель со значением метрики качества F1 не меньше 0.75.

## Задачи:
  - Подготовить данные.
  - Обучите разные модели.
  - Выбрать лучшую модель, сделать выводы.
## Навыки и инструменты:
  - pandas
  - numpy
  - nltk
  - lightgbm
  - nltk.corpus.wordnet
  - nltk.corpus.stopwords as nltk_stopwords
  - nltk.stem.WordNetLemmatizer
  - sklearn.model_selection.train_test_split, cross_val_score, GridSearchCV
  - sklearn.linear_model.LogisticRegression
  - sklearn.ensemble.RandomForestClassifier
  - sklearn.feature_extraction.text.TfidfVectorizer
  - sklearn.metrics.f1_score
  - lightgbm.LGBMClassifier

## Общий вывод:
Было проведено обучение выбранных моделей для определения токсичных комментариев, проведена провкерка выбранных обученных моделей на тестовом наборе и выбрана одна наиболее удачная для использования Интернет-магазином. 
