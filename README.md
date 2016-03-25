# Essentials of JavaScript

### 1.
```js
console.log(tesla); // ReferenceError: tesla is not defined
```

### 2.
```js
console.log(tesla); // undefined
var tesla = 'Model S';
```

### 3.
```js
openDoors(); // 'Opening doors'

function openDoors() {
  console.log('Opening doors');
}
```

### 4.
```js
var buyTesla = function buyTeslaStock() {
  console.log('Buying TSLA stock');
};

buyTeslaStock(); // ReferenceError: buyTeslaStock is not defined
```

### 5.
```js
var buyTesla = function buyTeslaStock() {
  return typeof buyTeslaStock;
};

console.log(typeof buyTeslaStock, buyTesla()); // 'undefined' 'function'
```

### 6.
```js
console.log(typeof NaN); // 'number'
```

### 7.
```js
console.log(typeof model); // 'undefined' not a ReferenceError!
```

### 8.
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

### 9.
```js
console.log(this === window); // true
```
