# Определение возраста покупателей

Сетевой супермаркет «Хлеб-Соль» внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы:
* Анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы;
* Контролировать добросовестность кассиров при продаже алкоголя.

## Цель исследования

Построить модель, которая по фотографии определит приблизительный возраст человека со средним абсолютным отклонением MAE ниже 7.

## Исходные данные

В распоряжении набор фотографий людей с указанием возраста. 7591 фото.

## Итоги исследования

1. В качестве основы за модель была взята уже предобученная нейросеть с архитектурой ResNet50 и дополнительно обучена на  данных. 
2. В выходном слое использована оптимизация Adam c шагом обучения 0.0001, а в качестве функции потерь использовалась mean_squared_error (MSE).
3. Cреднее абсолютное отклонение на тестовой выборке получилось ниже 6, это даже лучше, чем было поставлено в цели.
4. MAE уменьшилось с 10.5673 до 2.7609 за 10 эпох.

## Используемый стек

Jupyter Notebook

Python - pandas, numpy, matplotlib, keras, tensorflow
