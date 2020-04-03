# SPEL web site

## How to contribute

### Site content

- Most part of the site content is in: `_config.yml`. Please maintain and follow the [YAML sintaxis](https://en.wikipedia.org/wiki/YAML)
- Each section is defined in html files inside: `_includes/`. We use [Bootstrap](https://getbootstrap.com/docs/4.4/getting-started/introduction/).
- In `_layouts/front.html` reorder or remove section as you prefer.

### Upload changes

 - Commit your changes to the **master** brach. You can edit the content directly in GitHub.
 - Create a new [pull request](https://github.com/spel-uchile/spel-site/compare/gh-pages...master?expand=1) to merge **master** into **gh-pages** branch (gh-pages <- master).
 - The merge will be approved by the site maintainers and automatically deployed to https://spel-uchile.github.io/spel-site/

## How to test and deploy locally

The site uses [Jekyll](https://jekyllrb.com/) to generate a static site. GitHub automatically generates and serves the content after each commit to **gh-pages** branch.

Please follow the GitHub documentation about testing a Jekyll site locally: https://help.github.com/en/github/working-with-github-pages/testing-your-github-pages-site-locally-with-jekyll

Or follow this quick setup:

    bundle install --path vendor/bundle
    bundle update github-pages
    bundle exec jekyll serve

# Creative Theme for Jekyll

This site is based on the Jekyll implementation of the [Creative Theme](http://startbootstrap.com/template-overviews/creative/) template by [Start Bootstrap](http://startbootstrap.com).

Creative is a one page Bootstrap theme for creatives, small businesses, and other multipurpose uses.
The theme includes a number of rich features and plugins that you can use as a great boilerplate for your next Jekyll project! 

Originall version: <https://github.com/volny/creative-theme-jekyll/>

See it live in action at <https://volny.github.io/creative-theme-jekyll/>
