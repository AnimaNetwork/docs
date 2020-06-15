[anima](../../index.md) / [io.anima.core.transform](../index.md) / [SparqlQuestionMessageTransformation](index.md) / [filter](./filter.md)

# filter

`fun filter(input: `[`QuestionMessageCapsule`](../-question-message-capsule/index.md)`, context: `[`TransformationContext`](../../io.anima.transform/-transformation-context/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Decides whether to transform or not.

You can use this method to filter out some input which
this transformation doesn't support without stopping
the whole transformation process.

### Parameters

`input` - The input to filter

**Return**
True if [transform](../../io.anima.transform/-transformation/transform.md) should be applied otherwise false
