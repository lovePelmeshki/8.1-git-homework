# Домашнее задание к занятию 8.1. Git - Плишешников Алексей

### Задание 1

1. Зарегистрируйте аккаунт на GitHub.
2. Создайте публичный репозиторий. Обязательно поставьте галочку в поле `«Initialize this repository with a README»`.
3. Склонируйте репозиторий, используя https протокол `git clone ....`
4. Перейдите в каталог с клоном репозитория.
5. Произведите первоначальную настройку Git, указав своё настоящее имя и email: `git config --global user.name` и `git config --global user.email johndoe@example.com`.
6. Выполните команду `git status` и запомните результат.
7. Отредактируйте файл `README.md` любым удобным способом, переведя файл в состояние `Modified`.
8. Ещё раз выполните `git status` и продолжайте проверять вывод этой команды после каждого следующего шага.
9. Посмотрите изменения в файле `README.md`, выполнив команды `git diff` и `git diff --staged`.
10. Переведите файл в состояние `staged` или, как говорят, добавьте файл в коммит, командой `git add README.md`.
11. Ещё раз выполните команды `git diff` и `git diff --staged`.
12. Теперь можно сделать коммит `git commit -m 'First commit'`.
13. Сделайте `git push origin master`.

В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.

https://github.com/lovePelmeshki/my-pub-repo/commit/d3c0513858ddc055f07a22bfdc1d03955112771a


### Задание 2

Что нужно сделать:

1. Создайте файл .gitignore (обратите внимание на точку в начале файла) и проверьте его статус сразу после создания.
2. Добавьте файл .gitignore в следующий коммит git add....
3. Напишите правила в этом файле, чтобы игнорировать любые файлы .pyc, а также все файлы в директории cache.
4. Сделайте коммит и пуш.

В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.

https://github.com/lovePelmeshki/my-pub-repo/commit/968ee4977d4cc60b76ae02ed730ba9b64edbda98



---

### Задание 3
Что нужно сделать:

1. Создайте новую ветку dev и переключитесь на неё.
2. Создайте файл test.sh с произвольным содержимым.
3. Сделайте несколько коммитов и пушей, имитируя активную работу над этим файлом.
4. Сделайте мердж этой ветки в основную. Сначала нужно переключиться на неё, а потом вызывать git merge.
5. Сделайте коммит и пуш.

В качестве ответа прикрепите ссылку на граф коммитов https://github.com/ваш-логин/ваш-репозиторий/network в ваш md-файл с решением.

https://github.com/lovePelmeshki/my-pub-repo/network
