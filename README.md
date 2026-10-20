# Mbër Muscu

Application web de prise de masse pensée pour le Sénégal : repas avec des aliments du marché ou d'Auchan (prix en FCFA), liste de courses, et séances de musculation quotidiennes avec mannequins animés.

## Ce que fait l'app

- **Aujourd'hui** : séance du jour, repas à cocher, objectif de calories et de protéines, suivi du poids.
- **Repas** : plan du jour qui respecte le budget en FCFA saisi dans le profil. On peut changer un repas.
- **Séances** : programme pour 3, 4 ou 5 jours par semaine, à la salle ou à la maison. Suivi des charges série par série, minuteur de repos, suggestion de progression.
- **Courses** : liste sur 1 ou 7 jours, séparée entre marché et Auchan, à copier vers WhatsApp.
- **Profil** : calcul des besoins (formule de Mifflin-St Jeor, protéines à 1,8 g par kg).

## Lancer

Un seul fichier, sans installation : ouvre `index.html` dans un navigateur, ou déploie le dossier tel quel (Netlify, Vercel, GitHub Pages). Les données restent dans le navigateur (`localStorage`).

## Notes

- Les prix sont des estimations pour Dakar, à ajuster dans le code (objet `FOODS`, champ `price`).
- Les valeurs nutritionnelles sont approximatives.
- Estimations générales pour un adulte en bonne santé.
