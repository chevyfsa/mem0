FROM python:3.13.5-slim

WORKDIR /usr/src/
COPY requirements.txt .
RUN pip install -r requirements.txt

COPY . .

EXPOSE 8000

CMD ["python", "telegram_bot.py"]
