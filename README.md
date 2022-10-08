# Для чего нужен контроль версий:

1. Возможность хранить различные версии проекта
2. Возможность возвращаться к различным версиям проекта.

Руководство по работе с Git

# Команды:

*Git init* - команда инициализирующая репозиторий в текущей директории.

*git status* - команда описывающая текущее состояние

*git add* + название файла(первые 2 буквы + tab) - сохранение

*git commit -m* "коментарий описывающий действие"

*git log* - журнал изменений

*git checkout* - переход к выбранной версии из сохранненых

*git checkout* + название сохранненого файла- переход от одного сохранния к другому

*git checkout master* - продолжить работу в актуальном состоянии (ветке)

*git diff* - разница между текущим состояним и сохранненым

# Команда сохранения на клавиатуре:
Ctrl+S

# Выход из журнала:
Q

## Lesson 2 (branch)

*Изучаем команды создания новых веток, перехода по ним и их слияние между собой.*

1. git branch -  отображает список имеющихся веток

2. git branch + new name branch - создание новой ветки

3. git checkout + name branch - переход с  ветки на ветку

объединение веток: git merge
4. git merge + name branch - слияние веток между собой

5. git branch -d + name branch - удаляет ненужную ветку

## Git Hub
 *копирование с Git hub*:
1. *Fork* - копирование чужого удаленного репозитория в свой локальный для внесения каких-то изменений. 

2. *git clone + ссылка* - загрузка чужого репозитория.

3. *cd* + название файла в проводнике в котором нужно работать - для работы именно в загруженном файле, а не в папке.

* выгрузка из локального в удаленный репозиторий*:

1.  git remete add origin 
2. git branch - M main/master
3. git push - u origin main/master 
