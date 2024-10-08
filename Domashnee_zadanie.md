# Инструкция по работе с Git и удалёнными репозиториями

## 1. Что такое Git?
Git — это система контроля версий, которая помогает отслеживать изменения в проектах и управлять ими. Она позволяет хранить разные версии проекта, возвращаться к предыдущим версиям и работать с удалёнными репозиториями.

## 2. Подготовка репозитория
Чтобы начать работу с проектом, нужно инициализировать новый репозиторий. Для этого выполните команду:
```bash
git init
```
Это создаст скрытую папку .git, которая будет хранить всю информацию о версиях.
## 3. Добавление файлов в репозиторий
Когда вы внесли изменения в файлы проекта, их нужно добавить в индекс для последующего сохранения. 
Для того чтобы добавить изменения в репозиторий, используйте команду:
```bash
git add <имя файла>
```
Можно добавить все изменённые файлы с помощью команды:
```bash
git add
```
## 4. Создание коммита
Чтобы зафиксировать изменения, выполните команду:
```bash
git commit -m "Описание изменений"
```
Это сохранит ваши изменения в репозитории с описанием того, что было сделано.
## 5. Проверка статуса репозитория
Для проверки состояния репозитория и того, какие файлы были изменены, используйте:
```bash
git status
```
## 6. Работа с удалённым репозиторием
## *Подключение удалённого репозитория*
Чтобы связать локальный репозиторий с удалённым, выполните команду:
```bash
git remote add origin <URL репозитория>
```
## *Отправка изменений в удаленный репозиторий*
После того, как изменения зафиксированы, их нужно отправить в удалённый репозиторий командой:
```bash
git push origin master
```
## Получение изменнений из удаленного репозитория
Для загрузки последних изменений с удалённого репозитория используйте команду:
```bash
git pull origin master
```
## 7. Дополнительно
## *Цитаты*
Чтобы добавить цитату, используйте символ > перед текстом. 

Пример:
```bash 
***> Это важное примечание.***
```
Пример:
***> Это важное примечание.***
## *Картинки*
Для добавления изображений из интернета используйте синтаксис:
```bash
![Логотип Git](https://git-scm.com/images/logos/downloads/Git-Logo-2Color.png)

```
Пример:
![Логотип Git](https://git-scm.com/images/logos/downloads/Git-Logo-2Color.png)


Для добавления картинки из локального размещения, используйте синтаксис: 
```bash
![Логотип Git](./Git-Logo-2Color.png)
```
Пример:
![Логотип Git](./Git-Logo-2Color.png)
## *Ссылки*
Чтобы добавить ссылку на ресурс, используйте:
```bash
[Текст ссылки](URL)
```
Пример:
```bash
[Официальная документация Git](https://git-scm.com/doc)
```
[Официальная документация Git](https://git-scm.com/doc)

# Добавим как добавлять картинки в Markdown
Это яблоко
![Яблоко](apple.jpg)
Это итоговое изменение, объединяющее branch_3 и branch_4

Попытка добавить люда текст из локального репа.

Попытка удалась

## Подсказки по основным командам Git

```sh
git help
```
*- Справка покомандам Git.*

*- Используй для получения помощи по конкретной команде.*
```sh
git clone
```
*Клонирование удаленного репозитория на локальный компьютер.*

```sh
git status
```
*- проверка текущего состояния репозитория: какие файлы изменены, добавлены или готовы к коммиту.*

```sh
git branch
```
*- Управление ветками: создание, удаление, отображение списка веток.*
```sh
git checkout
```
*- Переключение между ветками или восстановление файлов до определенного состояния.*

```sh
git merge 
```
*- Объединение из одной ветки с текущей.*

```sh
git remote
```
*- Управление подключениями к удаленным репозиториями.

```sh
git fetch
```
*- Получение изменений из удаленного репозитория без их объединения*

```sh
git push
```
*- Отправка локальных коммитов в удаленный репозиторий.*

```sh
git pull
```
*- Получение и объединение изменений из удаленного репозитория*