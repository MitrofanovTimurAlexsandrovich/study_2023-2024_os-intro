---
## Front matter
title: "Отчёт о выполнении. Индивидуальный проект."
subtitle: "Этап 1"
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

Размещение на Github pages заготовки для персонального сайта.

# Задание


-Установить необходимое программное обеспечение.
-Скачать шаблон темы сайта.
-Разместить его на хостинге git.
-Установить параметр для URLs сайта.
-Разместить заготовку сайта на Github pages.

# Выполнение лабораторной работы

Скачиваем hugo для последующей работы с шаблонми (рис. [-@fig:001], рис. [-@fig:002] и рис. [-@fig:003]).

![Скачивание hugo из интернета](image/1.png){#fig:001 width=70%}

![Скачивание hugo из интернета](image/2.png){#fig:002 width=70%}

![Скачивание hugo из интернета](image/3.png){#fig:003 width=70%}

Распаковывваем скаченый архив с hugo. (рис. [-@fig:004])

![Распаковка архива](image/4.png){#fig:004 width=70%}

Переносим программу в необходимый для её работы репозиторий. (рис. [-@fig:005])

![перемещение Hugo](image/5.png){#fig:005 width=70%}

Теперь создадим свой репозиторий на github. Назовём его blog. (рис. [-@fig:006])

![Созданный репозиторий на github](image/6.png){#fig:006 width=70%}

Клонируем наш репозиторий в файлы операционной системы. (рис. [-@fig:007])

![Клонирование репозитория с github](image/7.png){#fig:007 width=70%}

Установим go который нужен для работы hugo. (рис. [-@fig:008])

![Установка go](image/8.png){#fig:008 width=70%}

Инициализируем hugo в нашем репозитории blog. (рис. [-@fig:009])

![Запуск Hugo](image/9.png){#fig:009 width=70%}

Из репозитория удаляем не нужный дерикторий public(рис. [-@fig:010])

![Удаление дериктории public](image/10.png){#fig:010 width=70%}

Запускаем локальный сервер hugo при помощи команды ***hugo server*** Для проверки работы. (рис. [-@fig:011] и рис. [-@fig:012])

![Запуск локального хоста](image/11.png){#fig:011 width=70%}

![Проверка работы шаблона сайта визитки](image/12.png){#fig:012 width=70%}

Для размещения визитки на github создадим ещё один репозиторий **MitrofanovTimurAlexandrovich.github.io** (рис. [-@fig:013])

![Создание репозитория на github](image/13.png){#fig:013 width=70%}

После как и предыдущий репозиторий клонируем его в оперционную систему с сайта при помощи ***git clone***. Затем создаём там новую ветку. (рис. [-@fig:014])

![Созданём новую ветку](image/14.png){#fig:014 width=70%}

Создаём там стандартный файл *README* (рис. [-@fig:015])

![Создание файла](image/16.png){#fig:015 width=70%}

При помщи стандартных команд ***add***, ***commit*** и ***push*** добавляем соответствующие изменения на сервер. (рис. [-@fig:016])

![отправка изменений на сервер](image/17.png){#fig:016 width=70%}

Перейдём в файл конфигурации игнорирования пути нашего репозитория в репозитории blog и отключим игнорирования для **public**. (рис. [-@fig:017])

![отключение игнорирования для pyblic](image/18.png){#fig:017 width=70%}

Создадим новый раздел public в замен раннее удалённого.(рис. [-@fig:018])

![Создание нового pyblic](image/19.png){#fig:018 width=70%}

Теперь проверим наличие всех нобходимых веток и их работоспособность(рис. [-@fig:019])

![Проверка внесённых изменений](image/20.png){#fig:019 width=70%}

Загружаем все изменения на сервер(рис. [-@fig:020])

![отправка внесённых изменений](image/21.png){#fig:020 width=70%}

Проверяем работу сайта на github(рис. [-@fig:021] и рис. [-@fig:022])

![файлы репозитория на git](image/22.png){#fig:021 width=70%}

![страничка сайта](image/23.png){#fig:022 width=70%}

Проверяем работу сайта на github

# Выводы

Сегодня я разместил на Github pages заготовки для персонального сайта.

