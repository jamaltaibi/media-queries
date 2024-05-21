# Mon Projet HTML et CSS avec Media Queries

Bienvenue dans mon projet HTML et CSS ! Ce projet présente une structure de page web avec des styles adaptés à différents formats d'écran grâce aux media queries.

## Structure du Projet

- **index.html** : Définit la structure de la page avec une navigation et une section d'en-tête.
- **Styles/style.css** : Applique les styles et les media queries pour différents formats d'écran.

## Aperçu des Sections

### index.html

- `<header>` : Contient le menu burger et la navigation.
  - `<div class="menuBurger">` : Icône de menu burger.
  - `<ul>` : Liste de navigation.
  - `<div class="bgHeader">` : Image de fond de l'en-tête.
- `<h1>` : Titre principal.

### styles/style.css

- **Styles généraux** :
  - `ul` : Flexbox, espace entre les éléments, pas de puces.
  - `.menuBurger` : Initialement masqué, sauf sur petits écrans.
  - `.bgHeader` : Image de fond couvrant toute la section, centrée.

- **Media queries** :
  - **Téléphone (max-width: 550px)** :
    - Masque le titre `<h1>` et la liste de navigation `<ul>`.
    - Affiche l'icône de menu burger.
  - **Tablette (min-width: 551px) and (max-width: 800px)** :
    - Masque la liste de navigation `<ul>`.
    - Change l'image de fond de `.bgHeader`.
    - Affiche l'icône de menu burger.
  - **Ordinateur (min-width: 801px)** :
    - Masque l'icône de menu burger.

## Instructions pour Visualiser le Projet

1. Clonez le dépôt
2. Accédez au dossier du projet 
3. Ouvrez `index.html` dans votre navigateur.

## Auteur

- **Jamal Taibi**

---

© Taibi Jamal
