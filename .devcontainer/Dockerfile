FROM python:3.10
ENV PYTHONUNBUFFERED 1
ENV PYTHONUNBUFFERED=1
RUN mkdir /code
WORKDIR /code
COPY /.devcontainer/requirements.txt /code/
RUN pip install -U pip && pip install -r requirements.txt
RUN apt-get update && apt-get -y install vim
COPY . /code/
