# Определение стоимости автомобилей

## Данные

В наличии были следующие исторические данные:

- дата скачивания анкеты из базы
- тип автомобильного кузова
- год регистрации автомобиля
- тип коробки передач
- мощность (л. с.)
- модель автомобиля
- пробег (км)
- месяц регистрации автомобиля
- тип топлива
- марка автомобиля
- была машина в ремонте или нет
- дата создания анкеты
- количество фотографий автомобиля
- почтовый индекс владельца анкеты (пользователя)
- дата последней активности пользователя
- цена (евро)

## Задачи проекта

Разработка системы рекомендации стоимости автомобиля на основе его описания.

## Описание проекта

Сервис по продаже автомобилей с пробегом  разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. На основе исторические данные необходимо построить модель для определения стоимости автомобиля.

## Навыки и инструменты

- Python
- Pandas
- lightgbm

## Вывод по итогам исследования

Наилучшая модель для заказчика это CatBoost.
