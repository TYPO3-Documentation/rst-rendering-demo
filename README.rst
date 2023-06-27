
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

You will now find the rendered files in directory `output` you can view these
files by calling::

    ddev launch Index.html

If you want to try out the bootstrap-based example theme shipped with this repo,
call::

    ddev composer render-example


See what else is possible::

    ddev exec .Build/bin/guides -h

Usage without ddev
==================

#.  Use PHP 8.2
#.  Clone this repository
#.  Run the following::

        composer install
        composer render

See what else is possible::

    .Build/bin/guides -h
