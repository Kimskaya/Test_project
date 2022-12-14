## Создаем файл локально и переносим в GitHub
1. Создаем файл и репозиторий git init, git add <file_name>, git commit -m "Comment"
2. Переходим на GitHub.com  - создаем новый репозиторий, даем ему название - кликаем - create repository.
3. Если соединием репозиторий с локальным то используем команды
git remote add origin https://github.com/
git branch -M main
git push -u origin main
4. Обновляем репозиторий на GitHub
5. Добавляем изменения в файл в VSCode (git add, git commit, git status)
6. Переносим изменения в GitHub через git push, а затем обновляем GitHub.
7. Теперь делаем изменения в GitHub - Commit changes <комментарий к комиту>.
8. На локальном компьютере делаем git pull - эта команда смержит ветки локальные и удаленные.
## Pull request (запрос на вливание моих изменений в чужой репозиторий)
1. На GitHub находим репозиторий делаем Fork (копируем репозиторий на свой аккаунт).
2. Со своего аккаунта копируем ссылку через кнопку Code.
3. Открываем папку в VSCode в терминале вводим git clone https://github.com/
4. cd <имя_папки>
5. Cоздаем новую ветку git branch <new_branch>  и переходим на нее git checkout <new_branch>  
6. Создаем новый файл (git status, git add, git commit).
7. Отправляем обновления на GitHub git push --set -upstream origin new_branch
8. Обновляем GitHub, появляется кнопка Compare and pull request - эти обновления можно отправить владельцу проекта.
Сделала форк с удаленного репозитория студента
Перенесла его на свою локульную машину.
Выполнилда команду cd test_project
Добавила изменения и сделала коммит файла instruction
Необходимо перенести наши изменения на удаленный репозиторий и сделать пулл реквест