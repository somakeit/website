So Make It Website
==================

This repo holds the So Make It website's source code. Please feel free
to submit small pull requests e.g. to fix typos/correct wording. If you
want to make larger changes, probably best to discuss it on the mailing
list first.

Website pages to be published should be stored in the `public` folder -
other resources (that should not be published) can be stored elsewhere
in this repository - for example CoffeeScript source files or LESS/SASS
stylesheets.

The website is built using [Twitter Bootstrap](http://twitter.github.com/bootstrap/).

How to build
------------

### Have git pull down dependencies:

`git submodule init; git submodule update`

### Install Wintersmith:

`[sudo] npm install -g wintersmith`

### Run the preview server:

`wintersmith preview`

### View it in your browser:

[http://localhost:8080/](http://localhost:8080/)

How to publish
--------------

Sorry, Benjie's not got around to this yet! Why not [nag
him](http://twitter.com/Benjie)?
