# DJ TEX — site one page

Site statique (HTML/CSS, sans build) : `index.html` + `assets/`.

## À compléter
Dans `index.html`, section **Contact** :
- Téléphone : remplacer `tel:+33600000000` et `06 00 00 00 00`
- Facebook / Instagram : remplacer les `href="#"` par l'adresse des pages

## Mise en ligne sur Cloudflare Pages
1. Cloudflare → Workers & Pages → Create → Pages → *Connect to Git* → choisir ce dépôt.
2. Framework preset : **None** · Build command : *(vide)* · Build output directory : **/**
3. Deploy. Chaque `git push` met le site à jour automatiquement.
4. Nom de domaine perso : onglet *Custom domains* du projet.
