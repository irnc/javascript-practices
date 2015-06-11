## Initial code

```js
var model = require('mongoose').model('Model');

// ...

model.create(doc)
```

## Problem with initial code

1. `model.create()` call gives wrong impression, that `model` stores `Document` object while it is a constructor function.

## Better code

```js
var Model = require('mongoose').model('Model');

// ...

Model.create(doc)
```
