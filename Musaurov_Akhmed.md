# Практическое задание  по семинару №1 + №2 +№3.

## Основные команды Git.
1. **git init** - *инициализация локального репозитория*.
2. **git status** - *получить информацию от git о его текущем состоянии.*
3. **git add** - *добавить файл или файлы к следующему коммиту.*
4. **git commit -m "message"** - *создание коммита.*
5. **git log** - *вывод на экран истории всех коммитов с их хеш-кодами.*
6. **git checkout** - _переход от одного коммита к другому._
7. **git checkout master** - - _вернуться к актуальному состоянию и продолжить работу_. 
* __git checkout name_branch__ - *позволяет перемещаться между ветками.*
8. __git diff__ - *увидеть разницу между текущим файлом и закоммиченным файлом.*
9. **git branch** - *позволяет посмотреть кол-во веток, и актуальную для работы*.
10. **git merge name_branch** - _слияние текущей ветки с другой веткой (наименование которой мы ввели при команде)_
11. **git checkout -b new_name_branch** - *создает новую ветку и сразу делает ее актуальной для работы.*
# Инструкция по совместной работе через GitHub

1. Переходим по ссылке нужного удаленного репозитория.
2. Жмем на кнопку Fork (в списке наших репозиториев появился fork)
3. Клонируем к себе в папку
4. Открывает папку в VS
5. выполняем git branch FIO
6. выполняем git checkout FIO
7. Добавляем свой файл с названием FIO.MD
8. Выполняем Коммит
9. выполняем git push (если git ругается, выполняем команду из подсказки)
10. на github выполняем pull request