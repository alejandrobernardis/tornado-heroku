Tornado Heroku
==============

A Tornado server skeleton for Heroku platform.

.. image:: https://www.herokucdn.com/deploy/button.png
   :target: `https://heroku.com/deploy?template=https://github.com/alejandrober
   nardis/tornado-heroku`_

Installation
------------

**Automatic installation**:

.. code-block:: bash

    $ pip install tornado-heroku

Tornado Heroku is listed in `PyPI <http://pypi.python.org/pypi/
tornado-heroku/>`_ and can be installed with ``pip`` or ``easy_install``.

**Manual installation**: Download the latest source from `PyPI <http://pypi.
python.org/pypi/tornado-heroku/>`_.

.. parsed-literal::

    tar xvzf tornado-heroku-$VERSION.tar.gz
    cd tornado-heroku-$VERSION
    python setup.py build
    sudo python setup.py install

The Tornado Heroku source code is `hosted on GitHub <https://github.com/
alejandrobernardis/tornado-heroku>`_.


How to use
----------

**Running Locally:**

You need to install `[Python 2.7.x] <http://install.python-guide.org/>`_ and
`[Heroku Toolbelt] <https://toolbelt.heroku.com/>`_.

.. code-block:: shell

    $: git clone https://github.com/alejandrobernardis/tornado-heroku.git
    $: cd tornado-heroku
    $: pip install -r requirements.txt
    $: python server.py

**Deploying:**

.. code-block:: shell

    $: heroku create
    $: git push heroku master
    $: heroku open


License
-------

The MIT License (MIT)

Copyright (c) 2015 Alejandro Bernardis and contributors.  See AUTHORS
for more details.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NON-INFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
