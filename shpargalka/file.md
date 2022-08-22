# Шпаргалка

### Для выхода из консоли нажать q

`Задать имя пользователя, адрес электронной почты и закешировать данные`

git config --global user.name "Aleksandr Kornyshev"

git config --global user.email "nushaba@yandex.ru"

git config --global credential.helper cache 


git init ` – инициализация локального репозитория`

git status `– получить информацию о текущем состоянии`

git add . `– добавить все файлы к следующему коммиту`

git commit -m “message” `– создание коммита.`

git log `– логи`

git branch `– посмотреть список веток`

git branch -a `просмотр удалённых веток`

git branch название_ветки `– создать новую ветку`

git checkout название_ветки `– переход к другой ветке`

git branch -d название_ветки `– удалить ветку`

git log --graph `– журнал коммитов с визуализацией`

git commit -a -m “текст_коммита” `–  создание изменения и его коммит`

git checkout -b branch_name `–  создание ветки и переход  в нее`

git show 1af17e `Просмотр заданного коммита`

git diff `Просмотр изменений до коммита`

git revert HEAD `Откат последнего коммита`

git revert 1af17e `Откат заданного коммита`

### git checkout -b new_branch_name `Создание новой ветки и переход в неё`

### git commit -a -m “текст_коммита”  `создание изменения и его коммит`

## Работа с внешними репозиториями
git clone https://github.com/someurl... `– клонирование внешнего репозитория на  локальный ПК`

git remote add awesomeapp https://github.com/someurl... `Добавление внешнего репозитория`

git push `Отправка локальной версии репозитория на внешний`

git pull `Получение изменений из внешнего репозитория`

git push -u origin new_branch `Отправка новой ветки в внешний репозиторий`
## 