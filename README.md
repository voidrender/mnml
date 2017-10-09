mnml
====

Another minimal theme for [Octopress](http://octopress.org) based on [whiterspace](https://github.com/mjhea0/whiterspace).

See it live at [Overacker.me](http://overacker.me).

Using mnml?  Consider adding your site to the [wiki](https://github.com/ioveracker/mnml/wiki)!

# Install
    $ cd octopress
    $ git clone git://github.com/ioveracker/mnml.git .themes/mnml
    $ rake install['mnml']
    $ rake generate
    
# Customization

Mnml supports several customizations that can be added to your `_config.yml` file.

## mnml_mailto
If `mnml_mailto` is defined in your config file, your name in the footer will be automatically wrapped in a mailto tag with the given address.

    mnml_mailto: you@example.com
    
## mnml_host_name and mnml_host_url
If you'd like to show your host some love, define the `mnml_host_name` *and* `mnml_host_url` variables in your config file.

    mnml_host_name: Heroku
    mnml_host_url: http://heroku.com
    
This will add a sentence to the end of your footer like this:

Hosted by [Heroku](http://heroku.com).

## Dark Theme
If you'd like to turn down the white, you can enable a dark theme by setting `mnml-dark-theme` to `true` in `octopress/.themes/mnml/sass/custom/_styles.scss` and then running `rake install['mnml']`.  (Thanks to [AaronLenoir](https://github.com/AaronLenoir) for contributing this!)

#Plugins
mnml plays nice with some of the plugins that are out there.

##octopress-responsive-video-embed
The CSS for [octopress-responsive-video-embed](https://github.com/optikfluffel/octopress-responsive-video-embed) is included in the theme, so if you want to use it you only have to copy the Ruby files into your plugins directory.
