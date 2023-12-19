# Предсказание стоимости жилья

В проекте вам нужно обучить модель линейной регрессии на данных о жилье в Калифорнии в 1990 году. На основе данных нужно предсказать медианную стоимость дома в жилом массиве. Обучите модель и сделайте предсказания на тестовой выборке. Для оценки качества модели используйте метрики RMSE, MAE и R2.

## Задача:

Обучить модель линейной регрессии предсказывающую медианную стоимость дома в жилом массиве и сделайте предсказания на тестовой выборке. 


## Используемые библиотеки
- pandas <br>
- python <br>
- spark <br>


## Итоги проекта

Метрики оценки модели без категориальных переменных: <br>
RMSE: 81097.491594 <br>
MAE: 58068.517936 <br>
r2: 0.511866 <br>

Метрики оценки модели с категориальными переменными: <br>
RMSE: 73713.406219 <br>
MAE: 52746.654759 <br>
r2: 0.596710 <br>

По результату исследования модель с категориальными переменными показала лучшие показатели, хотя модель далека от идеальной. При выборе из двух модели, выберем модель с категориальными переменными.

```python

```
