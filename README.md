# Site académique personnel — Lhousain Mouatadid

Site statique bilingue (français/anglais), responsive, réalisé en HTML, CSS et JavaScript sans framework. Il peut être publié gratuitement sur GitHub Pages.

## Aperçu local

1. Décompressez l'archive ZIP.
2. Ouvrez `index.html` dans un navigateur. La bascule FR/EN, le menu mobile, les liens DOI et le téléchargement du CV sont fonctionnels.
3. Pour un aperçu local plus fidèle, démarrez un serveur statique depuis ce dossier, par exemple `python -m http.server 8000`, puis ouvrez `http://localhost:8000`.

## Publier avec GitHub Pages

1. Connectez-vous à GitHub et créez un dépôt public nommé `lhousain-mouatadid.github.io` (ou un autre nom de dépôt si vous préférez une URL de projet).
2. Téléversez le contenu de ce dossier à la racine du dépôt : `index.html`, `styles.css`, `script.js`, `assets/` et `documents/`.
3. Dans le dépôt, ouvrez **Settings → Pages**.
4. Sous **Build and deployment**, choisissez **Deploy from a branch**, sélectionnez `main` et `/ (root)`, puis enregistrez.
5. Attendez la fin du déploiement. GitHub affichera l'adresse publique dans la section Pages.

Pour un dépôt nommé `lhousain-mouatadid.github.io`, l'adresse sera généralement `https://lhousain-mouatadid.github.io/`. Pour un autre nom, l'URL comprendra le nom du dépôt.

## Fichiers

- `index.html` : structure et contenu des sections.
- `styles.css` : identité visuelle et adaptations mobile.
- `script.js` : traduction FR/EN et menu mobile.
- `assets/favicon.svg` : icône du site.
- `documents/CV_Lhousain_Mouatadid.pdf` : CV PDF disponible au téléchargement.
- `documents/CV_Lhousain_Mouatadid.tex` : source LaTeX du CV.

## À compléter avant publication

- Confirmer les métadonnées finales de toutes les publications auprès des pages éditeur. Le site reprend les titres et DOI fournis dans le CV; une note de vérification reste visible.
- Ajouter les identifiants/URLs confirmés pour ORCID, Google Scholar, MathSciNet, zbMATH ou un profil institutionnel.
- Ajouter des supports pédagogiques téléchargeables (PDF) si vous souhaitez les partager.
- Vérifier la date et l'intitulé officiel de votre poste actuel, notamment la dénomination de l'école et de l'affiliation.
- Vérifier si vous souhaitez publier l'adresse e-mail sur un site public. Le numéro de téléphone et l'adresse postale n'ont volontairement pas été exposés sur le site.
- Envisager un nom de domaine personnel plus tard, si souhaité.

## Notes techniques

- Aucun framework ou outil de compilation n'est requis.
- La police web est chargée depuis Google Fonts; des polices système servent de secours si le service n'est pas disponible.
- Les identifiants ORCID et Google Scholar ne sont pas inventés : ils sont signalés comme éléments à ajouter une fois confirmés.
