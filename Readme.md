Tonka
=====
**Tonka** builds and destroys static HTML sites.

Installation
--------

To install **Tonka** use the following command:

```
$ gem install tonka

```


Getting Started
------

To build a blank, basic static site use:

```
$ tonka build SITE_NAME

```

To include the jQuery library, use:

```
$ tonka build SITE_NAME -jquery

```

To add some text to the body element of the index.html file, use:

```
$ tonka build SITE_NAME -jquery BODY_TEXT

```