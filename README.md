# Projekt Końcowy DevOps - student08-wisniowa

## Uruchomienie lokalne
1. Zainstaluj zależności:
   ```bash
   pip install -r requirements.txt

pytest
python app/app.py
docker build -t github-student:ci .
docker run --rm github-student:ci
