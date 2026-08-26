# keskikout-site

Site vitrine de **Keskikout** (app Android de suivi d'abonnements) — [keskikout.fr](https://keskikout.fr).

HTML/CSS statique, sans framework, hébergé sur **GitHub Pages**.

## Pages
- `index.html` — accueil FR
- `en/index.html` — accueil EN
- `confidentialite/index.html` — politique de confidentialité FR (URL Play Console)
- `en/privacy/index.html` — privacy policy EN

## Design
Sobre, mobile-first, aligné sur l'app : accent `#7C3AED`, fond clair, police système.
Tout le style est dans `styles.css`. Le logo (`assets/logo.png`) est le symbole de l'app :
PNG carré, 512 × 512 px recommandé (affiché en 36 × 36 dans l'en-tête, et servi comme favicon,
apple-touch-icon et image Open Graph).

## Développement
Pages 100 % statiques : ouvrir un fichier `.html` dans le navigateur, ou servir le dossier
(`python -m http.server`). Aucune build.

## Emplacements à compléter avant lancement
- Lien Google Play : le bouton « Bientôt sur Google Play » pointe sur `href="#"` dans
  `index.html` et `en/index.html` — à remplacer par l'URL de la fiche Play.
  Au passage, repasser `.cta` (dans `styles.css`) en bouton actif : `background: var(--accent)`,
  `color: #fff`, `cursor: pointer`.
- Captures d'écran dans le hero.
