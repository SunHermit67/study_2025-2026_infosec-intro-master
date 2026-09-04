---
## Front matter
title: "Отчет"
subtitle: "Индивидуальный проект этап №5"
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

Работа с Burp Suite.

# Задание

Поработать с Burp Suite.

# Выполнение лабораторной работы

Запускаем Burp Suite (рис. [-@fig:001]).

![Запуск Burp Suite](image/501.PNG){#fig:001 width=70%}

Включаем соединение (рис. [-@fig:002]).

![Включение соединения](image/502.PNG){#fig:002 width=70%}

Вводим локальный сервер (рис. [-@fig:003]).

![Ввод локального сервера](image/503.PNG){#fig:003 width=70%}

Видим сайт в подлючении (рис. [-@fig:004]).

![Сайт в приложении](image/504.PNG){#fig:004 width=70%}

После залогинивания можем увидеть всю информацию о нашем заходе на сайт (рис. [-@fig:005]-[-@fig:006]).

![Проверка логов после логина](image/505.PNG){#fig:005 width=70%}

![Проверка логов после логина](image/506.PNG){#fig:006 width=70%}

# Выводы

В ходе данного этапа были получены знания для работы с Burp Suite.
