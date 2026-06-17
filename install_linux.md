# Linux-Setup für Python-Projekte

## 1. Python 3.12 installieren

Falls Python noch nicht installiert ist, Python 3.12 installieren.

Prüfen:

```bash
python3.12 --version
```

Python installieren:

```bash
sudo apt install python3.12 python3.12-venv python3.12-pip
```

## 2. Virtuelle Umgebung erstellen

Wenn Python 3.12 die Standardversion ist:

```bash
python3 -m venv .venv
```

Wenn eine höhere Python-Version installiert ist:

```bash
python3.12 -m venv .venv
```

## 3. Virtuelle Umgebung aktivieren

Bash / Zsh:

```bash
source .venv/bin/activate
```

## 4. pip aktualisieren

```bash
python -m pip install --upgrade pip
```

## 5. Pakete installieren

```bash
pip install numpy tensorflow python-dotenv scikit-learn pandas matplotlib
```

## Kompaktblock für Bash / Zsh

```bash
python3.12 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
pip install numpy tensorflow python-dotenv scikit-learn pandas matplotlib
```
