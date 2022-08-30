## Что такое Git?

Git - это одна из реализаций распределенных систем контроля версий, имеющая как локальные, так и удаленные репозитории. Является самой популярной реализацией систем контроля версий в мире.

Git - это одна из реализаций распределенных систем контроля версий, имеющая как локальные, так и удаленные репозитории. Является самой популярной реализацией систем контроля версий в мире.

## Подготовка репозитри# Начальная работа с системой контроля версий Git

*git --version* - команда для проверки версии git

*git init* - инициализация пустого репозитория

*git status* - проверка теекущего состояния файлов

*git add имя_файла.расширение* - добавление версионности файлу

*git commit -m "Message"* - команда для фиксации изменений файлов

*git log* - вывод истории коммитов в хронологическом порядке

*git diff* - вывод изменений на текущий момент по отношению к последнему коммиту

*git checkout main/master/название_ветки/хэш-номер_коммита* - переход между изменениями или возврат к текущему состоянию


Для содания репозитория необходимо выполнить команду "git init" в папке с репозиторием

## Git add

Для добавления изменений в коммит используется команда *git add*. Чтобы использовать команду *git add*, напишите *git add <имя_файла>*

## Создание коммитов вносим изменения

Для того, чтобы создать коммит (сохранение), необходимо выполнить команду *git commit -m "Сообщение"*

## Создание ветки

Для того, чтобы создать ветку, нужно использовать *git branch <имя_ветки>* или *git checkout -b <имя_ветки>*

# Markdown 

![books](books.jpg)

[как вставить ссылку в маркдаун](https://yandex.ru/search/?text=%D0%BA%D0%B0%D0%BA+%D0%B2%D1%81%D1%82%D0%B0%D0%B2%D0%B8%D1%82%D1%8C+%D1%81%D1%81%D1%8B%D0%BB%D0%BA%D1%83+%D0%B2+%D0%BC%D0%B0%D1%80%D0%BA%D0%B4%D0%BE%D1%83%D0%BD&search_source=morda_desktop_simple&lr=100799)

> пример цитаты
>> второй уровень цитирования  

# Ненумерованный список
* строка 1
* строка 2
* строка 3

# Нумерованный список
1. строка 1
3. строка 2
2. строка 3

# Таблица

Таблица1   | 1параметр | 2параметр
:----------|:---------:| -------:
БЛА бла    | 1000      | 1001
бла        | 10        | 25705
бла 1      | 333       | 7777