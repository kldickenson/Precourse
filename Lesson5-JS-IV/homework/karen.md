## Callback Functions
Passing a function (callback, cb) as an argument to another function (higher order function).
```javascript
function foo(cb) {
    cb();
}
foo(function() {
    console.log('Hi!');
});
```
Commonly used for different helper methods on arrays i.e. forEach() or map().
```javascript
const names = ['Ben', 'Austen', 'Karen', 'Jocelyn'];
names.forEach(function(name, i) {
    console.log(i + ' - ' + name + ', hi!');
});
```

## arguments


## prototype

## Constructors
aka Classes. Templates for creating objects with specific keys and methods.