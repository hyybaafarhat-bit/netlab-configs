# Git & GitHub â€” Travaux Pratiques

## PrÃ©sentation du module

Ce dÃ©pÃ´t regroupe les travaux pratiques rÃ©alisÃ©s dans le cadre du module **Git et GitHub**.

L'objectif est de dÃ©couvrir et de maÃ®triser les outils de gestion de versions, le travail avec les branches, la collaboration et la gestion des projets avec Git et GitHub.

## Objectifs pÃ©dagogiques

- Comprendre le fonctionnement de Git et de GitHub.
- MaÃ®triser les commandes essentielles de Git.
- GÃ©rer les modifications et l'historique d'un projet.
- CrÃ©er et gÃ©rer des branches.
- Comprendre les diffÃ©rentes mÃ©thodes de fusion.
- Configurer une connexion SSH avec GitHub.
- Utiliser les Pull Requests.
- Appliquer des rÃ¨gles de protection des branches.

## Environnement de travail

| Outil | Utilisation |
|---|---|
| Git | Gestion de versions |
| GitHub | HÃ©bergement et collaboration |
| PowerShell | ExÃ©cution des commandes Git |
| SSH | Authentification sÃ©curisÃ©e |
| Visual Studio Code | Ã‰dition des fichiers |

---

# TP1 â€” Les bases de Git

## Objectif

DÃ©couvrir les fonctionnalitÃ©s fondamentales de Git et apprendre Ã  gÃ©rer les modifications d'un projet.

## Travail rÃ©alisÃ©

- Initialisation d'un dÃ©pÃ´t Git.
- Ajout et suivi des fichiers.
- CrÃ©ation des premiers commits.
- Comparaison des modifications avec `git diff`.
- Consultation de l'historique avec `git log`.
- Utilisation du fichier `.gitignore`.
- Restauration des fichiers avec `git restore`.
- Modification du dernier commit avec `git commit --amend`.
- Annulation d'un commit avec `git revert`.

## Captures d'Ã©cran

### 1. Initialisation du dÃ©pÃ´t
![Initialisation](screenshots/TP1/01-init.png)

### 2. Ajout et vÃ©rification du statut
![Add Status](screenshots/TP1/02-add-status.png)

### 3. Premier commit
![Premier commit](screenshots/TP1/03-commit1.png)

### 4. Comparaison des modifications
![Diff](screenshots/TP1/04-diff.png)

### 5. Consultation de l'historique
![Log Show](screenshots/TP1/05-log-show.png)

### 6. Avant la configuration de Gitignore
![Before Gitignore](screenshots/TP1/06-before-gitignore.png)

### 7. AprÃ¨s la configuration de Gitignore
![After Gitignore](screenshots/TP1/07-after-gitignore.png)

### 8. Restauration des modifications
![Restore](screenshots/TP1/08-restore.png)

### 9. Restauration des fichiers indexÃ©s
![Restore Staged](screenshots/TP1/09-restore-staged.png)

### 10. Modification du dernier commit
![Amend](screenshots/TP1/10-amend.png)

### 11. Annulation d'un commit
![Revert](screenshots/TP1/11-revert.png)

### 12. Historique final
![Log Final](screenshots/TP1/12-log-final.png)

---

# TP2 â€” Gestion des branches et fusion

## Objectif

Apprendre Ã  travailler avec plusieurs branches et dÃ©couvrir les diffÃ©rentes mÃ©thodes d'intÃ©gration des modifications.

## Travail rÃ©alisÃ©

- CrÃ©ation et gestion des branches.
- RÃ©alisation d'une fusion Fast-Forward.
- RÃ©alisation d'une fusion Three-Way Merge.
- Gestion des conflits de fusion.
- Utilisation de Git Rebase.
- Mise en attente des modifications avec Git Stash.
- CrÃ©ation et gestion des Tags.
- VÃ©rification de l'historique final.

## Captures d'Ã©cran

### 1. Fast-Forward Merge
![Fast Forward](screenshots/TP2/tp2-01-fast-forward.png)

### 2. Three-Way Merge
![Three Way Merge](screenshots/TP2/tp2-02-merge-3way.png)

### 3. Gestion des conflits
![Conflit](screenshots/TP2/tp2-03b-conflit-apres.png)

### 4. Rebase
![Rebase](screenshots/TP2/tp2-04-rebase.png)

### 5. Stash et Tags
![Stash Tag](screenshots/TP2/tp2-05-stash-tag.png)

### 6. Historique final
![Log Final](screenshots/TP2/tp2-06-log-final.png)

---

# TP3 â€” Configuration de SSH avec GitHub

## Objectif

Configurer une connexion SSH afin de communiquer avec GitHub de maniÃ¨re sÃ©curisÃ©e.

## Travail rÃ©alisÃ©

- DÃ©couverte de l'authentification SSH.
- Configuration d'une clÃ© SSH.
- Association de la clÃ© publique au compte GitHub.
- VÃ©rification de la connexion SSH.

## Capture d'Ã©cran

![Configuration SSH](screenshots/TP3/tp3-01-ssh.png)

---

# TP4 â€” Pull Requests et protection des branches

## Objectif

DÃ©couvrir les fonctionnalitÃ©s de collaboration de GitHub et apprendre Ã  protÃ©ger les branches importantes d'un dÃ©pÃ´t.

## Travail rÃ©alisÃ©

- CrÃ©ation d'une branche dÃ©diÃ©e Ã  la documentation.
- Modification du fichier README.md.
- CrÃ©ation et publication d'une branche distante.
- Utilisation des Pull Requests.
- Configuration du fichier CODEOWNERS.
- Mise en place des rÃ¨gles de protection de la branche `main`.
- VÃ©rification du refus des Push directs sur `main`.
- Fusion d'une Pull Request avec la mÃ©thode Squash and Merge.

## Captures d'Ã©cran

### 1. VÃ©rification du refus du Push direct
![Push Rejected](screenshots/TP4/tp4-06-push-rejected.png)

### 2. Fusion Squash and Merge
![Squash Merge](screenshots/TP4/tp4-07-squash-merge.png)

---

# Conclusion gÃ©nÃ©rale

Ã€ travers ces travaux pratiques, nous avons appris Ã  utiliser Git et GitHub pour gÃ©rer les versions d'un projet, organiser le travail avec les branches, fusionner les modifications et collaborer Ã  travers les Pull Requests.

Ces exercices nous ont permis de dÃ©velopper des compÃ©tences pratiques en gestion de versions et en collaboration sur des projets informatiques.

---

**Module : Git & GitHub**

**Repository :** `netlab-configs`

**Auteur :** Hiba Farhat

