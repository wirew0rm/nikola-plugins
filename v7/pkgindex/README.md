Package Indexes
===============

A set of Nikola plugins to facilitate creation of package indexes.  This plugin
depends on `pkgindex_compiler`, `pkgindex_scan` and `pkgindex_zip`, which
implement the real functionality.

Package indexes are sites like <https://plugins.getnikola.com/>. They provide
both a human-friendly interface (website), and a computer-friendly interface
(JSON file). The generated package indexes are compatible with Nikola’s plugin
and theme install features; however, they can be modified to work with any
other packaging system (with some Python code)
