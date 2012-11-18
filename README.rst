Quill Utilities
===============

Nicholas A. Knouf

Version 0.01

http://zeitkunst.org

A few utilities for parsing Quill files (https://code.google.com/p/android-quill/) into SVGs or PDFs.

Usage
=====

parse_quill.py -f FILENAME

This is take a given Quill file (with .quill extension), create a new directory based on the name of the notebook, and generate a set of SVGs for each page. Converting this into a PDF can then be done with a separate program.

Caveats
=======

This requires the python-cairo bindings to be installed.

This was done quickly and does not have as much error checking as there should be.

The script doesn't currently deal with earlier Quill formats.

The script doesn't deal with line art.

TODO
====

* Better error handling

* Incorporate tags into SVG metadata

* Deal with aspect ratios

* Deal with line art

* Deal with images

* Deal with earlier quill formats


