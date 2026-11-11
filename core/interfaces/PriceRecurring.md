[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / PriceRecurring

# Interface: PriceRecurring

Defined in: [core/services/prices.service.ts:32](https://github.com/Bates-Solutions/stripe/blob/3fa5db4b3d85da4031c1d76f0641e98a7929d5c3/src/core/services/prices.service.ts#L32)

Billing interval for a recurring price.

## Properties

### interval

> **interval**: `"day"` \| `"week"` \| `"month"` \| `"year"`

Defined in: [core/services/prices.service.ts:34](https://github.com/Bates-Solutions/stripe/blob/3fa5db4b3d85da4031c1d76f0641e98a7929d5c3/src/core/services/prices.service.ts#L34)

How often the price is charged

***

### intervalCount?

> `optional` **intervalCount?**: `number`

Defined in: [core/services/prices.service.ts:39](https://github.com/Bates-Solutions/stripe/blob/3fa5db4b3d85da4031c1d76f0641e98a7929d5c3/src/core/services/prices.service.ts#L39)

Number of intervals between charges (e.g. `3` with `month` is quarterly).

#### Default

```ts
1
```
