# Formulaire d'Inscription aux Clubs Solicode

## Contexte
Les activités parascolaires sont essentielles pour le développement des apprenants. Elles offrent des opportunités d'échange, de partage, et d'acquisition de compétences dans des domaines variés. Solicode encourage ses apprenants à participer à des clubs couvrant différents centres d'intérêt.

Ce projet vise à concevoir et réaliser une interface d'inscription pour les clubs de Solicode.

## Fonctionnalités
Le formulaire d'inscription comprend les champs suivants :

- **Nom** : Input texte
- **Prénom** : Input texte
- **Email** : Input texte
- **Genre** : Boutons radio pour F (Féminin) et M (Masculin)
- **Filière** : Menu déroulant (select) avec deux options : Web et Mobile
- **Groupe** : Menu déroulant (select) qui dépend de la filière choisie
- **Clubs** : Cases à cocher pour choisir un ou plusieurs clubs parmi :
  - Club IA
  - Club Hackathon
  - Club Musique
  - Club Sport

Le formulaire dispose également de deux boutons :
- **Ajouter** : Valide le formulaire et ajoute une nouvelle ligne dans un tableau listant les inscrits.
- **Annuler** : Réinitialise tous les champs du formulaire.

### Contraintes de validation
- Tous les champs du formulaire sont obligatoires.
- Le bouton "Annuler" doit réinitialiser tous les champs.
- Le bouton "Ajouter" ajoute une nouvelle ligne avec les informations de l'utilisateur dans le tableau des inscrits.

## Technologies Utilisées
- HTML5
- CSS3
- JavaScript 
