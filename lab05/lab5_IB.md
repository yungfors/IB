---
## Front matter
title: "Отчет по лабораторной работе №5"
subtitle: "Дискреционное разграничение прав в Linux. Исследование влияния дополнительных атрибутов"
author: "Петрова Мария Евгеньевна"

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
polyglossia-lang:
  name: russian
  options:
  - spelling=modern
  - babelshorthands=true
polyglossia-otherlangs:
  name: english
babel-lang: russian
babel-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Изучение механизмов изменения идентификаторов, применения SetUID- и Sticky-битов. Получение практических навыков работы в консоли с дополнительными атрибутами. Рассмотрение работы механизма смены идентификатора процессов пользователей, а также влияние бита Sticky на запись и удаление файлов.

# Выполнение лабораторной работы

1. Установила gcc. Отключила систему защиты до очередной перезагрузки системы. 

2. Вошла в систему от имени guest.

3. Создала simpleid.c. 

4. Скомплилировала программу и убедилась, что файл программы создан. 

5. Выполнила программу simpleid. Выполнила системную программу id. Сравнила полученные результаты. Они схожи. 

6. Усложнила программу,добавив вывод действительных идентификаторов. Получившуюся программу назовала simpleid2.c.
Скомпилировала и запустила simpleid2.c.

7. От имени суперпользователя выполнила команды. 
8. Выполнила проверку правильности установки новых атрибутов и смены
владельца файла simpleid2.Запустила simpleid2 и id. Сравнила результаты. 

9.  Проделала тоже самое относительно SetGID-бита. 

10. Создала программу readfile.c. Откомпелировала ее. 
11. . Сменила владельца у файла readfile.c и изменила права так, чтобы только суперпользователь (root) мог прочитать его, a guest не мог. Проверила, что пользователь guest не может прочитать файл readfile.c.

12. Проверила, может ли программа readfile прочитать файл readfile.c. Проверила, может ли программа readfile прочитать файл. 

13. Повысила прова до суперпользователя. Сняла аотрибут t. Покинула режим суперпользователя. Проверила отсутвтвие атрибута t. Повторила предыдущие шаги.
14. Вернула атрибут t. 

# Вывод

      Изучила механизмы изменения идентификаторов, применения SetUID- и Sticky-битов. Получила практические навыки работы в консоли с дополнительными атрибутами. Рассмотрела работы механизма смены идентификатора процессов пользователей, а также влияние бита Sticky на запись и удаление файлов.









