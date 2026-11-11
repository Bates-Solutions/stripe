[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [server](../README.md) / WebhookEvent

# Type Alias: WebhookEvent

> **WebhookEvent** = `Stripe.Event`

Defined in: [server/types.ts:9](https://github.com/Bates-Solutions/stripe/blob/fa8bcb341ddb431baa1770084df3a0ac3fee6fff/src/server/types.ts#L9)

A verified Stripe webhook event.

This is the Stripe SDK's `Event` type — a discriminated union on `type`, so
narrowing on `event.type` gives you the correct `event.data.object` shape.
