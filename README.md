# **Readme**
## **Prérequis**
- GIT
- Docker (facultatif)
- Node, NPX
- HTML / SCSS / REACT / WordPress
- Création de Plugin WordPress
## **Installation sous Docker**
- Après avoir cloner le repo, faites un :

  docker-compose up

- Cela installera l’environnement Wordpress, finalisez l’installation en vous rendant sur l’url suivante :

  localhost:8000

Vous pouvez commencer à développer.

Si Docker n’est pas disponible, tout autre moyen de déployer un WordPress est valide a partir du moment où le rendu est un plugin WordPress.
## **Rendu**
- Un Plugin Gutenberg - Wordpress - contenant les différents bloc / composants demandé
- Un code propre, sans log et commenté
## **Interdiction**
- l’usage de Frameworks :
  - Bootstrap
  - JQuery
## **À Faire**
Le test demande un plugin WordPress développé sous REACT pour l'éditeur Gutenberg :

- Un bloc “Section” dans lequel on peut retrouver :
  - **Un composant** **texte** - modifiable, couleur, taille, gras / Italique / barré - réutilisable plusieurs fois dans la section pour :
    - Un titre
    - Une description
  - **2 boutons** ( ils peuvent être caché si besoin d’en afficher que 1 ou aucun) : possibilité de modifier le label, son lien, possibilité d’afficher ou non une icone ( **>** ou **<** ) a gauche ou a droite du label
  - **Une image** situé a droite des 3 champs décrit ci-dessus
- Le tout devra être **responsive**
## **Bonus**
- Créer une section Slider d’images : libre
- Utilisations de VARIABLE SCSS
- Utilisation de GRID et/ou FLEX
- Connaissance de CONCENTRIC CSS
