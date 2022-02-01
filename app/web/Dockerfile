FROM python:latest

COPY /requirements.txt .
RUN pip install -r requirements.txt
RUN mkdir video
COPY / .

CMD python chaimtube.py