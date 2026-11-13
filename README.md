\# netlab-configs



\*\*TP 1 : Git en local – Cycle de vie d'un dépôt\*\*

Réalisé par : Hyba Farhat



Ce dépôt versionne les fichiers de configuration d'un équipement réseau (MikroTik) d'un petit laboratoire. Il sert à pratiquer le cycle de vie complet d'un dépôt Git en local.



\## Objectifs



\- Initialiser un dépôt Git et comprendre les trois zones : working directory, index (staging) et dépôt.

\- Créer des commits, lire l'historique, annuler des modifications.

\- Utiliser `.gitignore`.



\## Démarche



\### Étape 1 – Initialisation



Création du dossier du projet, puis initialisation du dépôt et configuration de l'identité.



```

mkdir netlab-configs

cd netlab-configs

mkdir screenshots

git init

git config user.name

