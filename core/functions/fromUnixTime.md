[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / fromUnixTime

# Function: fromUnixTime()

> **fromUnixTime**(`seconds`): `Date` \| `undefined`

Defined in: [core/utils.ts:124](https://github.com/Bates-Solutions/stripe/blob/c9f04229824430326404a02bd17b0a539a09cfb3/src/core/utils.ts#L124)

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
