# Обучение модели классификации комментариев

## Краткая суть

* Необходимо обучить модель классифицировать комментарии на позитивные и негативные

## Описание

* Интернет-магазин «Викишоп» запускает новый сервис, где пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.

## Критерии оценки модели

* Значение метрики F1 на тестовой выборке должно быть не меньше 0.75

## План выполнения проекта

1. Загрузить и подготовьть данные.
2. Обучить разные модели.
3. Сделать выводы.

## Вывод:
* произвели предобрабтку текстовой информации, чтобы данные можно было подавать в модель.
* по результатам лучше всего себя показал LGBMClassifier со значением f1 0.78
