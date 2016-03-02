Alloy with Jade and Stylus Sample
=================================

Preparation
------------

Require [Jade](https://www.npmjs.com/package/jade) and [Stylus](https://www.npmjs.com/package/stylus)

```
$ [sudo] npm install -g Jade
$ [sudo] npm install -g stylus
```


Usage
-----

### Use `include`

Jade-file to be included, start a file name from the underscore


Example:

*index.jade*

```
Alloy
  Window.container
    include ./_index_body.jade
```

*\_index\_body.jade*

```
Label#label(onClick="doClick") Hello, Alloy with Jade and Stylus
```
