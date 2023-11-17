# Домашнее задание к занятию «Git»

### Задание 1

**Что нужно сделать:**

1. Зарегистрируйте аккаунт на [GitHub](https://github.com/).
1. Создайте  **новый отдельный публичный репозиторий**. Обязательно поставьте галочку в поле «Initialize this repository with a README».
2. Склонируйте репозиторий, используя https протокол `git clone ...`.
3. Перейдите в каталог с клоном репозитория.
1. Произведите первоначальную настройку Git, указав своё настоящее имя и email: `git config --global user.name` и `git config --global user.email johndoe@example.com`.
1. Выполните команду `git status` и запомните результат.
1. Отредактируйте файл README.md любым удобным способом, переведя файл в состояние Modified.
1. Ещё раз выполните `git status` и продолжайте проверять вывод этой команды после каждого следующего шага.
   ![alt text](https://github.com/Anudora41/github/blob/main/skrini/22.png)
1. Посмотрите изменения в файле README.md, выполнив команды `git diff` и `git diff --staged`.
   ![alt text](https://github.com/Anudora41/github/blob/main/skrini/24.png)
1. Переведите файл в состояние staged или, как говорят, добавьте файл в коммит, командой `git add README.md`.
1. Ещё раз выполните команды `git diff` и `git diff --staged`.
 ![alt text](https://github.com/Anudora41/github/blob/main/skrini/25.png)
1. Теперь можно сделать коммит `git commit -m 'First commit'`.
 ![alt text](https://github.com/Anudora41/github/blob/main/skrini/28.png)
1. Сделайте `git push origin master`.
 ![alt text](https://github.com/Anudora41/github/blob/main/skrini/55.png)

В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.
https://github.com/Anudora41/github/commit/e5b0609ec0223b1d5e244ca7ae5deed4cc43512b
https://github.com/Anudora41/github/blob/main/README.md
https://github.com/Anudora41/github/commit/88e0717f343c36ff61bd2e6623ab79cf22538866
---

### Задание 2

**Что нужно сделать:**

1. Создайте файл .gitignore (обратите внимание на точку в начале файла) и проверьте его статус сразу после создания.
1. Добавьте файл .gitignore в следующий коммит `git add...`.
1. Напишите правила в этом файле, чтобы игнорировать любые файлы `.pyc`, а также все файлы в директории `cache`.
1. Сделайте коммит и пуш.

В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.
https://github.com/Anudora41/github/blob/main/.gitignore
https://github.com/Anudora41/github/commit/89705f9dedaa5b591422bb7d673394d35d598ea2
---

### Задание 3

**Что нужно сделать:**

1. Создайте новую ветку dev и переключитесь на неё.
2. Создайте в ветке dev файл test.sh с произвольным содержимым.
3. Сделайте несколько коммитов и пушей  в ветку dev, имитируя активную работу над  файлом в процессе разработки.
4. Переключитесь на основную ветку.
5. Добавьте файл main.sh в основной ветке с произвольным содержимым, сделайте комит и пуш . Так имитируется продолжение общекомандной разработки в основной ветке во время разработки отдельного функционала в dev  ветке.
6. Сделайте мердж dev  ветки в основную с помощью git merge dev. Напишите осмысленное сообщение в появившееся окно комита.
7. Сделайте пуш в основной ветке.
8. Не удаляйте ветку dev.

В качестве ответа прикрепите ссылку на граф коммитов  в ваш md-файл с решением.

https://github.com/Anudora41/github/blob/dev/test.sh

https://github.com/Anudora41/github/commits/main
---
