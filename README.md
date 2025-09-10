# Cévennes — Mapbox GL (Pro, GeoJSON)

**Ce qui change :**
- Icônes personnalisées (couleurs + lettres) par type.
- **Clustering activé sur desktop & mobile** (clic cluster = zoom + expansion).
- **Popups enrichies** selon la couche (offices/commerces → adresse/horaires/téléphone/site ; cascades → hauteur ; cols/sommets/panoramas → altitude ; lien Google Maps auto).

## Déploiement
- GitHub Pages : créez un repo → “Upload files” (ce dossier) → Settings → Pages → *Deploy from a branch* (`main` / `/ (root)`).
- Vercel / Cloudflare Pages : import du dossier tel quel.

## Champs lus pour les points
- `name` / `nom` / `title` (titre), `type`, `description`, `elev`/`altitude`, `photo`, `url`/`website`/`site`,
- (offices/commerces) `address`/`adresse`, `hours`/`horaires`, `phone`/`tel`,
- (cascades) `height`/`hauteur`.

Bon déploiement !
