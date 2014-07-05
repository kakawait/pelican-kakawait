# Pelican theme Greyshade

Greyshade is a minimal, responsive theme for Pelican.

Starting point forked from [Slash](https://github.com/tommy351/Octopress-Theme-Slash) then forked from (GreyShade)[https://github.com/shashankmehta/greyshade/]. I also picked some code from [Pelican-cait](https://github.com/hdra/pelican-cait).


## Features

* Responsive design.
* Gravatar support thanks to [Zhigang Fang](https://github.com/zhigang1992).
* [Schema.org](http://schema.org/) support thanks to [Nathan Shaughnessy](https://github.com/nathanshox)
* (Pygments style)[http://www.realultimateprogramming.com/solarized-dark-pygments/] based on the dark background variant of [Solarized](http://ethanschoonover.com/solarized)

## TODO

[] [fancyBox](http://fancyapps.com/fancybox/#license)
[] Better [Schema.org](http://schema.org/) integration
[] User the [assets](https://github.com/getpelican/pelican-plugins/tree/master/assets) module
[] socialshareprivacy
[] Disqus comments


## Conditions (from the original greyshade theme)

The only condition to use this theme for your octopress blog is that you have to set a different highlight color than the ones mentioned [here](https://github.com/shashankmehta/greyshade/wiki/Sites-using-Greyshade). When you have chosen a highlight color, please add it to the [wiki](https://github.com/shashankmehta/greyshade/wiki/Sites-using-Greyshade) so that no one else uses it.

Highlight color: This color is used on a:hover, blockquotes etc. I'll be using it in more places so that blogs with different highlight colors look slightly different and maintain a bit of their uniqueness.

## Install

Assuming you have installed the default theme, type the code below in terminal.

    $ git clone git@github.com:2xyo/pelican-theme-greyshade.git
    $ cd pelican-theme-greyshade
    $ echo "\$greyshade: color;" >> sass/custom/_colors.scss // Substitue 'color' with your highlight color
    $ compass compile
    $ cd your-pelican-blog
    $ pelican-themes -s /path/to/pelican-theme-greyshade

For profile picture and description, just add the relevant details in `pelicanconf.py`

##License

MIT: [http://sm.mit-license.org](http://sm.mit-license.org/)
