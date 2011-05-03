
Introduction
============

collective.recipe.changelogger is a zc.buildout recipe that takes
two KGS files and outputs a changelog.

e.g.

* http://dist.plone.org/release/4.0.4/versions.cfg
* http://dist.plone.org/release/4.0.5/versions.cfg

Usage
-----

You can use this recipe in your buildout like so::

    [changelog]
    recipe = collective.recipe.changelogger
    prev = http://dist.plone.org/release/4.0.4/versions.cfg
    next = http://dist.plone.org/release/4.0.5/versions.cfg
