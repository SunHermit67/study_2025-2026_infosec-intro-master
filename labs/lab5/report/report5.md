---
## Front matter
title: "Отчёт"
subtitle: "Лабораторная работа №5"
author: "Приходько Иван Иванович"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
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
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Изучение механизмов изменения идентификаторов, применения SetUID- и Sticky-битов.

# Задание

Изучить механизмы изменения идентификаторов, применения SetUID- и Sticky-битов.

# Выполнение лабораторной работы

Создаем файл с кодом на С (рис. [-@fig:001]).

![Создание файла simpleid.c](image/5001.PNG){#fig:001 width=70%}

Запускаем файл и видим, что оно работает корректно (рис. [-@fig:002]).

![Проверка работы файла](image/5002.PNG){#fig:002 width=70%}

Создаем второй файл с кодом на С (рис. [-@fig:003]).

![Создание файла simpleid2.c](image/5003.PNG){#fig:003 width=70%}

Запускаем второй файл и видим, что оно работает корректно (рис. [-@fig:004]).

![Проверка работы второго файла](image/5004.PNG){#fig:004 width=70%}

Изменение атрибутов второго файла (рис. [-@fig:005]).

![Изменение атрибутов второго файла](image/5005.PNG){#fig:005 width=70%}

Создаем третий файл (рис. [-@fig:006]).

![Создание третьего файла](image/5006.PNG){#fig:006 width=70%}

Запускаем третий файл (рис. [-@fig:007]).

![Запуск третьего файла](image/5007.PNG){#fig:007 width=70%}

Пробуем прочитать самого себя (рис. [-@fig:008]).
 
![Попытка прочитать собственный файл](image/5008.PNG){#fig:008 width=70%}

Меняем атрибуты файлов и попытка прочитать или изменить некоторые файлы (рис. [-@fig:009]).

![Работа с файлами и их атрибутами](image/5009.PNG){#fig:009 width=70%}

# Выводы

В ходе данной лабораторной работы были получены знания для работы с файлами С
