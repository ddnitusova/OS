---
# Front matter
lang: ru-RU
title: "Отчёт по лабораторной работе номер 10"
subtitle: "Операционные системы"
author: "Нитусова Диана Денисовна"

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
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Познакомиться с операционной системой Linux. Получить
практические навыки работы с редактором Emacs.

# Задание

Изучить редактор Emacs.

# Выполнение лабораторной работы
Откроем редактор Emacs с помощью команды «emacs &».
Создадим файл lab07.sh с помощью комбинации «Ctrl-x» «Ctrl-f». (рис. -@fig:001)

![Рисунок 1](snapshots10/lab10.1.png){ #fig:001 width=70% }

В открывшемся буфере наберем необходимый текст (рис. -@fig:002 )

![Рисунок 2](snapshots10/lab10.2.png){ #fig:002 width=70% }

Сохраним файл с помощью комбинации «Ctrl-x» «Ctrl-s».

Вырежем одной командой целую строку («Сtrl-k»)(рис. -@fig:003)

![Рисунок 3](snapshots10/lab10.3.png){ #fig:003 width=70% }

Вставим эту строку в конец файла («Ctrl-y») (рис. -@fig:004) 

![Рисунок 4](snapshots10/lab10.4.png){ #fig:004 width=70% }

Выделим область текста («Ctrl-space»). (рис. -@fig:005)

![ Рисунок 5](snapshots10/lab10.5.png){ #fig:005 width=70% }

Скопируем область в буфер обмена («Alt-w»)
Вставим область в конец файла («Ctrl-y») (рис. -@fig:006)  

![Рисунок 6](snapshots10/lab10.6.png){ #fig:006 width=70% }

Вновь выделим эту область («Ctrl-space») (Рисунок 9) и на этот раз
вырежем её («Ctrl-w») (рис. -@fig:007)

![ Рисунок 7](snapshots10/lab10.7.png){ #fig:007 width=70% } 

Отменим последнее действие («Ctrl-/») (рис. -@fig:008)

![ Рисунок 8](snapshots10/lab10.8.png){ #fig:008 width=70% } 

Переместим курсор в начало строки («Ctrl-a»)(рис. -@fig:009) 

![ Рисунок 9](snapshots10/lab10.9.png){ #fig:009 width=70% } 

Переместим курсор в конец строки («Ctrl-e») (рис. -@fig:010)

![ Рисунок 10](snapshots10/lab10.10.png){ #fig:010 width=70% } 

Переместим курсор в начало буфера («Alt-<») (рис. -@fig:011) 

![ Рисунок 11](snapshots10/lab10.11.png){ #fig:011 width=70% } 

Переместим курсор в конец буфера («Alt->») (рис. -@fig:012)

![ Рисунок 12](snapshots10/lab10.12.png){ #fig:012 width=70% } 

Выведем список активных буферов на экран («Ctrl-x» «Ctrl-b»)(рис. -@fig:013)

![ Рисунок 13](snapshots10/lab10.13.png){ #fig:013 width=70% } 

Переместимся во вновь открытое окно («Ctrl-x o») со списком
открытых буферов и переключимся на другой буфер (для
этого необходимо нажать на «enter» после выбора необходимого буфера)(рис. -@fig:014)

![ Рисунок 14](snapshots10/lab10.14.png){ #fig:014 width=70% } 

Закроем это окно («Ctrl-x 0»)
Теперь вновь переключимся между буферами, но уже без вывода их
списка на экран («Ctrl-x b») (рис. -@fig:015)

![ Рисунок 15](snapshots10/lab10.15.png){ #fig:015 width=70% } 

Поделим фрейм на 4 части: разделим фрейм на два окна по
вертикали («Ctrl-x 3»), а затем каждое из этих окон на две части по
горизонтали («Ctrl-x 2»)(рис. -@fig:016)

![ Рисунок 16](snapshots10/lab10.16.png){ #fig:016 width=70% } 

В каждом из четырёх созданных окон откроем новый буфер (файл)
и введем несколько строк текста. Для этого предварительно создадим
эти файлы с помощью команд «touch lab09.1.txt», «touch lab09.2.txt»,
«touch lab09.3.txt», «touch lab09.4.txt».

(рис. -@fig:017)(рис. -@fig:018)

![ Рисунок 17](snapshots10/lab10.17.png){ #fig:017 width=70% }

![ Рисунок 18](snapshots10/lab10.18.png){ #fig:018 width=70% }

Переключимся в режим поиска («Ctrl-s») и найдем несколько
слов, присутствующих в тексте.

(рис. -@fig:019)(рис. -@fig:020)

![ Рисунок 19](snapshots10/lab10.19.png){ #fig:019 width=70% }

![ Рисунок 20](snapshots10/lab10.20.png){ #fig:020 width=70% }

Переключимся между результатами поиска, нажимая «Ctrl-s».(рис. -@fig:021)

![ Рисунок 21](snapshots10/lab10.21.png){ #fig:021 width=70% } 

Выйдем из режима поиска, нажав «Ctrl-g».

Пробуем режим поиска, нажав «Alt-s o».(рис. -@fig:022)

![ Рисунок 22](snapshots10/lab10.22.png){ #fig:022 width=70% } 

# Контрольные вопросы

1) Emacs − один из наиболее мощных и широко распространённых
редакторов, используемых в мире Unix. По популярности он
соперничает с редактором vi и его клонами. В зависимости от ситуации,
Emacs может быть:

текстовым редактором;
программой для чтения почты и новостей Usenet;
интегрированной средой разработки (IDE);
операционной системой и т.д.

Всё это разнообразие достигается благодаря архитектуре Emacs,
которая позволяет расширять возможности редактора при помощи
языка Emacs Lisp. На языке C написаны лишь самые базовые и
низкоуровневые части Emacs, включая полнофункциональный 
интерпретатор языка Lisp. Таким образом, Emacs имеет встроенный
язык программирования, который может использоваться для настройки,
расширения и изменения поведения редактора. В действительности,
большая часть того редактора, с которым пользователи Emacs работают
в наши дни, написана на языке Lisp.

2) Основную трудность для новичков при освоении данного редактора
могут составлять большое количество команд, комбинаций клавиш,
которые не получится все запомнить с первого раза и поэтоу придется
часто обращаться к справочным материалам.

3) Буфер – это объект, представляющий собой текст. Если имеется
несколько буферов, то редактировать можно только один. Обычно буфер
считывает данные из файла или записывает в файл данные из буфера.
Окно – это область экрана, отображающая буфер. При запуске редактора
отображается одно окно, но при обращении к некоторым функциям
могут открыться дополнительные окна. Окна Emacs и окна графической
среды X Window – разные вещи. Одно окно X Window может быть
разбито на несколько окон в смысле Emacs, в каждом из которых
отображается отдельный буфер.

4) Да, можно.

5) При запуске Emacs по умолчанию создаются следующие буферы:
«scratch» (буфер для несохраненного текста)
«Messages» (журнал ошибок, включающий также информацию,
которая появляется в области EchoArea)
«GNU Emacs» (справочный буфер о редакторе)

6) C-c | сначала, удерживая «ctrl», нажимаю «c», после – отпускаю обе
клавиши и нажимаю «|»
C-c C-| сначала, удерживая «ctrl», нажимаю «с», после – отпускаю обе
клавиши и, удерживая «ctrl», нажимаю «|»

7) Чтобы поделить окно на две части необходимо воспользоваться
комбинацией «Ctrl-x 3» (по вертикали) или «Ctrl-x 2» (по горизонтали).

8) Настройки Emacs хранятся в файле .emacs.

9) По умолчанию клавиша «←» удаляет символ перед курсором, но в
редакторе её можно переназначить. Для этого необхдимо изменить
конфигурацию файла .emacs.

10) Более удобным я считаю редактор emacs, потому что в нем проще
открывать другие файлы, можно использовать сразу несколько окон, нет
«Командного режима», «Режима ввода», «Режима командной строки»,
которые являются немного непривычными и в какой-то степени
неудобными

# Выводы

В ходе выполнения данной лабораторной работы я познакомилась
с операционной системой Linux и получила практические навыки работы
с редактором Emacs