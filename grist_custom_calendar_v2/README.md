# Calendrier BMEO – V2

Améliorations intégrées :
- design plus moderne et plus léger ;
- couleurs pastel attribuées par Service ;
- affichage uniquement des lignes dont `Événement` est vrai/coché ;
- popup renommée « Détail de l’événement » ;
- événement légèrement agrandi au survol ;
- texte visible dans les blocs : Assigné + Service + Description ;
- tooltip enrichi au survol ;
- création d’une nouvelle action avec `Événement` coché par défaut.

## Nouveau mapping Grist obligatoire
En plus des champs précédents, mapper :
- Événement → la colonne booléenne `Événement` de `Toutes les actions BMEO`.

## Mise à jour GitHub
Remplacer simplement l'ancien `index.html` du dépôt par ce nouveau `index.html`, puis valider le commit.
GitHub Pages redéploiera automatiquement le widget.
