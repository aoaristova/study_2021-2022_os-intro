---
# Front matter
lang: ru-RU
title: "Лабораторная работа 3"
subtitle: "Markdown"
author: "Арина Олеговна Аристова"

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
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

# Цель работы

Научиться оформлять отчёты с помощью легковесного языка разметки Markdown.

# Задание

– Сделайте отчёт по предыдущей лабораторной работе в формате Markdown.

– В качестве отчёта просьба предоставить отчёты в 3 форматах: pdf, docx и md (в архиве, поскольку он должен содержать скриншоты, Makefile и т.д.)

# Теоретическое введение

Markdown (произносится маркдаун) — облегчённый язык разметки, созданный с целью обозначения форматирования в простом тексте, с максимальным сохранением его читаемости человеком, и пригодный для машинного преобразования в языки для продвинутых публикаций.

# Выполнение лабораторной работы

Открываю шаблон отчета и указываю номер лабораторной работы, тему и автора отчета.

![Указание номера, темы лабораторной работы и автора.](image/1.jpg){ #fig:001 width=70% }

Указываю цель работы.

![Указание цели работы.](image/image1/2.jpg){ #fig:002 width=70% }

Указываю задание лабораторной работы.

![Указание задания лабораторной работы.](image/image1/3.jpg){ #fig:003 width=70% }

Заполняю теоретическое введение к лабораторной работе.

![Заполнение теоретического введения работы.](image/image1/4.jpg){ #fig:004 width=70% }

Приступаю к выполнению лабораторной работы, добавляю скриншоты выполненной работы, названия картинок и описание к ним. 

![Этап выполнение лабораторной работы.](image/image1/5.jpg){ #fig:005 width=70% }

Указываю вывод по выполнению лабораторной работы.

![Вывод по выполнению лабораторной работы.](image/image1/6.jpg){ #fig:006 width=70% }


Отвечаю на контрольные вопросы к лабораторной работе №2.

![Ответы на контрольные вопросы.](image/image1/7.jpg){ #fig:007 width=70% }

Затем я преобразовываю файл .md в .pdf и .docx. 

![Преобразование файла .md в .pdf и .docx](image/image1/8.jpg){ #fig:008 width=70% }

И проверяю их содержание. 

![Проверка содержания файлов.](image/image1/9.jpg){ #fig:009 width=70% }

# Выводы

В ходе лабораторной работы я научилась оформлять отчёты с помощью легковесного языка разметки Markdown.
