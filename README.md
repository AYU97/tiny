# @ayu97/tiny



![npm Badge](https://img.shields.io/badge/npm-v1.0.0-blue)
![npm bundle size (scoped)](https://img.shields.io/bundlephobia/min/@cycle/core)


Removes all spaces from a string.

## Install

```
$ npm i @ayu97/tiny
```

## Usage

```js
const tiny = require("@ayu/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
