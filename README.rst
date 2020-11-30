⛔️ DEPRECATION WARNING
======================

This library is deprecated and archived. This repository has been archived and is no longer supported — use it at your own risk. This repository may depend on out-of-date libraries with security issues, and security updates will not be provided. Pull requests against this repository will also not be merged.

Please use https://github.com/edx/frontend-component-footer instead.

frontend-component-site-footer
=========================

|Build Status| |Coveralls| |npm_version| |npm_downloads| |license|
|semantic-release|

frontend-component-site-footer is a library containing a site footer
component for use when building edX frontend applications.

At this time, this component is hard-coded to match the legacy LMS site footer, including all of its links. As implemented, this component should probably be called the ``frontend-component-lms-footer``.

Usage
-----

To install frontend-component-site-footer into your project::

   npm i --save @edx/frontend-component-site-footer

The component expects properties specifying the various URLs that are
linked in the footer. See the sample app in `src/index.jsx <src/index.jsx>`__ for an example
of how the SiteFooter component can be specified.

Requirements
------------

This component uses ``@edx/frontend-i18n``. Any containing app must provide ``@edx/frontend-i18n`` as a peer dependency, and be wrapped inside an ``IntlProvider`` element, whether or not your consuming application is actually localized. For a basic default locale (English) version, follow the ``IntlProvider`` example in the sample application in `src/index.jsx <src/index.jsx>`__.

Development
-----------

Start the dev server::

   npm i && npm start

Build the component::

   npm run build

.. |Build Status| image:: https://api.travis-ci.org/edx/frontend-component-site-footer.svg?branch=master
   :target: https://travis-ci.org/edx/frontend-component-site-footer
.. |Coveralls| image:: https://img.shields.io/coveralls/edx/frontend-component-site-footer.svg?branch=master
   :target: https://coveralls.io/github/edx/frontend-component-site-footer
.. |npm_version| image:: https://img.shields.io/npm/v/@edx/frontend-component-site-footer.svg
   :target: @edx/frontend-component-site-footer
.. |npm_downloads| image:: https://img.shields.io/npm/dt/@edx/frontend-component-site-footer.svg
   :target: @edx/frontend-component-site-footer
.. |license| image:: https://img.shields.io/npm/l/@edx/frontend-component-site-footer.svg
   :target: @edx/frontend-component-site-footer
.. |semantic-release| image:: https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg
   :target: https://github.com/semantic-release/semantic-release
