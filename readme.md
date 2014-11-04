# trim-object-stream

stream that trims all whitespace from keys and values on the top level of an object

[![NPM](https://nodei.co/npm/trim-object-stream.png?global=true)](https://nodei.co/npm/trim-object-stream/)

## usage

```js
$ cat line-delimited-json.json | trim-object-stream
```

## example

```js
$ echo $'{" foo ":" bar ", " baz ": { " qux ": 1 }}' | trim-object-stream
{"foo":"bar","baz":{"qux":1}}
```
