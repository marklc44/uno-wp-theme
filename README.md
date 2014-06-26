# Uno WP Theme
<em>Beta.</em>
This theme is built with Bootstrap, Wordpress and [Shuffle.js](http://vestride.github.io/Shuffle/), and used on [my portfolio site](http://markcentoni.com). It's the first theme I've built from scratch, so it needs some refactoring and has some bugs. Use it at your own peril ;)

## Highlights
+ Responsive
+ Single page site and multi-page site options
+ Shuffle.js filtering for smooth animation of grid items
+ Custom post types and taxonomy for Portfolio and About section items


A stable(r) version with improved performance, bug fixes and a couple more features will be available in winter 2014.

## Known Issues
1000000: must hardcode links in admin panel > menus for header-menu-alt. Programatically add links to home page IDs.
1000001: Shuffle.js on IE < 10 projects and blog posts listed in one column. Generated translateX = 0, so all items are pulled to left.
1000002: Refactor JS.
1000003: Too many favicon icons slowing down loading.
1000004: jQuery loaded multiple times and loading in the head by Wordpress. Slowing loading.
1000005: Responsive nav open and close not smooth...custom behavior fights with Bootstrap default behavior causing a flash of different styling during transitions.