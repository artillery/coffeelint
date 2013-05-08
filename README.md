Artillery coffeelint fork
=========================

Getting started:

    $ git clone git@github.com:artillery/coffeelint.git
    $ cd coffeelint
    $ git remote add upstream git://github.com/clutchski/coffeelint.git
    $ git remote add upstream git://github.com/clutchski/coffeelint.git

Differences from upstream:

  * This README
  * Fixes npm dependencies that reference the github repo directly (e.g. in package.json: `{... "coffeelint": "git://github.com:artillery/coffeelint.git" ...}`) by including compiled versions of the package (since the source is excluded from the npm package).

----------------------------

CoffeeLint
==========

CoffeeLint is a style checker that helps keep CoffeeScript code
clean and consistent.

For guides on installing, using and configuring CoffeeLint, head over
[here](http://www.coffeelint.org).

To suggest a feature, report a bug, or general discussion, head over
[here](http://github.com/clutchski/coffeelint/issues/).

[![Build Status](https://secure.travis-ci.org/clutchski/coffeelint.png)](http://travis-ci.org/clutchski/coffeelint)

Disclaimer
----------

I don't have time to devote to this project these days, so if you want to work on it, send me an e-mail and I'll add you to the repo. Or feel free to fork your own version.