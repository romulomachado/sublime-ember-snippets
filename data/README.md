# EmberData

## Usage

### attr⇥

```js
attr('${1:string}'),
```

### bT⇥

```js
belongsTo('${1:string}'),
```

### fAll⇥

```js
this.store.findAll('${1:model}');
```

### fRecord⇥

```js
this.store.findRecord('${1:model}', params.${1:model}_id);
```

### hM⇥

```js
hasMany('${1:string}'),
```

### pAll⇥

```js
this.store.peekAll('${1:model}');
```

### pRecord⇥

```js
this.store.peekRecord('${1:model}', params.${1:model}_id);
```

### qAll⇥

```js
this.store.query('${1:model}', { ${2:queryKey}: ${3:queryValue}});
```

### qRecord⇥

```js
this.store.queryRecord('${1:model}', { ${2:queryKey}: ${3:queryValue}});
```

