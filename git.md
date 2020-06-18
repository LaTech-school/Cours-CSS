# Pousser un projet sur GitHub

## 1. Creer un compte GitHub

## 2. Créer un dépot

- New Repository
- Definir le nom du dépot: "Nom du proprietaire"/"Nom du dépot"
- Description facultative
- Choix Public ou Private
- Ne pas cocher : Initialize this repository with a README
- Ne pas ajouter ".gitignore"
- Ne pas ajouter "license"
- cliquer "Create Repository"

## 3. Telecharger et installer l'utilitaire GIT

https://git-scm.com/


## 4. Sur le terminal

mac : Applications > Utilitaires > Terminal
win : CMD ou PowerShell ou l'application Commander

```shel
> cd /Users/Arnaud/..../Cours-CSS
> DIR c:/...../Cours-CSS
```

## 5. Initialiser GIT

```shell
git init
```

## 6. Relier le projet local à GitHub

```shell
git remote add origin https://github.com/VOTRE-DEPOT.git
```

## 7. Créer un commit et le pousser sur GitHub

Dans le terminal toujours pointé vers le repertoire racine du projet.

```shell
git add *;
git commit -m '-';
git push;
```

Uniquement pour le premier 'push'

```shell
git push --set-upstream origin master
```
