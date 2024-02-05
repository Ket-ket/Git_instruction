# **Инструкция по работе с Git**
 Создание пустого репозитория (*[документация](https://git-scm.com/docs/git-init)*):
 ```sh
git init
 ```
 Просмотр текущего состояния репозитория (*[документация](https://git-scm.com/docs/git-status)*):
```sh
git status
```
## Создание коммитов
Добавление файла в индекс изменений (*[документация](https://git-scm.com/docs/git-add)*):
```sh
git add <file_name>
```
Добавление всех файлов в индеск изменений:
```sh
git add .
```
Сохранение изменений с указанием комментария (*[документация](https://git-scm.com/docs/git-commit)*):
```sh
git commit -m <message>
```

## Работа с историей

## Работа с ветками репозитория
Просмотр доступных веток в репозитории (*[документация](https://git-scm.com/docs/git-branch)*):
```sh
git branch
```
Создание новой ветки:
```sh
git branch <branch_name>
```
Переход на указанную ветку:
```sh
git checkout <branch_name>
```
Удаление указанной ветки:
```sh
git branch -d <branch_name>
```