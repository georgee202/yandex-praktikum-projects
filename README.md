# yandex_practicum_projects

Репозиторий с проектами, выполненными в процессе обучения на курсе "Специалист по Data Science" от Yandex.

## Аналитика
| Название проекта | Описание | Стек | 
| :--- | --- | :--- |
| [Яндекс.Музыка](analytics/big_city_music) | Сравнение предпочтений пользователей Яндекс.Музыки из Москвы и Санкт-Петербурга в зависимости от времени (утро и вечер) и дня недели (понедельник, среда, пятница)| Jupyter Notebook, Python - *pandas* |
| [Исследование надёжности заёмщиков](analytics/credit_scoring) | Проведение исследования зависимости риска возникновения задолженности от различных факторов. | Jupyter Notebook, Python - *pandas, numpy, seaborn, pymorphy2, os, collections* |
| [Исследование объявлений о продаже квартир](https://clck.ru/35gUP6) | В нашем распоряжении данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. Нужно научиться определять рыночную стоимость объектов недвижимости. | Jupyter Notebook, Python - *pandas, numpy, seaborn, os, matplotlib* |
| [Исследование данных о российском кинопрокате](analytics/russian_cinema) | Заказчик исследования — Министерство культуры Российской Федерации. Изучим рынок российского кинопроката, уделим внимание фильмам, которые получили государственную поддержку. | Jupyter Notebook, Python - *pandas, numpy, seaborn, os, matplotlib* |

## Статистика
| Название проекта | Описание | Стек | 
| :--- | --- | :--- |
| [Определение перспективного тарифа для телеком-компании](statystic/cell_phone_tariffs) | Проведём аналитику для компании «Мегалайн» — федерального оператора сотовой связи. Клиентам предлагают два тарифных плана: «Смарт» и «Ультра». Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег. | Jupyter Notebook, Python - *pandas, numpy, seaborn, os, matplotlib, math, scipy* |

## Классическое машинное обучение
| Название проекта | Описание | Стек | 
| :--- | --- | :--- |
| [Рекомендация тарифов](machine_learning/tariff_prediction) | Оператор мобильной связи «Мегалайн» выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра». | Jupyter Notebook, Python - *pandas, numpy, seaborn, os, tqdm, sklearn* |
| [Отток клиентов](machine_learning/bank_customer_churn) | Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых. Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. | Jupyter Notebook, Python - *pandas, numpy, seaborn, os, tqdm, matplotlib, sklearn* |
| [Выбор локации для скважины](machine_learning/oil_well_location) | Мы работаем в добывающей компании «ГлавРосГосНефть». Нужно решить, где бурить новую скважину. | Jupyter Notebook, Python - *pandas, numpy, seaborn, os, tqdm, matplotlib, pandas_profiling, sklearn* |
| [Прогнозирование оттока клиентов в сети отелей «Как в гостях»](machine_learning/hotel_customer_churn) | Заказчик исследования — сеть отелей «Как в гостях». Чтобы привлечь клиентов, сеть отелей добавила на свой сайт возможность забронировать номер без предоплаты. Eсли клиент отменяет бронирование - компания терпит убытки. Нам нужно разработать систему, которая предсказывает отказ от брони. | Jupyter Notebook, Python - *pandas, numpy, seaborn, os, tqdm, matplotlib, pandas_profiling, statsmodels, sklearn* |
| [Предсказание стоимости жилья в Калифорнии](machine_learning/spark_house_pricing) | В проекте нам нужно обучить модель линейной регрессии на данных о жилье в Калифорнии в 1990 году используя фреймворк Spark для распределённых вычислений. | Jupyter Notebook, Python - *pandas, numpy, pyspark* |
| [Защита персональных данных клиентов](machine_learning/personal_data_protection) | Нам нужно защитить данные клиентов страховой компании «Хоть потоп». Разработаем такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Обоснуем корректность его работы. | Jupyter Notebook, Python - *pandas, numpy, os, pandas_profiling, sklearn* |
| [Определение стоимости автомобилей](machine_learning/car_price_boosting) | Сервис по продаже автомобилей с пробегом «Не бит, не крашен» разрабатывает приложение для привлечения новых клиентов. Нам нужно построить модель для определения стоимости. | Jupyter Notebook, Python - *pandas, numpy, os, seaborn, pandas_profiling, sklearn, lightgbm, catboost* |
| [Оценка риска ДТП](machine_learning/car_accident_risk) | Нужно создать систему для каршеринговой компании, которая могла бы оценить риск ДТП по совокупности факторов. Как только водитель забронировал автомобиль, сел за руль и выбрал маршрут, система должна оценить уровень риска. Если уровень риска высок, водитель увидит предупреждение и рекомендации по маршруту. | Jupyter Notebook, Python - *pandas, numpy, plotly, matplotlib, pandas_profiling, snap, sklearn, sqlalchemy, lightgbm, catboost* |

## Временные ряды
| Название проекта | Описание | Стек | 
| :--- | --- | :--- |
| [Прогнозирование заказов такси](time_series/taxi_order_forecast) | Компания «Чётенькое такси» собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. | Jupyter Notebook, Python - *os, pandas, numpy, plotly, matplotlib, sklearn, statsmodels, lightgbm* |

## Нейронные сети
| Название проекта | Описание | Стек | 
| :--- | --- | :--- |
| [Прогнозирование температуры звезды](neural_networks/star_temperature_prediction) | Нам пришла задача от обсерватории «Небо на ладони»: придумать, как с помощью нейросети определять температуру на поверхности обнаруженных звёзд. | Jupyter Notebook, Python - *os, pandas, numpy, plotly, tqdm, pandas_profiling, sklearn, pytorch* |

## NLP
| Название проекта | Описание | Стек | 
| :--- | --- | :--- |
| [Мастерская. KPMI.ru](NLP/kpmi) | Тест «Ключи персонального мастерства» предназначен для определения индивидуального поведенческого стиля личности. Является оригинальной отечественной разработкой на базе широко известного типологического опросника Майер-Бриггс. С помощью моделей классического машинного обучения попробуем улучшить качество предсказания сферы деятельности в которой человек сможет максимально самореализоваться. | Jupyter Notebook, Python - *os, pandas, numpy, matplotlib, seaborn, pymorphy2, statsmodels, sys, re, nltk, collections, symspellpy, sklearn* |
| [Проект для «Викишоп» с BERT](NLP/toxic_comments) | Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. Обучим модель классифицировать комментарии на позитивные и негативные. | Jupyter Notebook, Python - *os, pandas, pandas_profiling, numpy, matplotlib, seaborn, re, nltk, sklearn, pytorch, transformers, tqdm, pickle* |

## CV
| Название проекта | Описание | Стек | 
| :--- | --- | :--- |
| [Определение возраста покупателей](CV/customer_age_recognition) | Сетевой супермаркет «Хлеб-Соль» внедряет систему компьютерного зрения для обработки фотографий покупателей. Построим модель, которая по фотографии определит приблизительный возраст человека. | Jupyter Notebook, Python - *pandas, numpy, matplotlib, plotly, keras* |
| [Поиск фото "Со смыслом"](CV/photo_search) | В фотохостинге для профессиональных фотографов «Со Смыслом» (“With Sense”) пользователи размещают свои фотографии и сопровождают их полным описанием. Разработаем демонстрационную версию поиска изображений по запросу. | Jupyter Notebook, Python - *pandas, numpy, matplotlib, pathlib, pickle, re, nltk, PIL, keras, tensorflow, tqdm, sklearn, sentence_transformers, glob* |
