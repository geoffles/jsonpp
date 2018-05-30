JSONPP - Pretty print your JSON
===============================

This is a simple stream enabled JSON pretty printer that uses pure bash script.

Currently does not support any of `{}[],` in strings.

Installation
------------

Copy to any location in your $PATH and allow exec permissions.

Usage
-----

*Piping:* `cat my.json | jsonpp`

*File indirection:* `jsonpp < my.json`

TODO
----

Add escape support