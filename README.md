# SteveOctets

La vitrine : <https://snouhaud.github.io>

Ce dépôt ne contient que le site d'accueil. Chaque application a le sien, dans son
propre dépôt, avec ses versions publiées et son flux de mises à jour.

| Application | Dépôt | Site |
| ----------- | ----------------------------------------------- | ----------------------------------- |
| Kodama      | [snouhaud/kodama](https://github.com/snouhaud/kodama) | <https://snouhaud.github.io/kodama/> |

## Ajouter une application

1. Créer son dépôt, sur le modèle de `snouhaud/kodama` : `docs/` pour le site servi par
   GitHub Pages, `docs/appcast.xml` pour le flux de mises à jour, les archives en pièces
   jointes de release.
2. Déposer son icône dans `images/`, en PNG de 256 pixels.
3. Copier le bloc `<a class="application">` de `index.html`, et l'adapter.
4. Ajouter une ligne au tableau ci-dessus.

`style.css` est commun aux deux sites, mais chacun en garde sa copie : un site doit
pouvoir vivre sans l'autre.
