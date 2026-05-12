# Tableau de bord (Home)

Application statique : `dashboard.html`, avec `manifest.json` pour installation PWA.

- **`.gitignore`** : ignore les fichiers système / temporaires (`.DS_Store`, etc.).
- **`LICENSE`** : MIT — tu peux la retirer ou la remplacer si tu préfères tout garder privé sans licence explicite.

## GitHub Pages

1. Crée un dépôt vide sur GitHub (sans README généré, ou supprime le sien après coup).
2. Dans ce dossier sur ton Mac :

   ```bash
   cd ~/Desktop/HOME
   git remote add origin https://github.com/TON_USER/TON_REPO.git
   git branch -M main
   git push -u origin main
   ```

3. Sur GitHub : **Settings → Pages → Build and deployment → Source** : branche **main**, dossier **/** (racine).
4. Après le déploiement (1–2 min), l’URL sera du type  
   `https://TON_USER.github.io/TON_REPO/`  
   (redirection vers `dashboard.html` via `index.html`).

Les données restent dans le **localStorage du navigateur** pour ce domaine (donc une URL GitHub = un stockage distinct du fichier ouvert en `file://` sur ton Mac).
