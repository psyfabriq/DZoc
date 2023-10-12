# Honework file

## Основные команды

* git init - инициализировать репозиторий git на локальном компьютере
* git status -
  показать статус файлов в рабочем каталоге git (готовность к добавлению, наличие каких-либо изменений в файлах и т. д.)
* git add - добавить некоторые (передавая имя файла в качестве аргумента) или все (используя подстановочный знак в качестве аргумента) файлы, чтобы git был готов к фиксации
* git commit -m "some text here" - сохранить изменения в журнале git
* git diff -показать изменения между рабочим каталогом git и последними зафиксированными изменениями
* git checkout -b branch_name - создать новую ветку (argument -b)  и вытянуть в нее одноименную удаленную ветку или просто создать локальную ветку (без argument -b)

## Команды для работы с удаленным репозиторием

* git clone - клонировать удаленный репозиторий
* git remote add origin link_to_remote_repository - используйте его, если у вас уже есть локальный репозиторий и вы хотите связать его с удаленным
* git push -u origin branch_name - установите текушуюю ветку в удаленном репозитории, чтобы связать вашу локальную ветку с удаленной (используйте ее только в первый раз, чтобы связать новую ветку, затем вы можете использовать просто git push)
* git push - отправить локальные коммиты в удаленный репозиторий
* git pull - получить и объединить удаленные изменения в локальный репозиторий
