---
## Front matter
lang: ru-RU
title: Лабораторная работа
subtitle: Номер 5
author:
  - Приходько И. И. 
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 4 сентября 2026

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}

## Fonts
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Приходько Иван Иванович
  * Студент
  * Российский университет дружбы народов

:::
::: {.column width="30%"}


:::
::::::::::::::

## Цель работы

Изучение механизмов изменения идентификаторов, применения SetUID- и Sticky-битов.

## Работа с файлами и их атрибутами

Создаем файл с кодом на С 

![Создание файла simpleid.c](image/5001.PNG)

## Работа с файлами и их атрибутами

Запускаем файл и видим, что оно работает корректно

![Проверка работы файла](image/5002.PNG)

## Работа с файлами и их атрибутами

Создаем второй файл с кодом на С 

![Создание файла simpleid2.c](image/5003.PNG)

## Работа с файлами и их атрибутами

Запускаем второй файл и видим, что оно работает корректно

![Проверка работы второго файла](image/5004.PNG)

## Работа с файлами и их атрибутами

Изменение атрибутов второго файла

![Изменение атрибутов второго файла](image/5005.PNG)

## Работа с файлами и их атрибутами

Создаем третий файл

![Создание третьего файла](image/5006.PNG)

## Работа с файлами и их атрибутами

Запускаем третий файл 

![Запуск третьего файла](image/5007.PNG)

## Работа с файлами и их атрибутами

Пробуем прочитать самого себя

![Попытка прочитать собственный файл](image/5008.PNG)

## Работа с файлами и их атрибутами

Меняем атрибуты файлов и попытка прочитать или изменить некоторые файлы 

![Работа с файлами и их атрибутами](image/5009.PNG)

## Выводы

В ходе данной лабораторной работы были получены знания для работы с файлами С
