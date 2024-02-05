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
Добавление одного файла в индекс изменений (*[документация](https://git-scm.com/docs/git-add)*):
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
Просмотр журнала изменений (*[документация](https://git-scm.com/docs/git-log)*):
```sh
git log
```
Просмотр журнала изменений в более компактном виде:
```sh
git log --oneline
```
Просмотр разницы между текущим состоянием файла и сохраненным (*[документация](https://git-scm.com/docs/git-diff)*):
```sh
git diff
```
Возврат к сохраненной версии файла (все изменения не сохраненные командой git commit пропадут)(*[документация](https://git-scm.com/docs/git-restore)*):
```sh
git restore
```
Переход к другой версии файла (*[документация](https://git-scm.com/docs/git-checkout)*):
```sh
git checkout <number_of_commit>
```
Переход на актуальную версию файла:
```sh
git checkout master
```

## Работа с ветками репозитория

