# Инструкция для работы с Git

* git init - инициализация локального репозитория
* git status - получить информацию о текущем состояние репозитория
* git add - добавить файл или файлы к следующему коммиту
* git commit -m "коммент" - создание комментария и фиксация изменений
* git log - вывод на экран истории всех коммитов с их хеш-кодами для текущего репозитория
* git checkout 1234 - переход к коммиту 1234 (где первые четыре символа хеш-кода)
* git checkout master - переход в актуальную запись ветки
* git diff - просмотреть разницу между текущим и закомиченным файлами
* git branch - посмотреть список веток в репозитории
+ git checkout <название ветки> - переход к другой ветке
* git branch <название ветки> - создать новую ветку
+ git branch -d <название ветки> - удалить ветку
* git merge <название ветки> - сливает текущую ветку и указанную
+ git branch --move <название ветки> <переименованное название>
+ git branch -v - просмотр последнего коммита всех веток
* git branch --no-merged - увидеть все ветки, содержащие наработки, которые ещё не слили в текущую ветку
+ git branch --merged - посмотреть те ветки, которые вы уже слили с текущей
