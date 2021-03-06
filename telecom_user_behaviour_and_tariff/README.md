# Проект - Анализ поведения клиентов телеком компании

### Библиотеки
pandas,  NumPy, SciPy, math, Matplotlib, seaborn

## Задача
Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег. Необходимо сделать предварительный анализ тарифов на небольшой выборке клиентов. Есть данные 500 пользователей: кто они, откуда, каким тарифом пользуются, сколько звонков и сообщений каждый отправил за 2018 год. Нужно проанализировать поведение клиентов и сделать вывод — какой тариф лучше.

## Описание
После предобработки данных (удаления звонков и сессий, которые не тарифицируются, округления значений вверх для минут и мегабайт), была сдалана сводная таблицу по количеству используемых минут, сообщений, мегабайт по каждому пользователю за месяц. На основании этой таблицы была посчитана выручка помесячно для каждого клиента и было произведено сравнение друх тарифов между собой. Наконец, было проверено две гипотезы о том, что средняя выручка пользователей двух тарифов различается и средняя выручка пользователей из Москвы отличается от выручки пользователей из других регионов

## Выводы
Анализ выявил, что оба тарифа не удовлетворяют потребностям пользователей и оператору имеет смысл пересмотреть тарифы для их оптимизации. Был сделан вариант оптимизации по количеству минут, сообщений и гигабайт для каждого тарифа. 

Статистическая проверка первой гипотезы о разнице выручки с тарифов показала, что несмотря на разную дисперсию среднее выборок отличается. Статистическая проверка второй гипотезы о разности выручки с Москвы и других городов не позволила отвергнуть нулевую гипотезу, соответственно, средняя выручка пользователей из Москвы не отличается от выручки пользователей из других регионов.
