---
## Front matter
title: "Вторая лабораторная работа. Шифры перестановки"
subtitle: "НПИмд-01-23"
author: "Бармина Ольга Константиновна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: gost-r-7-0-5-2008-numeric.csl

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

Цель данной работы - ознакомиться с шифрами перестановки, а также научиться применять их на практике.

# Задание

1. Реализовать маршрутное шифрование
2. Реализовать шифрование с помощью решеток
3. Реализовать шифрование с использованием таблицы Вижинера

# Теоретическое введение

Шифры перестановки преобразуют открытый текст в криптограмму путем перестановки его символов. Способ, каким при шифровании переставляются буквы открытого текста и является ключом шифра. Важным требования является равенство длин ключа исходного текста [@kurs].

# Выполнение лабораторной работы

1. Произведено ознакомление с шифрами перестановки по методическим материалам курса

2. Прописан код для маршрутного шифрования на языке программирования Python. Выводим на экран результат применения.

![Маршрутное шифрование](images/1.jpg){#fig:001 width=70%}

4. Прописан код для шифрования с помощью решеток на языке программирования Python. Выводим на экран результат применения.

![Шифрование с помощью решеток](images/2.jpg){#fig:003 width=70%}

![Результат применения 2](images/3.jpg){#fig:004 width=70%}

6. Прописан код для шифрования с использованием таблицы Вижинера на языке программирования Python. Выводим на экран результат применения.

![Таблица Вижинера](images/4.jpg){#fig:005 width=70%}

# Выводы

В рамках данной лабораторной работы было произведено ознакомление с шифрами перестановки.
Шифры были реализованы на языке программирования Python.

# Список литературы{.unnumbered}

::: {#refs}
:::
