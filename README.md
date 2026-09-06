# Site — [Nom du praticien]

## Structure du projet
```
index.html         → Accueil
prestations.html   → Prestations (4 catégories)
apropos.html       → À propos
contact.html       → Contact
assets/            → CSS, script, icônes et images placeholder
```

## Ce qu'il reste à personnaliser
Cherchez ces marqueurs dans les fichiers et remplacez-les :
- `[Nom du praticien]`, `[Prénom Nom]` → votre nom / nom de votre pratique
- `assets/portrait-placeholder.svg` → votre photo (gardez le même nom de fichier, ou mettez à jour le `src`)
- `assets/img-guidance.svg`, `img-soin.svg`, `img-chaman.svg`, `img-formation.svg` → vos images par catégorie
- `assets/logo-mark.svg` → votre logo, une fois défini
- Les textes signalés par une pastille « à ajuster / à compléter »
- Coordonnées (mail, téléphone, ville, réseaux sociaux) dans les 4 pages (en-tête, pied de page, page Contact)
- Tarifs et durées des prestations dans `prestations.html`

## Mettre le site en ligne gratuitement avec GitHub Pages

1. **Créer un compte GitHub** (si ce n'est pas déjà fait) sur github.com

2. **Créer un nouveau dépôt (repository)**
   - Cliquez sur « New repository »
   - Nommez-le par exemple `mon-site` (le nom n'a pas d'importance)
   - Laissez-le en « Public »
   - Ne cochez pas « Add a README » (nous avons déjà le nôtre)

3. **Envoyer les fichiers du site**
   - Sur la page du dépôt vide, cliquez sur « uploading an existing file »
   - Glissez-déposez tous les fichiers et le dossier `assets/` de ce projet
   - Cliquez sur « Commit changes »

4. **Activer GitHub Pages**
   - Dans le dépôt, allez dans **Settings** → **Pages** (menu de gauche)
   - Sous « Build and deployment » → « Source », choisissez **Deploy from a branch**
   - Branch : `main`, dossier : `/ (root)` → **Save**
   - Attendez 1 à 2 minutes

5. **Votre site est en ligne**
   - L'adresse sera de la forme : `https://votre-pseudo.github.io/mon-site/`
   - Elle est indiquée en haut de la page Settings → Pages une fois le déploiement terminé

## Mettre à jour le site plus tard
Depuis GitHub, ouvrez le fichier à modifier, cliquez sur l'icône crayon (Edit), faites vos changements, puis « Commit changes ». Le site se met à jour automatiquement en 1 à 2 minutes.

## Nom de domaine personnalisé (optionnel)
Si vous achetez un nom de domaine (ex. `www.votresite.fr`), vous pourrez le relier à GitHub Pages depuis Settings → Pages → « Custom domain ». Dites-le-moi si vous voulez de l'aide pour cette étape le moment venu.
