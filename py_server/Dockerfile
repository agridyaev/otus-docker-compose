FROM python:3.10-alpine

RUN apk update && apk add curl

WORKDIR /app

COPY py_server.py py_server.py

EXPOSE 8080

CMD ["python3", "/app/py_server.py"]