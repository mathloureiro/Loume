# Loume & Gromf

Loume is a WordPress starter theme based on [Roots](https://github.com/roots/roots) 7.0, using [Foundation](http://foundation.zurb.com) & [Gulp](http://gulpjs.com) instead of Bootstrap & Grunt.


## Features

Since Loume is heavily based on [Roots](https://github.com/roots/roots), most of the features apply to Loume, except for Grunt & Bootstrap features. Some of the features are:

* [Gulp](http://gulpjs.com) for compiling SCSS to CSS, checking for JS errors, live reloading, concatenating and minifying files
* [Bower](http://bower.io/) for front-end package management(Foundation, Modernizr, jQuery)
* [HTML5 Boilerplate](http://html5boilerplate.com/)
	* An optimized Google Analytics snippet
* Organized file and template structure
* ARIA roles and microformats
* [Theme activation](http://roots.io/roots-101/#theme-activation)
* [Theme wrapper](http://roots.io/an-introduction-to-the-roots-theme-wrapper/)
* Cleaner HTML output of navigation menus
* [Multilingual ready](http://roots.io/wpml/) and over 30 available [community translations](https://github.com/roots/roots-translations)

### Additional features

Install the [Soil](https://github.com/roots/soil) plugin to enable additional features:

* Root relative URLs
* Nice search (`/search/query/`)
* Cleaner output of `wp_head` and enqueued assets markup
* Image captions use `<figure>` and `<figcaption>`


## Installation

Before you start using Loume make sure you have [NodeJS](http://nodejs.org), [Bower](http://bower.io) and [Gulp](http://gulpjs.com) installed. If you already have NodeJS installed then just run `npm install -g bower gulp`

Then:

* Clone the git repo - `git clone https://github.com/mathloureiro/Loume.git && cd Loume`
* `npm install`
* `bower install`
* `gulp`
* Profit!


## Theme activation

Reference the [theme activation](http://roots.io/roots-101/#theme-activation) documentation to understand everything that happens once you activate Roots.

## Configuration

Edit `lib/config.php` to enable or disable theme features and to define a Google Analytics ID.

Edit `lib/init.php` to setup navigation menus, post thumbnail sizes, post formats, and sidebars.

## Documentation

Since Loume is heavily based on [Roots](https://github.com/roots/roots), 90% of the documentation are relevant.

* [Roots 101](http://roots.io/roots-101/) — A guide to installing Roots, the files, and theme organization
* [Theme Wrapper](http://roots.io/an-introduction-to-the-roots-theme-wrapper/) — Learn all about the theme wrapper
* [Build Script](http://roots.io/using-grunt-for-wordpress-theme-development/) — A look into how Roots uses Grunt
* [Roots Sidebar](http://roots.io/the-roots-sidebar/) — Understand how to display or hide the sidebar in Roots

## Changlog

  * 0.1 Com a utilização 'gulp build', há a chance de gerar os arquivos necessários e minificado do tema, bastando apenas evia-los ao servidor. 