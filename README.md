# Documentation du tuto Git&Github

## Initialisation du dépôt

``` bash
git init
git remote add origin SSH_REPO
```

## Rédiger un commit (proprement)

```
Titre du commit
Description du commit avec info sur l'évolution du projet
```

## Envoyer un commit sur le dépôt à distance

```bash
git add.
git commit -m "Titre du commit"
git push origin main
```

## Création d'une branche

```bash
git checkout -b "Nom de la branche"
```

Pour les bonnes pratique, on va intégrer la notion de revue de code. Pour cela, on va créer une branche, faire des modifications, les envoyer sur le dépôt à distance, puis créer un pull request pour demander une revue de code.
