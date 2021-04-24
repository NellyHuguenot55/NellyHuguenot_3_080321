# NellyHuguenot_3_080321 - Ohmyfood

# lien vers votre repository GitHub : https://nellyhuguenot55.github.io/NellyHuguenot_3_080321/
# lien vers la page web du site : https://nellyhuguenot55.github.io/NellyHuguenot_3_080321/index.html

### Projet 3 du parcours "Développeur web" d'OpenClassrooms - Dynamisez une page web avec des animations CSS

## Objectif

Intégrer les maquettes responsive d'Ohmyfood, un site 100% mobile proposant le menu de 4 grands restaurants parisiens. Les utilisateurs pourront composer leur propre menu parmi un répertoire de restaurants gastronomiques et pourront réserver.



## Contraintes techniques

- Les polices du site sont :
  - [Shrikhand](https://fonts.google.com/specimen/Shrikhand) pour le logo et les titres
  - [Roboto](https://fonts.google.com/specimen/Roboto) pour le texte
- Les couleurs de la charte sont :
  - Primaire (violet) #9356DC
  - Secondaire (rose) #FF79DA
  - Tertiaire (vert) #99E2D0
- Le développement devra se faire en CSS, sans JavaScript
- Aucun framework ne devra être utilisé
- Aucun code CSS ne devra être appliqué via un attribut style dans une balise HTML  - Le site devra être développer en utilisant une approche mobile-first
- Le site devra également être adapté sur tablette et desktop avec une mise en page libre
- Les pages devront passer la validation W3C en HTML et CSS sans erreur
- Le site doit être parfaitement compatible avec les dernières versions desktop de Chrome et Firefox
- Les effets accessibles au clic ou au survol, visibles sur la maquette, devront utiliser les animations ou transitions CSS mais pas de JavaScript ni de librairie
- Il faudra recréer les éléments de zéro (titres, texte...)

## Fonctionnalités

#### Page d'accueil

- Affichage de la localisation des restaurants
- Courte présentation de l’entreprise
- Une section contenant les 4 menus sous forme de cartes cliquables menant vers leur page de menu
- En arrivant sur la page d'accueil : apparition d'un loading spinner (cohérent avec la charte graphique du site) pendant 1 à 3 secondes, couvrant l'intégralité de l'écran et utilisant les animations CSS

#### Pages de menu

- 4 pages contenant chacune le menu d’un restaurant
- Les plats devront apparaître progressivement avec un léger décalage dans le temps (soit un par un, soit par groupe “Entrée”, “Plat” et “Dessert”)
- En cliquant sur un plat : une petite coche devra apparaître à droite du plat
- La coche devra coulisser de la droite vers la gauche
- Pour cette première version et sur desktop, l’effet de coche peut apparaître au survol au lieu du clic
- Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension

#### Footer

- Identique sur toutes les pages
- Au clic sur “Contact”, renvoi vers une adresse mail

#### Header

- Présent sur toutes les pages
- Sur la page d’accueil : le logo du site
- Sur les pages de menu : ajout d'un bouton de retour vers la page d’accueil

#### Boutons

- Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir
- L’ombre portée devra également être plus visible
- Au clic, le bouton "J’aime" en forme de cœur devra se remplir progressivement
- Pour cette première version et sur desktop, l’effet du bouton "J’aime" peut apparaître au survol au lieu du clic

## Recommandation

- L’utilisation de SASS serait un plus
