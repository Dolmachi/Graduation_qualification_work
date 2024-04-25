<img src = https://ecovolna.ru/wp-content/uploads/2018/03/vap.png alt="drawing">

# Выпускная квалификационная работа

### Разработка модели машинного обучения для распознавания типов сельскохозяйственных культур, произростающих на территории Хабаровского края, на основе данных дистанционного зондирования Земли

<div style="text-align: right"> Выполнил студент: Кузнецов Э.С. </div>
<div style="text-align: right"> Научный руководитель: Агапова Е.Г. </div>
<div style="text-align: right"> к-т физ.-мат.наук, доцент. </div>

***

### Введение
Данная дипломная работа посвящена разработке модели мультиклассификации
сельскохозяйственных культур, произрастающих на территории Хабаровского
края, по временным рядам нормализированного вегетационного индекса
(NDVI). Данный индекс показывает наличие и состояние растительности. Он
использует контраст характеристик двух каналов из набора
мультиспектральных растровых данных — поглощения пигментом
хлорофилла в красном канале и высокой отражательной способности
растительного сырья в инфракрасном канале.


В качестве моделей машинного обучения взяты следующие алгоритмы:
- LogisticRegression
- RandomForest
- LightGBM


Вся разработка производилась на языке программирования Python.

- :computer: [Ноутбук проекта](https://github.com/Dolmachi/Graduation_qualification_work/blob/master/Model.ipynb)
- :page_facing_up: [Данные](https://github.com/Dolmachi/Graduation_qualification_work/tree/master/data)

#### Установка библиотек
```pip install -r requirements.txt```