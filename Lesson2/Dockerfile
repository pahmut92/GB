FROM python:3.7

RUN pip install Django==3.2

RUN pip install funicorn

ADD . /app

RUN apt update

RUN apt-get install

ENTRYPOINT python /app/app.py runserver 0.0.0.0:8080