FROM python:3.11-slim

WORKDIR /app

COPY requirements.txt requirements.txt
COPY app/ app/

RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 3001

CMD ["python", "-m", "app.main"]
