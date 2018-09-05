heroku-buildpack-gifsicle
=========================

Heroku buildpack for gifsicle with lossy-compression support.

Binary for gificle is compiled using the a release on [giflossy's repo](https://github.com/kornelski/giflossy).

Current version: 1.91

Usage
=====

To use, checkout the usage guide on https://github.com/ddollar/heroku-buildpack-multi then add this repo in your `.buildpacks`.

Example:

    $ cat .buildpacks
    https://github.com/heroku/heroku-buildpack-ruby
    https://github.com/bzanchet/heroku-buildpack-giflossy
