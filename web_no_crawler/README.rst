===========================================
Disallow indexing completely via robots.txt
===========================================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:b8b50c8295628a5b4b023b131d53197c549173928c06edbae969ab9bee21ef92
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-LGPL--3-blue.png
    :target: http://www.gnu.org/licenses/lgpl-3.0-standalone.html
    :alt: License: LGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fweb-lightgray.png?logo=github
    :target: https://github.com/OCA/web/tree/12.0/web_no_crawler
    :alt: OCA/web
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/web-12-0/web-12-0-web_no_crawler
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/web&target_branch=12.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

This module was written to implement a robots.txt file to prevent web crawlers (like google) from indexing pages.
This module does not depend on Website module.

**Table of contents**

.. contents::
   :local:

Installation
============

Installation as usual. No specific installation steps / configuration required.

**WARNING:** this module is not to be used with `Website` module as it has a separate functionality for robots.txt.

Usage
=====

To use this module, you need to:

No configuration needed. Once installed adds robots.txt (ex.: http://example.org/robots.txt).

Known issues / Roadmap
======================

* Investigate possibilies for compatibility with `Website` module as it has a separate functionality for robots.txt.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/web/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/web/issues/new?body=module:%20web_no_crawler%0Aversion:%2012.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* Ventor
* Xpansa Group

Contributors
~~~~~~~~~~~~

* Nedas Zilinskas <nedas.zilinskas@xpansa.com> (http://xpansa.com)
* Stefan Rijnhart <stefan@opener.amsterdam>

Other credits
~~~~~~~~~~~~~

The development of this module has been financially supported by:

* Ventor, Xpansa Group (<https://ventor.tech/>)

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

This module is part of the `OCA/web <https://github.com/OCA/web/tree/12.0/web_no_crawler>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
