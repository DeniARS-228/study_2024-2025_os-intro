---
## Front matter
title: "Лабораторная работа №1"
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

Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.  

# Задание

Установка ОС  
Установка системы на диск  
Повышение комфорта работы  
Автоматическое обновление  
Отключение SELinux  
Настройка раскладки клавиатуры  
Установка программного обеспечения для создания документации  



# Выполнение лабораторной работы   

Добавляем iso образ Fedor'ы  
![](image/1.png){#fig:001 width=70%}  

Настраиваем пользователя и и выбираем диск  
![](image/2.png){#fig:001 width=70%}  
![](image/3.png){#fig:001 width=70%}  

Установка средства разработки  
![](image/4.png){#fig:001 width=70%}  

Устанавливаю программу для удобства работы в консоли  
![](image/5.png){#fig:001 width=70%}   

'+' еще другой вариант консоли  
![](image/6.png){#fig:001 width=70%}  

Настраиваю автоматическое обновление  
![](image/7.png){#fig:001 width=70%}  
Запускаю таймер  

В файле /etc/selinux/config заменяю значение  

SELINUX=enforcing  
на значение  
SELINUX=permissive  
![](image/8.png){#fig:001 width=70%}  

Устанавливаю пакет DKMS  
![](image/10.png){#fig:001 width=70%}  

Устанавливаю драйвера  
![](image/11.png){#fig:001 width=70%}  

И перезагружаю систему  
![](image/12.png){#fig:001 width=70%}  

Настройка раскладки клавиатуры:  
Создаю папку и конф. файл  
![](image/13.png){#fig:001 width=70%}  

Редактирую файл с помощью команды nano  
![](image/14.png){#fig:001 width=70%}  

Устанавливаю pandoc  
![](image/16.png){#fig:001 width=70%}  

Скачиваю pandoc-crossref и распаковываю файл  
![](image/17.png){#fig:001 width=70%}  

Перемещаю pandoc-crossref в папку bin  
![](image/18.png){#fig:001 width=70%}  

Устанавливаю texlive  
![](image/19.png){#fig:001 width=70%}  

Отыеты на вопросы  
![](image/20.png){#fig:001 width=70%}  
![](image/21.png){#fig:001 width=70%}  

# Выводы

Мы настрили системы для работы.  

::: {#refs}
:::
