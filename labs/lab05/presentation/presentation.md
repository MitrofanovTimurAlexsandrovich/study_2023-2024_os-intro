---
## Front matter
lang: ru-RU
title: "Лабораторная работа №5"
subtitle: "Настройка рабочей среды."
author:
  - Митрофанов Тимур Александрович
institute:
  - Российский университет дружбы народов, Москва, Россия
  
date: 02 марта 2024

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
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
 
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9

---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Митрофанов Тимур Александрович
  * Студент 1 курса
  * Российский университет дружбы народов
  * [1132231842@pfur.ru](1132231842@pfur.ru)

:::
::: {.column width="30%"}


:::
::::::::::::::


# Цель работы

Настройка рабочей среды для дальнейшей работы.


# Выполнение лабораторной работы

Устанавливаем менеджер паролей при помощи команд ***dnf install pass pass-otp*** и ***dnf install gopass***.

![Установка pass](image/1.png){#fig:001 width=70%}

![Установка gopass](image/2.png){#fig:002 width=70%}

Просмотрим список ключей

![Просмотр списка ключей](image/3.png){#fig:003 width=70%}

Инициализируем хранилище

![Инициализация хранилища](image/4.png){#fig:004 width=70%}

Создадим структуру git

![Создадие структуры git](image/5.png){#fig:005 width=70%}

Созданим новый репозиторий pass

![Создание нового репозитория pass](image/6.png){#fig:006 width=70%}

Зададим адрес репозитория на хостинге

![Зададие адреса репозитория на хостинге](image/7.png){#fig:007 width=70%}

Для синхронизации выполним следующие команды

![Выполнение для синхранизации](image/8.png){#fig:008 width=70%}

Проверим чтовсе данные синранизированы и нам нечего еомитить на сервер

![Проверка актуальности синхранизации](image/9.png){#fig:009 width=70%}

Также проверим статус синхронизации

![Также проверим статус синхронизации](image/10.png){#fig:010 width=70%}

Для настройки работы с интерфейсом браузера добавим разрешения и установим соответствующие плагины

![Разрешение внедрения плагина](image/11.png){#fig:011 width=70%}

![Установка плагина](image/12.png){#fig:012 width=70%}

![Установка плагина в браузере](image/13.png){#fig:013 width=70%}

Создадим файл с поролями и запишем туда первый пароль

![Сохранение пароля](image/14.png){#fig:014 width=70%}

Проверим заданый пароль

![Вывод пароля](image/15.png){#fig:015 width=70%}

Сгенерируем новый пароль и запишем его в файл

![Генерация пароля](image/16.png){#fig:016 width=70%}

Установим доп. ПО для работами с файлами конфигурации

![Установим доп. ПО](image/17.png){#fig:017 width=70%}

Установим шрифты

![Установим шрифты](image/18.png){#fig:018 width=70%}

Установим бинарный файл

![Установка бинарного файла](image/19.png){#fig:019 width=70%}

Создадим собственный репозиторий с помощью утилит

![Создадим собственный репозиторий с помощью утилит](image/20.png){#fig:020 width=70%}

Инициализируем chezmoi с нашим репозиторием dotfiles

![Инициализируем chezmoi](image/21.png){#fig:021 width=70%}

Проверим, какие изменения внесёт chezmoi в домашний каталог

![Проверим, какие изменения внесёт chezmoi](image/22.png){#fig:022 width=70%}

Нас устраивают изменения, внесённые chezmoi, запустим ***chezmoi apply -v***

![Нас устраивают изменения, внесённые chezmoi, запустим ***chezmoi apply -v***](image/23.png){#fig:023 width=70%}

Установим chezmoi на второй вирт машине

![Установим chezmoi](image/24.png){#fig:024 width=70%}

Инициализируем chezmoi с нашим репозиторием dotfiles

![Инициализируем chezmoi](image/25.png){#fig:025 width=70%}

Проверим, какие изменения внесёт chezmoi в домашний каталог

![Проверим, какие изменения внесёт chezmoi](image/26.png){#fig:026 width=70%}

Нас устраивают изменения, внесённые chezmoi, запустим ***chezmoi apply -v***

![Нас устраивают изменения, внесённые chezmoi, запустим ***chezmoi apply -v***](image/27.png){#fig:027 width=70%}

Извлечём последние изменения из репозитория и применим их

![Извлечём последние изменения из репозитория и применим их. ](image/28.png){#fig:028 width=70%}

Включим автоматическую фиксацию изменений прописав соответствующие команды в файле ~/.config/chezmoi/chezmoi.toml

![Подключение атосохранения изменений](image/29.png){#fig:029 width=70%}

# Выводы

В этой лабораторной работе я Настроил рабочую среду для дальнейшей работы.



