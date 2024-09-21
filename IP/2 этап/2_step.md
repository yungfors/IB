---
## Front matter
title: "Отчет по проекту"
subtitle: "Этап 2"
author: "Петрва Мария евгеньевна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"
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

Преобретение практических навыков по установке DVWA.

# Выполнение этапа 2

**1. Перешла в директорию /var/www/html. Затем клонировала репозиторий. 

**2. Проверяю, что файл склонировался. Повышаю права доступа к папке до 777. 

**3. Перешла в каталог /dvwa/config. Создала копию файла. 

**4. Открыла файл в тектовом редакторе. 
**5. Изменила данные об имени пользователя и пароле. 
**6. Запустила mysql. 

**7. Авторизовалась в базе от имени пользователя root. Создала нового пользователя. 
**8.** Перешла в директорию. 


**9.В файле php.ini изменила один параметр. 


**10. Запустила службу веб-сервера apache. 


**11. Зашла в веб-сервер. 

**12. Авторизовалась. 


# Вывод

Преобрела практические навыки по установке DVWA.
