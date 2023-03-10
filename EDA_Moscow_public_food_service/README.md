# Исследовательский анализ данных рынка общественного питания Москвы

**NB: Для отображения карт и хороплетов воспользуйтесь сервисом https://nbviewer.org/.**

## Цель исследования

Найти закономерности и интересные особенности, которые помогут инвесторам в выборе подходящего места для открытия кофейни «Central Perk» из культового сериала «Friends».

## Результат исследования

Были найдены закономерности, исследованы особенности рынка общественного питания Москвы, проведен анализ конкурентов, в результате чего были сформулированы рекомендации для открытия кофейни.

## Данные

В наличии датасет с информацией о заведениях общественного питания Москвы, составленный на основе данных сервисов Яндекс Карты и Яндекс Бизнес на лето 2022 года:

- название заведения

- адрес заведения

- категория заведения, например «кафе», «пиццерия» или «кофейня»

- информация о днях и часах работы

- широта географической точки, в которой находится заведение

- долгота географической точки, в которой находится заведение

- рейтинг заведения по оценкам пользователей в Яндекс Картах (высшая оценка — 5.0)

- категория цен в заведении, например «средние», «ниже среднего», «выше среднего» и так далее

- среднюю стоимость заказа в виде диапазона

- число с оценкой среднего чека

- число с оценкой стоимости одной чашки капучино

- число, выраженное 0 или 1, которое показывает, является ли заведение сетевым
              
- административный район, в котором находится заведение, например Центральный административный округ

- количество посадочных мест.

## Используемые библиотеки

- pandas
- matplotlib.pyplot
- seaborn
- numpy
- json
- plotly
- folium
