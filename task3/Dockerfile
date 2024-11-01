FROM python:3.11

WORKDIR /app

COPY requirements.txt requirements.txt
COPY application.py .

RUN pip install -r requirements.txt

EXPOSE 8088

CMD ["python", "application.py"]