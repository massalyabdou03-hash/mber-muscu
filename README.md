<p align="center"><img src="logo.svg" width="96" alt="Logo Mbër Muscu"></p>

# Mbër Muscu

Application web de prise de masse pensée pour le Sénégal : repas avec des aliments du marché ou d'Auchan (prix en FCFA), liste de courses, et séances de musculation quotidiennes avec mannequins animés.

## Ce que fait l'app

- **Aujourd'hui** : séance du jour, repas à cocher, objectif de calories et de protéines, suivi du poids.
- **Repas** : plan du jour qui respecte le budget en FCFA saisi dans le profil. On peut changer un repas.
- **Séances** : programme pour 3, 4 ou 5 jours par semaine, à la salle ou à la maison. Suivi des charges série par série, minuteur de repos, suggestion de progression.
- **Courses** : liste sur 1, 3 ou 7 jours qui reste en place jusqu'à la fin de la période.
  - Quantités en vrais conditionnements (baguettes, boîtes, briques, paquets) et prix sur ce que tu paies vraiment.
  - Sorties planifiées : une grande course pour le stock, puis le frais racheté tous les 2 ou 4 jours ; pain compté chaque matin.
  - « Déjà à la maison ? » pour retirer ce qu'il te reste au placard, option congélateur, ajouts libres, copie WhatsApp de ce qui reste à acheter.
  - Le marché d'abord, Auchan seulement si l'article n'y est pas ou s'il y est au moins 20 % moins cher.
- **Profil** : calcul des besoins (formule de Mifflin-St Jeor, protéines à 1,8 g par kg).

## Design

- Identité noir et or : le logo est un « M » qui forme une barre de musculation, sur un badge or (`logo.svg`).
- Thème clair et thème sombre, selon le réglage du téléphone.
- Tableau de bord avec anneau de calories, macros en couleur, barre d'onglets flottante.

## Lancer

Un seul fichier, sans installation : ouvre `index.html` dans un navigateur, ou déploie le dossier tel quel (Netlify, Vercel, GitHub Pages). Les données restent dans le navigateur (`localStorage`).

## Notes

- Les prix sont des estimations pour Dakar, à ajuster dans le code (objet `FOODS`, champ `price`).
- Les valeurs nutritionnelles sont approximatives.
- Estimations générales pour un adulte en bonne santé.
