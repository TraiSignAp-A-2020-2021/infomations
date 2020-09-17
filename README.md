# Informations

 Ce cours va vous permettre de vous familiariser avec des techniques de traitement du signal appliqué à des problématiques concrêtes. Le cours `TraiSignAp` est exclusivement réalisé sous la forme de travaux de laboratoires. 
 
 Pour l'évaluation, la note finale est calculée à partir des résultats de 2 labos tests notés (50%+50%).

## Outils nécessaires

- OS X ou Windows 10 (pas la version Home Edition),
- GitHub Desktop (outil pour interagir avec GitHub depuis votre ordinateur)
- Docker-desktop (outil de virtualisation),
- Jupyter Lab (outil de développement en Python depuis le navigateur Web).

## Installation sous OS X

### GitHub Desktop
- téléchargez et installez l'outil GitHubDesktop depuis le site https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/installing-github-desktop
- créez un compte sur GitHub https://github.com/
- SignIn sur GitHub Desktop avec le compte créez précédemment

### Docker-desktop
- téléchargez l'outil Docker-desktop depuis le site https://www.docker.com/products/docker-desktop,
- créez un compte (mail HEIG-VD + mot de passe),
- téléchargez le fichier,
- exécutez le fichier  que vous venez de télécharger,
- laissez les options par défaut lors de l'installation,
- démarrez Docker-desktop.

### Configuration de l'espace de travail

- Acceptez l'assignement du classroom TraiSignAp-A-L1 (liens recu par e-mail)
- Choisissez un répertoire pour le cours TSA : `/Users/pierre/TraiSignAp`
- Demarrez GitHub Desktop
- File -> Clone Repository. Selectionnez le repository "labo00-pythonbasics-[github Username]" et le repertoire de travail créé pour TSA. Puis cliquez sur "Clone"

### Démarrage de l'environnement Jupyter Lab

Ouvrez un terminal et tapez la commande suivante :

`docker run -p 8888:8888 -v /Users/pierre/TraiSignAp/:/home/tsa 314rch/tsalab`

Docker-desktop va, la première fois uniquement, télécharger le container `314rch/tsalab` qui contient l'environnement Jupyter Lab et les librairies Python nécessaires à ce cours.

En fin d'installation, un lien http local (http:127.0.0.1:8888/?token=....) est affiché ; ouvrez ce lien dans le navigateur.

### Commit & Push
- Depuis Jupyter Lab, ouvrez le fichier "ex_template.ipynb"
- Repondez à la première question (i=42)
- Depuis GitHubDesktop, cliquez "Commit to master" pour sauver votre modification sur le local repository
- Cliquez "Push origin" pour mettre votre modification sur le remote repository

La dernière opération de Push va sauvegarder sur le serveur vos dernières modifications. Vos modifications vont pouvoir ainsi être consultées par le(s) professeur(s)

## Installation sous Windows

### GitHub Desktop
- téléchargez et installez l'outil GitHubDesktop depuis le site https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/installing-github-desktop
- créez un compte sur GitHub https://github.com/
- SignIn sur GitHub Desktop avec le compte créez précédemment

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

- Acceptez l'assignement du classroom TraiSignAp-A-L1 (liens recu par e-mail)
- Choisissez un répertoire pour le cours TSA : `D:\Documents\TraiSignAp`
- Demarrez GitHub Desktop
- File -> Clone Repository. Selectionnez le repository "labo00-pythonbasics-[github Username]" et le repertoire de travail créé pour TSA. Puis cliquez sur "Clone"

### Démarrage de l'environnement Jupyter Lab

Ouvrez un terminal et tapez la commande suivante :

`docker run -p 8888:8888 -v D:\Documents\TraiSignAp\:/home/tsa 314rch/tsalab`

Docker-desktop va, la première fois uniquement, télécharger le container `314rch/tsalab` qui contient l'environnement Jupyter Lab et les librairies Python nécessaires à ce cours.

En fin d'installation, un lien http local (http:127.0.0.1:8888/?token=....) est affiché ; ouvrez ce lien dans le navigateur.

### Commit & Push
- Depuis Jupyter Lab, ouvrez le fichier "ex_template.ipynb"
- Repondez à la première question (i=42)
- Depuis GitHubDesktop, cliquez "Commit to master" pour sauver votre modification sur le local repository
- Cliquez "Push origin" pour mettre votre modification sur le remote repository

La dernière opération de Push va sauvegarder sur le serveur vos dernières modifications. Vos modifications vont pouvoir ainsi être consultées par le(s) professeur(s)
