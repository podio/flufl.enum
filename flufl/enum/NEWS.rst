===================
NEWS for flufl.enum
===================

3.3.1 (2012-01-19)
==================
 * Fix Python 3 compatibility with Sphinx's conf.py ($python setup.py install).


3.3 (2012-01-19)
================
 * Remove the dependency on 2to3 for Python 3 support; support Python 3
   directly with a single code base.
 * flufl.enum.make_enum() is deprecated in favor of flufl.enum.make() which
   provides a better API.  (LP: #839529)
 * Updated to distribute 0.6.19.
 * Moved all documentation to .rst suffix.
 * Make test_deprecations() compatible with Python 3 and Python 2.
 * Removed markup for pylint.
 * Improve documentation to illustrate that enum values with similar names and
   integer representations still do not hash equally.  (Found by Jeroen
   Vermeulen).


3.2 (2011-08-19)
================
 * make_enum() accepts an optional `iterable` argument to provide the values
   for the enums.
 * The .enumclass and .enumname attributes are deprecated.  Use .enum and
   .name instead, respectively.
 * Improve the documentation regarding ordered comparisons and equality
   tests.  (LP: #794853)
 * make_enum() now enforces the use of valid Python identifiers. (LP: #803570)


3.1 (2011-03-01)
================
 * New convenience function `make_enum()`. (Contributed by Michael Foord)
 * Fix `from flufl.enum import *`.
 * Enums created with the class syntax can be pickled and unpickled.
   (Suggestion and basic implementation idea by Phillip Eby).


3.0.1 (2010-06-07)
==================
 * Fixed typo which caused the package to break.


3.0 (2010-04-24)
================
 * Package renamed to flufl.enum.


2.0.2 (2010-01-29)
==================
 * Fixed some test failures when running under 2to3.


2.0.1 (2010-01-08)
==================
 * Fix the manifest and clarify license.


2.0 (2010-01-07)
================
 * Use Sphinx to build the documentation.
 * Updates to better package Debian/Ubuntu.
 * Use distribute_setup instead of ez_setup.
 * Rename pep-xxxx.txt; this won't be submitted as a PEP.
 * Remove dependencies on nose and setuptools_bzr
 * Support Python 3 via 2to3.


Earlier
=======

Try `bzr log` for details.
