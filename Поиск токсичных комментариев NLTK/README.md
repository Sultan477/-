## Проект 13. Поиск токсичных комментариев (с NLTK)


### Цель проекта

Провести исследование с целью построения модели машинного обучения, которая поможет классифицировать комментарии на позитивные и негативные.

Результаты исследования позволят магазину искать токсичные комментарии и отправлять их на модерацию.

Входные данные: набор данных с разметкой о токсичности правок.


### Задачи проекта

Решим поставленную в проекте задачу **с помощью библиотеки *NLTK***.

1. Изучить данные.
2. Подготовить данные.
3. Лемматизировать данные.
4. Построить и обучить модели.
5. Протестировать лучшую модель.
6. Написать общий вывод.

Построим модель со значением метрики качества *F1* не меньше 0.75.


### Навыки и инструменты

- lightgbm
- nltk.corpus
- nltk.stem 
- numpy
- pandas
- python
- re
- sklearn.feature_extraction.text
- sklearn.linear_model
- sklearn.metrics
- sklearn.model_selection
- sklearn.tree
- sklearn.utils


### Общий вывод 
Не было обнаружено пропусков или дубликатов в данных, и все требуемые модели были успешно обучены.
Модель `Logistic Regression` показала лучший результат с точки зрения метрики `F1` исследования на тестовой выборке, ее оценка составляет 0.76.
