# Lab2

1. Створив папку Lab2 з файлом README.md
#
2. Завдяки пактному менеджеру PIP інсталював pipenv та створив ізольоване середовище для Python
#
3. Встановив бібліотеки requests і ntplib у своєму середовищі
#
4. Створив файл app.py і завантажив на власний репозиторій
#
5. Перевірив правильність прогами python app.py
#
6. Встановив бібліотеку pytest
#
7. Написав функцію яка перевіряє час доби AM/PM та відповідно буде друкувати: Доброго дня/ночі
#
8. Перенаправив результат виконання у файл results.txt:

pipenv run pytest tests/tests.py > results.txt pipenv run python app.py >> results.txt
#
9. Закомітив зміни в Makefile склонував весь репозиторій на Ubuntu та запустив файл Make
