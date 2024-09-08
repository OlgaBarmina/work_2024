---
## Front matter
lang: ru-RU
title: Отчёт по лабораторной работе №7.  
subtitle: Дискретное логарифмирование в конечном поле
author: "Бармина Ольга"
institute: Российский университет дружбы народов, Москва, Россия
date: 2024 September 8th

## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
linestretch: 1.25

mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.7
---

# Цели и задачи работы

## Цель лабораторной работы

\centering \Large \textbf{Целью} данной лабораторной работы является ознакомление с алгоритмом, реализующим p-метод Полларда для дискретного логарифмирования, а также программное воплощение данного алгоритма.

## Задание

1. Реализовать рассмотренный в инструкции к лабораторной работе алгоритм программно.

2. Подставить численное значение из примера в программный код, проверить правильность полученного ответа.

# Ход выполнения и результаты

## Ввод функции, зависящей от c,u,v

![Вспомогательная функция, зависящая от c,u,v ](images/1.jpg){ #fig:001 width=50% }

## Ввод функции для внедрения расш. алгоритма Евклида

![Вспомогательная функция. Расширенный алгоритм Евклида](images/2.jpg){ #fig:002 width=60% }

## Алгоритм, реализующий Po-метод Полларда. Реализация

![Реализация алгоритма Po-метода Полларда для логарифмирования](images/3.jpg){ #fig:003 width=50% }

## Результат проверки по данным из примера

![Результат реализации Po-метода Полларда на примере](images/4.jpg){ #fig:005 width=60% }

## Вывод

В результате выполнения данной лабораторной работы нам удалось осуществить программно алгоритм, рассмотренный в описании к лабораторной работе. А также получить ответ, совпадающий с ответом из инструкции.

