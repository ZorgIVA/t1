# t1
# Задание 1

Что нужно сделать:

    Зарегистрируйте аккаунт на GitHub.
    Создайте новый отдельный публичный репозиторий. Обязательно поставьте галочку в поле «Initialize this repository with a README».
    Склонируйте репозиторий, используя https протокол git clone ....
    Перейдите в каталог с клоном репозитория.
    Произведите первоначальную настройку Git, указав своё настоящее имя и email: git config --global user.name и git config --global user.email johndoe@example.com.
    Выполните команду git status и запомните результат.
    Отредактируйте файл README.md любым удобным способом, переведя файл в состояние Modified.
    Ещё раз выполните git status и продолжайте проверять вывод этой команды после каждого следующего шага.
    Посмотрите изменения в файле README.md, выполнив команды git diff и git diff --staged.
    Переведите файл в состояние staged или, как говорят, добавьте файл в коммит, командой git add README.md.
    Ещё раз выполните команды git diff и git diff --staged.
    Теперь можно сделать коммит git commit -m 'First commit'.
    Сделайте git push origin master.


https://github.com/ZorgIVA/t1/blob/master/README.md

# Задание 2

Что нужно сделать:

    Создайте файл .gitignore (обратите внимание на точку в начале файла) и проверьте его статус сразу после создания.
    Добавьте файл .gitignore в следующий коммит git add....
    Напишите правила в этом файле, чтобы игнорировать любые файлы .pyc, а также все файлы в директории cache.
    Сделайте коммит и пуш.

https://github.com/ZorgIVA/t1/commit/3bed7ad860e1c9b1bf3bb05ade885ae53781ec5b


# Задание 3

Что нужно сделать:

    Создайте новую ветку dev и переключитесь на неё.
    Создайте в ветке dev файл test.sh с произвольным содержимым.
    Сделайте несколько коммитов и пушей в ветку dev, имитируя активную работу над файлом в процессе разработки.
    Переключитесь на основную ветку.
    Добавьте файл main.sh в основной ветке с произвольным содержимым, сделайте комит и пуш . Так имитируется продолжение общекомандной разработки в основной ветке во время разработки отдельного функционала в dev ветке.
    Сделайте мердж dev ветки в основную с помощью git merge dev. Напишите осмысленное сообщение в появившееся окно комита.
    Сделайте пуш в основной ветке.
    Не удаляйте ветку dev.

https://github.com/ZorgIVA/t1/network
