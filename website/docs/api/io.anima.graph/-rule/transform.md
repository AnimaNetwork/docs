[anima](../../index.md) / [io.anima.graph](../index.md) / [Rule](index.md) / [transform](./transform.md)

# transform

`open fun transform(input: `[`AnimaGraphCapsule`](../../io.anima.transform/-anima-graph-capsule/index.md)`, outputPromise: Promise<`[`ExtendedAnimaGraphCapsule`](../../io.anima.transform/-extended-anima-graph-capsule/index.md)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Transforms the input to some output.

This method must be implemented as a pure function.
This method only gets [DEFAULT_TIMEOUT](../../io.anima.transform/-transformation/-d-e-f-a-u-l-t_-t-i-m-e-o-u-t.md) milliseconds for completion.
If you need more, you can disable the timeout by overriding [enableTimeout](../../io.anima.transform/-transformation/enable-timeout.md).

### Parameters

`input` - The input

`outputPromise` - A promise returning the output or an error

**Return**
Unit because the result is returned by [outputPromise](../../io.anima.transform/-transformation/transform.md#io.anima.transform.Transformation$transform(io.anima.transform.Transformation.A, io.vertx.core.Promise((io.anima.transform.Transformation.B)))/outputPromise)

