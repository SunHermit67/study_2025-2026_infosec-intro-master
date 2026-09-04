---
## Front matter
title: "Отчёт"
subtitle: "Лабораторная работа №1"
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

Приобрестение практических навыков для установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

# Задание

Приобрести практические навыки для установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

# Выполнение лабораторной работы

Для начала добавляем установочный диск (рис. [-@fig:001]).

![Установочный диск](image/1001.PNG){#fig:001 width=70%}

Устанавливаем имя и пароль (рис. [-@fig:002]).

![Установка логина и пароля](image/1002.PNG){#fig:002 width=70%}

Устанавливаем процессоры и оперативную память (рис. [-@fig:003]).

![Установка процессоров и опетаривную память](image/1003.PNG){#fig:003 width=70%}

Устанавливаем размер жесткого диска (рис. [-@fig:004]).

![Установка размера жесткого диска](image/1004.PNG){#fig:004 width=70%}

После этого уставливаем язык (рис. [-@fig:005]).

![Установка языка](image/1005.PNG){#fig:005 width=70%}

Устанавливаем пароль для админа (рис. [-@fig:006]).

![Установка пароля для админа](image/1006.PNG){#fig:006 width=70%}

Установка логина и пароля устройства (рис. [-@fig:007]).

![Установка логина и пароля для устройства](image/1007.PNG){#fig:007 width=70%}

Добавляем Debugging Tools (рис. [-@fig:008]).

![Добавление Debugging Tools](image/1008.PNG){#fig:008 width=70%}

Устанавливаем жесткий диск (рис. [-@fig:009]).

![Установка жесткого диска](image/1009.PNG){#fig:009 width=70%}

Вписываем имя хоста (рис. [-@fig:010]).

![Добавление имени хоста](image/1010.PNG){#fig:010 width=70%}

После этого ждем установку пакетов (рис. [-@fig:011]).

![Успешный запуск виртуальной машины](image/1011.PNG){#fig:011 width=70%}

Находим: (рис. [-@fig:012]-[-@fig:016]).
1. Версия ядра Linux (Linux version).
2. Частота процессора (Detected Mhz processor).
3. Модель процессора (CPU0).
4. Объем доступной оперативной памяти (Memory available).
5. Тип обнаруженного гипервизора (Hypervisor detected).
6. Тип файловой системы корневого раздела.
7. Последовательность монтирования файловых систем.

![Поиск информации о компьютере](image/1012.PNG){#fig:012 width=70%}

![Поиск информации о компьютере](image/1013.PNG){#fig:013 width=70%}

![Поиск информации о компьютере](image/1014.PNG){#fig:014 width=70%}

![Поиск информации о компьютере](image/1015.PNG){#fig:015 width=70%}

![Поиск информации о компьютере](image/1016.PNG){#fig:016 width=70%}

# Выводы

В ходе данной лабораторной работы были получены знания для установки Rocky.
