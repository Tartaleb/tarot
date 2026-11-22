# Tarot expliqué simplement

Une petite appli pour tirer les cartes du tarot de Marseille et comprendre chaque carte en mots simples. Elle ne prédit pas l'avenir : c'est un outil pour réfléchir, et un jeu.

## Ce qu'elle fait

- Quatre tirages : la carte du jour ; passé, présent, futur ; situation, obstacle, conseil ; le tirage en croix, avec sa 5e carte calculée.
- Chaque carte retournée est expliquée selon sa place : son sens, son côté sombre, son conseil, une question pour réfléchir, puis une lecture d'ensemble.
- Un résumé s'affiche au survol d'une carte, ou en la touchant sur téléphone.
- La galerie des 22 arcanes majeurs, avec une fiche détaillée par carte.
- Une page « Comprendre » : à quoi sert un tirage, l'effet Barnum, l'histoire du tarot, les arnaques à éviter.

## L'utiliser

- **En ligne** : une fois GitHub Pages activé (voir plus bas), l'appli est à l'adresse https://tartaleb.github.io/tarot/
- **Sur Android** : ouvre l'adresse dans Chrome, puis menu ⋮ → « Installer l'application » (ou « Ajouter à l'écran d'accueil »). Elle s'ouvre ensuite comme une appli, même sans connexion.
- **Sur PC** : ouvre l'adresse dans Chrome ou Edge, puis clique sur « Installer l'appli » en haut de la page, ou sur l'icône d'installation dans la barre d'adresse.
- **Sur PC sans internet** : télécharge le dépôt (bouton **Code** → **Download ZIP**), dézippe-le et double-clique sur `index.html`.

## Activer l'adresse en ligne (une seule fois)

Dans ce dépôt : **Settings** → **Pages** → *Build and deployment* → Source : **Deploy from a branch**, Branch : **main** et **/ (root)** → **Save**. Après une ou deux minutes, l'adresse s'affiche en haut de la page Pages.

## Mettre à jour l'appli

Après une modification de `index.html`, change le numéro de version dans `sw.js` (`tarot-v1` → `tarot-v2`) pour que les applis déjà installées récupèrent la nouvelle version.

## Les fichiers

| Fichier | Rôle |
|---|---|
| `index.html` | Toute l'appli : textes, dessins des cartes, code et polices intégrées |
| `manifest.webmanifest`, `icon-*.png` | Ce qui permet de l'installer sur Android et PC |
| `sw.js` | Le cache qui la fait marcher hors ligne |
| `licences/` | Licences des polices |

## Crédits

Dessins originaux inspirés du tarot de Marseille. Polices : IM Fell English (numérisée par Igino Marini) et Alegreya Sans (Huerta Tipográfica), sous licence SIL Open Font License 1.1.
