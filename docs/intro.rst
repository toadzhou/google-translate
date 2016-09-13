Introduction
============

Description
-----------
    Small library to translate text for *free* using Google translate.

.. note:: google_translate is not a replacement of the official Google translate API.

   You should use the official API for large projects.

Features
--------
    * Translate text
    * Retrieve additional translations
    * Retrieve info dictionary
    * Detect the source language
    * Detect typos
    * Text romanization [#f1]_
    * Proxy support
    * Multiple user-agents support
    * Python logging support
    * Caching

Requirements
------------
    * `python 2.7.\* <https://www.python.org/downloads/>`_
    * `twodict <https://pypi.python.org/pypi/twodict>`_
    * `mock <https://pypi.python.org/pypi/mock>`_ (to run the tests)

Installation
------------
    #TODO Pypi

    #TODO Source code

License
-------

    *google-translate* package is distributed under the `UNLICENSE <http://unlicense.org/>`_ license.

Quick start
-----------
    Use GoogleTranslator to translate a word::

        from google_translate import GoogleTranslator

        translator = GoogleTranslator()
        print translator.translate("hello world", "french")

.. rubric:: Footnotes
.. [#f1] Romanization <https://en.wikipedia.org/wiki/Romanization>