#### Binary Search

Binary Search in JavaScript

`npm i binary-search-jsv2`

[npm link](https://www.npmjs.com/package/binary-search-jsv2)

for example :

```javascript
import binarySearch from 'binary-search-jsv2';

const list = [4, 5, 15, 7, 9, 10, 12];
const sortList = list.sort(function (a, b) {
  return a - b;
});
const value = 15;

binarySearch(value, sortList); // 6
```
