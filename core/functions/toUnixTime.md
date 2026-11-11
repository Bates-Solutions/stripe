[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / toUnixTime

# Function: toUnixTime()

> **toUnixTime**(`value`, `field?`): `number`

Defined in: [core/utils.ts:146](https://github.com/Bates-Solutions/stripe/blob/3fa5db4b3d85da4031c1d76f0641e98a7929d5c3/src/core/utils.ts#L146)

Convert a JS `Date` to Unix seconds, the time format Stripe expects. A
number is taken to be Unix seconds already and passed through.

## Parameters

### value

`number` \| `Date`

A `Date`, or whole Unix seconds

### field?

`string` = `'value'`

Field name reported on a validation error

## Returns

`number`

## Throws

When the value is an invalid `Date`, not a
  whole number, or looks like milliseconds (above 1e11, i.e. after the year
  5000)

## Example

```typescript
toUnixTime(new Date('2026-03-01T00:00:00Z')); // 1772323200
```
