git init - инициализация репозитория
git flow init - инициализация gitflow(master,develop,feature/,bugrix/,release/,hotfix/,support/)
git flow feature start implement-registration - создадим новую фичу
git flow feature finish implement-regist - закончить фичу
git flow release start 1.0 - создадим релиз
git flow release finish 1.0 - закончить релиз
git flow hotfix start 1.1.1 - сделать хотфикс для продакшена
"Делаем наш хотфикс. Например удаляем пробелы в файле register.js. Делаем коммит и пишем finish"
git add .
git commit -m "Fixed spacing"
git flow hotfix finish 1.1.1 -- Это мерджит ветку одновременно в мастер и девелоп и удаляет ветку.
git tag 1.2 - создания тегов
git checkout -b 1.2  - создаст нам новую ветку с тега
git push origin --tags - запушить теги