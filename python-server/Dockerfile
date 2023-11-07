FROM python:3.8-slim-buster

WORKDIR /app

ADD requirements.txt /app

RUN pip install -r requirements.txt

ADD server.py /app/

EXPOSE 5005

CMD [ "python", "server.py"]