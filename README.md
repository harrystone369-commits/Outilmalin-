# OutilMalin — version statique améliorée

## Inclus
- `index.html` : site responsive avec 5 outils fonctionnels : budget, marge de revente avec frais de plateforme, objectif d'épargne, TVA HT/TTC et estimation d'affiliation.
- `config.js` : configuration de l'adresse de contact et des liens d'affiliation validés.
- `robots.txt` et `sitemap.xml` : fichiers SEO à mettre à jour avec l'URL publique.
- Aucun framework, backend, base de données, abonnement ou dépendance externe nécessaire.

## Tester sur ordinateur
1. Décompressez l'archive.
2. Ouvrez `index.html` dans un navigateur récent. Pour tester avec un serveur local, ouvrez un terminal dans le dossier et lancez `python3 -m http.server 8000`, puis visitez `http://localhost:8000`.
3. Testez chaque outil avec plusieurs valeurs, y compris zéro et des valeurs élevées.

## Publier gratuitement avec GitHub Pages
1. Créez un compte sur https://github.com/.
2. Créez un dépôt public, par exemple `outilmalin`.
3. Téléversez `index.html`, `config.js`, `robots.txt` et `sitemap.xml` à la racine du dépôt.
4. Dans Settings > Pages, choisissez `Deploy from a branch`, branche `main`, dossier `/ (root)`, puis enregistrez.
5. Attendez la publication. Récupérez l'URL fournie par GitHub Pages.
6. Remplacez `https://REMPLACER-PAR-URL-DU-SITE/` dans la balise canonical et dans `sitemap.xml`; remplacez l'URL dans `robots.txt` par celle du sitemap réel. Committez les modifications.

## Configurer l'affiliation
1. Inscrivez-vous auprès d'un programme pertinent et attendez son approbation.
2. Ouvrez `config.js` et remplissez `partners` avec le nom, une description honnête et l'URL de suivi fournie par le programme. Les liens doivent être des URL HTTPS réelles et autorisées.
3. Remplissez `contactEmail` avec une adresse de contact valide.
4. Ne collez jamais de mots de passe, clés secrètes ou données bancaires dans les fichiers publics.
5. Vérifiez les règles du programme et indiquez clairement les liens rémunérés aux visiteurs.

## À compléter avant une exploitation commerciale
- Remplacer les placeholders du domaine.
- Renseigner les mentions légales avec les informations exactes de l'éditeur et de l'hébergeur.
- Vérifier les obligations françaises applicables, notamment celles liées à l'activité, à la confidentialité et à l'affiliation.
- Si vous ajoutez statistiques, publicités ou formulaires, évaluer les obligations RGPD/cookies et configurer le consentement approprié.
- Vérifier le nom commercial avant de l'utiliser durablement.

## Limites importantes
Ce site statique ne comporte pas de tableau d'administration en ligne, de base de données, de paiement, de collecte de prospects, d'analytique globale ni de compte affilié. Les calculs fonctionnent localement. Les liens d'affiliation et les revenus ne peuvent pas être activés automatiquement sans comptes approuvés et liens personnels fournis par l'utilisateur. L'hébergement gratuit ne garantit pas de trafic ou de revenus.
