# Tutos PRONOTE — Collège Jean Lafosse

Portail de tutoriels illustrés en français pour les enseignants. Interface aux couleurs de PRONOTE, grands boutons, lecture en trois étapes et téléchargement du PDF original.

## Fichiers

- `index.html` : page d’accueil complète et catalogue des tutoriels.
- `tableau-resultats.html` : tutoriel complet en trois étapes illustrées.
- `styles.css` : présentation, adaptation aux téléphones et impression.
- `tutoriels/tableau-resultats.pdf` : PDF original fourni, conservé sans modification.
- `tutoriels/capture-000.png` à `capture-002.png` : captures extraites du PDF original.

Le site fonctionne sans JavaScript, police externe ni compte applicatif.

## Publier avec GitHub Pages

1. Dans le dépôt, ouvrir **Settings**, puis **Pages**.
2. Sous **Build and deployment**, choisir **Deploy from a branch**.
3. Sélectionner la branche **main** et le dossier **/(root)**.
4. Cliquer sur **Save**, puis attendre la fin de la publication.

GitHub affichera l’adresse du site dans cette même page. L’adresse attendue après activation est https://97411-code.github.io/TUTO-PRONOTE/ .

Le fichier `.nojekyll` permet de servir directement les fichiers statiques.

## Consulter localement

Ouvrir le fichier complet `index.html` dans un navigateur. Pour servir le dossier par HTTP :

```bash
python3 -m http.server 8000
```

Ouvrir ensuite http://localhost:8000 .

## Ajouter un tutoriel

1. Placer son PDF dans `tutoriels/`, avec un nom simple sans espace.
2. Copier le fichier complet `tableau-resultats.html` sous un nouveau nom.
3. Adapter son titre, ses instructions, ses captures, ses ancres et ses liens de téléchargement à partir du document d’origine.
4. Ajouter une carte complète dans `index.html`, puis mettre à jour le nombre de tutoriels.
5. Vérifier les liens et la lisibilité sur ordinateur et téléphone.

Utiliser des captures sans noms ni données permettant d’identifier les élèves.

## Documentation officielle

- [Publication depuis une branche avec GitHub Pages](https://docs.github.com/fr/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
- [Élément HTML a et téléchargement — MDN](https://developer.mozilla.org/fr/docs/Web/HTML/Reference/Elements/a)

Ressource du collège indépendante d’INDEX ÉDUCATION.
