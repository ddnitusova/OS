---
# Front matter
lang: ru-RU
title: **"Отчет по лабораторной работе №2"**
subtitle: *"Операционные системы"*
author: "Диана Денисовна Нитусова"

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
lot: true # List of tables
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
  - usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

**Цель:** Изучить идеологию и применение средств контроля версий.

# Задание

**Задание:** Изучить Github.

# Выполнение лабораторной работы

**Ход работы:**

Создаем учётную запись на GitHub (Рисунок 1)

![Рисунок 1](Snapshots/lab03.1.png){Рисунок 1 width=70% }

Настраиваем систему контроля версий (Рисунок 2,3)

![Рисунок 2](Snapshots/lab03.2.png){Рисунок 2 width=70% }

![Рисунок 3](Snapshots/lab03.3.png){Рисунок 3 width=70% }

Создаем структуру каталога лабораторных работ (Рисунок 4)

![Рисунок 4](Snapshots/lab03.4.png){Рисунок 4 width=70% }

Создаем репозиторий на GitHub (Рисунок 5)

![Рисунок 5](Snapshots/lab03.5.png){Рисунок 5 width=70% }

Добавляем файл README.md на GitHub (Рисунок 6)

![Рисунок 6](Snapshots/lab03.6.png){Рисунок 6 width=70% }

Добавляем файл лицензии и шаблон игнорируемых файлов, добавляем на GitHub (Рисунок 7,8)

![Рисунок 7](Snapshots/lab03.7.png){Рисунок 7 width=70% }

![Рисунок 8](Snapshots/lab03.8.png){Рисунок 8 width=70% }

Работаем с gitflow. Создаем релиз, записываем VERSION, сливаем ветки, отправляем данные на GitHub. (Рисунок 9,10)

![Рисунок 9](Snapshots/lab03.9.png){Рисунок 9 width=70% }

![Рисунок 10](Snapshots/lab03.10.png){Рисунок 10 width=70% }

Создаем релиз на GitHub. (Рисунок 11)

![Рисунок 11](Snapshots/lab03.11.png){Рисунок 11 width=70% }

# Выводы

**Вывод:** Я изучила идеологию и применение средств контроля версий.



