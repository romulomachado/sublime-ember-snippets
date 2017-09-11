# Ember.Object

## Usage

### actions⇥

```js
actions: {
  ${1:// body}
}
```

### alias⇥

```js
computed.alias('${1:property}')
```

### computed⇥

```js
computed('${1:property}', function() {
  ${2:// body}
}),
```

### get⇥

```js
${1:this}.get('${2}');
```

### init⇥

```js
init() {
  this._super(...arguments);
  ${1}
},
```

### inject⇥

```js
inject.service(${1}),
```

### lget⇥

```js
let $1 = ${2:this}.get('$1');
```

### observer⇥

```js
observer('${1:property}', function() {
  ${2:// body}
}),
```

### set⇥

```js
${1:this}.set('${2}', ${3});
```

### super⇥

```js
this._super(...arguments);
```

