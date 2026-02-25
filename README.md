# Superstore Sales Dashboard

Интерактивный дашборд по продажам компании Superstore (анализ выручки, прибыли, возвратов и топ-продуктов).

Создан в Power BI Desktop с использованием Power Query для очистки и моделирования данных.

## Основные элементы дашборда

- KPI-карточки: общая выручка, прибыль, средний чек, количество заказов, % прибыльных заказов
- Срез по регионам (Central, South, East, West)
- Карта по штатам США (размер пузырька — выручка, цвет — прибыль)
- Линейный график динамики продаж по месяцам
- Таблица топ-10 продуктов по выручке с условным форматированием прибыли

## Скриншоты
![Общий вид дашборда](https://github.com/ermolnikita99-eng/PowerBI_Superstore_Dashboard/blob/main/1.png%20—%20общий%20вид%20страницы.png)
![KPI-карточки](https://github.com/ermolnikitka-eng/PowerBI_Superstore_Dashboard/raw/main/2.png)](https://github.com/ermolnikita99-eng/PowerBI_Superstore_Dashboard/blob/main/2.png%20—%20карточки%20крупно.png)
![График и карта](https://github.com/ermolnikitka-eng/PowerBI_Superstore_Dashboard/raw/main/3.png)
![Топ-продукты](https://github.com/ermolnikitka-eng/PowerBI_Superstore_Dashboard/raw/main/4.png)

## Как открыть дашборд

1. Скачайте файл `Superstore_Sales_Dashboard.pbix`
2. Установите бесплатную программу Power BI Desktop[](https://powerbi.microsoft.com/desktop/)
3. Откройте файл двойным кликом

## Источник данных

Superstore Sales — классический тренировочный датасет (~8400 строк заказов, листы Orders, Returns, Users)

## Навыки, продемонстрированные в проекте

- Импорт и очистка данных в Power Query
- Построение модели данных (связи между таблицами)
- Создание мер DAX (% прибыльных, % возвратов)
- Визуализации: карточки, линейный график, карта, таблица с условным форматированием
- Интерактивность: срезы и динамическое обновление
