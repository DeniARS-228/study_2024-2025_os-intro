---
## Front matter
title: "Лабораторная работа №5"
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

Менеджер паролей pass — программа, созданная в рамках идеологии Unix. Также носит название стандартного менеджера паролей для Unix (Стандартный менеджер паролей Unix).  


# Выполнение лабораторной работы
Установим менеджер паролей pass   
![q](image/1.png){#fig:001 width=70%}  
![q](image/2.png){#fig:001 width=70%}  

Выводим список gpg ключей  
![q](image/3.png){#fig:001 width=70%}  

И инициализируем хранилище   
![q](image/4.png){#fig:001 width=70%}  

Синхранизируем с git  
![q](image/5.png){#fig:001 width=70%}  

Задаем адрес репозитория на хосте  
![q](image/6.png){#fig:001 width=70%}   

Для синхронизации выполняем  
![q](image/7.png){#fig:001 width=70%}   

Создаем каталог  
![q](image/8.png){#fig:001 width=70%}  

И прописываем следующие команды  
![q](image/9.png){#fig:001 width=70%}  

Для проверки статуса синхронизации используем  
![q](image/10.png){#fig:001 width=70%}  

Настройка интерфейса с броузером  
![q](image/11.png){#fig:001 width=70%}   
![q](image/12.png){#fig:001 width=70%}   

Создаю тхт файл  
![q](image/13.png){#fig:001 width=70%}   

Сохраняю пароль  
![q](image/14.png){#fig:001 width=70%}   
![q](image/15.png){#fig:001 width=70%}   

Заменяю пароль  
![q](image/16.png){#fig:001 width=70%}   

Скачиваю доп. программное обеспечение  
![q](image/17.png){#fig:001 width=70%}   

Уснановка шрифтов   
![q](image/18.png){#fig:001 width=70%}   

Создаю свой репозиторий  
![q](image/19.png){#fig:001 width=70%}   

Подключаю свой репозиторий к системе   
![q](image/20.png){#fig:001 width=70%}   

Указываю свое email  
![q](image/21.png){#fig:001 width=70%}   

Извлекаю изменения из репозитория  
![q](image/23.png){#fig:001 width=70%}  
![q](image/24.png){#fig:001 width=70%}  
![q](image/25.png){#fig:001 width=70%}  
 
Автоматическое обновление  
![q](image/26.png){#fig:001 width=70%}


# Выводы

Мы научились работать с менеджером паролей pass


:::
