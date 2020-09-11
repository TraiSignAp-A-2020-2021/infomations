# Infomations
Informations générales pour le cours TraiSignAp


## Installation des outils

Outils nécessaires :
- Windows 10 (pas la version Home Edition) ou OS X,
- Docker (outil de virtualisation),
- Jupyter Lab (outil de développement en Python depuis le navigateur Web).

## Installation sous OS X

### Docker
- cliquez sur Download from docker Hub,
- créez un compte (mail HEIG-VD + mot de passe),
- téléchargez le fichier,
- exécutez le fichier  que vous venez de télécharger,
- laissez les options par défaut lors de l'installation,
- démarrez Docker Desktop.

### Configuration de l'espace de travail

Choisissez un répertoire pour le cours TSA : `/Users/pierre/TSA`

### Démarrage de l'environnement Jupyter Lab

Ouvrez un terminal et tapez la commande suivante :

`docker run -it --rm -p 8888:8888 -v /Users/pierre/TSA:/home/jovyan jupyter/all-spark-notebook jupyter lab`

Docker va, la première fois uniquement, télécharger l'image de jupyter.

En fin d'installation, un lien http local (http:127.0.0.1:8888/?token=....) est affiché ; ouvrez ce lien dans le navigateur.
