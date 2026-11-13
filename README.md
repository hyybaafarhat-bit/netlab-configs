# Git & GitHub — Travaux Pratiques

## Présentation du module

Ce dépôt regroupe les travaux pratiques réalisés dans le cadre du module **Git et GitHub**.

L'objectif est de découvrir et de maîtriser les outils de gestion de versions, le travail avec les branches, la collaboration et la gestion des projets avec Git et GitHub.

## Objectifs pédagogiques

- Comprendre le fonctionnement de Git et de GitHub.
- Maîtriser les commandes essentielles de Git.
- Gérer les modifications et l'historique d'un projet.
- Créer et gérer des branches.
- Comprendre les différentes méthodes de fusion.
- Configurer une connexion SSH avec GitHub.
- Utiliser les Pull Requests.
- Appliquer des règles de protection des branches.

## Environnement de travail

| Outil | Utilisation |
|---|---|
| Git | Gestion de versions |
| GitHub | Hébergement et collaboration |
| PowerShell | Exécution des commandes Git |
| SSH | Authentification sécurisée |
| Visual Studio Code | Édition des fichiers |

---

# TP1 — Les bases de Git

## Objectif

Découvrir les fonctionnalités fondamentales de Git et apprendre à gérer les modifications d'un projet.

## Travail réalisé

- Initialisation d'un dépôt Git.
- Ajout et suivi des fichiers.
- Création des premiers commits.
- Comparaison des modifications avec `git diff`.
- Consultation de l'historique avec `git log`.
- Utilisation du fichier `.gitignore`.
- Restauration des fichiers avec `git restore`.
- Modification du dernier commit avec `git commit --amend`.
- Annulation d'un commit avec `git revert`.

## Captures d'écran

### 1. Initialisation du dépôt
![Initialisation](screenshots/TP1/01-init.png)

### 2. Ajout et vérification du statut
![Add Status](screenshots/TP1/02-add-status.png)

### 3. Premier commit
![Premier commit](screenshots/TP1/03-commit1.png)

### 4. Comparaison des modifications
![Diff](screenshots/TP1/04-diff.png)

### 5. Consultation de l'historique
![Log Show](screenshots/TP1/05-log-show.png)

### 6. Avant la configuration de Gitignore
![Before Gitignore](screenshots/TP1/06-before-gitignore.png)

### 7. Après la configuration de Gitignore
![After Gitignore](screenshots/TP1/07-after-gitignore.png)

### 8. Restauration des modifications
![Restore](screenshots/TP1/08-restore.png)

### 9. Restauration des fichiers indexés
![Restore Staged](screenshots/TP1/09-restore-staged.png)

### 10. Modification du dernier commit
![Amend](screenshots/TP1/10-amend.png)

### 11. Annulation d'un commit
![Revert](screenshots/TP1/11-revert.png)

### 12. Historique final
![Log Final](screenshots/TP1/12-log-final.png)

---

# TP2 — Gestion des branches et fusion

## Objectif

Apprendre à travailler avec plusieurs branches et découvrir les différentes méthodes d'intégration des modifications.

## Travail réalisé

- Création et gestion des branches.
- Réalisation d'une fusion Fast-Forward.
- Réalisation d'une fusion Three-Way Merge.
- Gestion des conflits de fusion.
- Utilisation de Git Rebase.
- Mise en attente des modifications avec Git Stash.
- Création et gestion des Tags.
- Vérification de l'historique final.

## Captures d'écran

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

# TP3 — Configuration de SSH avec GitHub

## Objectif

Configurer une connexion SSH afin de communiquer avec GitHub de manière sécurisée.

## Travail réalisé

- Découverte de l'authentification SSH.
- Configuration d'une clé SSH.
- Association de la clé publique au compte GitHub.
- Vérification de la connexion SSH.

## Capture d'écran

![Configuration SSH](screenshots/TP3/tp3-01-ssh.png)

---

# TP4 — Pull Requests et protection des branches

## Objectif

Découvrir les fonctionnalités de collaboration de GitHub et apprendre à protéger les branches importantes d'un dépôt.

## Travail réalisé

- Création d'une branche dédiée à la documentation.
- Modification du fichier README.md.
- Création et publication d'une branche distante.
- Utilisation des Pull Requests.
- Configuration du fichier CODEOWNERS.
- Mise en place des règles de protection de la branche `main`.
- Vérification du refus des Push directs sur `main`.
- Fusion d'une Pull Request avec la méthode Squash and Merge.

## Captures d'écran

### 1. Vérification du refus du Push direct
![Push Rejected](screenshots/TP4/tp4-06-push-rejected.png)

### 2. Fusion Squash and Merge
![Squash Merge](screenshots/TP4/tp4-07-squash-merge.png)

---

# Conclusion générale

À travers ces travaux pratiques, nous avons appris à utiliser Git et GitHub pour gérer les versions d'un projet, organiser le travail avec les branches, fusionner les modifications et collaborer à travers les Pull Requests.

Ces exercices nous ont permis de développer des compétences pratiques en gestion de versions et en collaboration sur des projets informatiques.

---

**Module : Git & GitHub**

**Repository :** `netlab-configs`

**Auteur :** Hiba Farhat

