# Javascript-Sets

A Javascript `set` is an object/collection of unique elements.

* creating a `set`:

```
const set = new Set();
```

* creating a `set` from an array:

```
const numbersArray = [1, 2, 5, 3, 1, 2, 4, , 9, 3];

const setOfNumbers = new Set(numbersArray);

console.log(setOfNumbers)
///Will print:
Set(6) { 1, 2, 5, 3, 4, 9 }
```
* adding an element to a `set`:

```
const set = new Set();

set.add(2)

console.log(set)
///Will print:
Set(1) { 2 }
```
* looping a `set`:

```
const numbersArray = [1, 1, 2, 2, 3, 23, 5, 6, 8, 7];

const numberSet = new Set(numbersArray);

for (let number of numberSet) {
  console.log(number);
}
```
