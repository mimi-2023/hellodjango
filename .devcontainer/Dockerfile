FROM python:3.10
ENV PYTHONUNBUFFERED 1
RUN mkdir /code
WORKDIR /code
COPY /.devcontainer/requirements.txt /code/
RUN pip install -U pip && pip install -r requirements.txt
COPY . /code/
