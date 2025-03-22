---
## Front matter
title: "Лабораторная работа №6"
subtitle: "Отчет"
author: "Арсакаев Дени"

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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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
  
Приобретение практических навыков взаимодействия пользователя с системой посредством командной строки.  



# Выполнение лабораторной работы

Каталог в котором я сейчас нахожусь  
![Ф](image/1.png){#fig:001 width=70%}  

Переходим в tmp  
![Ф](image/2.png){#fig:001 width=70%}  

Выводим содержание tmp  
![Ф](image/3.png){#fig:001 width=70%}  

Используем флажок -а с ls. -a выводит все скрытые файлы   
![Ф](image/4.png){#fig:001 width=70%}  

ls -s выводит подробную информацию  
![Ф](image/5.png){#fig:001 width=70%}  

Создаем папку newdir  
![Ф](image/6.png){#fig:001 width=70%}  

В папке newdir создаем папку morefun  
Создаем и другие паки  
И удаляем  
![Ф](image/7.png){#fig:001 width=70%}  

Удаляем newdir принудительно, используя флаг -r  
![Ф](image/8.png){#fig:001 width=70%}  

Смотрим какие флаги есть у команды ls и используем ls -tl для вывода всей информации и вывод по времени   
![Ф](image/9.png){#fig:001 width=70%}  

Используем man для вывода информации о команде   
![Ф](image/10.png){#fig:001 width=70%}  

Используем команду history для вывода истории вводы команд  
![Ф](image/11.png){#fig:001 width=70%}  
![Ф](image/12.png){#fig:001 width=70%}  

Вот что получилось   
![Ф](image/13.png){#fig:001 width=70%}  


# Выводы

Я науличлся чуть лучше пользоваться командной строкой!  



::: {#refs}
:::
