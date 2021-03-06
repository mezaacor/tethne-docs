Requirements
============

Tethne is tested in Linux and Mac OSX running Python 2.7. Python
versions earlier than 2.7 are not supported (since
`NetworkX <https://networkx.github.io/>`_ does not support Python < 2.7).

Some users have had luck with Windows, but at this point we don't have plans to
support any Microsoft platforms. If you're interested in taking this on,
however, we welcome your contribution!

Installation
============

You can install the latest release of Tethne directly from the
`Python Package Index <http://python.org/pypi>`_, using
`pip <https://pypi.python.org/pypi/pip>`_.

.. code-block:: bash

   $ pip install -U tethne

If you don't already have pip, it is recommended to install the
`setuptools <https://pypi.python.org/pypi/setuptools>`_ package.

You can install the bleeding-edge development version from the Tethne
`git repository <http://github.com/diging/tethne>`_.

.. code-block:: bash

   $ git clone http://github.com/diging/tethne.git
   Cloning into 'tethne'...
   remote: Counting objects: 1580, done.
   remote: Compressing objects: 100% (1076/1076), done.
   remote: Total 1580 (delta 493), reused 1527 (delta 492), pack-reused 0
   Receiving objects: 100% (1580/1580), 10.89 MiB | 4.40 MiB/s, done.
   Resolving deltas: 100% (493/493), done.
   Checking connectivity... done.
   $ cd tethne
   $ pip install ./

Verify your Tethne version with:

.. code-block:: bash

   $ pip show tethne
   Metadata-Version: 1.0
   Name: tethne
   Version: 1.0
   Summary: Bibliographic network and corpus analysis for historians
   Home-page: http://diging.github.io/tethne/
   Author: Erick Peirson
   Author-email: erick [dot] peirson [at] asu [dot] edu
   License: GNU GPL 3
   Location: /Users/erickpeirson/anaconda/lib/python2.7/site-packages
   Requires: networkx, Unidecode, iso8601, rdflib
