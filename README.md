# keskikout-site

Site vitrine de **Keskikout** (app Android de suivi d'abonnements) — [keskikout.fr](https://keskikout.fr).

HTML/CSS statique, sans framework, hébergé sur **GitHub Pages**.

## Pages
- `index.html` — accueil FR
- `en/index.html` — accueil EN
- `confidentialite/index.html` — politique de confidentialité FR (URL Play Console)
- `en/privacy/index.html` — privacy policy EN
- `app/index.html`, `en/app/index.html` — passerelle : redirection vers la fiche Google Play (`keskikout.fr/app`)

## Design
Sobre, mobile-first, aligné sur l'app : accent `#7C3AED`, fond clair, police système.
Tout le style est dans `styles.css`. Le logo (`assets/logo.png`) est le symbole de l'app :
PNG carré, 512 × 512 px recommandé (affiché en 36 × 36 dans l'en-tête, et servi comme favicon,
apple-touch-icon et image Open Graph).

## Développement
Pages 100 % statiques : ouvrir un fichier `.html` dans le navigateur, ou servir le dossier
(`python -m http.server`). Aucune build.

## Emplacements à compléter avant lancement
- Captures d'écran dans le hero.
