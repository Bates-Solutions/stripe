[**@bates-solutions/stripe API Reference v2.0.0**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / fromUnixTime

# Function: fromUnixTime()

> **fromUnixTime**(`seconds`): `Date` \| `undefined`

Defined in: [core/utils.ts:243](https://github.com/Bates-Solutions/stripe/blob/604d8f5290f7d03ad00ba4783eb226f7df45973a/src/core/utils.ts#L243)

Convert a Unix timestamp (seconds) to a JS `Date`.

Stripe expresses times as Unix epoch **seconds**; this saves consumers from
the repetitive `new Date(value * 1000)`.

## Parameters

### seconds

`number` \| `null` \| `undefined`

Unix time in seconds (e.g. `subscription.current_period_end`)

## Returns

`Date` \| `undefined`

A `Date`, or `undefined` if the input is null/undefined

## Example

```typescript
fromUnixTime(1700000000); // Date
fromUnixTime(null);       // undefined
```
