# Info501 — Gestion de projets

## Objectif du dépôt

Ce dépôt sert de base de travail pour la matière **Gestion de projets**.  
Il permet de centraliser les documents, consignes et livrables du cours.

## Comment utiliser ce dépôt

1. Cloner le dépôt :
   ```bash
   git clone <url-du-depot>
   ```
2. Se placer dans le dossier du projet :
   ```bash
   cd Info501
   ```
3. Ajouter ou modifier les fichiers demandés par les activités du cours.
4. Enregistrer les changements :
   ```bash
   git add .
   git commit -m "Description des changements"
   ```

## Ce qu’il reste à faire

- [ ] Ajouter la structure des livrables (rapports, présentations, etc.)
- [ ] Documenter les consignes détaillées de chaque activité
- [ ] Ajouter des exemples de bonnes pratiques de gestion de projet

## Commit effectué ? Comment vérifier

Oui, un commit peut être effectué après modification des fichiers.  
Vous pouvez le vérifier avec :

```bash
git log --oneline
```

Cette commande affiche l’historique des commits.  
Vous pouvez aussi vérifier l’état courant avec :

```bash
git status
```