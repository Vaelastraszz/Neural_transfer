# Neural_transfer
Little project to create a neural transfer style via two photos to get an artist style and apply it to a second photo

Dans ce répertoire on pourra trouver l'ensemble des étapes pour réussir un transfer learning :
- Création des deux fonctions de perte (celle pour garder le fond de l'image cible, la forme pour récupérer les pattern de la toile d'artiste)
- Un travail sur les différents placeholder dans lesquels seront stockés nos trois images (artiste, cible, image transformée)
- Un travail sur les différents layers de convolution pour récupérer les pattern bas et haut niveaux
- Du transfer learning pour le travail sur l'image
