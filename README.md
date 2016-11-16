# Startline

<img src="https://raw.githubusercontent.com/ninefortyone/startline/master/img/logo.png" style="float:right;display:block" height="100">

[@joncarlmatthews](https://twitter.com/joncarlmatthews) [@tom_beavan](https://twitter.com/tom_beavan)

Startline is a super-skinny WordPress Theme that acts as a starting point for new themes that use both [Twitter Bootstrap](http://getbootstrap.com/) and [Font Awesome](http://fontawesome.io/). It also comes bundled with the [HTML5 Shiv](https://github.com/aFarkas/html5shiv) and [Respond.js](https://github.com/scottjehl/Respond) utilities. The CSS is written using [Sass](http://sass-lang.com/) and the packages are managed by [npm](https://www.npmjs.com/).

Requires at least: WordPress 4.6. Tested up to: WordPress 4.6.1

[Download the latest version](https://ninefortyone.co.uk/startline/latest.zip)

## Installation

 - [Download the theme from this ZIP](https://ninefortyone.co.uk/startline/latest.zip)
 - Activate the theme within the WordPress admin panel
 - Get customising.

## Customising

### CSS

Edit the Sass files within the `scss/` directory and run the Sass watch command

`$ sass --watch scss/main.scss:css/main.min.css`

### Favicons

The favicons are generated by [realfavicongenerator.net](http://realfavicongenerator.net/)

### Don't forget

Don't forget to change `screenshot.png` and the theme meta data in `style.css`.

## Contributing

We'd love your help! If you wish to contribute to Startline then fork the repository and create a pull request for any changes you wish to see included.

**Note** to work on the codebase you'll first need to run the build script. This installs all required packages and saves and minifies the CSS files.

```
$ cd wp-content/themes/startline
$ npm run build
```

## Copyright

Startline WordPress Theme, Copyright 2016 Nine Forty One.
Startline is distributed under the terms of the GNU GPL

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

## Third-party resources

Startline Theme bundles the following third-party resources:

Twitter Bootstrap
Licenses: The MIT License (MIT)
Source: http://getbootstrap.com

Font Awesome
License: http://fontawesome.io/license
Source: http://fontawesome.io

HTML5 Shiv, Copyright 2014 Alexander Farkas
Licenses: MIT/GPL2
Source: https://github.com/aFarkas/html5shiv

Respond.js, Copyright 2013 Scott Jehl
Licenses: https://github.com/scottjehl/Respond/blob/master/LICENSE-MIT
Source: https://github.com/scottjehl/Respond

## Changelog

v0.1 Initial release
