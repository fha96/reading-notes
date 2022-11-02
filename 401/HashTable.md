# Hash Table

- *Hash table stores key-value in pairs.*
- *key: unique integer that is used for indexing the values.*
- *value: retrieved(associated) via key.*

![element of hashTable](https://cdn.programiz.com/sites/tutorial2program/files/Hash-0.png)


# Implementation 

- *The simplest implementation is using the Object data type.*

`var simplehash = new Object();`
`// or`
`// var simplehash = {};`

`simplehash['key1'] = 'value1';`
`simplehash['key2'] = 'value2';`
`simplehash['key3'] = 'value3';`

`for (var key in simplehash) {`
`  // use hasOwnProperty() to filter out properties from Object.prototype`
  `if (simplehash.hasOwnProperty(key)) {`
   ` console.log('key is: ' + key + ', value is: ' + simplehash[key]);`
  `}`
`}`

```
simplehash = {
key1:'value1',
key2:'value2',
key3:'value3'
}
```
