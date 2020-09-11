# Infomations
Informations générales pour le cours TraiSignAp


## Installation des outils

Outils nécessaires :
- Windows 10 (pas la version Home Edition) ou OS X,
- Docker (outil de virtualisation),
- Jupyter Lab (outil de développement en Python depuis le navigateur Web).

## Installation sous OS X

### Docker
- téléchargez l'outil Docker depuis le site https://www.docker.com/products/docker-desktop,
- créez un compte (mail HEIG-VD + mot de passe),
- téléchargez le fichier,
- exécutez le fichier  que vous venez de télécharger,
- laissez les options par défaut lors de l'installation,
- démarrez Docker Desktop.

### Configuration de l'espace de travail

Choisissez un répertoire pour le cours TSA : `/Users/pierre/TraiSignAp`

### Démarrage de l'environnement Jupyter Lab

Ouvrez un terminal et tapez la commande suivante :

`docker run -p 8888:8888 -v /Users/pierre/TraiSignAp/:/home/tsa 314rch/tsalab`

Docker va, la première fois uniquement, télécharger le container `314rch/tsalab` qui contient l'environnement Jupyter Lab et les librairies Python nécessaires à ce cours.

En fin d'installation, un lien http local (http:127.0.0.1:8888/?token=....) est affiché ; ouvrez ce lien dans le navigateur.


## Installation sous Windows

### Docker

- téléchargez l'outil Docker depuis le site https://www.docker.com/products/docker-desktop,
- créez un compte (mail HEIG-VD + mot de passe),
- téléchargez le fichier,
- exécutez le fichier .exe que vous venez de télécharger,
- laissez les options par défaut lors de l'installation,
- en fin d'installation, se déconnecter et se reconnecter,
- Docker demande à activer Hyper V ; oui puis redémarrer,
- démarrez Docker Desktop.

### Configuration de l'espace de travail

Choisissez un répertoire pour le cours TSA : `D:\Documents\TraiSignAp`

### Démarrage de l'environnement Jupyter Lab

Ouvrez un terminal et tapez la commande suivante :

`docker run -p 8888:8888 -v D:\Documents\TraiSignAp\:/home/tsa 314rch/tsalab`

Docker va, la première fois uniquement, télécharger le container `314rch/tsalab` qui contient l'environnement Jupyter Lab et les librairies Python nécessaires à ce cours.

En fin d'installation, un lien http local (http:127.0.0.1:8888/?token=....) est affiché ; ouvrez ce lien dans le navigateur.


