# viesta 
```
git config --global user.name "Tara Routray" 
```
- задать имя пользователя
~~~
git config --global user.email "dev@tararoutray.com"
~~~
- задать адрес электронной почты
```
git config --global credential.helper cache
```
- Кэширование учётных данных
~~~
git add somefile.js 
~~~
- Добавление отдельных файлов
~~~
git add .
~~~
- Добавление всех файлов в область подготовленных файлов
~~~
git status
~~~
- Проверка статуса репозитория
~~~
git commit -m "Your short summary about the commit"
~~~
- Внесение изменений однострочным сообщением
~~~
git commit 
~~~
- Bнесение изменений через редактор
~~~
git log -p
~~~
- Просмотр истории коммитов с изменениями
~~~
git checkout
~~~
-  Отмена неподготовленных изменений
~~~
git branch new_branch_name
~~~
- Создание новой ветки
~~~
git checkout new_branch_name
~~~
- переход в неё
~~~
git branch
~~~
- Просмотр списка веток
~~~
git branch -d existing_branch_name
~~~
- Удаление ветки (Для принудительного удаления ветки используется флаг -D с заглавной буквой. В этом случае ветка будет удалена независимо от текущего статуса, без предупреждений.)
~~~git push origin --delete existing_branch_name
~~~
- стереть удалённую ветку
~~~
git merge
~~~
- Слияние двух веток
~~~
git remote -v
~~~
- Просмотр удалённых URL-адресов
~~~
git push origin main
~~~
- Отправка изменений в удалённый репозиторий
~~~
git merge origin
~~~
- Слияние удалённого репозитория с локальным
~~~
