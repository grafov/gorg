# Org mode' parser and generator for Go language

The purpose of this library is work with org-mode format inside Go
applications. It would be a part of Diane' organizer.

Features:

* parse org-mode files into Go structures
* functions for manipulating tree nodes inside org-mode tree
* generate org-mode file based on internal Go structures

## What this library wouldn't do?

Converting of org-mode format to another formats (like JSON, HTML,
Markdown and so on) is not a purpose of the library. Use other tools
that do this thing.

## Other projects that allow work with org-mode in Go

* https://github.com/jacobmoe/gorg - library that converts org-mode to JSON, HTML
* https://github.com/niklasfasching/go-org - org-mode parser and static site generator
