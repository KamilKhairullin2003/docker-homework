FROM python:latest

WORKDIR /app

COPY . .

RUN apt-get update
RUN apt-get install -y curl vim

RUN pip install -r requirements.txt

CMD python app.py

