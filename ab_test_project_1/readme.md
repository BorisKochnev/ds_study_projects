# Проект "A/B-тестирование гипотез отдела маркетинга"

## Данные

### Гипотезы
* `название`
* `охват по 10-бальной шкале`
* `влияние по 10-бальной шкале`
* `уверенность по 10-бальной шкале`
* `затраты по 10-бальной шкале`

### Заказы
* `id заказа`
* `id пользователя`
* `дата`
* `сумма заказа`
* `группа теста`

### Визиты
* `дата`
* `группа теста`
* `количество пользователей`

## Описание проекта 
вместе с отделом маркетинга вы подготовили список гипотез для увеличения выручки

## Задача проекта
приоритизировать гипотезы, а также проанализировать результаты A/B-теста


## Используемые библиотеки
* pandas
* numpy
* scipy.stats
* matplotlib.pyplot
* pandas.plotting.register_matplotlib_converters
* warnings
