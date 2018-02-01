## Objects
A way to group a collection of data of different properties.

## Properties
Also known as keys

## Methods
Functions that are part of an Object, inside the object.
```javascript
object_name {
    function_name: function() {

    }
}
```
To use the method, use dot notation
```javascript
object_name.method(any arguments you need to pass);
```

## for in loop
A for loop that allows you to loop through the keys of an object
```javascript
for (let key in object) {
    console.log(key); // to get the keys, only
    console.log(object[key]); // to get the values, must be bracket notation
}
```

## Dot notation vs bracket notation
Both are ways to access data within an object.

Dot notation allows you to access the data with the **object_name.key**

Bracket notation allows you to access as **object_name['key']**,

**_NOTE:_** key needs to be inside quotes.

Some times you cannot use Dot notation and you need to fall back on Bracket notation.

