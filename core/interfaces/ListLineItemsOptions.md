[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / ListLineItemsOptions

# Interface: ListLineItemsOptions

Defined in: [core/services/checkout.service.ts:21](https://github.com/Bates-Solutions/stripe/blob/3fa5db4b3d85da4031c1d76f0641e98a7929d5c3/src/core/services/checkout.service.ts#L21)

Options for listing a session's line items

## Properties

### expandProduct?

> `optional` **expandProduct?**: `boolean`

Defined in: [core/services/checkout.service.ts:26](https://github.com/Bates-Solutions/stripe/blob/3fa5db4b3d85da4031c1d76f0641e98a7929d5c3/src/core/services/checkout.service.ts#L26)

Expand `price.product` to the full Product (e.g. to read its metadata).

#### Default

```ts
false
```
