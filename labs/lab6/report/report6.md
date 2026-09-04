---
## Front matter
title: "Отчёт"
subtitle: "Лабораторная работа №6"
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

Развить навыки администрирования ОС Linux. Получить первое практическое знакомство с технологией SELinux. Проверить работу SELinx на практике совместно с веб-сервером Apache.

# Задание

Развить навыки администрирования ОС Linux. Получить первое практическое знакомство с технологией SELinux. Проверить работу SELinx на практике совместно с веб-сервером Apache.

# Выполнение лабораторной работы

Проверяем статус SELinux (рис. [-@fig:001]).

![Проверка статуса](image/6001.PNG){#fig:001 width=70%}

Находим Apache в списке процессов (рис. [-@fig:002]).

![Поиск Apache в списке процессов](image/6002.PNG){#fig:002 width=70%}

Проверяем текущее состояние переключателей SELinux (рис. [-@fig:003]).

![Проверка переключателей SELinux](image/6003.PNG){#fig:003 width=70%}

Проверяем информацию о SELinux (рис. [-@fig:004]).

![Проверка информации о SELinux](image/6004.PNG){#fig:004 width=70%}

Создаем тестовый html файл (рис. [-@fig:005]).

![Создание тестовых html файлов](image/6005.PNG){#fig:005 width=70%}

Изучение справки httpd_selinux (рис. [-@fig:006]).

![Изучение справки httpd_selinux](image/6006.PNG){#fig:006 width=70%}

Изучение справки httpd_selinux (рис. [-@fig:007]).

![Изучение справки httpd_selinux](image/6007.PNG){#fig:007 width=70%}

Обращаемся к тестовому html файлу (рис. [-@fig:008]).

![Обращение к тестовому html файлу](image/6008.PNG){#fig:008 width=70%}

Проверка логов (рис. [-@fig:009]).

![Проверка логов](image/6009.PNG){#fig:009 width=70%}

Тестовый файл работает успешно (рис. [-@fig:010]).

![Работа тестого файла](image/6010.PNG){#fig:010 width=70%}

Меняем конфиг файл (рис. [-@fig:011]).

![Изменение конфиг файла](image/6011.PNG){#fig:011 width=70%}

Проверка списка портов (рис. [-@fig:012]).

![Проверка списка портов](image/6012.PNG){#fig:012 width=70%}

После всего этого мы не можем зайти на текстовый сайт (рис. [-@fig:013]).

![Неудачный заход на тестовый сайт](image/6013.PNG){#fig:013 width=70%}

# Выводы

В ходе данной лабораторной работы были получены знания для работы с html файлами
