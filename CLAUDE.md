# SkyAra : consignes de projet

## But
Application personnelle de suivi d'une vision sur 6 ans (2026-2031) pour Donne, en français. Le propriétaire est débutant : expliquer simplement, étape par étape.

## Règles
- Répondre en français.
- Le fichier source unique est `index.html` (HTML, CSS et JavaScript ensemble). Pas de dépendance externe hormis la police Google Fonts.
- Garder les thèmes clair et sombre (variables CSS dans `:root`).
- Orange = passé, vert = avenir : ces deux couleurs ne servent qu'au temps.
- Ne jamais supprimer les données de l'utilisateur : toute évolution du modèle de données doit migrer l'ancien état (voir `mergeState` dans `index.html` et `docs/DONNEES.md`).
- Contenu à ne pas inclure dans l'application : sécurité, foi, santé, famille.

## Publication
- Artefact en ligne : https://claude.ai/artifact/4XQw2vY3AVhj6LF96uvWQJ
- Capacité utilisée : `db` (document `vision/state`). Republier `index.html` sur la même adresse garde les données.
- Avant une grosse modification, copier `index.html` dans `versions/`.
