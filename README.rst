This is a quick and dirty BBEdit/TextWrangler language module for the `Rust language`_.
Since Rust's syntax is still in flux, this is based off the existing
documentation and some inferences from reading the compiler source code.
Patches welcome!

Features
========

* Keyword, string, and comment highlighting
* Function scanning with folding support

Installation
============

To install the module with BBEdit, copy ``rust.plist`` into ``~/Library/Application
Support/BBEdit/Language Modules``.

To install with TextWrangler, copy ``rust.plist`` into ``~/Library/Application
Support/TextWrangler/Language Modules``.

Optionally add a custom extension mapping (suffix ".rs") in **Preferences > Languages**.

Author
======

Erik Rose. Suggestions? Mail erik att mozilla dott com.

.. _`Rust language`: http://www.rust-lang.org/
