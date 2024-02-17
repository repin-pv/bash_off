# Учим GIT

## Настроим GIT 
### Настройка персональных данных
* git config --global user.name "repin_pv"
* git config --global user.email "systemlogd@gmail.com"

### Настройка формата окончания строк для MS Windows
* git config --global core.safecrlf warn
* git config --global core.quotepath off
* git config --global core.safecrlf warn

### Настройка основной ветки
* git config --global init.defaultBranch main

### Проверим настройки персональных данных
* git config --global --list 

## Работа с локальным репозиторием
### Чтобы создать локальный репозиторий:
* Создайте папку проекта на компьютере
* Откройте для папки терминал
* Выполните команду `git init`
* Проверьте, что появилась папка `.git`

### Чтобы сделать снимок проекта (сформировать коммит):
* Добавьте файл или файлы в отслеживаемые командой `git add имя файла`
* Создайте коммит и подпишите его командой `git commit -m "Подпись коммита"`

* Чтобы проверить состояние файла На любом из этапов вы можете выполнить команду `git status`

* Просмотреть историю проекта `git log --oneline`