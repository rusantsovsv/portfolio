# Отток клиентов

Задача: спрогнозировать, уйдёт клиент из банка в ближайшее время или нет, на основе предоставленых исторических данных о поведении клиентов и расторжении договоров с банком.

Цели проекта: построить модель с предельно большим значением F1-метрики (не менее 0.59). Проверить F1-метрику на тестовой выборке.

Дополнительно: измерить AUC-ROC, сравнить её значение с F1-метрикой.

## Какой стек использовался?
- numpy
- pandas
- matplotlib
- sklearn

## Какие модели сравнивались?
- LogisticRegression
- DecisionTreeClassifier
- RandomForestClassifier
