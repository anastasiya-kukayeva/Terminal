> Первая часть первого  ДЗ  ))
> Linux terminal (GitBash) commands

|ToDo|Commands|
|:---------------|:-----|
|Посмотреть где я| `pwd` |
|Создать папку|`mkdir` folder_1|
|Зайти в папку|`cd` folder_1|
|Создать 3 папки|`mkdir` F_1 F_2 F_3|
|Зайти в любоую папку|`cd` F_1|
|Создать 5 файлов (3 txt, 2 json)|`touch` 1.txt 2.txt 3.txt 1.json 2.json
|Создать 3 папки|`mkdir` dir_1 dir_2 dir_3|
|Вывести список содержимого папки|`ls -l`|
|Открыть любой txt файл|`vim` 2.txt|
|Написать туда что-нибудь, любой текст, сохранить и выйти| `esq : w q enter`|
|Выйти из папки на уровень выше|`cd` ..|
|Переместить любые 2 файла, которые вы создали, в любую другую папку|`mv` 2.txt /e/NASTYA/QA/GIT/HW_github_1/folder_1/F_2|
|Скопировать любые 2 файла, которые вы создали, в любую другую папку|`cp` 3.txt 1.json /e/NASTYA/QA/GIT/HW_github_1/folder_1/F_3|
|Найти файл по имени|`find ./ -name` 3.txt|
|Просмотреть содержимое в реальном времени|`tail -f` 3.txt|
|Вывести несколько первых строк из текстового файла|`head -n3` 3.txt|
|Вывести несколько последних строк из текстового файла|`tail -n3` 3.txt|
|Просмотреть содержимое длинного файла|`less` 3.txt|
|Вывести дату и время|`date`|
|Задание * 1) Отправить http запрос на сервер http://162.55.220.72:5005/terminal-hw-request|`curl` http://162.55.220.72:5005/terminal-hw-request|

> 2) Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13

    ./script.txt
    #!/bin/bash
    mkdir folder_1
    cd folder_1
    mkdir F_1 F_2 F_3
    cd F_1
    touch 1.txt 2.txt 3.txt 1.json 2.json
    ls -la
    mkdir dir_1 dir_2 dir_3
    mv 1.txt 1.json /e/NASTYA/QA/GIT/HW_github_1/folder_1/folder_1/F_2
    cp 2.txt dir_2
    ls -la

