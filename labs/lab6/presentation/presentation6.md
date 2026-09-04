---
## Front matter
lang: ru-RU
title: Лабораторная работа
subtitle: Номер 6
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

Развить навыки администрирования ОС Linux. Получить первое практическое знакомство с технологией SELinux. Проверить работу SELinx на практике совместно с веб-сервером Apache.

## Работа с html файлами

Проверяем статус SELinux

![Проверка статуса](image/6001.PNG)

## Работа с html файлами

Находим Apache в списке процессов

![Поиск Apache в списке процессов](image/6002.PNG)

## Работа с html файлами

Проверяем текущее состояние переключателей SELinux

![Проверка переключателей SELinux](image/6003.PNG)

## Работа с html файлами

Проверяем информацию о SELinux 

![Проверка информации о SELinux](image/6004.PNG)

## Работа с html файлами

Создаем тестовый html файл 

![Создание тестовых html файлов](image/6005.PNG)

## Работа с html файлами

Изучение справки httpd_selinux

![Изучение справки httpd_selinux](image/6006.PNG)

## Работа с html файлами

Изучение справки httpd_selinux

![Изучение справки httpd_selinux](image/6007.PNG)

## Работа с html файлами

Обращаемся к тестовому html файлу

![Обращение к тестовому html файлу](image/6008.PNG)

## Работа с html файлами

Проверка логов

![Проверка логов](image/6009.PNG)

## Работа с html файлами

Тестовый файл работает успешно

![Работа тестого файла](image/6010.PNG)

## Работа с html файлами

Меняем конфиг файл 

![Изменение конфиг файла](image/6011.PNG)

## Работа с html файлами

Проверка списка портов 

![Проверка списка портов](image/6012.PNG)

## Работа с html файлами

После всего этого мы не можем зайти на текстовый сайт 

![Неудачный заход на тестовый сайт](image/6013.PNG)

## Выводы

В ходе данной лабораторной работы были получены знания для работы с html файлами
