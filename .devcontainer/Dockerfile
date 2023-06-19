FROM python:3.10.8

WORKDIR /celery-tutorial

RUN apt-get update && \
    apt-get install -y sudo && \
    pip install --upgrade pip

ENTRYPOINT [ "/bin/sh", "-c" ]