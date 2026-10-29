# Golden Moment — Le carnet des émotions

[Ouvrir la présentation](https://anis929.github.io/golden-moment-lyon/)

Présentation interactive de Golden Moment, création de contenu mariage et événementiel à Lyon et alentours.

- Ouverture animée avec le logo et transition au défilement.
- Portfolio photographique enrichi : mariages, portraits, traditions et cinq photos de séance en couple.
- Carnet interactif : trois regards sur une même séance, avec transitions courtes et accès à sa collection. Le carnet suit le défilement normal de la page.
- Révélations progressives des sections, filtres et lecteur photo avec navigation au clavier.
- Reels Instagram chargés à la demande.
- Formules First Look (3 h), Inoubliable (6 h), Infinity (10 h), shootings et options.
- Quatre messages clients recadrés, avec extraits et lecture des captures originales en grand.
- Parcours de devis en trois étapes, en mode démonstration.
- Affichage adapté aux petits et grands écrans et respect de la préférence de réduction des animations.

## Mode présentation

Le formulaire ne transmet et ne conserve aucune coordonnée. Aucun devis réel, aucune réservation et aucun paiement ne sont effectués. Pour une demande réelle : [@goldenmomentlyon](https://www.instagram.com/goldenmomentlyon/).

## Fichiers

`index.html` contient la présentation autonome, avec ses images, ses polices et ses interactions. `.nojekyll` permet sa publication directe avec GitHub Pages depuis la racine de la branche `main`.

`golden-moment-presentation-sources.zip` contient les sources React et les instructions de compilation. Les photos et le logo sont utilisés pour cette présentation ; aucune licence de réutilisation de ces éléments n’est accordée par ce dépôt.

## Recompiler

Node.js 22.13 ou supérieur est requis.

```sh
npm install
npm run build
```

Le fichier final se trouve dans `dist/index.html`.
