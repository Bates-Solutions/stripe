[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / formatMoney

# Function: formatMoney()

> **formatMoney**(`minor`, `currency?`, `locale?`): `string`

Defined in: [core/utils.ts:78](https://github.com/Bates-Solutions/stripe/blob/c9f04229824430326404a02bd17b0a539a09cfb3/src/core/utils.ts#L78)

Format money for display.

## Parameters

### minor

`number`

Amount in the smallest currency unit

### currency?

[`CurrencyCode`](../type-aliases/CurrencyCode.md) = `'usd'`

Currency code (default: usd)

### locale?

`string` = `'en-US'`

Locale for formatting (default: en-US)

## Returns

`string`

Formatted currency string

## Example

```typescript
formatMoney(1050) // "$10.50"
formatMoney(1000, 'jpy', 'ja-JP') // "￥1,000"
```
