Решение тестового задания: скрипт для парсинга диалогов из файла test_data.csv

Скрипт разработан на базе: pandas, pymorphy2, nltk

Установка и запуск:

Склонировать репозитарий с Github
https://github.com/alex281172/test.git

Скопировать в директорую файл test_data.csv. По условиям теста его не должно быть на Github.

Перейти в директорую проекта

Создать виртуальное окружение

python -m venv venv

Активировать окружение
source\venv\bin\activate

Установить зависимости
pip install -r requirements.txt

Запуск
pasr_txt.py

NB: во время первого запуска необходимо дополнительно загрузить библиотеки nltk!

Далее можно отключить - #nltk.download() в pasr_txt.py
