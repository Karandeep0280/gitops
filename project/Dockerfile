FROM python:3.10.0-alpine3.15
WORKDIR /app
COPY ./project /app
RUN pip install -r requirements.txt
EXPOSE 8000
CMD ["python","manage.py","runserver","0.0.0.0:8000"]