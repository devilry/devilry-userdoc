Documentation for regular Devilry users. This repo contains
the Sphinx-sources. You can view the build docs here:
https://devilry-userdoc.readthedocs.org/


Build the docs
##############
::

    $ virtualenv .
    $ bin/pip install zc.buildout
    $ bin/pip install sphinx_rtd_theme
    $ bin/buildout
    $ bin/sphinxbuilder

The output ends up in ``parts/docs/html/index.html``.
