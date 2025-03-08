---
## Front matter
title: "Лабораторная работа №2"
subtitle: "Отчет"
author: "Арсакаев Дени Умарович"

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

Изучить идеологию и применение средств контроля версий.  
Освоить умения по работе с git.  



# Задание

1.Создать базовую конфигурацию для работы с Git.  
2.Создать ключ SSH.  
3.Создать ключ PGP.  
4.Настроить подписи Git.  
5.Зарегистрироваться на Github.  
6.Создать локальный каталог для выполнения заданий по АКиОС.  


# Выполнение лабораторной работы
установим git и gh   
![git install](image/1.png){#fig:001 width=70%}  
![gh install](image/2.png){#fig:001 width=70%}  

Зададим имя и email владельца репозитория:  
![email and name](image/3.png){#fig:001 width=70%}  

Зададим имя начальной ветки, параметр autocrlf и safecrlf:  
![parametri git](image/4.png){#fig:001 width=70%}  

Создайем ключи ssh:  
![ssh key](image/5.png){#fig:001 width=70%}  

Создайем ключи pgp:  
![pgp key](image/6.png){#fig:001 width=70%}   

Создаю уч. запись GH:  
![git reg](image/7.png){#fig:001 width=70%}  

В настройках GitHub'a добавляю pgp ключ:  
![git key pgp in setting](image/8.png){#fig:001 width=70%}  

Настройка автоматических подписей коммитов git:  
![auto commit gh](image/9.png){#fig:001 width=70%}   

Настройка gh:  
![gh set.](image/10.png){#fig:001 width=70%}  

Cоздаю каталог и cкачиваю туда шаблон для рабочего пространства:  
![create folder and download shablon](image/11.png){#fig:001 width=70%}  
![create folder and download shablon+](image/12.png){#fig:001 width=70%}  

Удаляем лишние файлы и создаем каталоги:  
![make prepare](image/13.png){#fig:001 width=70%}  

Отправляем файлы на сервер:  
![git add](image/14.png){#fig:001 width=70%}  
![git push](image/15.png){#fig:001 width=70%}  



# Выводы

Мы научились пользоваться GitHub!

::: {#refs}
:::
