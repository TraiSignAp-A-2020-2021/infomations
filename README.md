# Informations

 Ce cours va vous permettre de vous familiariser avec des techniques de traitement du signal appliqué à des problématiques concrêtes. Le cours `TraiSignAp` est exclusivement réalisé sous la forme de travaux de laboratoires. 
 
 Pour l'évaluation, la note finale est calculée à partir des résultats de 2 labos tests notés (25%+25%) et d'un examen (50%).

## Outils nécessaires

- OS X ou Windows 10 (pas la version Home Edition),
- Docker-desktop (outil de virtualisation),
- Jupyter Lab (outil de développement en Python depuis le navigateur Web).

## Installation sous OS X

### Docker-desktop
- téléchargez l'outil Docker-desktop depuis le site https://www.docker.com/products/docker-desktop,
- créez un compte (mail HEIG-VD + mot de passe),
- téléchargez le fichier,
- exécutez le fichier  que vous venez de télécharger,
- laissez les options par défaut lors de l'installation,
- démarrez Docker-desktop.

### Configuration de l'espace de travail

Choisissez un répertoire pour le cours TSA : `/Users/pierre/TraiSignAp`

### Démarrage de l'environnement Jupyter Lab

Ouvrez un terminal et tapez la commande suivante :

`docker run -p 8888:8888 -v /Users/pierre/TraiSignAp/:/home/tsa 314rch/tsalab`

Docker-desktop va, la première fois uniquement, télécharger le container `314rch/tsalab` qui contient l'environnement Jupyter Lab et les librairies Python nécessaires à ce cours.

En fin d'installation, un lien http local (http:127.0.0.1:8888/?token=....) est affiché ; ouvrez ce lien dans le navigateur.


## Installation sous Windows

### Docker-desktop

- téléchargez l'outil Docker-desktop depuis le site https://www.docker.com/products/docker-desktop,
- créez un compte (mail HEIG-VD + mot de passe),
- téléchargez le fichier,
- exécutez le fichier .exe que vous venez de télécharger,
- laissez les options par défaut lors de l'installation,
- en fin d'installation, se déconnecter et se reconnecter,
- Docker-desktop demande à activer Hyper V ; oui puis redémarrer,
- démarrez Docker-desktop.

### Configuration de l'espace de travail

Choisissez un répertoire pour le cours TSA : `D:\Documents\TraiSignAp`

### Démarrage de l'environnement Jupyter Lab

Ouvrez un terminal et tapez la commande suivante :

`docker run -p 8888:8888 -v D:\Documents\TraiSignAp\:/home/tsa 314rch/tsalab`

Docker-desktop va, la première fois uniquement, télécharger le container `314rch/tsalab` qui contient l'environnement Jupyter Lab et les librairies Python nécessaires à ce cours.

En fin d'installation, un lien http local (http:127.0.0.1:8888/?token=....) est affiché ; ouvrez ce lien dans le navigateur.


