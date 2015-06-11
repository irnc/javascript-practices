## Initial code

```js
var defaultPost;

before(function () {
  defaultPost = Factory.build('postFactory');
});
```

## Better code

```js
before(function () {
  this.defaultPost = Factory.build('postFactory');
});
```

## See also

* https://github.com/mochajs/mocha/wiki/shared-behaviours
* https://github.com/mochajs/mocha/blob/master/lib/context.js
