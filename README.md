# Portfolio SBI4U | Biologie

Portfolio électronique de biologie 12e année (SBI4U), école secondaire catholique Sainte-Trinité. Site statique : un seul fichier, `index.html`, sans dépendances externes. La photo et les cartes conceptuelles sont déjà intégrées dans le fichier.

## Contenu du site
- **Accueil** : présentation, « À propos de moi », lettre d'ouverture, carte conceptuelle du cours, galerie de photos, lettre de clôture et bibliographie.
- **Page « Unités »** (bouton « Explorer les unités ») : cinq boutons, un par unité. Chaque unité contient un exposé sur un scientifique ontarien, une analyse d'article scientifique, une recherche sur une carrière et une carte conceptuelle. Les unités 1 et 2 sont complétées. Le bouton « ← Retour à l'accueil » ramène à la page d'accueil.

## Publier avec GitHub Pages
1. Créer un dépôt **public** sur github.com (ex. `portfolio-sbi4u`).
2. Cliquer sur **Add file → Upload files**, glisser `index.html` (et ce `README.md`), puis **Commit changes**.
3. Aller dans **Settings → Pages → Build and deployment → Deploy from a branch**, choisir `main` et `/ (root)`, puis **Save**.
4. Après 1 à 2 minutes, le site est à `https://VOTRE-NOM.github.io/portfolio-sbi4u/`.

## Mettre à jour le site
- **Remplacer le fichier** : dans le dépôt, **Add file → Upload files**, glisser le nouvel `index.html` (même nom), puis **Commit changes**.
- **Changer un texte** : ouvrir `index.html` sur GitHub, cliquer sur le crayon (Edit), modifier le texte, puis **Commit changes**.
- Le site se met à jour en quelques minutes. Si l'ancienne version s'affiche encore, actualiser la page (Cmd + Shift + R sur Mac).

## Photos et cartes conceptuelles
Les images sont intégrées directement dans `index.html`. Pour en changer ou en ajouter (unités 3, 4 et 5, photos 2 et 3 de la galerie), il faut générer un nouvel `index.html` avec les nouvelles images, puis le remplacer sur GitHub.

## Bouton « Modifier le contenu »
Ce bouton est caché pour les visiteurs. Il apparaît si on ajoute `?edit` à la fin de l'adresse (ex. `.../portfolio-sbi4u/?edit`). Les changements faits ainsi restent seulement dans le navigateur utilisé et ne modifient pas le site public.

## Avant de rendre le site public
Le site affiche le nom de l'élève et sa ville. Une page publique peut être trouvée par les moteurs de recherche. Vérifier ces informations et le choix d'un site public avec l'enseignant.
