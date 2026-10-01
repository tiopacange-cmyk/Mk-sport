# MK Sport – Catalogue en ligne

Site statique (une seule page) qui affiche le catalogue MK Sport à partir de `catalogue.json`.

## Contenu

- `index.html` : le site (HTML, CSS et JavaScript dans un seul fichier).
- `catalogue.json` : les catégories et la liste des photos de chaque catégorie.
- `produits/` : les photos des produits (`01_vintage_01.jpg`, etc.).

Tant qu'une photo n'est pas dans `produits/`, le site affiche une vignette de couleur à sa place.

## Ajouter les photos

Mettre les fichiers `.jpg` dans le dossier `produits/`, avec exactement les noms listés dans `catalogue.json`.
Sur GitHub : ouvrir le dossier `produits`, puis **Add file → Upload files** (100 fichiers maximum par envoi).

## Commandes WhatsApp

Dans `index.html`, renseigner `const WHATSAPP = "..."` avec le numéro au format international,
sans `+` ni espaces. Les boutons « Commander » apparaissent alors automatiquement.

## Voir le site en local

```
python3 -m http.server 8000
```

puis ouvrir http://localhost:8000
