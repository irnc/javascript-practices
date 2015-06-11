## Initial code

`url` variable is intended to be a constant, used only inside `getUrl` function. This variable was put outside `getUrl` for no reason.

```js
var url = '/api/v1/parts';
var getUrl = function (model, modelYear) {
  return url + '?model=' + model + '&model_year=' + modelYear;
};
```

## Better code

To be defined.
