cookiecutter-docopt
===================

A python command-line script template, for use with `cookiecutter <https://github.com/audreyr/cookiecutter>`_.

Features
--------

- docopt_ for command-line arguments parsing
- pytest_ for testing.
- The ``bundle`` branch has a vendorized version of docopt.


.. _docopt: http://docopt.org/
.. _pytest: http://pytest.org/latest/

To use this template
--------------------
::

    $ pip install cookiecutter
    $ cookiecutter https://github.com/carlesm/cookiecutter-docopt.git

You will be prompted for basic info (your name, script name, etc.) which will be used in the template.

That's all you need to get started.

Don't want to use docopt?
-------------------------

If you prefer not to use docopt for arguments parsing, simply remove the line ``install_requires=['docopt']`` from ``setup.py`` and remove the docopt code in your script.

Next steps
----------
* Create the Github repo for your project


.. _Tox: http://testrun.org/tox/
.. _Sphinx: http://sphinx-doc.org/


License
-------

`MIT Licensed <http://carlesm.mit-license.org>`_.
