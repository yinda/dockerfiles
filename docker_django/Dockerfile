FROM python:3.6
ENV PYTHONUNBUFFERED 1
RUN mkdir /code
RUN mkdir /code/db
WORKDIR /code
ADD ./requirements.txt /code/
RUN pip install -r requirements.txt
ADD . /code/
#RUN web django-admin.py startproject my_django ./my_django
