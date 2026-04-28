# Script_Html_CsS

Collection de demonstrations HTML, CSS, JavaScript et jQuery, organisees comme une galerie de scripts avec apercus, telechargements et menu principal.

## Accueil principal

Le fichier a ouvrir en premier est :

```text
index.htm
```

Il se trouve a la racine du dossier `Script_Html_CsS`.

Ce portail contient :

- 26 cartes de demonstrations
- les miniatures du dossier `apercus`
- un bouton `Ouvrir` vers chaque page `index.htm`
- un bouton `RAR` vers chaque archive du dossier `Download`
- une barre de recherche pour filtrer les scripts
- un menu social et un emplacement `<header></header>` pour le menu injecte

## Organisation

Chaque demonstration est placee dans son propre tiroir/dossier.

Exemples :

- `affichage_cercle_hover`
- `barre_chargement_facebook`
- `bouton_reseaux_sociaux`
- `effet_texture`
- `fenetre_modale`
- `formulaire_login_compact_noir`
- `image_effet_hover_1`
- `slideshow`

Les pages principales des demonstrations se trouvent generalement ici :

```text
nom_du_tiroir/nom_du_tiroir/index.htm
```

## Apercus

Le dossier `apercus` contient les miniatures utilisees par le portail principal.

Les images portent le meme nom que les tiroirs, par exemple :

```text
apercus/slideshow.png
apercus/fenetre_modale.png
apercus/bouton_poussoir.png
```

## Telechargements

Le dossier `Download` contient les archives `.rar`.

Chaque page `index.htm` de tiroir possede un gros bouton de telechargement qui pointe vers l'archive correspondante :

```text
Download/nom_du_tiroir.rar
```

Le portail principal propose aussi un bouton `RAR` pour chaque demonstration.

## Navigation

Chaque page `index.htm` dans les tiroirs contient :

- le menu social
- le menu injecte via `<header></header>`
- un bouton futuriste `RETOUR AU MENU INDEX`
- un bouton de telechargement RAR

Les liens `FERMER LA FENETRE` ont ete corriges. Ils tentent de fermer la fenetre avec JavaScript, puis redirigent vers le portail principal si le navigateur bloque la fermeture.

## Fichiers externes relies

Les pages utilisent plusieurs fichiers externes heberges sur `filedn.eu` :

- `Site_Web/style.css`
- `Site_Web/script.js`
- `Site_Web/menu.js`
- `Site_Web/basedusite.css`
- `Site_Web/couleurs.js`
- favicon PNG et ICO

## Notes

Ce dossier sert de galerie de scripts reutilisables pour effets visuels, boutons, formulaires, menus, slideshows et animations HTML/CSS/JavaScript.
