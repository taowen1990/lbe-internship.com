# The ETC Creative Good Fund.
### http://www.lbe-internship.com/
### https://github.com/evantahler/lbe-internship.com

## How do I build the site?

this is a static site hosted by [github pages](http://pages.github.com/).  We use [Jekyll](http://jekyllrb.com/) to build the site and test it locally.  Here's a quick guide:

- install [Ruby](http://www.ruby-lang.org/) (comes with OSX)
- [git](http://git-scm.com/) clone this project
- [install](http://gembundler.com/) bundler
- install the gems this project needs with `bundle install`
- run jekyll `jekyll server --watch` which will run this site locally on port 4000.
- running the site will also generate all the static assets for the site in a `_site` folder within this project.

To deploy this site, just push your changes to the `gh-pages` branch.
