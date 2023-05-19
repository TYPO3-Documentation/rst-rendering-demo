
=======================================
RST Rendering with phpDocumentor/guides
=======================================

Usage with ddev
===============

#.  Install docker and ddev
#.  Clone this repository
#.  Run the following::

        ddev start
        ddev composer install
        ddev composer render

Usage without ddev
==================

#.  Use PHP 8.2
#.  Clone this repository
#.  Run the following::

        composer install
        composer render

See what else is possible::

    .Build/bin/guides -h
