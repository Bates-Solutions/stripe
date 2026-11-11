[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / ListPricesOptions

# Interface: ListPricesOptions

Defined in: [core/services/prices.service.ts:14](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/core/services/prices.service.ts#L14)

Options for listing prices

## Properties

### active?

> `optional` **active?**: `boolean`

Defined in: [core/services/prices.service.ts:16](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/core/services/prices.service.ts#L16)

Only return active (or inactive) prices

***

### expandProduct?

> `optional` **expandProduct?**: `boolean`

Defined in: [core/services/prices.service.ts:26](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/core/services/prices.service.ts#L26)

Expand the related product inline (`price.product` becomes the full
`Stripe.Product` instead of an ID). Handy for reading product metadata.

#### Default

```ts
false
```

***

### limit?

> `optional` **limit?**: `number`

Defined in: [core/services/prices.service.ts:19](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/core/services/prices.service.ts#L19)

***

### product?

> `optional` **product?**: `string`

Defined in: [core/services/prices.service.ts:18](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/core/services/prices.service.ts#L18)

Only return prices for this product

***

### startingAfter?

> `optional` **startingAfter?**: `string`

Defined in: [core/services/prices.service.ts:20](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/core/services/prices.service.ts#L20)
