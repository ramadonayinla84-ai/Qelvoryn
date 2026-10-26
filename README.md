# Qelvoryn — Prototype 0.1

Prototype web 3D destiné à être testé sur iPhone Safari.

## Ce que contient cette version
- Petit quartier 3D construit avec des formes simples
- Personnage provisoire stylisé
- Contrôles tactiles avec joystick
- Bâtiment de travail interactif
- Portefeuille virtuel local (QV)
- Bouton pour gagner 50 QV près du bâtiment bleu

## Limites importantes
- Ce n'est pas encore un jeu photoréaliste.
- Le multijoueur n'est pas encore implémenté.
- Le portefeuille est uniquement en mémoire : il se réinitialise au rechargement.
- Aucun compte joueur ni serveur n'est configuré.
- Le projet charge Three.js depuis jsDelivr : connexion Internet requise.
- Le prototype est un point de départ, pas une version prête à publier.

## Tester sur iPhone
Le fichier `index.html` doit être hébergé sur une adresse HTTPS pour être exécuté de façon fiable dans Safari. La méthode la plus simple est GitHub Pages :

1. Créer un compte sur https://github.com/
2. Créer un dépôt public nommé `qelvoryn-prototype`
3. Ajouter `index.html` à la racine du dépôt.
4. Dans le dépôt, ouvrir Settings → Pages.
5. Sous Build and deployment, choisir Deploy from a branch.
6. Choisir la branche `main` et le dossier `/ (root)`, puis Save.
7. Attendre la publication et ouvrir l'URL Pages fournie par GitHub.

Les noms exacts des menus peuvent varier selon la langue ou la version de GitHub.

## Contrôles
- Joystick en bas à gauche : déplacer le personnage.
- INTERAGIR : affiche un message quand tu es près du bâtiment bleu.
- TRAVAIL +50 QV : gagne 50 unités virtuelles près du bâtiment bleu.

## Prochaines étapes techniques
1. Tester sur Safari et corriger les problèmes d'affichage.
2. Remplacer le personnage provisoire par un modèle 3D autorisé par sa licence.
3. Ajouter une caméra réglable et des collisions.
4. Créer un backend avec authentification et sauvegarde sécurisée.
5. Ajouter un serveur de jeu temps réel (pas simplement une base de données) pour synchroniser les joueurs.
6. Tester avec 2 à 5 joueurs avant toute montée en charge.

Ne jamais stocker de clés secrètes ou de mots de passe dans `index.html`.
