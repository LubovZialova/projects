# Улучшение процесса обогащения золота 
## Исходные данные:
gold_recovery_train_new.csv — обучающая выборка; gold_recovery_test_new.csv — тестовая выборка; gold_recovery_full_new.csv — исходные данные.

## Цель: 
выполнить прототип модели машинного обучения для предсказания коэффициента восстановления золота из золотосодержащей руды для оптимизации производства (чтобы не запускать предприятие с убыточными характеристиками).

## Задачи:
Подготовить данные (выполнить предобработку данных);
Провести исследовательский анализ данных; 
  - Изучить изменение концентрации металлов (Au, Ag, Pb) на различных этапах очистки. 
  - Сравнить распределения размеров гранул сырья на обучающей и тестовой выборках. 
  - Исследовать суммарную концентрацию всех веществ на разных стадиях: в сырье, в черновом и финальном концентратах.
Построить и обучить модель.

## Навыки и инструменты:
- python
- pandas
- numpy
- seaborn
- matplotlib
- scipy
- sklearn.preprocessing.StandardScaler
- sklearn.tree.DecisionTreeRegressor
- sklearn.ensemble.RandomForestRegressor
- sklearn.linear_model.LinearRegression
- sklearn.metrics.mean_absolute_error
- sklearn.metrics.mean_absolute_errormake_scorer
- sklearn.model_selection.GridSearchCV
- sklearn.dummy.DummyRegressor

## Общий вывод:
Провела обучение выбранных моделей для стадий грубой и тонкой очистки, выполнила проверку лучшей модели для запуска в производство на тестовом наборе.
