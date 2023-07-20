# @binhbdn/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@binhbdn/tiny.svg)](https://www.npmjs.com/package/@binhbdn/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@binhbdn/tiny.svg)](https://www.npmjs.com/package/@binhbdn/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @binhbdn/tiny
```

## Usage

```js
const tiny = require("@binhbdn/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```