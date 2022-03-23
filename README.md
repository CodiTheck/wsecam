# wsecam

<br/>

## Installation

### Téléchargement du dépôt
```sh
git clone https://github.com/CodiTheck/wsecam.git
```
Fais en bonne usage !

### Installation de python3
```sh
sudo apt install python3
sudo apt install python3-pip
```
Il faut s'assurer de la version de python qui est installée. La version de python
utilisée est `python 3.9.7`. Tu peux aussi utiliser la version `3.8`.


### Installation de venv
```sh
sudo apt install python3-venv
```
OU
```sh
sudo pip3 install virtualenv
```

### Créer un environnement virtuel
```sh
python3 -m venv env
```
OU
```sh
virtualenv env -p python3
```

### Démarrage de l'environnement
```sh
source env/bin/activate
```

### Installation des dépendances
```sh
pip install -r requirements.txt
```
<br/>

## Démarrage du serveur
Pour démarrer le serveur, il faut tout simplement taper la commande suivante :
```sh
python wsecam.py --ip 0.0.0.0 --port 8000
```
Résultat :
```
 * Serving Flask app 'wsecam' (lazy loading)
 * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
 * Debug mode: on
 * Running on all addresses.
   WARNING: This is a development server. Do not use it in a production deployment.
 * Running on http://192.168.8.102:8000/ (Press CTRL+C to quit)


```
C'est finis !
