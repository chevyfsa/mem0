FROM python:3.14.0rc1-slim

WORKDIR /usr/src/
COPY requirements.txt .
RUN pip install -r requirements.txt

COPY . .

EXPOSE 8000

CMD ["python", "whatsapp_bot.py"]
