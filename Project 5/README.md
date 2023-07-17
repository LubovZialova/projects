## Прогнозирование заказов такси
# Описание проекта:
В нашем рапоряжении данные компании «Чётенькое такси» о заказах такси в аэропортах.

# Цель: 
Привлекать больше водителей в период пиковой нагрузки.
# Задачи:
  - Загрузить данные и выполнить их ресемплирование по одному часу.
  - Проанализировать данные.
  - Обучить разные модели с различными гиперпараметрами.
  - Проверить данные на тестовой выборке и сделать выводы (Значение метрики RMSE на тестовой выборке должно быть не больше 48).
# Навыки и инструменты:
  - pandas
  - numpy
  - matplotlib
  - sklearn.linear_model.LinearRegression
  - sklearn.ensemble.RandomForestRegressor
  - sklearn.metrics.mean_squared_error
  - sklearn.model_selection.train_test_split, TimeSeriesSplit, GridSearchCV, cross_val_score
  - statsmodels.tsa.seasonal.seasonal_decompose
  - lightgbm
  - lightgbm.LGBMRegressor
  - catboost.CatBoostRegressor
# Общий вывод:
Было проведено обучение выбранных моделей, а также проверка обученных моделей на тестовом наборе и выбрана одна с наилучшими характеристиками.
