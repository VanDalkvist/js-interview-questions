# JS-interview-questions
Questions which could help to understand How deep a man knows JS.
 
```javascript
setTimeout(cb, 0);
```

```javascript
var arr = ['2', '12', '3', '4', '5', 'hello'];
var parsed = arr.map(parseInt);
console.log(parsed);
```

```javascript
console.log(new Boolean(false))
console.log(Boolean(false));
console.log(Boolean([]))
console.log(Boolean({}));
```

```javascript
const arr = [10, 12, 15, 21];
for (var i = 0; i < arr.length; i++) {
  setTimeout(function() {
    console.log('Index: ' + i + ', element: ' + arr[i]);
  }, 3000);
}
```

```
How to create a listener for an element click in the list of elements?
```
