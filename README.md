# Widths

The `widths` module is a simple file of helper classes to drop widths onto
elements such as grid systems.

## Dependencies

The `widths` module depends on two other modules:

* [settings.defaults](https://github.com/treeframework/settings.defaults)
* [tools.widths](https://github.com/treeframework/tools.widths)

If you install the `widths` module  using Bower or npm, you will get these
dependencies at the same time. If not using Bower or npm, please be sure to
install and @import these dependencies in the relevant way.

## Installation

You can install `widths` module via Bower, npm, or copy and paste.

## Install using Bower:

```sh
$ bower install tree-widths --save
```

Once installed, `@import` into your project in its Trump layer:

```scss
@import "bower_components/tree-widths/trump.widths";
```

### Install using npm:

```sh
$ npm install tree-widths --save
```

### Install via file download

The least recommended option for installation is to simply download
`_trump.widths.scss` into your project and `@import` it into your project in its
Trump layer.

## Usage

`widths` classes are available in one of two formats:

* fraction-like (default format), e.g.: `<div class="u-1/2">...<div>`
* spoken-word, e.g.: `<div class="u-1-of-2">...</div>`

Enable `spoken-word` format by predefining the `$tree-use-fractions` feature
switch, e.g.:

```scss
$tree-use-fractions:    false;
@import "path/to/trump.widths";
```

## Credits

* **[inuitcss](https://github.com/inuitcss)** Powerful, Sass-based, OOCSS
framework designed with scalability and performance in mind.
