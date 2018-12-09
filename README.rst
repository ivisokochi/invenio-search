..
    This file is part of Invenio.
    Copyright (C) 2015-2018 CERN.

    Invenio is free software; you can redistribute it and/or modify it
    under the terms of the MIT License; see LICENSE file for more details.

================
 Invenio-Search
================

.. image:: https://img.shields.io/github/license/RCOSDP/invenio-search.svg
        :target: https://github.com/RCOSDP/invenio-search/blob/master/LICENSE

.. image:: https://img.shields.io/travis/RCOSDP/invenio-search.svg
        :target: https://travis-ci.com/RCOSDP/invenio-search

.. image:: https://img.shields.io/coveralls/RCOSDP/invenio-search.svg
        :target: https://coveralls.io/r/RCOSDP/invenio-search

.. image:: https://img.shields.io/pypi/v/invenio-search.svg
        :target: https://pypi.org/pypi/invenio-search


Elasticsearch management for Invenio.

Features:

- Allows Invenio modules to register indexes, aliases and index templates.
- Manages the creation and deletion of indices, aliases and templates.
- API for providing stable searches (e.g. prevents bouncing of search results).
- Maps JSONSchema URLs to Elasticsearch indexes.
- Supports Elasticsearch v2, v5 and v6.

Further documentation is available at https://invenio-search.readthedocs.io/.
