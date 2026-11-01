# Portfolio — Loïs-Elie Ekollo

Portfolio personnel au style terminal : étudiant **DevOps & Cloud** à Epitech Lille.

- **Aucune dépendance, aucun build** : une seule page HTML, du CSS et du JavaScript natifs.
- Animations : nom « glitch », texte tapé, photo qui se « charge », démos animées des projets au survol.
- Accessible : respecte `prefers-reduced-motion`, navigation au clavier, textes alternatifs.

## Voir le site en local

Ouvrir `index.html` dans un navigateur, ou lancer un petit serveur :

```bash
python3 -m http.server 8000
# puis http://localhost:8000
```

## Mise en ligne avec GitHub Pages

1. Pousser ce dossier dans un dépôt GitHub (par exemple `portfolio`).
2. **Settings → Pages → Build and deployment** : *Deploy from a branch*, branche `main`, dossier `/ (root)`.
3. Le site est publié sur `https://<pseudo>.github.io/portfolio/`.

## Structure

```
.
├── index.html      # la page (HTML, CSS et JS)
└── assets/         # photo, CV, captures des projets, favicon
```
