# Защита персональных данных клиентов

## Данные

В наличии были следующие данные:

- пол
- возраст
- зарплата застрахованного
- количество членов его семьи
- количество страховых выплат клиенту за последние 5 лет

## Задачи проекта

Разработка модели анонимизации персональных данных.

## Описание проекта

Необходимо защитить данные клиентов страховой компании «Хоть потоп». Разработайте такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Обоснуйте корректность его работы. Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось. Подбирать наилучшую модель не требуется.

## Навыки и инструменты

- Python
- NumPy
- Scikit-learn

## Вывод по итогам исследования

Теоретически доказано, что произведение матрицы признаков на случайно сгенерированную обратимую матрицу не изменяет качество линейной регрессии.

