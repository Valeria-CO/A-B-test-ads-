# A/B Test of Advertising Impact on Conversion

## The company wanted to reduce advertising costs and test whether turning off ads for some users would affect their purchase conversion.

An A/B test was conducted comparing two groups:
- Ad group: users who saw the advertisement
- PSA group: users who saw only the public service announcement

## Goal - to determine whether disabling ads changes the conversion rate.

## Data
user id: unique identifier of users
test group: 'ad' or 'psa'
converted: whether the user purchased the product (True/False)
total ads: number of ads seen by the user
most ads day: day of week with most ads seen
most ads hour: hour of day with most ads seen

## Metrics
Primary metric: conversion rate (converted)
Secondary metrics: total ads - to confirm users actually saw different amounts of ads
                   most ads day - to explore if day of week affects conversion

## Methodology
Random sampling: 3112 users per group to ensure balanced A/B test
Statistical tests for primary metric: Z-test, Chi-square, Bootstrap
Tests for secondary metrics: Mann-Whitney U test for total ads, descriptive analysis for most ads day

## Results
Conversion rate: no statistically significant difference between groups (p > 0.05)
Total ads: users in the Ad group saw significantly more ads than the PSA group
Most ads day: conversion did not vary meaningfully by day of week

## Conclusion
## The A/B test shows that disabling advertising did not significantly affect purchase conversion.
### Users in the Ad group indeed saw more ads, but the day of maximum ad exposure did not significantly influence conversion.

Recommendation: the company can consider reducing ad spend without risk of losing conversions.


## Компания хотела сократить расходы на рекламу и проверить, повлияет ли отключение рекламы для некоторых пользователей на конверсию.

Было проведено A/B-тестирование, сравнивающее две группы:
- Группа рекламы: пользователи, которые увидели рекламу
- Группа социальной рекламы: пользователи, которые увидели только социальную рекламу

## Цель — определить, влияет ли отключение рекламы на коэффициент конверсии.

## Данные
user id: уникальный идентификатор пользователя
test group: 'ad'(видели рекламу) и 'psa'(видели социальную рекламу или ничего)
converted: купил ли пользователь товар (True/False)
total ads: количество просмотренных пользователем объявлений
boost ads day: день недели с наибольшим количеством просмотренных объявлений
boost ads hour: час дня с наибольшим количеством просмотренных объявлений

## Метрики
Основная метрика: Конверсия
Дополнительные метрики: общее количество просмотренных объявлений - для подтверждения того, что пользователи действительно видели разное количество объявлений
                        boost ads day - для изучения влияния дня недели на конверсию

## Методы
Случайная выборка: 3112 пользователей в группе для обеспечения сбалансированного A/B-тестирования
Статистические тесты для основной метрики: Z-тест, хи-квадрат, Bootstrap
Тесты для дополнительных метрик: U-тест Манна-Уитни для общего количества просмотренных объявлений, описательный анализ для дня с наибольшим количеством просмотренных объявлений

## Результаты
Конверсия: статистически значимых различий между группами нет (p > 0.05)
Общее количество рекламы: пользователи в группе 'ad' увидели значительно больше рекламы, чем в группе 'psa'
День с наибольшим количеством рекламы: конверсия существенно не менялась по дням недели.

## Вывод
## A/B-тестирование показывает, что отключение рекламы не оказало существенного влияния на конверсию покупки.
### Пользователи в группе 'ad' действительно увидели больше рекламы, но день максимального показа рекламы не оказал существенного влияния на конверсию.

Рекомендация: компания может рассмотреть возможность сокращения расходов на рекламу без риска потери конверсий.
