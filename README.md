# jekyll-site-bootstrap4

Jekyll Site with Bootstrap 4
----------------------------

This site is using jekyll and Bootstrap 4.

Bootstrap, jQuery and Popper.js are installed like in any Node.js powered apps with the npm package.

BootstrapCDN is also used to deliver cached version of Bootstrap’s compiled CSS and JS with CDN versions of jQuery and Popper.js.

## There are 2 branches:
- master: import bootstrap SASS into assets/css/main.scss from _sass/css/bootstrap (a copy from node_modules)
- gh-pages: import bootstrap SASS directly from node_modules into assets/css/main.scss. Then include node_modules as load_paths in _config.yml.

* The GitHub Pages site is being built from either master or the gh-pages branch

## What has been implemented
* Bootstrap, Cutomized Sass and Sass variables
* Navigation
* custom 404 page
* Use of layouts and include files 
* Combination of Markdown, HTML, and Liquid syntax


## Testing locally

To test the site locally:

From the root of project run the commands:

1. `jekyll build`
2. `jekyll serve`

<hr>

## References

- [simpleit.rocks]
(https://simpleit.rocks/ruby/jekyll/tutorials/how-to-add-bootstrap-4-to-jekyll-the-right-way/).

- [webnots]
(https://www.webnots.com/bootstrap-4-navbar-tutorial/).
