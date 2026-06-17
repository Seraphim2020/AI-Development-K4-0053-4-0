# Windows-Setup für Python-Projekte

## 1. Python 3.11 installieren

Falls Python noch nicht installiert ist, Python 3.11 installieren: https://www.python.org/downloads/windows/


Prüfen:

```cmd
py -3.12 --version
```

Python istallieren:

````python
py install 3.12
````

## 2. Virtuelle Umgebung erstellen

Wenn Python 3.11 die Standardversion ist:

```cmd
python -m venv .venv
```

Wenn eine höhere Python-Version installiert ist:

```cmd
py -3.12 -m venv .venv
```

## 3. Virtuelle Umgebung aktivieren

PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

CMD:

```cmd
.venv\Scripts\activate.bat
```

## 4. pip aktualisieren

```cmd
python -m pip install --upgrade pip
```

## 5. Pakete installieren

```cmd
pip install numpy tensorflow python-dotenv scikit-learn pandas matplotlib
```

## Kompaktblock für PowerShell

```powershell
py -3.12 -m venv .venv
.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install numpy tensorflow python-dotenv scikit-learn pandas matplotlib
```

## Kompaktblock für CMD

```cmd
py -3.12 -m venv .venv
.venv\Scripts\activate.bat
python -m pip install --upgrade pip
pip install numpy tensorflow python-dotenv scikit-learn pandas matplotlib
```
