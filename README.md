
This directory contains some C extensions modules for
the ADS python library.

Test:
========
% python setup.py test

Compile:
========
% python setup.py build

Install:
========
% python setup.py install

this will create a directory ../ads/plat-<platform>
and copy the modules to that directory.

Then, if the main directory for the ads library, ( the one 
containing this src/ directory ) is in the python path, the
instruction:

>>> import ads.Looker

should load the module Looker.so. You can, of course, change Looker
by the name of any of the modules in this directory
