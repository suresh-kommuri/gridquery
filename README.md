# gridquery [![NPM version](https://badge.fury.io/js/gridquery.svg)](https://npmjs.org/package/gridquery) [![Build Status](https://travis-ci.org/suresh-kommuri/gridquery.svg?branch=master)](https://travis-ci.org/suresh-kommuri/gridquery)

> "New way of grid view"

## Installation

```sh
$ npm install --save gridquery
```

## Usage

```html
<div class="gridbox">
  <div class="gridrow" cols="4" equal="true">
    <div class="c-2 x-3 t-1">
      Hello
    </div>
    <div class="c-2 x-1 t-3">
      World!
    </div>
  </div>
</div>
```
<h2>gridquery</h2>
New way of gridview

This is a new resposive style. It will set the width for specified arguments.

<h2>Hints</h2>
Gridbox is like container in bootstrap framework, it has some default css styling. Gridrow will have the default styling, it will act like a row for the gridbox.

Coming to gridrow : I have defined some attributes.

<h2>In the gridrow</h2>
You can set columns number with "cols" attribute i.e. you can define how many columns you want.
And the "equal" attribute by default it is false, if you want set the columns with equal width within gridrow you can define the equal attribute as "true".
The child classes for specifying the columns sizes like bootstrap [ex: c-1, c-2, c-3 ..etc; t-1, t-2, t-3 ..etc; x-1, x-4 ..etc.]
If you have a cols (columns) = 10; Then you have to devide columns in the terms of cols i.e. the number of child columns total will be equal to the parent grid cols.
Here the c-1 defines for desktops, t-1 defines for tablets and x-1 defines mobile.

## License

ISC © [Suresh Kommuri](https://github.com/suresh-kommuri)
