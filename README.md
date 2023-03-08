## Instructions pour David
### Ou trouver les informations utiles ?

- Contenu du call to action en page d'accueil: partials/cover.hbs --> Ligne 23
- Contenu du bouton de contact: partials/phone-btn.hbs --> Ligne 5

La plupart des contenus se trouvent dans le dossier Partials. Chaque fichier décrit une petite partie des pages.

### Comment éditer le contenu ?

Sur la page de chaque fichier, tu peux éditer le contenu en cliquant sur l'icone en haut à droite (à côté de RAW / BLAME). Une fois en mode édition, tape le contenu souhaité.

Pour sauvegarder ces changements, en bas de la page, le système demande 3 choses:

- Un titre: pour se rappeler ce que l'on a fait et pourquoi
- Une description: facultatif
- Sur la branche *main* ou sur une nouvelle: toujours choisir *main*

### Comment activer le changement ?

Il n'y a rien à faire. Au bout de 20 à 60s, le site se met à jour.

---
# Edition Wedreadz

The newsletter theme for [Ghost](http://github.com/tryghost/ghost/). This is the latest development version of Edition! If you're just looking to download the latest release, download the theme [here](https://github.com/TryGhost/Edition/archive/refs/heads/main.zip).

&nbsp;

# Development

Edition styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need [Node](https://nodejs.org/), [Yarn](https://yarnpkg.com/) and [Gulp](https://gulpjs.com) installed globally. After that, from the theme's root directory:

```bash
# Install
yarn

# Run build & watch for changes
$ yarn dev
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

The `zip` Gulp task packages the theme files into `dist/<theme-name>.zip`, which you can then upload to your site.

```bash
# create .zip file
yarn zip
```

# PostCSS Features Used

- Autoprefixer - Don't worry about writing browser prefixes of any kind, it's all done automatically with support for the latest 2 major versions of every browser.

# Copyright & License

Copyright (c) 2013-2022 Ghost Foundation - Released under the [MIT license](LICENSE).
