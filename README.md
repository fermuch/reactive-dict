
# reactive-dict v1.1.1 [![experimental](http://badges.github.io/stability-badges/dist/experimental.svg)](http://github.com/badges/stability-badges)

This package is stripped from [meteor/reactive-dict](https://atmospherejs.com/meteor/reactive-dict) and made compatible with [React Native](https://github.com/facebook/react-native).

**Note:** This package is only for client-side usage.

&nbsp;

## usage

```js
var ReactiveDict = require('reactive-dict');

// Provide a unique string to hot-reload the data.
var myDict = ReactiveDict('unique id');

myDict.set('someProperty', 1) // => undefined

myDict.get('someProperty') // => 1
```

&nbsp;

## install

```sh
npm install aleclarson/reactive-dict#1.1.1
```
