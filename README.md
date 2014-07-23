jekyll-example
==============

This is a setup example for a jekyll site with [bootstrap](http://getbootstrap.com) installed thanks to [bower](http://bower.io/), and fully hosted on github pages.

See the blog post: <http://www.aymerick.com/2014/07/22/jekyll-github-pages-bower-bootstrap.html>

View the site here: <http://jekyll-example.aymerick.com>


Development
===========

Install tools:

    $ npm install -g grunt-cli
    $ npm install -g bower
    $ gem install bundle

Install dependencies:

    $ npm install
    $ bower install
    $ bundle install

Build the site and watch for changes:

    $ grunt -v

Browse <http://127.0.0.1:4000>

Deploy to Github Pages:

    $ rake deploy
