# Setup

Clone and install dependencies

    git clone git@github.com:jsteiner/mockup.git
    cd mockup
    bundle install

I already installed bourbon, neat and bitters (meaning you don't have to run
these in this repo). If you create your own projects, you will have to install
them yourselves:

    cd stylesheets
    bourbon install
    neat install
    bitters install

Start the sass server to watch and compile sass to css:

    sass --watch stylesheets:public

## Bourbon

Useful sass mixins that simplify styles. Neat and Bitters depend on this.

*Don't* change anything in the generated `bourbon` directory.

* [bourbon docs]

## Neat

Used for layouts and positioning.

*Don't* change anything in the generated `neat` directory.

* [neat examples]
* [neat docs]

## Bitters

A simple scaffold of styles, variable, and structure. Drop it into your project
for a small amount of default styling that you can work off of.

*Do* change things in the generated `bitters` directory.

* [bitters default styles]

## Refills

Reuseable components that you can paste into your project for common interface
elements like navigation, accordions, badges, etc.

Copy and paste the HTML and CSS for these into your project.

* [refills]

[bourbon docs]: http://bourbon.io/docs/
[neat examples]: http://neat.bourbon.io/examples/
[neat docs]: http://neat.bourbon.io/docs/
[bitters default styles]: http://bitters.bourbon.io/example.html
[refills]: http://thoughtbot.github.io/refills/
