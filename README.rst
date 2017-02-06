============
pyxform v0.9
============


I edited https://github.com/SEL-Columbia/pyxform/tree/master/pyxform for tattara
pyxform is a Python library that makes writing XForms for ODK Collect and enketo
easy by converting XLS(X) spreadsheets into XForms. A new user of pyxform should
look at the documentation `here <https://formhub.org/syntax/>`_ or
`here <http://opendatakit.org/help/form-design/xlsform/>`_.

pyxform is used by `opendatakit.org <http://opendatakit.org>`_ and by `formhub.org <http://formhub.org>`_.

* opendatakit.org uses the repo here:
https://github.com/uw-ictd/pyxform

* formhub.org uses the repo here:
https://github.com/modilabs/pyxform

pyxform is a major rewrite of `xls2xform <http://github.com/mvpdev/xls2xform/>`_. 

Running pyxform as a Python script:
===========================

1. install xlrd.

    #On ubuntu these terminal commands should do it:

    easy_install pip

    pip install xlrd

    python setup.py install

2. Run this command:

    python pyxform/xls2xform.py path_to_XLSForm output_path

Testing
=======
To make sure the install worked out, you can do the following::

	pip install nose==1.0.0

	cd your-virtual-env-dir/src/pyxform

	nosetests

Documentation
=============
To check out the documentation for pyxform do the following::

	pip install Sphinx==1.0.7

	cd your-virtual-env-dir/src/pyxform/docs

	make html

Change Log
=========
https://github.com/UW-ICTD/pyxform/blob/master/CHANGES.txt
