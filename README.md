# GuineaGood mini-site

Ce dossier contient le mini-site statique de présentation de l'application GuineaGood.

## Structure

- `index.html` : page d'accueil
- `privacy.html` : page de politique de confidentialité
- `css/styles.css` : styles globaux
- `lang/fr.json` et `lang/en.json` : textes traduits
- `lang/privacy_fr.md` et `lang/privacy_en.md` : contenu de la politique

## Publication GitHub Pages

1. Pousser ce dossier sur la branche `gh-pages` du dépôt GitHub, ou utiliser un dossier `docs/` depuis la branche `main`.
2. Dans GitHub, ouvrir `Settings > Pages`.
3. Sélectionner la source de publication :
   - `Deploy from a branch` ;
   - branche `gh-pages` ;
   - dossier `/` (root).
4. Sauvegarder puis attendre la génération.
5. L'URL publique sera de la forme : `https://guineagood.github.io/`

## Personnalisation

- Remplacez le lien Play Store si le package diffère.
- Mettez à jour le texte dans `lang/fr.json` et `lang/en.json`.
- Adaptez le contenu de la politique dans `lang/privacy_fr.md` et `lang/privacy_en.md`.

## Vérification locale

Ouvrez simplement `index.html` dans un navigateur, ou lancez un petit serveur local :

```bash
cd guinea_WEB
python -m http.server 8000
```

Puis ouvrez : `http://localhost:8000/`
