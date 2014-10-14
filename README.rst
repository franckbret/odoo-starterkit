Odoo Starter Kit
================

--------------------------------------------
A base buildout for starting an Odoo project 
--------------------------------------------

This buildout use  `Anybox recipe Odoo <https://pypi.python.org/pypi/anybox.recipe.odoo>`_ 

If you miss some system dependencies, see http://anybox.fr/blog/debian-package-helpers-for-openerp-buildouts

Or run it through vagrant, see https://github.com/franckbret/vagrant-salt-odoo

For odoo recipe common scenario usage see http://docs.anybox.fr/anybox.recipe.openerp/trunk/
and https://github.com/gracinet/opendays-2014

Bootstrap the project
----------------------

    python bootstrap.py

Build it
--------

    ./bin/buildout

Init and run a project
----------------------

    ./bin/upgrade_openerp -d yourdatabase

    ./bin/start_openerp -d yourdatabase

