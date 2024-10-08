
# API de Gestion des Recettes

## Description

L'application de gestion de recettes permet aux utilisateurs d'ajouter, modifier, supprimer et afficher des recettes de cuisine.
l'application a été developpeée en utilisant vuejs 3 avec la compostion  API et pinia et bootstrap pour styliser l'interface utilisateur et doit etre deployée sur vercel, conteneurisée avec Docker, et publiée sur Docker Hub.

## Fonctionnalités

- Ajout de Recettes : Les utilisateurs peuvent ajouter de nouvelles recettes en spécifiant le titre, les ingrédients, et le type de recette

- Modification de Recettes : Les utilisateurs peuvent modifier les recettes existantes.

- Suppression de Recettes : Les utilisateurs peuvent supprimer des recettes de la liste.

- Affichage de la Liste des Recettes : Une page permet de visualiser toutes les recettes


## Prérequis

- nodejs
- vuejs3
- bootstrap
- pinia

## Installation

1. Clonez le repository :
```
git clone https://github.com/NdiayeOusmanaCamara/gestion-recettes.git

```
2. Accédez au dossier du projet
 ```
 cd gestion-recettes
 ```

3. Installez les dépendances :
```
npm install
```

## Démarrer le projet
```
npm run dev
```
## Utilisation d'Axios
L'application de gestion de recettes utilise Axios pour gérer la communication avec le serveur backend. Elle permet de récupérer, ajouter, modifier et supprimer des recettes et des catégories en envoyant des requêtes HTTP.

## Gestion de la Traduction (i18n)
Pour la gestion multilingue, l'application intègre i18n pour la traduction, permettant aux utilisateurs de changer de langue en temps réel. Les textes de l'interface s'adaptent automatiquement, offrant une expérience utilisateur localisée, avec des solutions de secours en cas de traduction manquante.

## Auteur
[N'Diaye Ousmane Camara](https://github.com/NdiayeOusmanaCamara)

