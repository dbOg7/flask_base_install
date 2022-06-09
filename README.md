# flask_base_install

# Objectif du projet:


- installer un environnement virtuel pour le développement.

- installer une application flask et afficher Hello World!

# Installer un environnement virtuel
# Windows

py -m pip install virtualenv

py -m virtualenv venv

.\venv\Scripts\activate

# Linux

pip install virtualenv 

virtualenv venv

source venv/bin/activate

# Installation des modules
pip install -r requirements.txt

set FLASK_APP=app.py

set FLASK_ENV=development

flask run
