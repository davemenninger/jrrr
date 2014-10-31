# Jrrr: Mojolicious + heroku/proclet

[![Jrr](http://img3.wikia.nocookie.net/__cb20090516105325/en.futurama/images/2/2f/Popplers.jpg)](http://theinfosphere.org/Jrrr)

simplest possible app for local or cloud hosting

## Generate app

The Mojolicious app is generated with:

    $ mojo generate lite_app jrrr

## Usage

### Heroku

See: [kazeburo/heroku-buildpack-perl-procfile](https://github.com/kazeburo/heroku-buildpack-perl-procfile)

Bascially:

    $ heroku create --buildpack https://github.com/kazeburo/heroku-buildpack-perl-procfile.git

    $ git push heroku master

Or:

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

### Locally

See: [proclet](http://search.cpan.org/dist/Proclet/bin/proclet)

Bascially:

    $ proclet start
