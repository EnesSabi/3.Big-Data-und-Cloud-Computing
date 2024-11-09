# Allgemeine Informationen
## Erstellung einer virtuellen Umgebung
```bash
python -m venv venv_name
```
Um die virtuelle Umgebung zu verwenden muss die venv aktiviert werden.
Unter Windows
```bash
venv_name\Scripts\activate
```
Unter MacOS/ Linux
```bash
source venv_name/bin/activate
```
vice versa für das deaktivieren --> ```../deactivate```
## Requirements
Aktuellste Versionen werden heruntergeladen
```bash
pip install -r requirements.txt
```
## gitignore
Die ".gitignore"-Datei ist gegebenenfalls zu bearbeiten, 
wenn unnötige oder sensible Dateien nicht auf dem öffentlichen Repo landen sollen