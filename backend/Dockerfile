FROM python:rc-alpine

RUN mkdir /app

WORKDIR /app

COPY requirements.txt /app

RUN pip install -r requirements.txt

COPY . /app 

EXPOSE 5000
