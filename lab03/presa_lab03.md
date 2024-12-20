---
## Front matter
lang: ru-RU
title: Лабораторная работа №3
subtitle: Дискреционное разграничение прав в Linux. Два пользователя
author:
  - Петрова Мария
institute:
  - Российский университет дружбы народов, Москва, Россия

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
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Петрова Мария Евгеньевна
  * НФИбд-02-21
  * Российский университет дружбы народов
  * 1032216450 


:::
::: {.column width="30%"}

:::
::::::::::::::

# Выполнение

## Цель работы

Получение практических навыков работы в консоли с атрибутами файлов для групп пользователей.

# Выполнение лабораторной работы

**1. Создала учетную запись пользователя guest2 и задала пароль. 


##

**2. Добавьте пользователя guest2 в группу guest. 



##

**3. Осуществила вход в систему от двух пользователей на двух разных консолях: guest на первой консоли и guest2 на второй консоли. 


##

**4. Для обоих пользователей командой pwd определила директорию, в которой нахожусь. Сравнила её с приглашениями командной строки. 



##


##

**5.** Уточнила имя пользователя, его группу, кто входит в неё
и к каким группам принадлежит он сам. Определила командами
groups guest и groups guest2, в какие группы входят пользователи guest и guest2. Сравнила вывод команды groups с выводом команд
id -Gn и id -G. 

##



##

**6.** Сравнила полученную информацию с содержимым файла /etc/group. 


##

**7. От имени пользователя guest2 выполнила регистрацию пользователя
guest2 в группе guest. 


##

**8. От имени пользователя guest изменила права директории /home/guest,
разрешив все действия для пользователей группы. Сняла с директории /home/guest/dir1
все атрибуты командой. 



##

**9.Меняя атрибуты у директории dir1 и файла file1 от имени пользователя guest и делая проверку от пользователя guest2, заполнила таблицу,
определив опытным путём, какие операции разрешены, а какие нет.


# Вывод

Получила практические навыки работы в консоли с атрибутами файлов для групп пользователей.
