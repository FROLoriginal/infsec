---
# Front matter
lang: ru-RU
title: "Отчёт по лабораторной работе №1"
subtitle: "Развертывание виртуальной машины"
author: ""

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Выполнил работу:
Волков Фрол НПИбд-01-19

# Цели и задачи работы

## Цель лабораторной работы

Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

– Изучить идеологию и применение средств контроля версий.

– Освоить умения по работе с git.


# Процесс выполнения лабораторной работы

## Создаю виртуальную машину

![Создание новой виртуальной машины](image/01.png){ #fig:001 width=70% height=70% }

## Задаю конфигурацию оперативной памяти

![Конфигурация оперативной памяти](image/02.png){ #fig:002 width=70% height=70% }

## Задаю конфигурацию жёсткого диска

![Конфигурация жёсткого диска](image/03.png){ #fig:003 width=70% height=70% }

## Задаю конфигурацию жёсткого диска

![Конфигурация жёсткого диска](image/04.png){ #fig:004 width=70% height=70% }

## Добавляю новый привод оптических дисков и выбираю образ

![Конфигурация системы](image/05.png){ #fig:005 width=70% height=70% }

## Установка системы

![Приветственный экран](image/06.png){ #fig:006 width=70% height=70% }

## Установка системы

![Параметры установки](image/07.png){ #fig:007 width=70% height=70% }

## Установка системы

![Этап установки](image/08.png){ #fig:008 width=70% height=70% }

## Установка системы

![Завершение установки](image/09.png){ #fig:009 width=70% height=70% }

## Первый запуск

![Запущенная система](image/10.png){ #fig:010 width=70% height=70% }

## Задания:
1. Версия ядра Linux (Linux version).
![Версия ядра Linux (Linux version)](image/11.png){ #fig:011 width=70% height=70% }
2. Частота процессора (Detected Mhz processor).
![Частота процессора](image/12.png){ #fig:012 width=70% height=70% }
3. Модель процессора (CPU0).
![Модель процессора](image/13.png){ #fig:013 width=70% height=70% }
4. Объем доступной оперативной памяти (Memory available).
![Объем доступной оперативной памяти (Memory available)](image/14.png){ #fig:014 width=70% height=70% }
5. Тип обнаруженного гипервизора (Hypervisor detected).
![Тип обнаруженного гипервизора (Hypervisor detected)](image/15.png){ #fig:015 width=70% height=70% }
6. Тип файловой системы корневого раздела.
![Тип файловой системы корневого раздела](image/16.png){ #fig:016 width=70% height=70% }
7. Последовательность монтирования файловых систем.
![Последовательность монтирования файловых систем](image/17.png){ #fig:017 width=70% height=70% }

# Git задачи
1. Создать базовую конфигурацию для работы с git.
![Создать базовую конфигурацию для работы с git](image/20.png){ #fig:020 width=70% height=70% }

2. Создать ключ SSH.
![Создать ключ SSH](image/21.png){
	#fig:021 width=80% height=70% }

3. Создать ключ PGP.
![Создать ключ PGP](image/22.png){
	#fig:022 width=80% height=70% }

4. Настроить подписи git.
![Настроить подписи git](image/23.png){ #fig:023 width=70% height=70% }

5. Зарегистрироваться на Github.
![Зарегистрироваться на Github](image/24.png){ #fig:024 width=70% height=70% }

6. Создать локальный каталог для выполнения заданий по предмету.
![Создать локальный каталог для выполнения заданий по предмету](image/25.png){ #fig:025 width=70% height=70% }

# Вывод

Мы приобрели практические навыки установки операционной системы на виртуальную машину, Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, разместили файлы работы на сервисе Git и подготовили отчет в формате Markdown.

– Изучили идеологию и применение средств контроля версий.

– Освоили умения по работе с git.
