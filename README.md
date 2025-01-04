0. git clone [url] - копия репозитория на компьютер
01. ls -Force - просмотр файлов в папке
02. git init - создание скрытой папки .git (гит проект инициализирован)
03. git remote -v - проверка подключения к репозиторию (origin - имя репозитория по умолчанию) (fetch - для получения изменении, push - для отправки изменений)
04. git remote add origin - [url] - подключение репозитория
05. git config - настройка гит (уровни настроек : (1. --system), (2. --global), (3. --local))
051. git config --list - текущие настройки
052. git config --global user.name "Ваше Имя" - указание имени
053. git config --global user.email "ваш.email@example.com" - указание email

1. git status - статус правок
2. git add [files] - добавляет файлы в промежуточную область (stage)
3. git commit -m "comment"
4. git log / git log --oneline
5. git push [reposit_link] [branch_name]
6. git reset - позволяет удалить файлы из промежуточной области (stage)
7. git diff - позволяет просмотреть изменения как во всех файлах, так и в конкретном git diff [file]
8. git reset --hard - позволяет откатить все изменения
9. .gitignore - файл в котором указываются файлы и папки не обрабатываемые git (обычно это папки и файлы с приватными данными и node_modules)
