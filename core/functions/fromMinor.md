[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / fromMinor

# Function: fromMinor()

> **fromMinor**(`minor`, `currency?`): `number`

Defined in: [core/utils.ts:59](https://github.com/Bates-Solutions/stripe/blob/3fa5db4b3d85da4031c1d76f0641e98a7929d5c3/src/core/utils.ts#L59)

Convert an amount in the smallest currency unit to a major-unit amount.

## Parameters

### minor

`number`

Amount in the smallest currency unit

### currency?

[`CurrencyCode`](../type-aliases/CurrencyCode.md) = `'usd'`

Currency code (default: usd)

## Returns

`number`

Major-unit amount

## Example

```typescript
fromMinor(1050) // 10.50
fromMinor(1000, 'jpy') // 1000
```
