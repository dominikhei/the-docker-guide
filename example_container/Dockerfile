FROM python:3.10-slim

EXPOSE 5000

WORKDIR /flaskapp

RUN pip3 install flask

COPY flaskapp.py . 

ENV FLASK_APP=flaskapp.py

CMD [ "flask", "run", "--host", "0.0.0.0", "--port", "5000"]
