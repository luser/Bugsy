
0.4.0 / 2014-12-05
==================

 * Add in the ability to use change history fields for searchings
 * allow searching to handle time frames
 * Change UserAgent for bugsy to that Bugzilla knows that it is us calling. Fixes #4
 * Add version added to comments documentation
 * Add documenation for comments

0.3.0 / 2014-07-14
==================

 * Updated Documentation
 * Fix adding comments to bugs that already exist. Fixes #2
 * Give the ability to search for multiple bugs which allows changing the fields returned
 * Only request a small number of fields from Bugzilla. Fixes #3
 * Initial Comments API design

0.2.0 / 2014-06-26
==================

 * Added the ability to search Bugzilla
    * Set include_fields to have defaults as used in Bugs object
    * Add the ability to search whiteboard
    * Add the ability to search summary fields
    * Add in the ability to search for bugs assigned to people

0.1.0
==============================

 * Initial implementation