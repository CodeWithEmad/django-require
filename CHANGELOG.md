django-require changelog
========================

Unreleased
----------

* Updating almond to 0.3.1


1.0.7 - 26/02/2015
------------------

* Added in OptimizedManifestStaticFilesStorage.
* Updating requirejs to 2.1.16.
* Updating r.js to 2.1.16.
* Updating almond to 0.3.0
* Updating closure compiler to v20150126.
* Updating rhino to 1.7R5.


1.0.6 - 10/04/2014
------------------

* Increasing stack size of Rhino environment.
* Updating requirejs to 2.1.11.
* Updating r.js to 2.1.11.
* Updating almond to 0.2.9
* Updating closure compiler.


1.0.5 - 12/11/2013
------------------

* Updating requirejs to 2.1.9
* Updating r.js to 2.1.9
* Updating almond to 0.2.6
* Updating closure compiler.
* Restructures tests to work with Django 1.6.


1.0.4 - 27/07/2013
------------------

* Updating requirejs to 2.1.8
* Updating r.js to 2.1.8
* Updating closure compiler.


1.0.3 - 25/04/2013
------------------

* Added ability to specify custom compiler environments, either by class name or alias.
* Added default 'auto' environment alias, which uses 'node' if available, else 'rhino'.
* Updating requirejs to 2.1.5
* Updating closure compiler.


1.0.2 - 25/02/2013
------------------

* Not adding build profiles to REQUIRE_EXCLUDE during compilation, to speed up redeploys to remote filesystems.
* Updating requirejs to 2.1.4
* Updating almond to 0.2.5
* Updating closure compiler to r2388 
* Updating rhino to 1.7R4.


1.0.1 - 30/11/2012
------------------

* Support for running the optimizer using node (much faster).
* Updating to RequireJS 2.1.2 and almond 0.2.1
* Better error message when no STATICFILES_DIRS are defined.


1.0.0 - 01/11/2012
------------------

* First production release.
