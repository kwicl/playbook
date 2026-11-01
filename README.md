# SkyAra

Application de suivi de vision sur 6 ans (janvier 2026 à décembre 2031) : une carte de métro verticale avec des bandeaux (lignes), des stations, des liaisons datées, et des objectifs chiffrés avec leurs moyens et leur suivi.

## Ouvrir l'application
- Version en ligne (données enregistrées) : https://claude.ai/artifact/4XQw2vY3AVhj6LF96uvWQJ
- Version locale : ouvrir `index.html` dans un navigateur. Les données sont alors gardées dans le navigateur uniquement (localStorage, clé `cap2031`).

## Contenu de l'application
1. **Carte** : un bandeau par axe (Apprentissage, Immobilier, IA & automatisation, Revenus alternatifs, Capital & Bourse). Rail du temps orange (passé) puis vert (avenir), curseur clignotant sur aujourd'hui.
2. **Stations** : étape, sous-objectif à valider (losange), objectif final (étoile). Statuts : Réalisé, En cours, Planifié, Prévisionnel.
3. **Bandeaux** : ajout, suppression, nom, couleur, définition de l'objectif final, ordre.
4. **Liaisons** : entre deux bandeaux, avec une date. Fusion (la ligne de départ s'arrête) ou correspondance (les deux continuent).
5. **Objectifs chiffrés** : échéance, résultat concret, moyens (actions à cocher), suivi daté avec courbe, rythme (en avance, dans le rythme, en retard).

## Arborescence
- `index.html` : toute l'application (HTML, CSS, JavaScript dans un seul fichier)
- `docs/DONNEES.md` : structure des données
- `docs/JOURNAL.md` : historique des versions
- `versions/` : sauvegardes de versions précédentes
- `CLAUDE.md` : consignes pour continuer le projet avec Claude

## Prochaines pistes
- Sauvegarde et export des données (fichier JSON)
- Vue mobile dédiée pour la carte
- Rappels sur les stations dont la date est dépassée
