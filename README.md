# @andymuniz/tiny

![npm (scoped)](https://img.shields.io/npm/v/@andymuniz/tiny.svg)
![npm bundle size (scoped)](https://img.shields.io/bundlephobia/min/@andymuniz/tiny.svg)

Removes all spaces from a string.

## Install

```bash
npm install @andymuniz/tiny
```

## Usage

```js
const tiny = require("@andymuniz/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
