[**@bates-solutions/stripe API Reference v2.0.0**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / LineItem

# Type Alias: LineItem

> **LineItem** = `Stripe.LineItem`

Defined in: [core/services/checkout.service.ts:16](https://github.com/Bates-Solutions/stripe/blob/604d8f5290f7d03ad00ba4783eb226f7df45973a/src/core/services/checkout.service.ts#L16)

A line item that was sold (on a Checkout Session or Payment Link). `price`
holds the Price (and its `product`), `quantity` and `amount_total` what was
bought.
