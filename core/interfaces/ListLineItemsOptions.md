[**@bates-solutions/stripe API Reference v2.0.0**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / ListLineItemsOptions

# Interface: ListLineItemsOptions

Defined in: [core/services/checkout.service.ts:21](https://github.com/Bates-Solutions/stripe/blob/604d8f5290f7d03ad00ba4783eb226f7df45973a/src/core/services/checkout.service.ts#L21)

Options for listing a session's line items

## Properties

### expandProduct?

> `optional` **expandProduct?**: `boolean`

Defined in: [core/services/checkout.service.ts:26](https://github.com/Bates-Solutions/stripe/blob/604d8f5290f7d03ad00ba4783eb226f7df45973a/src/core/services/checkout.service.ts#L26)

Expand `price.product` to the full Product (e.g. to read its metadata).

#### Default

```ts
false
```
