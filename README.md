# Rotation équitable U10

Application React/Vite pour préparer et suivre les rotations d'un match U10 en 8 contre 8.

## Fonctions
- 12 joueurs, absences et remplaçants
- 2 gardiens, 30 minutes au goal et passages sur le terrain
- 8 séquences de 7 min 30
- poste prioritaire conservé pendant le match
- historique des positions et du temps de jeu
- mode match avec minuterie, alerte sonore et vibration
- export PNG des terrains
- sauvegarde et restauration JSON
- stockage local dans le navigateur

## Publication gratuite avec GitHub Pages
1. Créez un dépôt GitHub vide.
2. Décompressez ce package et envoyez tout son contenu dans le dépôt, y compris `.github`.
3. Dans GitHub, ouvrez `Settings` > `Pages`.
4. Dans `Build and deployment`, choisissez `GitHub Actions` comme source.
5. Ouvrez l'onglet `Actions` et vérifiez que le workflow `Deploy GitHub Pages` est terminé.
6. Le lien public apparaît dans `Settings` > `Pages`.

Le workflow est déjà fourni dans `.github/workflows/deploy.yml`.

## Utilisation locale facultative
```bash
npm install
npm run dev
```

## Vérification de production
```bash
npm install
npm run build
```

## Données
Les données sont enregistrées dans le navigateur de l'appareil. Utilisez `Exporter` pour créer une sauvegarde JSON et `Importer` pour la restaurer sur un autre appareil.
