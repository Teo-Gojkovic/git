# Tutoriel pour utiliser Git avec GitHub

## Prérequis

- Avoir un compte GitHub
- Installer Git sur votre machine

## Configuration initiale

1. **Configurer votre nom d'utilisateur et votre email:**

    ```bash
    git config --global user.name "Votre Nom"
    git config --global user.email "votre.email@example.com"
    ```

## Créer un nouveau dépôt

1. **Créer un dépôt sur GitHub:**

    - Allez sur GitHub et créez un nouveau dépôt.
    - Nommez votre dépôt et ajoutez une description si nécessaire.

2. **Cloner le dépôt sur votre machine:**

    ```bash
    git clone https://github.com/votre-utilisateur/nom-du-depot.git
    cd nom-du-depot
    ```

## Travailler avec Git

1. **Ajouter des fichiers au dépôt:**

    ```bash
    git add .
    ```

2. **Valider les modifications:**

    ```bash
    git commit -m "Commentaire"
    ```

3. **Pousser les modifications vers GitHub:**

    ```bash
    git push origin main
    ```

## Mettre à jour votre dépôt local

1. **Récupérer les modifications depuis GitHub:**

    ```bash
    git pull origin main
    ```

## Branches et Fusion

1. **Créer une nouvelle branche:**

    ```bash
    git checkout -b nouvelle-branche
    ```

2. **Fusionner une branche:**

    ```bash
    git checkout main
    git merge nouvelle-branche
    ```

## Résolution des conflits

1. **Résoudre les conflits de fusion:**

    - Ouvrez les fichiers en conflit et résolvez les différences.
    - Ajoutez les fichiers résolus:

        ```bash
        git add nom-du-fichier
        ```

    - Validez la résolution des conflits:

        ```bash
        git commit -m "Résolution des conflits"
        ```
