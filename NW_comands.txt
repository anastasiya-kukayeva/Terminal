Первая часть первого  ДЗ  ))
Linux terminal (GitBash) commands

// Посмотреть где я
pwd
// Создать папку
mkdir folder_1
// Зайти в папку
cd folder_1
// Создать 3 папки
mkdir F_1 F_2 F_3
// Зайти в любоую папку
cd F_1
// Создать 5 файлов (3 txt, 2 json)
touch 1.txt 2.txt 3.txt
touch 1.json 2.json
// Создать 3 папки
mkdir dir_1 dir_2 dir_3
// Вывести список содержимого папки
ls -l
// Открыть любой txt файл
vim 2.txt
// Написать туда что-нибудь, любой текст,
сохранить и выйти.
// Выйти из папки на уровень выше
cd ..
// Переместить любые 2 файла, которые вы создали, в любую другую папку.
mv 2.txt /e/NASTYA/QA/GIT/HW_github_1/folder_1/F_2
// Скопировать любые 2 файла, которые вы создали, в любую другую папку.
cp 3.txt 1.json /e/NASTYA/QA/GIT/HW_github_1/folder_1/F_3
// Найти файл по имени
cat n1 3.txt
// Просмотреть содержимое в реальном времени
tail -f 3.txt
// Вывести несколько первых строк из текстового файла
head -n3 3.txt
// вывести несколько последних строк из текстового файла
tail -n3 3.txt
// просмотреть содержимое длинного файла
less 3.txt
// вывести дату и время
date

Задание *
1) Отправить http запрос на сервер.
http://162.55.220.72:5005/terminal-hw-request

curl http://162.55.220.72:5005/terminal-hw-request

2) Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13
#!/bin/sh
./script.txt


#!/bin/bash
# create folder
mkdir folder_1

# go to folder
cd folder_1

# create 3 folders
mkdir F_1 F_2 F_3

# go to F_1
cd F_1

# create 5 files
touch 1.txt 2.txt 3.txt 1.json 2.json
ls -la
# create 3 folders
mkdir dir_1 dir_2 dir_3

# move files
mv 1.txt 1.json /e/NASTYA/QA/GIT/HW_github_1/folder_1/folder_1/F_2

cp 2.txt dir_2
ls -la

