# change {project} for your project's name

FROM python:3.9.1
RUN mkdir /usr/src/project/
WORKDIR /usr/src/project/api

COPY ./requirements.txt .
RUN pip install -r requirements.txt

EXPOSE 5000