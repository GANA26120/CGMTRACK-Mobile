# CGMTRACK-Mobile — les lanceurs

Ce dépôt public ne contient **que des lanceurs** : des pages qui vont chercher la dernière
version d'une application dans son dépôt privé, avec un jeton GitHub à lecture seule, puis
l'affichent. Aucune donnée, aucun prix, aucune marge ici. Publié par GitHub Pages :

| Adresse | Application | Dépôt privé lu |
|---|---|---|
| `https://gana26120.github.io/CGMTRACK-Mobile/` | CGMTRACK | `GANA26120/CGMTRACK`, fichier `cgmtrack-bureau.html` |
| `https://gana26120.github.io/CGMTRACK-Mobile/chiffrage/` | Chiffrage Gaines HVAC | `GANA26120/CGM-CHIFFRAGE-HVAC-`, fichier `dist/CGM-Chiffrage-Gaines-HVAC.html` |

## iPad / iPhone (une fois, ~3 minutes)

1. Ouvrir l'adresse voulue dans **Safari**.
2. Coller le jeton GitHub demandé (la page explique pas à pas comment le créer : lecture
   seule, dépôt concerné uniquement). Il est mémorisé sur l'appareil. Un seul jeton qui
   coche les deux dépôts suffit aux deux lanceurs : le lanceur Chiffrage essaie d'abord le
   jeton CGMTRACK déjà enregistré.
3. Bouton **Partager** (carré avec flèche) → **Sur l'écran d'accueil**. L'icône apparaît
   comme une application.

À chaque ouverture, l'icône charge la dernière version publiée sur `main` du dépôt privé.
Rien à retélécharger. Les données restent sur l'appareil ; pour passer un devis d'un
appareil à l'autre : **Exporter** puis **Importer**.

## Contenu

- `index.html` : lanceur CGMTRACK.
- `chiffrage/` : lanceur Chiffrage Gaines HVAC (`index.html`, copie de `lanceur.html` du
  dépôt privé), icônes d'écran d'accueil (`icone-180.png`, `icone-512.png`) et
  `manifest.json`. Toute modification se fait dans le dépôt privé (dossier `mobile/`) puis
  se recopie ici.
