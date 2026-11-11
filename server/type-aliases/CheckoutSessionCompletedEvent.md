[**@bates-solutions/stripe API Reference v2.0.0**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [server](../README.md) / CheckoutSessionCompletedEvent

# Type Alias: CheckoutSessionCompletedEvent

> **CheckoutSessionCompletedEvent** = `Extract`\<`Stripe.Event`, \{ `type`: `"checkout.session.completed"`; \}\>

Defined in: [server/types.ts:73](https://github.com/Bates-Solutions/stripe/blob/604d8f5290f7d03ad00ba4783eb226f7df45973a/src/server/types.ts#L73)

Convenience aliases for the subscription-lifecycle events, each narrowed to
its concrete `data.object` type. Handy for typing standalone handler
functions without re-deriving the `Extract<…>`.
