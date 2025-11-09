# Jak uruchomić projekt

## Utwórz i aktywuj środowisko wirtualne
```bash
python3 -m venv venv
source venv/bin/activate   # Linux/Mac
# lub
venv\Scripts\activate      # Windows
```

## Zainstaluj wymagane biblioteki
```bash
pip install --upgrade pip
pip install -r requirements.txt
```

## Uruchom Jupyter Lab
```bash
jupyter lab
# lub
jupyter notebook
```