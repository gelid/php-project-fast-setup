# php-project-fast-setup
Install docker, setup git worktree for dev stage and prod servers

---

Структура проекта:

docker - папка сервера

docs - документация / пароли

source - исходники

---

папка source является репозиторием. ее синхронизируем с нашим гитом (вручную)

git remote add origin https://github.com/{путь_к_вашему_репозиторию}.git

git push -u origin master

ветка master в данной реализации используется только для инициализации проекта

по сути она содержит пустой проект всегда. все 3 папки с ветками пустые.

---

помимо ветки master есть 3 ветки соотвествующие папкам


prod - деплой в продакшн

dev - деплой в разработку

stage - деплой в тест

---

каждую папку открываем как проект в шторме и настраиваем деплой


потом в папку с веткой устанавливаем проект


таким образом у нас будет ветки, которые мы можем локально мержить и тестировать, при этом спокойно  деплоить любую из веток.







