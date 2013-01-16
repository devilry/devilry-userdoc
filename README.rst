Documentation for regular Devilry users. This repo contains
the Sphinx-sources. You can view the build docs here:
https://devilry-userdoc.readthedocs.org/


Build the docs
##############
::

    $ virtualenv .
    $ bin/easy_install zc.buildout
    $ bin/buildout
    $ bin/sphinxbuilder

The output ends up in ``parts/docs/html/index.html``.
