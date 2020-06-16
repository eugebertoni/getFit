# GetFit LandingPage

### Generate `style.css` file by compiling scss files
```
sass --watch assets/styles/style.scss:style.css
```
<br>
<br>

# File architecture
<br>

# Assets directory difination

* **fonts/** - Contains all fonts
* **image/** - Contains all images
* **styles/**
  * **style.scss** - Contains all scss pertials
  * **abstracts/**
    * **_animations.scss** - This file contains all animations.
    * **_variables.scss** - This file contains all application-wide Sass variables.
  * **base/**
    * **_base.scss** - This file contains very basic styles.
    * **_fonts.scss** - This file contains all @font-face declarations, if any.
    * **_grid.scss** - This file contains grid classes.
    * **_typography.scss** - Basic typography style for copy text  
   * **components/** - This directory holds all components partials scss files such as `_buttons.scss` , `_card.scss` , `_modal.scss` ...
   * **layout/** - This directory contains all styles of application layouts such as `_header.scss` , `_footer.scss` etc...
   * **pages/** - Page specific scss partials file will be here.