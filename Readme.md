# Инструкция по работе с git

## Что такое git
Git - одна из реализаций распределенных систем  контроля версий, позволяющая управлять изменениями, создавать фиксации, ветки и сливать их.

## Подготовка репозитория
Репозиторий - хранилище файлов, поддерживающее версионность. Создать репозиторий можно с помощью применения в папке команды *git init*

## Создание сохранений

## Перемещение между сохранениями
Перемещаться между сохранениями можно с помощью команды *git checkout* Для этого достаточно применить команду *git checkout <номер коммита>*
Можно отменить изменения с помощью команд *git revert* и *git reset*
*git revert <номер коммита>* отменить изменение до указанной версии и создаст новый коммит
*git resert --hard <номер коммита>* отменит изменения до указанного коммита и застрет всю историю изменений после этого коммита.

## Журнал изменений

## Ветки в git

## Слияние веток и решение конфликтов

## Удаление веток

## Скачивание удаленного репозитория