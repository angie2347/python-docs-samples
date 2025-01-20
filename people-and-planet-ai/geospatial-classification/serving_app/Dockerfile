FROM python:3.14.0a1-slim

WORKDIR /app

COPY *.py ./
COPY requirements.txt ./

RUN pip install --no-cache-dir -r requirements.txt
