# Определение стоимости автомобилей

Сервис по продаже автомобилей с пробегом «Не бит, не крашен» разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. Нужно построить модель для определения стоимости.

## Цель исследования

Построить модель для определения стоимости.

## Исходные данные

В распоряжении исторические данные: технические характеристики, комплектации и цены автомобилей. Всего 354369 строк.

## Итоги исследования

Во время проекта были выполены задачи и цель. На предобработке данных были:
- Изменены названия столбцов на *snake_case*
- Удалены дубликаты и неинформативные столбцы
- Пропущенные данные для категориальных (небинарных) признаков были заполнены значением 'unknown'
- Пропущенные значение в *gearbox* заменены на самые часто встречающиеся
- В столбце *repaired* было принято решение заменить пропущенные на 'no'
- Удалены автомобили с неправдоподобным годом выпуска, осталсиь от 1992 до 2022
- Также удалена неправдоподобная лошадиная сила (больше 400), нули заменены на медиану по бренду


1. Лучшей моделью стала LGBMRegressor с RMSE равной 1580.43 и параметрами *num_leaves=100* и *learning_rate = 0.3*.
2. CatBoostRegressor с RMSE равной 1871.86 и параметрами *depth = 10* и *learning_rate = 0.1*. Она сильно проигрывает во времени обучения и предсказания другим моделям.
3. DecisionTreeRegressor уступает другим моделям в метрике RMSE = 1978.84, но выигрывает по времени предсказания.

Заказчику важны: качество предсказания, скорость предсказания, время обучения. Исходя из этого можно предложить модель LGBMRegressor. У нее самое выское качаество предсказания и быстрое время обучения и предсказания.

## Используемый стек

Jupyter Notebook

Python - pandas, numpy, seaborn, sklearn, lightgbm, catboost
