# Silkway
OptimizedHTML is all-inclusive start HTML5 template with Bootstrap 4 (grid & reboot), Gulp, Sass, Browsersync, Autoprefixer, Clean-CSS, Uglify, Rsync and Bower (libs path) support. The template contains a .htaccess file with caching rules for web server.

The template uses a Sass with Sass or Scss syntax (optional).

---

## Technologies
* `HTML` / `*`
* `CSS` / `Sass` or `Scss`
* `JavaScript` / `jQuery`

## Quickstart
1. `git clone https://github.com/betelgeuseAS/OptimizedHTML-4.git`
2. `cd OptimizedHTML-4` and `npm install` or `npm i`
3. `gulp`

If the tab doesn't open on your own browser, then open your web browser to localhost:3000.

Gulp tasks:
 `gulp`: run default gulp task (sass, js, watch, browserSync) for web development;
 `rsync`: project deployment on the server from dist folder via RSYNC;

## Dependencies
A brief description of each package and the function it will serve (front-end):
* `browser-sync`: time-saving synchronised browser testing
* `gulp`: gulp is a toolkit for automating painful or time-consuming tasks in your development workflow

Rules for working with the starting HTML template
1) All HTML files should have similar initial content as in app/index.html;
2) Template Basic Images Start comment in app/index.html - all your custom template basic images (og:image for social networking, favicons for a variety of devices);
3) Custom Browsers Color Start comment in app/index.html: set the color of the browser head on a variety of devices;
4) Custom HTML comment in app/index.html - all your custom HTML;
5) For installing new jQuery library, just run the command "bower i plugin-name" in the terminal. Libraries are automatically placed in the folder app/libs. Bower must be installed in the system (npm i -g bower). Then place all jQuery libraries paths in the 'libs' task (gulpfile.js);
6) All custom JS located in app/js/common.js;
7) All Sass vars placed in app/sass/_vars.sass | app/scss/_vars.scss;
8) All Bootstrap media queries placed in app/sass/_media.sass | app/scss/_media.scss;
9) All libraries CSS styles placed in app/sass/_libs.sass | app/scss/_libs.scss;
10) Rename ht.access to .htaccess before place it in your web server. This file contain rules for files caching on web server.

## Bug fixes
* `Another`  
You can always use [nvm (Node Version Manager)](https://canonium.com/articles/managing-node-versions-with-windows-nvm)
