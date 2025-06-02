# Micro-SaaS 
Projet de micro SaaS de fin de formation CDA (concepteur développeur d'application). Présentation du projet, diagrammes de cas d'utilisation, wireframes et modèle de base de données.

# Peps*, l'appli qui répond à la question "On mange quoi ce soir?" 🫑

*Peps* ou auparavent *Weekly Meals* est une application destinée à tous ceux qui sont fatigués de se poser toujours la même question : **"Qu'est ce qu'on mange ce soir?"** 🥪\
Avec un catalogue contenant des **recettes variées** et organisées par régimes alimentaires, pays d'origine ou préférences, Peps vous permettra de **sauvegarder des recettes** et de **générer des menus** personnalisables pour la semaine!
En plus des recettes disponibles sur l'application, vous pourrez également **créer les vôtres** et les partager aux autres utilisateurs.

**Nom temporaire*

# Présentation

Retrouvez la présentation de l'appli sous forme de slides ici :
[Peps, la présentation](https://www.canva.com/design/DAGnmqVN7EU/8eikM_W8gUlPJpHhNQLuSQ/edit?utm_content=DAGnmqVN7EU&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

## Fonctionnalités principales

🍔 Catalogue de recettes \
🥦 Filtrer les recettes selon vos préférences (filtre sur le régime alimentaire, le pays, par ingrédients de saison ...) \
🍪 Inscription et Connexion utilisateur \
🍲 Possibilité de sauvegarder des recettes \
🌮 Créer vos propres recettes \
🍜 Génération de menus de la semaine \
🍱 Personnalisation d'un menu (nombre de jours, régime spécifique au menu, modification d'un menu) \

## Stack Technique choisie

- Base de données en **PostgreSQL** 
- Conteneur Docker
- Back-end en **Java SpringBoot** architecture en couche (model > repository > service > controller)
- OAuth2 Spring Boot security pour la connexion
- Front-end en **Typescript Angular**
- Tailwind et DaisyUI comme librairies UI/UX


# Détails Techniques

## Wireframes

 ![accueil mobile](/img/w-home.png "Accueil mobile")
 ![menus mobile](/img/w-menus.png "Menus mobile")
 ![page recettes](/img/w-recipes.png "Page recettes")

## Diagramme de Cas d'Utilisation

 ![usecase](/img/use-case.png "Diagramme de Cas d'Utilisation")

 ## Première maquette desktop (2024)

 ![maquette home](/img/m-home.jpg "Home desktop")
 ![page menus desktop](/img/m-menus.jpg "Page Menus")
 ![page recette](/img/m-details.jpg "Page Recette Détails")

 ## Premier modèle MERISE (2024)

  ![modèle merise](/img/merise.png "Modèle Merise")
