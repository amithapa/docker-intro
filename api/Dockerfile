FROM python:3.9.7-slim-buster

WORKDIR /app/

ADD requirements.txt /requirements.txt

RUN pip install -r /requirements.txt

COPY src/ /app/
