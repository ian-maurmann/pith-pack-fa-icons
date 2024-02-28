# pith-pack-fa-icons
Pack Font Awesome 4 and the free version of Font Awesome 6 for Pith




-------

# About

This project packs Font Awesome 4 and the free version of Font Awesome 6 so that they can be used with the Pith Framework. 

(If you're using the paid version of Font Awesome 6, you can use this repo as a how-to)

For info on Font Awesome, see the Font Awesome website at https://fontawesome.com

For info on Pith, see the Pith website at https://pith-framework.org/

# Install

Install to an existing Pith Framework project

Use Composer to install pack to the `vendor` folder.
```bash
php composer.phar require pith-front/pith-pack-fa-icons
```

Add new route to your Route List:

```php
public array $routes = [
    // Other routes....
    // ...
    
    // Add route to call Font Awesome resource-pack resources from
    ['route', 'GET', '/resources/vendor/library/font-awesome/{filepath:.+}', '\\PithFront\\PithPackFaIcons\\FaIconsResourceRoute'],
];
```

-------------


# Licensing Info

### Font Awesome 4
- Font Awesome 4
- Author: Dave Gandy (@davegandy)
- Font License: **SIL OFL 1.1**,
- CSS License: **MIT License**. (See https://fontawesome.com/v4/license/).
- Documentation License: **Creative Commons: CC BY 3.0** - (Documentation License applies to all Font Awesome project files that are not a part of the Font or Code licenses).
- *All brand icons are trademarks of their respective owners. The use of these trademarks does not indicate endorsement of the trademark holder by Font Awesome, nor vice versa. Brand icons should only be used to represent the company or product to which they refer. Please do not use brand logos for any purpose except to represent that particular brand or service.*
- Website: https://fontawesome.com/v4/icons/

### Font Awesome 6 free version
- Font Awesome 6 free version for web
- Author: Dave Gandy (@davegandy)
- Website: https://fontawesome.com/
- License: Font Awesome Free License (https://fontawesome.com/license/free)
- License for Icons: CC BY 4.0 License ---- In the Font Awesome Free download, the CC BY 4.0 license applies to all icons packaged as .svg and .js files types.
- License for Fonts: SIL OFL 1.1 License ---- In the Font Awesome Free download, the SIL OFL license applies to all icons packaged as web and desktop font files.
- License for Code: MIT License ---- In the Font Awesome Free download, the MIT license applies to all non-font and non-icon files.

### Font Awesome 4 Compatibility Fork
- Font Awesome 4.7.0 compatibility fork
- (Simple find-and-replace of .fa* to .fa4* by Ian Maurmann, to files created by Dave Gandy and released under the MIT license)
- Purpose of fork: To enable Font Awesome 4 icons to be used alongside Font Awesome 5 and 6.
- In most countries, not a substantial-enough change to affect copyright, so follow the licenses that Font Awesome 4.7.0 is released under.
- In countries where this is subject to copyright, it is hereby released under the same licenses that Font Awesome 4.7.0 is released under.
- Link: https://github.com/ian-maurmann/fa4-compatibility-fork/

### pith-pack-fa-icons
- pith-pack-fa-icons
- The MIT License (MIT)
- Copyright (c) Ian Maurmann
- Link: https://github.com/pith-front/pith-pack-fa-icons






