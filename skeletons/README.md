# Skeletons

## Usage

### Adapters

#### activeAdapter⇥

```js
import DS from 'ember-data';

const { ActiveModelAdapter } = DS;

export default ActiveModelAdapter.extend({
  ${1:// body}
});
```

#### jaAdapter⇥

```js
import DS from 'ember-data';

const { JSONAPIAdapter } = DS;

export default JSONAPIAdapter.extend({
  ${1:// body}
});
```

#### adapter⇥

```js
import DS from 'ember-data';

const { RESTAdapter } = DS;

export default RESTAdapter.extend({
  ${1:// body}
});
```

### boundHelper⇥

```js
import Ember from 'ember';

const { Handlebars: { makeBoundHelper } } = Ember;

export default makeBoundHelper(function() {
  ${1:// body}
});
```

### component⇥

```js
import Ember from 'ember';

const { Component } = Ember;

export default Component.extend({
  ${1:// body}
});
```

### controller⇥

```js
import Ember from 'ember';

const { Controller } = Ember;

export default Controller.extend({
  ${1:// body}
});
```

### helper⇥

```js
import Ember from 'ember';

const { Helper } = Ember;

export default Helper.extend({
  compute() {
    ${1:// body}
  }
});
```

### initializer⇥

```js
export default {
  name: '${1:name}',

  initialize() {
    ${2:// body}
  }
};
```

### mixin⇥

```js
import Ember from 'ember';

const { Mixin } = Ember;

export default Mixin.extend({
  ${1:// body}
});
```

### model⇥

```js
import DS from 'ember-data';

const { Model } = DS;

export default Model.extend({
  ${1:// body}
});
```

### object⇥

```js
import Ember from 'ember';

const { Object } = Ember;

export default Object.extend({
  ${1:// body}
});
```

### route⇥

```js
import Ember from 'ember';

const { Route } = Ember;

export default Route.extend({
  model() {
    ${1:// body}
  }
});
```

### serializers

#### activeSerializer⇥

```js
import DS from 'ember-data';

const { ActiveModelSerializer } = DS;

export default ActiveModelSerializer.extend({
  ${1:// body}
});
```

#### jaSerializer⇥

```js
import DS from 'ember-data';

const { JSONAPISerializer } = DS;

export default JSONAPISerializer.extend({
  ${1:// body}
});
```

#### serializer⇥

```js
import DS from 'ember-data';

const { RESTSerializer } = DS;

export default RESTSerializer.extend({
  ${1:// body}
});
```

### service⇥

```js
import Ember from 'ember';

const { Service } = Ember;

export default Service.extend({
  ${1:// body}
});
```

### utility⇥

```js
export default function ${1:myUtility}() {
  ${2:// body}
};
```
