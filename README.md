# GoIT RDB - Homework 3: Seoul Bike Sharing Demand

## Опис проекту
Цей проект містить повний пайплайн обробки даних (ETL), розвідувальний аналіз (EDA) та аудит якості даних для набору **Seoul Bike Sharing Demand** із репозиторію UCI Machine Learning. Робота виконана на чистому SQL у середовищі PostgreSQL (через `pgserver` у Google Colab).

## Офіційне джерело даних
- **Назва:** Seoul Bike Sharing Demand Dataset
- **Джерело:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Seoul+Bike+Sharing+Demand)
- **Кількість рядків:** 8760 годинних записів

## Структура репозиторію
- `notebooks/` — Jupyter Notebook з повним кодом виконання від початку до кінця (`Restart & Run All`).
- `data/` — Вихідний CSV-файл (`hw3_seoul_bike.csv`).
- `README.md` — Опис проекту та інструкція запуску.

## Інструкція запуску
1. Відкрийте ноутбук у Google Colab.
2. Послідовно запустіть усі клітинки (`Runtime -> Restart and run all`).
3. Переконайтеся, що всі етапи (Setup, Staging, Clean, Audit, DQL-запити та Reflection) виконуються без помилок.
