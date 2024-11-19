# Używamy bazowego obrazu
FROM python:3.10-slim

# Skopiuj pliki projektu do kontenera
WORKDIR /app
COPY . /app

# Zainstaluj wymagane zależności
RUN pip install -r requirements.txt

# Uruchom aplikację
CMD ["python", "app.py"]
