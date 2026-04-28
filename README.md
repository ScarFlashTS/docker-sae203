# SAE 2.03

## Description
Ce projet installe un lecteur de vidéo pour apprendre les maths. 
Il est basé sur une image Debian et utilise le serveur Apache2.

## Installation et Lancement
1. **Construire l'image :**
   `docker build -t mon-serveur-partage .`

2. **Lancer le conteneur :**
   `docker run -d -p 46029:80 --name sae-container mon-serveur-partage`

3. **Utilisation :**
   Accédez à l'adresse `http://localhost:46029/partage` pour voir et télécharger les fichiers.
