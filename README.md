# Portfolio d’acteur — déploiement GitHub Pages

Ce dossier contient un **site statique complet** (HTML+CSS+JS) prêt à publier sur **GitHub Pages**.  
Il inclut : thème switch, bannière, galerie, section films, et contacts.

## 1) Personnaliser
- Ouvrez `index.html` et remplacez :
  - `Votre Nom`, la bio, mensurations, email, téléphone, agent.
  - Les images `https://placehold.co/...` par vos photos **publiques** (ou hébergées dans ce repo).
  - Les liens vers **IMDb / AlloCiné / Showreel / Bande‑annonce**.
- Optionnel : modifiez les couleurs dans `:root` et les variantes `theme-…`.

## 2) Créer le dépôt
1. Connectez‑vous à GitHub.
2. Créez un nouveau repo public, par ex. `actor-portfolio` (ou `votrepseudo.github.io` si vous voulez un domaine racine).
3. Ajoutez les fichiers : `index.html`, `README.md`, `.nojekyll` (fichier vide).

## 3) Activer GitHub Pages
- Allez dans **Settings → Pages**.
- **Source** : *Deploy from a branch*.
- **Branch** : `main` (root `/`). Enregistrez.
- Une URL sera générée, typiquement :  
  `https://<votrepseudo>.github.io/actor-portfolio/`

## 4) Intégrer dans Google Sites (avec les effets conservés)
- Dans Google Sites : **Insérer → Intégrer → Par URL**.
- Collez l’URL GitHub Pages du site.
- Ajustez la largeur (100%).

## 5) Domaine personnalisé (optionnel)
- Achetez/possédez un domaine (ex. `votrenom.com`).
- Dans **Settings → Pages → Custom domain** : suivez l’assistant (CNAME chez votre registrar).
- Ajoutez un fichier `CNAME` à la racine du repo contenant **exactement** votre domaine.

## Dépannage
- Page blanche : vérifiez **Settings → Pages** et que la branche/chemin sont corrects.
- Images qui ne s’affichent pas : l’URL est‑elle publique ?
- Style cassé : videz le cache du navigateur (Ctrl/Cmd+Shift+R).

Bon déploiement ! 🎬
