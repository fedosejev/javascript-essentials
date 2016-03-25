# Essentials of JavaScript

```js
console.log(tesla); // ReferenceError: tesla is not defined
```
```js
console.log(tesla); // undefined
var tesla = 'Model S';
```
```js
openDoors(); // 'Opening doors'

function openDoors() {
  console.log('Opening doors');
}
```
```js
var buyTesla = function buyTeslaStock() {
  console.log('Buying TSLA stock');
};

buyTeslaStock(); // ReferenceError: buyTeslaStock is not defined
```
```js
var buyTesla = function buyTeslaStock() {
  return typeof buyTeslaStock;
};

console.log(typeof buyTeslaStock, buyTesla()); // 'undefined' 'function'
```
```js
console.log(typeof NaN); // 'number'
```
```js
console.log(typeof model); // 'undefined' not a ReferenceError!
```
Turn any value into it's `boolean` value:
```js
var tesla = 'Model S';
console.log(!! tesla); // true
```
First `!` converts value into an opposite boolean value. Second `!` converts it into an opposite value.

`!!` is a shortcut for:
```js
console.log(Boolean('Model S')); // true
```

