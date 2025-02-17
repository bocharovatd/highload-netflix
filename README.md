# Проектирование высоконагруженного сервиса Netflix

## Содержание:
1. [Тема и целевая аудитория](#1)

## 1. Тема и целевая аудитория:
Netflix - стриминговый сервис для просмотра фильмов и сериалов.

### Функционал MVP
- регистрация и авторизация пользователей
- просмотр фильмов и сериалов в режиме стриминга
- полнотекстовый поиск по названию, жанру, актерам и режиссеру
- добавления фильмов и сериалов в избранное
- история просмотров
- система рекомендаций (общая, по событиям, на основе начатых просмотров, потребленного контента)
- push-уведомления о выходе новых сериалов и серий просмотренных сериалов

### Целевая аудитория

#### Анализ трафика
- количество уникальных пользователей в день (DAU) - 67.5M [^1]
- количество уникальных пользователей в месяц (MAU) - 2B [^1]
- среднее время просмотра стримов в день в первой четверти 2024 (daily time spent streaming) - 2 hours [^2]

 #### Трафик по странам [^4]
- основное географическое положение аудитории - США

![Geography](images/geography.png)

#### Количество позиций в библиотеке по странам [^3]
| country    | titles | 
| ---------- | ------ | 
| US         | 7427   |
| Australia  | 7711   |
| Canada     | 7626   |
| UK         | 8691   |

#### Подписчики
- новых подписчиков за последнюю четверть 2024 года - 18M [^5]

## Список источников:
[^1]: [Traffic Analysis](https://hypestat.com/info/netflix.com)

[^2]: [Time Spent Streaming](https://www.statista.com/statistics/1497100/time-spent-streaming-netflix-per-account/)

[^3]: [Library Titles](https://www.whats-on-netflix.com/news/netflix-library-by-the-numbers-2024/)

[^4]: [Traffic Demographics](https://www.similarweb.com/ru/website/netflix.com/#demographics)

[^5]: [Subscribers Fourth Quarter of 2024](https://www.statista.com/statistics/250934/quarterly-number-of-netflix-streaming-subscribers-worldwide/)
