
# interval

Function interval decorator

`component-install stagas/interval`

## Usage

```js
var Interval = require('interval')
Interval(fn)
var iv = fn.interval(1000)
```

or

```js
var Interval = require('interval')
var intervaled = Interval.decorate(fn)
var iv = intervaled(1000)
```

You may also pass additional arguments:

```js
fn.interval(1000, 'hello', ['world'])
```

## License

MIT
