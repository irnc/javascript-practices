## Code in question

```js
expect(result).to.be.empty;
```

Common to `chai`.

TODO: link to GitHub issues discussing property getters which change state.

## WebStorm IDE

* `BadExpressionStatementJS`
  * Inspection "Expression statement which is not assignment or call"
  * `//noinspection BadExpressionStatementJS`
  * Description: _This inspection reports expression statements which are not assignments or calls. Such statements have no dubious semantics, are normally the result of programmer error._
