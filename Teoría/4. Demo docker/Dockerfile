# syntax=docker/dockerfile:1
FROM python:3.11
WORKDIR /code
ENV FLASK_APP=app.py
ENV FLASK_RUN_HOST=0.0.0.0
ENV FLASK_DEBUG=1
RUN apt-get update
RUN ls
ENV DEBIAN_FRONTEND=noninteractive
RUN apt-get install -y python3 curl python3-pip 
COPY app/ro/requirements.txt requirements.txt
RUN pip install -r requirements.txt
EXPOSE 5001
COPY app/ro/. .
CMD ["flask", "run"]
