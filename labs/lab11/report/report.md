---
## Front matter
title: "Лабораторная работа №10"
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
       
Познакомиться с операционной системой Linux. Получить практические навыки рабо-
ты с редактором vi, установленным по умолчанию практически во всех дистрибутивах.  

# Выполнение лабораторной работы
     
Создаем каталог lab06, создаем файл hello.sh и открываем его через vi   
![q](image/1.png){#fig:001 width=70%}  
![q](image/2.png){#fig:001 width=70%}  

Дальше вставляем код  
![q](image/3.png){#fig:001 width=70%}   

Используя клавиши esc, :, w, q, i, enter я редактирую текст файла и делаю файл исполняемым  
![q](image/4.png){#fig:001 width=70%}  

Открываем снова hello.sh и начинаем редактирования.  
Устанавливаю курсор на четвертую строку и стираю слово LOCAL.  
В последней строке вставляю echo $HELLO и нажимаю esc.   
![q](image/5.png){#fig:001 width=70%}  
  
Сохраняю файл написав  
![q](image/6.png){#fig:001 width=70%}  

# Выводы
Мы научились пользоваться текстовым редактором vi.   
