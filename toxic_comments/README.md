# Поиск токсичных комментариев

## Данные

В наличии были следующие данные о комментариях:

- текст
- разметка о токсичности

## Задачи проекта

Определение токсичности комментарии.

## Описание проекта

Интернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Требуется инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.

## Навыки и инструменты

- Python
- Pandas
- nltk
- tf-idf

## Вывод по итогам исследования

Лучше всего с предсказанием токсичных комментариев справиласть модель логистической регрессии, но были рассмотрены лишь линейные алгоритмы из-за большого числа параметров. Возможно результат был бы иным, если бы количество параметров было меньшее.