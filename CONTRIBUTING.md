# Contibuting to Vole.cc

## Required gems

You may want to configure RubyGems to not install the unneeded RDoc stuff for each gem. To do that, add a `~/.gemrc` file and insert the following lines:

    install: --no-rdoc --no-ri
    update:  --no-rdoc --no-ri

In Terminal, run these commands to install everything you need:

    sudo gem update --system
    sudo gem install jekyll

## Jekyll server

In Terminal, run the following command to get a server started:

    jekyll serve -w

The server will exist as long as your command is running. By default you go to http://localhost:4000/ to see your Jekyll site.

The ```-w``` argument means *watch* so now whenever you make changes to the filesystem, Jekyll will respond by regenerating a new copy of the site.

## Content

### Templating

* Crash course in Liquid templates: https://github.com/Shopify/liquid/wiki/Liquid-for-Designers
* High-level overview of structured content in Jekyll: http://developmentseed.org/blog/2011/09/09/jekyll-github-pages/
* Look in the ```_layouts``` folder to see all of our templates.
