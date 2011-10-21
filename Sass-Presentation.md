!SLIDE
<link href="/stylesheets/screen.css" media="screen, projection" rel="stylesheet" type="text/css" />
#WHAT IS SASS?#

Sass is an extension of CSS3, adding nested rules, variables, mixins, selector inheritance, and more.

!SLIDE

#FEATURES#

* Variables
* Nesting
* Mixings
* Selector Inheritance

!SLIDE

#INSTALLATION#

###Windows###

	$ gem install compass

### OSX & Linux ###

	$ sudo gem install compass

!SLIDE

#DEMO#

	$ compass create ~/desktop/my_project


###config.rb file###

	# Require any additional compass plugins here.

	# Set this to the root of your project when deployed:
	http_path = "/"
	css_dir = "stylesheets"
	sass_dir = "sass"
	images_dir = "images"
	javascripts_dir = "javascripts"

	preferred_syntax = :scss

!SLIDE

#COMPASS WATCH#

	$ cd ~/desktop/my_project

	$ compass watch

Stop the watcher by hitting **Ctrl-C**

!SLIDE

#WHAT ABOUT LESS?#

I don't know.

Here's a [good comparison](https://gist.github.com/674726) by Chris Eppstein .

!SLIDE

##RESOURCES##

* [Sass](http://sass-lang.com/)
* [The Sass Way](http://thesassway.com/)
* [Compass](http://compass-style.org/)
* [Compass for Designers](http://sonspring.com/journal/sass-for-designers)

!SLIDE

##TOOLS##

* [Scout](http://mhs.github.com/scout-app/)
* [LiveReload](http://livereload.com/)