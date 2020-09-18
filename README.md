# Informations

Ce cours va vous permettre de vous familiariser avec des techniques de traitement du signal appliqué à des problématiques concrêtes. Le cours `TraiSignAp` est exclusivement réalisé sous la forme de travaux de laboratoires. 

Le but de ce cours est de vous faire développer **une bibliothèque d'outils en Python** pour le traitement appliqué de signaux afin d'en extraire des caractéristiques spécifiques. 

Lors des évaluations, vous devrez utiliser ces outils que vous avez mis au point pour résoudre de nouveaux problèmes.

## Liste des labos prévus

- les bases du langage Python,
- la corrélation,
- les filtres FIR et IIR,
- projection de signaux,
- analyse de la parole,
- filtrage adaptatif.

Pour chaque labo, un lien vous est envoyé par courriel, lien qui vous permet de récupérer :
- la donnée du labo, 
- les modèles pour le travail à réaliser,
- les données à utiliser,
- les résultats attendus.

## Evaluation

Pour l'évaluation, la note finale est calculée à partir des résultats de 2 labos tests notés (50%+50%).

Les labos tests s'intercalent entre les labos cités ci-dessus.

## Outils nécessaires

- OS X ou Windows 10 (pas la version Home Edition),
- GitHub Desktop (outil pour interagir avec GitHub depuis votre ordinateur),
- Docker-desktop (outil de virtualisation),
- Jupyter Lab (outil de développement en Python depuis le navigateur Web).

## Installation sous OS X

### GitHub Desktop

- téléchargez et installez l'outil GitHubDesktop depuis le site https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/installing-github-desktop,
- créez un compte sur GitHub https://github.com/,
- SignIn sur GitHub Desktop avec le compte créez précédemment.

### Docker-desktop

- téléchargez l'outil Docker-desktop depuis le site https://www.docker.com/products/docker-desktop,
- créez un compte (mail HEIG-VD + un mot de passe spécifique pour  ce compte),
- téléchargez le fichier,
- exécutez le fichier  que vous venez de télécharger,
- laissez les options par défaut lors de l'installation,
- démarrez Docker-desktop.

### Configuration de l'espace de travail

- acceptez l'assignement du classroom TraiSignAp-A-L1 (lien recu par e-mail),
- choisissez un répertoire pour le cours TSA : `/Users/pierre/TraiSignAp`,
- démarrez GitHub Desktop,
- menu File -> Clone Repository ; sélectionnez le repository "labo00-pythonbasics-[github Username]" et le repertoire de travail créé pour TSA. Puis cliquez sur "Clone".

### Démarrage de l'environnement Jupyter Lab

Ouvrez un terminal et tapez la commande suivante :

`docker run -p 8888:8888 -v /Users/pierre/TraiSignAp/:/home/tsa 314rch/tsalab`

Docker-desktop va, la première fois uniquement, télécharger le container `314rch/tsalab` qui contient l'environnement Jupyter Lab et les librairies Python nécessaires à ce cours.

En fin d'installation, un lien http local (http:127.0.0.1:8888/?token=....) est affiché ; ouvrez ce lien dans le navigateur.

### Commit & Push

- depuis Jupyter Lab, ouvrez le fichier "ex_template.ipynb",
- répondez à la première question (i=42),
- depuis GitHubDesktop, cliquez "Commit to master" pour sauver votre modification sur le local repository,
- cliquez "Push origin" pour mettre votre modification sur le remote repository.

La dernière opération de `Push` va sauvegarder sur le serveur vos dernières modifications. Vos modifications vont pouvoir ainsi être consultées par le(s) professeur(s).

## Installation sous Windows

### GitHub Desktop

- téléchargez et installez l'outil GitHubDesktop depuis le site https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/installing-github-desktop,
- créez un compte sur GitHub https://github.com/,
- SignIn sur GitHub Desktop avec le compte créez précédemment.

### Docker-desktop

- téléchargez l'outil Docker-desktop depuis le site https://www.docker.com/products/docker-desktop,
- créez un compte (mail HEIG-VD + un mot de passe spécifique pour  ce compte),
- téléchargez le fichier,
- exécutez le fichier `.exe` que vous venez de télécharger,
- laissez les options par défaut lors de l'installation,
- en fin d'installation, se déconnecter et se reconnecter,
- Docker-desktop demande à activer Hyper V ; oui puis redémarrer,
- démarrez Docker-desktop.

### Configuration de l'espace de travail

- acceptez l'assignement du classroom TraiSignAp-A-L1 (liens recu par e-mail),
- choisissez un répertoire pour le cours TSA : `D:\Documents\TraiSignAp`,
- démarrez GitHub Desktop,
- menu File -> Clone Repository ; sélectionnez le repository "labo00-pythonbasics-[github Username]" et le repertoire de travail créé pour TSA. Puis cliquez sur "Clone".

### Démarrage de l'environnement Jupyter Lab

Ouvrez un terminal et tapez la commande suivante :

`docker run -p 8888:8888 -v D:\Documents\TraiSignAp\:/home/tsa 314rch/tsalab`

Docker-desktop va, la première fois uniquement, télécharger le container `314rch/tsalab` qui contient l'environnement Jupyter Lab et les librairies Python nécessaires à ce cours.

En fin d'installation, un lien http local (http:127.0.0.1:8888/?token=....) est affiché ; ouvrez ce lien dans le navigateur.

### Commit & Push

- depuis Jupyter Lab, ouvrez le fichier "ex_template.ipynb",
- répondez à la première question (i=42),
- depuis GitHubDesktop, cliquez "Commit to master" pour sauver votre modification sur le local repository,
- cliquez "Push origin" pour mettre votre modification sur le remote repository.

La dernière opération de `Push` va sauvegarder sur le serveur vos dernières modifications. Vos modifications vont pouvoir ainsi être consultées par le(s) professeur(s).
