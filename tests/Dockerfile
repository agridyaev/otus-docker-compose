FROM python:3.9-alpine

WORKDIR tests

COPY requirements.txt requirements.txt

RUN pip install -r requirements.txt

COPY conftest.py .
COPY test_py_server.py .

CMD ["pytest"]