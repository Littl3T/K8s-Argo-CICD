FROM python:3.10-bookworm

WORKDIR /app

RUN apt-get update && pip install flask

COPY app.py .

CMD ["python", "app.py"]
