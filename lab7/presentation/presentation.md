---
## Front matter
lang: ru-RU
title: Элементы криптографии. Однократное гаммирование
author: Александр Воробьев

institute: RUDN University

date: 18 октября, 2022, Москва, Россия

## Formatting
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
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

---

# Цель лабораторной работы

Освоить на практике применение режима однократного гаммирования

# Процесс выполнения лабораторной работы


## Блок функции для расчетов

### Результат

![Блок функции для расчетов](screens/1.png){ #fig:001 width=70% }  

## Определил вид шифротекста при известном ключе и известном открытом тексте. 

### Результат

![Получение шифротекста](screens/2.png){ #fig:002 width=70% }  

## Определил ключ,с помощью которого шифротекст может быть преобразован в некоторый фрагмент текста,представляющий собой один из возможных вариантов прочтения открытого текста.  

### Результат

![Прочтение открытого текста](screens/3.png){ #fig:003 width=70% }  

# Выводы

Освоил на практике применение режима однократного гаммирования.
