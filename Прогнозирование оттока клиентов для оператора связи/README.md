# Прогнозирование оттока клиентов для оператора связи
## Дано: 
Оператор связи «Ниединогоразрыва.ком» хочет научиться прогнозировать отток клиентов. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах.

## Цель: 
построить модель способную наиболее точно спрогнозировать, уйдёт клиент от оператора в ближайшее время или нет.

## Задачи:
  - Выполнить предобработку данных
  - Проверить корреляцию признаков
  - Провести исследовательский анализ данных, сравнить распределения признаков для ушедших и оставшихся клиентов
  - Устранить дисбаланс данных
  - Обучить модели RandomForestClassifier, LogisticRegression, LGBMRegressor на тренировочных данных
  - Проверить лучшую модель (с лучшей метрикой AUC-ROC) на тестовых даных (значение AUC-ROC должно быть > 0.85), измерить accuracy
  - Сравнить значение AUC-ROC лучшей модели и случайной модели.
    
## Навыки и инструменты:
  - pandas 
  - numpy 
  - seaborn 
  - matplotlib.pyplot
  - sklearn.preprocessing.OneHotEncoder, StandardScaler
  - sklearn.metrics.accuracy_score, roc_auc_score, roc_curve
  - sklearn.model_selection.cross_val_score, train_test_split, GridSearchCV
  - sklearn.ensemble.RandomForestClassifier
  - sklearn.linear_model.LogisticRegression#логистическая регрессия
  - sklearn.utils.class_weight.compute_class_weight 
  - lightgbm
  - lightgbm.LGBMClassifier
  - catboost.CatBoostClassifier
  - phik
  - phik.resources

## Общий вывод:
Было проведено обучение выбранных моделей, а также проверка обученных моделей на тестовом наборе и выбрана одна с наилучшими характеристиками.
