---
## Front matter
title: "Отчёт о выполнении. Индивидуальный проект."
subtitle: "Этап 2"
author: "Митрофанов Тимур Александрович"

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
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
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
lofTitle: "Список иллюстраций"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Добавление информации об авторе и первые посты.

# Выполнение лабораторной работы

Заменим фотографию полтзователся на свою (рис. [-@fig:001])

![Новая фотография](image/1.png){#fig:001 width=70%}

В находящимся тамже репозитории изменим данные об авторе (рис. [-@fig:002])

![Файл с данными об авторе после редактирования](image/2.png){#fig:002 width=70%}

Сделаем первый пост о прошедшей неделе (рис. [-@fig:003])

![Файл с конфигурацией поста](image/3.png){#fig:003 width=70%}

Сделаем пост про git (рис. [-@fig:004])

![Файл с конфигурацией поста про git](image/4.png){#fig:004 width=70%}

Полсе коммита всех изменений и ново-ведений мжно увидеть изменения на сайте(рис. [-@fig:005])

![Сайт после изменений](image/5.png){#fig:005 width=70%}


# Выводы

Сегодня я добавил информацию об авторе и первые посты.

