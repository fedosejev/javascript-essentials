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
openDoors(); // TypeError: openDoors is not a function

var openDoors = function () {
  console.log('Opening doors');
};
```


