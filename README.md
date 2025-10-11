# 🌐 Projet : Page Web "Devoir à la maison"

## 📖 Description

Ce projet consiste à créer une **page web statique** en **HTML5** et **CSS3** reproduisant une structure de site inspirée du portail administratif *mon.service-public.fr*.  
L’objectif est de pratiquer la mise en page, les balises sémantiques HTML, et l’utilisation du **Flexbox** pour la disposition des éléments d’en-tête.

---

## 🧩 Structure des fichiers

### `index.html`
Ce fichier contient la **structure HTML** principale de la page.

#### Contenu principal :
- **`<header>`** : contient le logo du site et un champ de recherche fonctionnel.  
- **`<nav>`** : menu de navigation avec plusieurs sous-menus imbriqués.  
- **`<main>`** : section principale présentant les rubriques du tableau de bord.  
- **`<aside>`** : blocs d’actualités et d’astuces.  
- **`<footer>`** : informations légales, partenariats et liens utiles.

#### Objectifs techniques :
- Respecter la sémantique HTML5 (`header`, `nav`, `main`, `aside`, `footer`)
- Structurer correctement les listes et les liens
- Utiliser des images locales pour enrichir le contenu

---

### `style.css`
Ce fichier définit la **mise en forme** de la page.

#### Points clés :
- Importation d’un fichier `reset.css` pour uniformiser le rendu entre navigateurs :
  ```css
  @import url('reset.css');
