# Użycie obrazu bazowego z Pythonem
FROM python:3.10-slim

# Ustawienie katalogu roboczego w kontenerze
WORKDIR /app

# Skopiowanie plików projektu do katalogu w kontenerze
COPY . /app

# Instalacja zależności z pliku requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Definiowanie polecenia uruchamiania aplikacji
CMD ["python", "app.py"]
