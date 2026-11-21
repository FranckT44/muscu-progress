# Muscu Progress

**Version 2.2.1** (21/11/2026) — liens vidéo YouTube enregistrables par exercice avec titre automatique (🎬), démonstrations 3D (👁).

Appli de suivi de musculation (PWA) : programmes, modules réutilisables, trisets/supersets, rest-pause, chrono de repos, bilans de progression.
Elle fonctionne sur téléphone (Android / iPhone) et sur Windows, hors connexion, sans compte ni serveur.

## Mise en ligne avec GitHub Pages (5 minutes)

1. Sur github.com → **New repository** → nom : `muscu-progress` → Public → *Create*.
2. **Add file → Upload files** : glisser `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `README.md` → *Commit*.
3. **Settings → Pages** → Source : *Deploy from a branch* → Branch : `main` / `(root)` → *Save*.
4. Après ~1 minute, l'appli est disponible sur `https://<ton-pseudo>.github.io/muscu-progress/`.

## Installer l'appli

- **Android (Chrome)** : ouvrir l'adresse → menu ⋮ → *Ajouter à l'écran d'accueil* / *Installer l'application*.
- **iPhone (Safari)** : ouvrir l'adresse → bouton Partager → *Sur l'écran d'accueil*.
- **Windows (Edge ou Chrome)** : ouvrir l'adresse → icône « Installer » dans la barre d'adresse. L'appli s'ouvre ensuite dans sa propre fenêtre, comme un logiciel.

## Données

- Tout est enregistré **sur l'appareil** (stockage du navigateur). Rien n'est envoyé sur Internet.
- Les données du téléphone et du PC sont séparées : **Réglages → Sauvegarde (.json)** sur l'un, puis **Restaurer** sur l'autre.
- **Réglages → Export Excel (.csv)** : toutes les séries (date, exercice, reps, charge, rest-pause, volume) à ouvrir dans Excel.
- Exporte une sauvegarde régulièrement (effacer les données du navigateur efface aussi l'appli).

## Mettre à jour

Remplacer `index.html` dans le dépôt GitHub. Le téléphone récupère la nouvelle version à la prochaine ouverture avec du réseau.
