# Portfolio — Fatoumata Sarr

Site vitrine personnel en HTML/CSS/JS pur — aucune installation, aucun build, aucun compte
Vercel nécessaire. Pensé pour être publié en un clic via **GitHub Pages**.

## 🚀 Publier le site (GitHub Pages)

1. Crée un nouveau repository sur GitHub, par exemple `portfolio` (public).
2. Ajoute ces fichiers et dossiers à la racine du repo :
   - `index.html`
   - `style.css`
   - `script.js`
   - le dossier `assets/` en entier (contient tes 3 vraies captures : tableau de bord, campagne Google Ads, scénario email nurturing)
3. Sur GitHub : **Settings → Pages**.
4. Dans *Source*, choisis **Deploy from a branch**, branche `main`, dossier `/ (root)`.
5. Enregistre. Après 1–2 minutes, ton site est en ligne à l'adresse :
   `https://FIFI-cyb.github.io/portfolio/`

Aucune autre étape : pas de `npm install`, pas de build, pas de variable d'environnement.

## ✏️ Avant de publier — à compléter

Cherche le mot **"à compléter"** dans `index.html` (surligné en orange sur le site) :

- [ ] **Formation précédente** (section Formation) — ton BTS / licence / autre.
- [ ] **Niveau d'anglais** (section Langues).
- [ ] **Centres d'intérêt** (section Langues & intérêts).
- [ ] **Email de contact** (dans le footer, remplace `ton.email@exemple.com` par ta vraie adresse
      — cherche `mailto:` dans `index.html`).
- [ ] **Photo** — si tu veux remplacer le bloc "FS" par une vraie photo, remplace le `<div class="portrait">`
      dans la section À propos par une balise `<img>` pointant vers une image que tu ajoutes dans le repo.
- [ ] **Descriptions des projets GitHub** (SalesOps, Hôpital Pitié-Salpêtrière, MID-APP, Projet_Spe1) —
      les descriptions actuelles sont génériques, personnalise-les avec le vrai contenu de chaque projet.

## 🎨 Personnaliser les couleurs

Tout se change dans `style.css`, tout en haut, dans `:root{ }` :

```css
--accent: #FF5A36;   /* couleur d'accent (liens, boutons, highlights) */
--ink: #14181C;      /* texte principal / fond sombre */
--paper: #FAFAF7;    /* fond clair */
```

## 📱 Structure

- Une seule page (`index.html`), sections ancrées : À propos, Expérience, Formation,
  Compétences, Projets, Langues, Contact.
- Responsive (mobile, tablette, desktop) — testé de 390px à 1440px de large.
- Police display : *Fraunces* — police body : *Inter* — police mono (labels/données) : *IBM Plex Mono*.
