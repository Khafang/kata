# Reverse Integer

Reverse digits of an integer.

```
Example1: x = 123, return 321
Example2: x = -123, return -321
```

```js
import test from 'ava'
import reverseInteger from './reverseInteger'

test('reverseInteger', function (t) {
  t.is(reverseInteger(123), 321)
  t.is(reverseInteger(-123), -321)
})
```
