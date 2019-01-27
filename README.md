# Diaporama simple
Module jQuery

## Installation
* A besoin de jQuery pour fonctionner.
* Inclure le fichier "slider.js" dans votre application.
* Copier la structure HTML du diaporama, située à l'intérieur du fichier "demo-slider.html", puis coller la au sein de votre document (html, php, etc...).
* Au sein de votre fichier JavaScript, il suffit d'écrire : $('#mon_slider').slider(first_creation, animation, add_slide, remove_slide, colorsARR, autoplay, autoplay_interval) où :
- first_creation = true (false pour la version démo),
- animation = 'slideInLeft' (ou tout autre nom de classe CSS pouvant animer vos transitions),
- add_slide = false (true pour la version démo),
- remove_slide = false (true pour la version démo),
- colorsARR = false (true pour la version démo),
- autoplay = true ou false
- autoplay_interval = temps de défilement entre chaque slide, exprimé en millisecondes.

## Built with
* JavaScript
