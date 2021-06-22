Viewport
======================

The Viewport module is a simple module that allows administrators, or users
with the "Administer Viewport Settings" permission, to set a Viewport HTML
metatag with the desired properties for one or several pages that can be
configured from the Settings page of the module.

The aim of the module is to provide an easy way to debug or test websites or
apps, as well as responsive designs on smartphones and tablets. This is *NOT* a
complete suite of tools to work with when delivering this kind of design / apps,
but a small utility to help with one specific aspect of responsive design.

Sometimes, one may need to set specific viewport values for a specific page on
the site (e.g when embedding a game for smartphones / tablets). This tool
helps to chase easily situations like that.

Requirements
------------

This module requires that the following modules are also enabled:

No requirements.

Installation
------------

- Install this module using the official Backdrop CMS instructions at
  https://backdropcms.org/guide/modules.

- Navigate to "admin/people/permissions" and assign
     the "Administer Viewport Settings" permission to the desired roles.

- Navigate to "admin/config/user-interface/viewport", and set the desired
     values for the different viewport properties.

- In the textarea provided, enter the paths (oner per line) for which you
     want the viewport tag to appear.

- For more information on the Viewport properties and their meanings,
     navigate to "admin/help/viewport".

Documentation
-------------

Additional documentation is located in the Wiki:
https://github.com/backdrop-contrib/viewport/wiki/Documentation.

Issues
------

Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/viewport/issues.

Current Maintainers
-------------------

- [Justin Christoffersen](https://github.com/larsdesigns).
- [jen Lampton](https://github.com/jenlampton).
- Seeking additional maintainers.

Credits
-------

- Ported to Backdrop CMS by [Justin Christoffersen](https://github.com/larsdesigns).
- Current Drupal project maintainer [Salvador Molina](salvador.molinamoreno@codeenigma.com).
- Originally written for Drupal by [Salvador Molina](salvador.molinamoreno@codeenigma.com).
- Originally written for Drupal by [Dmitriy.trt](https://www.drupal.org/u/dmitriytrt).
- Port Sponsored by [Jeneration Web Development](https://www.jenerationweb.com)

License
-------

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.
