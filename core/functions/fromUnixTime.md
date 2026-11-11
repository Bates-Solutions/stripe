[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / fromUnixTime

# Function: fromUnixTime()

> **fromUnixTime**(`seconds`): `Date` \| `undefined`

Defined in: [core/utils.ts:124](https://github.com/Bates-Solutions/stripe/blob/3fa5db4b3d85da4031c1d76f0641e98a7929d5c3/src/core/utils.ts#L124)

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
