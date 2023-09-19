# yandex_practicum_projects

Репозиторий с проектами, выполненными в процессе обучения на курсе "Специалист по Data Science" от Yandex.

## Аналитика
| Название проекта | Описание | Стек | 
| :--- | --- | :--- |
| [Яндекс.Музыка](https://clck.ru/35msC2) | Сравнение предпочтений пользователей Яндекс.Музыки из Москвы и Санкт-Петербурга в зависимости от времени (утро и вечер) и дня недели (понедельник, среда, пятница)| Jupyter Notebook, Python - *pandas* |
| [Исследование надёжности заёмщиков](https://clck.ru/35msGd) | Проведение исследования зависимости риска возникновения задолженности от различных факторов. | Jupyter Notebook, Python - *pandas* |
| [Исследование объявлений о продаже квартир](https://clck.ru/35msHp) | В нашем распоряжении данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. Нужно научиться определять рыночную стоимость объектов недвижимости. | Jupyter Notebook, Python - *pandas, numpy, matplotlib* |
| [Определение перспективного тарифа для телеком-компании](https://clck.ru/35msJk) | Проведение аналитики для компании «Мегалайн» — федерального оператора сотовой связи. Клиентам предлагают два тарифных плана: «Смарт» и «Ультра». Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег. | Jupyter Notebook, Python - *pandas, numpy, seaborn, matplotlib, scipy* |
| [Исследование продаж компьютерных игр](https://clck.ru/35msL8) | Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы. Нужно выявить определяющие успешность игры закономерности. | Jupyter Notebook, Python - *pandas, numpy, seaborn, matplotlib, scipy* |

## Классическое машинное обучение
| Название проекта | Описание | Стек | 
| :--- | --- | :--- |
| [Рекомендация тарифов](machine_learning/tariff_prediction) | Оператор мобильной связи «Мегалайн» выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра». | Jupyter Notebook, Python - *pandas, numpy, seaborn, os, tqdm, sklearn* |
| [Отток клиентов](machine_learning/bank_customer_churn) | Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых. Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. | Jupyter Notebook, Python - *pandas, numpy, seaborn, os, tqdm, matplotlib, sklearn* |
| [Выбор локации для скважины](machine_learning/oil_well_location) | Мы работаем в добывающей компании «ГлавРосГосНефть». Нужно решить, где бурить новую скважину. | Jupyter Notebook, Python - *pandas, numpy, seaborn, os, tqdm, matplotlib, pandas_profiling, sklearn* |
| [Защита персональных данных клиентов](machine_learning/personal_data_protection) | Нам нужно защитить данные клиентов страховой компании «Хоть потоп». Разработаем такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Обоснуем корректность его работы. | Jupyter Notebook, Python - *pandas, numpy, os, pandas_profiling, sklearn* |
| [Определение стоимости автомобилей](machine_learning/car_price_boosting) | Сервис по продаже автомобилей с пробегом «Не бит, не крашен» разрабатывает приложение для привлечения новых клиентов. Нам нужно построить модель для определения стоимости. | Jupyter Notebook, Python - *pandas, numpy, os, seaborn, pandas_profiling, sklearn, lightgbm, catboost* |

## Временные ряды
| Название проекта | Описание | Стек | 
| :--- | --- | :--- |
| [Прогнозирование заказов такси](time_series/taxi_order_forecast) | Компания «Чётенькое такси» собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. | Jupyter Notebook, Python - *os, pandas, numpy, plotly, matplotlib, sklearn, statsmodels, lightgbm* |

## NLP
| Название проекта | Описание | Стек | 
| :--- | --- | :--- |
| [Проект для «Викишоп»](NLP/toxic_comments) | Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. Обучим модель классифицировать комментарии на позитивные и негативные. | Jupyter Notebook, Python - *os, pandas, pandas_profiling, numpy, matplotlib, seaborn, re, nltk, sklearn, pytorch, transformers, tqdm, pickle* |

## CV
| Название проекта | Описание | Стек | 
| :--- | --- | :--- |
| [Определение возраста покупателей](CV/customer_age_recognition) | Сетевой супермаркет «Хлеб-Соль» внедряет систему компьютерного зрения для обработки фотографий покупателей. Построим модель, которая по фотографии определит приблизительный возраст человека. | Jupyter Notebook, Python - *pandas, numpy, matplotlib, plotly, keras* |
