# Python Block

source: https://colab.research.google.com/drive/1rlj_0ZpBHKHDlitm0EMzvhuNSNbnO7zr?usp=sharing

## Проверка данных
![alt text](imgs/image.png)


## Посмотрите формат таблиц
![alt text](imgs/image-1.png)

## Сразу переведем столбец "Дата" в правильный формат
![alt text](imgs/image-2.png)

## Сгруппируйте данные по дате, посчитайте количество продаж
## Вывести несколько первых строк сгруппированных данных
![alt text](imgs/image-3.png)

## Нарисуйте график продаж у `grouped_df`
![alt text](imgs/image-4.png)

##  Опишите что вы видите на графике. Ваша задача - максимально описать график
- В январе и феврале количество продаж колеблется в пределах 3500–4000 единиц.
- В марте начинается заметный рост, достигающий пиков до 5000 единиц.
- В апреле наблюдается снижение продаж с падением к уровню около 3500 к концу месяца.
- В начале мая продажи резко снижаются до минимума около 2500 единиц.
- С середины мая начинается постепенный рост, достигая 5000 единиц к концу июня.
- В июле и августе продажи продолжают расти, достигая пиков в 5500–6000 единиц.


## Найдите строку, у которой максимальный выброс по количеству продаж (нужно найти выброс у `df`)
![alt text](imgs/image-5.png)

## Найдите топовый товар по продажам по средам за июнь, июль, август у 3 склада
![alt text](imgs/image-11.png)

## Скачайте данные по погоде с https://rp5.ru/Архив_погоды_в_Астане (скачайте исходные данные, и далее преобразуйте так, чтобы мы имели Дату и Среднюю температуру за день)
![alt text](imgs/image-6.png)

## объедините таблицу температуры с `grouped_df`
![alt text](imgs/image-7.png)

## Нарисуйте график `y=['Количество продаж', 'T']`, где Т это температура. А также отдельно график температуры.
![alt text](imgs/image-8.png)
![alt text](imgs/image-9.png)
![alt text](imgs/image-10.png)
