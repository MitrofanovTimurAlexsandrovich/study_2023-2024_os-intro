---
## Front matter
lang: ru-RU
title: "Лабораторная работа №2"
subtitle: "Первоночальная настройка git"
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


## Цель работы

Получить навыки правильной работы с репозиториями git.


## Выполнение лабораторной работы

Разрешаем доступ к репозиторию в которм находится gitflow ***dnf copr enable elegos/gitflow***.

![Активация доступа к репозиторию](image/1.png){#fig:001 width=70%}

##

Устанавливаем gitflow, используя команду ***dnf install gitflow**.

![Установка gitflow](image/2.png){#fig:002 width=70%}

##

Устанавливем Node.js и pnpm

![Установка Node.js](image/3.png){#fig:003 width=70%}

![Установка pnpm](image/4.png){#fig:004 width=70%}

##

Настраиваем Node.js для работы.

![Настройка Node.js](image/5.png){#fig:005 width=70%}

##

При помощи команды ***pnpm add -g commitizen*** устанавливаем программу для помощи в форматировании комитов.

![Установка commitizen](image/6.png){#fig:006 width=70%}

##

При помощи команды ***pnpm add -g standard-changelog*** устанавливаем программу для помощи в создании логов.

![Установка standard-changelog](image/7.png){#fig:007 width=70%}

##

Создаём репозитрий git-extended.

![Создание репозитория git-extended](image/8.png){#fig:008 width=70%}

##

Копируем внось созданный репозиторий себе на вирт. машину.

![Клонирование репозитория git-extended](image/9.png){#fig:009 width=70%}

##

Делаем первый комит на репозиторий git-extended.

![Создание нового файла и сохранение его на сервер](image/10.png){#fig:010 width=70%}

##

Смотри конфигурацию пакетов Node.js.

![Конфегурация пакетов Node.js](image/11.png){#fig:011 width=70%}

##

Модификация конфигурации Node.js.

![Модификация конфигурации Node.js](image/12.png){#fig:012 width=70%}

##

Добавляем новые фалый, делаем коммит и отправляем на github.

![Добавляем файлы](image/13.png){#fig:013 width=70%}

##

![Отправляем файлы на github](image/14.png){#fig:014 width=70%}

Инициализируем gitflow.

##

![Инициализация gitflow](image/15.png){#fig:015 width=70%}

Проверяем в какой мы ветке.

##

![Проверка выбранной ветки](image/16.png){#fig:016 width=70%}

Загружаем всего репозитория в хранилище.

##

![Загрузка всего репозитория в хранилище](image/17.png){#fig:017 width=70%}

Установливаем внешнюю ветку как вышестоящую для этой ветки при помощи команды ***git branch --set-upstream-to=origin/develop develop***.

##

![Установка внешней ветки как вышестоящей для этой ветки](image/18.png){#fig:018 width=70%}

Создадим релиз с версией 1.0.0 при помощи команды ***git flow release start 1.0.0***.
##

![Создание релиз версии 1.0.0](image/19.png){#fig:019 width=70%}

Создадим журнал изменений при помощи команды ***standard-changelog --first-release***.

##

![Создание журнала изменений](image/20.png){#fig:020 width=70%}

##

Добавим журнал изменений в индекс при помощи команд ***git add CHANGELOG.md*** и ***git commit -am 'chore(site): add changelog'***.

![Добавление журнала изменений в индекс](image/21.png){#fig:021 width=70%}

##

Зальём релизную ветку в основную ветку при помощи команды ***git flow release finish 1.0.0***.

![Залив релизной ветки в основную ветку](image/22.png){#fig:022 width=70%}

##

Отправим данные на github.

![Отправка данных на github](image/23.png){#fig:023 width=70%}

##

Создадим релиз на github. Для этого будем использовать утилиты работы с github.

![Создание релиза на github](image/24.png){#fig:024 width=70%}

##

Создадим ветку для новой функциональности.

![Создание ветки для новой функциональности](image/25.png){#fig:025 width=70%}

##

По окончании разработки новой функциональности следующим шагом объединим ветку feature_branch c develop.

![объединение ветки feature_branch c develop](image/26.png){#fig:026 width=70%}

##

Создадим релиз с версией 1.2.3.

![Создание релиза с версией 1.2.3](image/27.png){#fig:027 width=70%}

##

Изменений файла конфигурации для соответствия версии релиза.

![Изменений файла конфигурации](image/28.png){#fig:028 width=70%}

##

Создадим журнал изменений.

![Создание журнала изменений](image/29.png){#fig:029 width=70%}

##

Добавим журнал изменений в индекс при помощи команд ***git add CHANGELOG.md*** и ***git commit -am 'chore(site): update changelog'***.

![Добавление журнала изменений в индекс](image/30.png){#fig:030 width=70%}

##

Зальём релизную ветку в основную ветку при помощи команды ***git flow release finish 1.2.3***.

![Залив релизной ветки в основную ветку](image/31.png){#fig:031 width=70%}

##

Отправим данные на github.

![Отправка данных на github](image/32.png){#fig:032 width=70%}

##

Создадим релиз на github. Для этого будем использовать утилиты работы с github.

![Создание релиза на github](image/33.png){#fig:033 width=70%}

## Выводы

В этой лабораторной работе я получить навыки правильной работы с репозиториями git.


