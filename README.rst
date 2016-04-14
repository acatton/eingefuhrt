Eingeführt
==========

.. image:: https://travis-ci.org/acatton/eingefuhrt.svg?branch=master
    :target: https://travis-ci.org/acatton/eingefuhrt

German quality import linter and formatter for Python.

::

    $ pip install eingefuhrt
    $ echo from foo import foo, bar, baz | eingefuhrt
    from foo import bar
    from foo import baz
    from foo import foo
