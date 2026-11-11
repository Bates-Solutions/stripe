[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / LineItem

# Type Alias: LineItem

> **LineItem** = `Stripe.LineItem`

Defined in: [core/services/checkout.service.ts:16](https://github.com/Bates-Solutions/stripe/blob/3fa5db4b3d85da4031c1d76f0641e98a7929d5c3/src/core/services/checkout.service.ts#L16)

A line item that was sold (on a Checkout Session or Payment Link). `price`
holds the Price (and its `product`), `quantity` and `amount_total` what was
bought.
