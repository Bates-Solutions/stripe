[**@bates-solutions/stripe API Reference v2.0.0**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [server](../README.md) / WebhookEvent

# Type Alias: WebhookEvent

> **WebhookEvent** = `Stripe.Event`

Defined in: [server/types.ts:9](https://github.com/Bates-Solutions/stripe/blob/604d8f5290f7d03ad00ba4783eb226f7df45973a/src/server/types.ts#L9)

A verified Stripe webhook event.

This is the Stripe SDK's `Event` type — a discriminated union on `type`, so
narrowing on `event.type` gives you the correct `event.data.object` shape.
