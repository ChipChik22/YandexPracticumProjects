# Прогнозирование количества заказов такси на следующий час

## Краткая суть

* Необходимо построить модель, которая будет прогнозировать количество заказов такси на следующий час

## Описание

* Компания собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Нужно построить модель для такого предсказания. **Проект выполнен полностью**

## Критерии оценки модели

* Значение метрики RMSE на тестовой выборке должно быть не больше 48.

## План выполнения проекта

1. Загрузить данные и выполнить их ресемплирование по одному часу.
2. Проанализировать данные.
3. Обучить разные модели с различными гиперпараметрами. Сделать тестовую выборку размером 10% от исходных данных.
4. Проверить данные на тестовой выборке и сделать выводы.

## Вывод:
* создали дополнительные фичи
* CatBoostRegressor справляется лучше всех с результатом RMSE 41
