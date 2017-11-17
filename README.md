# html & css

## pré-requis

Avec tous les OS :
- git ([git-scm.com](http://git-scm.com/))
- nodejs & npm ([nodejs.org](http://nodejs.org/))
- bower ([bower.io](http://bower.io/))
- ruby ([ruby-lang.org](http://ruby-lang.org/))
- sass ([sass-lang.com](http://sass-lang.com/))

Avec Windows :
- WAMP ([wampserver.com](http://wampserver.com/))
- Easy Php ([www.easyphp.org](http://www.easyphp.org/))
- MAMP ([mamp.info](http://mamp.info/))

Avec Mac OS :
- MAMP ([mamp.info](http://mamp.info/))

Avec Linux :
- Apache *
- MySql *
- PHP *

Avec Linux, utilisez votre gestionnaire de paquet pour installer les applications.

A = Apache, M = MySql, P = PHP

## install

    git clone https://github.com/jibundeyare/epsi-lille-html-css-2017-2018
    cd epsi-lille-html-css-2017-2018

## server

Si ce n'est pas déjà fait, ouvrir un terminal et se rendre dans le dossier de travail. Par exemple :

    cd cours/epsi-lille-html-css-2017-2018

Lancer un serveur web visible localement seulement :

    php -S localhost:8000

Lancer un serveur web visible sur le réseau :

    php -S 0.0.0.0:8000

Si le client http (le navigateur), ne demande aucun fichier particulier, le serveur web renvoie le fichier `index.html` par défaut.

## html

Les entités html servent à afficher du code html. Elles permettent d'afficher les caractères spéciaux du html : `<`, `>`, `"` et `&`.

Les enttités html permettent aussi de protéger un site contre des attaques de type XSS (injection de code js).

## css

Les balises de type "block" occupent tout l'espace disponible en largeur.

Les balises de type "inline" occupent un espace équivalent à la taille de leur contenu.

## sass

Transpiler un fichier sass en feuille de style :

    sass sass/blog.sass css/blog.css

Surveiller et créer automatiquement la feuille de style :

    sass --watch sass:css

Surveiller et créer automatiquement une version compressée de la feuille de style :

    sass --watch --style compressed sass:css

## bower

Démarrer un nouveau projet :

    bower init

Répondez bien `y` à la question suivante :

    ? would you like to mark this package as private which prevents it from being accidentally published to the registry? Yes

Installer bootstrap :

    bower install -S bootstrap

## structure du dossier projet

    dossier projet/
      .sass-cache/
      bower_components/
      css/
        *.css
        main.css
      img/
        *.gif
        *.jpg
        *.png
      js/
        *.js
        main.js
      sass/
        *.sass
        main.sass
      *.html
      bower.json
      index.html

## ressources

- [HTML element reference - HTML | MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
- [CSS reference - CSS | MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
- [Ready to check - Nu Html Checker](https://validator.w3.org/nu/)
- [Service de validation CSS du W3C](https://jigsaw.w3.org/css-validator/)
- [Bootstrap · The world's most popular mobile-first and responsive front-end framework.](https://getbootstrap.com/docs/3.3/)
- [Beautiful Free Images | Unsplash](https://unsplash.com/)
- [iconmonstr - Free simple icons for your next project](https://iconmonstr.com/)
- [Font Awesome, the iconic font and CSS toolkit](http://fontawesome.io/)
- [Free Fonts! Legit Free & Quality » Font Squirrel](https://www.fontsquirrel.com/)
- [Create Your Own @font-face Kits » Font Squirrel](https://www.fontsquirrel.com/tools/webfont-generator)
- [Google Fonts](https://fonts.google.com/)
- [Bower — a package manager for the web](https://bower.io/)
- [Sass: Install Sass](http://sass-lang.com/install)
- [Sass Documentation](http://sass-lang.com/documentation/file.SASS_REFERENCE.html)
- [Character Entity Reference Chart](https://dev.w3.org/html5/html-author/charref)
- [test htmlentities online - PHP string functions - functions-online](https://www.functions-online.com/htmlentities.html)
- [Sticky Footer, Five Ways | CSS-Tricks](https://css-tricks.com/couple-takes-sticky-footer/)
- [Retina Display Media Query | CSS-Tricks](https://css-tricks.com/snippets/css/retina-display-media-query/)

## credits

- file: XIqCQx02E1U9W.gif
  source: [Gif GIFs - Find & Share on GIPHY](https://giphy.com/gifs/XIqCQx02E1U9W)
