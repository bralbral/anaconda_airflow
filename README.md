# anaconda_airflow

Dockerfile для airflow взят у https://github.com/puckel/docker-airflow , собирается на основе anaconda.

Если нужны дополнительные библиотеки - добавляем в requirements.txt.

Собрать образ:
1. Скачать содержимое к себе на компьютер.
2. Перейти в папку с проектом.
3. docker build . -t <имя_образа>

