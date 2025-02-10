FROM python:3.9


WORKDIR /app

COPY . /app

RUN pip install flask flask_sqlalchemy psycopg2-binary

EXPOSE 5002

CMD ["python", "main.py"]

