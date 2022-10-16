=== bootCommerce Child Theme ===

Contributors: Bastian Kreiter, Justin Kruit

Requires at least: 4.5
Tested up to: 6.0.1
Requires PHP: 5.6
Stable tag: 5.2.0.0
License: MIT License
License URI: https://github.com/bootscore/bootcommerce-child/blob/main/LICENSE


== Description ==

WooCommerce Child Theme for bootScore, Copyright 2019 - 2021 bootScore.

This child theme has already all settings to create a shop. This child needs WooCommerce to work.

Start developing your new project right away in a upgrade-safe way using overrides by copying files from bootScore parent theme.


== Live preview ==

https://bootscore.me/shop/


== Installation ==

WooCommerce must be installed first!

1. In your admin panel, go to Appearance > Themes and click the Add New button.
2. Click Upload Theme and Choose File, then select the theme's .zip file. Click Install Now.
3. Click Activate to use your new theme right away.


== Documentation ==

https://bootscore.me/documentation/using-the-child-themes/


== Changelog ==

    = 5.2.0.0 - July 22 2022 =

        * Removed IE alert hook and updated version in header.php f0ef313
        * Removed navbar-light class
        * SCSS to main.css

    = 5.1.3.1 - January 25 2022 =
    
        * [REMOVED] @import "fontawesome"; in css/scss/bootstrap.min.scss
        * [REMOVED] language folder
        * [ADDED] @import "bscore_woocommerce";
        * [BUGFIX] Fixed class typo #9

    = 5.1.0.2 - October 07 2021 =

        * [UPDATE] header.php (bootscore 5.1.2.0)

    = 5.1.0.1 - September 29 2021 =

        * [IMPROVEMENT] Enqueue styles & scripts
        * [NEW] Added Sass

    = 5.1.0.0 - September 08 2021 =
    
        * [CHANGED] Set path to the new repository name of bootScore parent theme.

    = 5.0.2.2 - August 03 2021 =
    
        * [UPDATE] header.php (bootscore 5.0.2.4)

    = 5.0.2.1 - July 14 2021 =
    
        * [UPDATE] header.php (bootscore 5.0.2.3)

    = 5.0.2.0 - May 31 2021 =
    
        * [UPDATE] Bootstrap 5 Nav Walker (header.php)

    = 5.0.1.3 - May 16 2021 =
    
        * [BUGFIX] Readded jQuery in header.php. Required if a 3rd party plugin loads jQuery in header instead in footer.

    = 5.0.1.2 - May 11 2021 =
    
        * [IMPROVENENT] Removed WP jQuery from header.php
        * [SEO] Removed aria-labelledby="" from offcanvas (thnx Mike Collignon)

    = 5.0.1.1 - April 16 2021 =
    
        * [NEW] Added empty folder css/lib/ to insert your own bootstrap.min.css.

    = 5.0.1.0 - April 12 2021 =
    
        * [UPDATE] header.php for Bootstrap 5.0.0 Beta-3
        * [NEW] Added language folder (languages moves from bootScore parent into language packs later)
        * [IMPROVEMENT] Readded custom.css
        * [IMPROVEMENT] Readded custom.js
        * [IMPROVEMENT] Added readme.txt

    = 5.0.0.2 - March 11 2021 =
    
        * [REMOVED] Removed custom.css
        
    = 5.0.0.1 - February 27 2021 =
    
        * [REMOVED] Removed child.js

    = 5.0.0.0 - February 01 2021 =
    
        * Initial release


