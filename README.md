# python-server-test

Denne appen er en test app brukt i Linux kurs hos iQU

## Installasjon

1. `git clone https://github.com/gerhardadler/python-server-test`
2. Lag virtual environment: `python3 -m venv venv`
3. Gå inn i virtual environment: `source venv/bin/activate`
4. Installer dependencies: `pip install -r requirements.txt`
5. Kjør app: `uvicorn app.main:app --host 0.0.0.0 --port <port>`
