[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [server](../README.md) / CheckoutSessionCompletedEvent

# Type Alias: CheckoutSessionCompletedEvent

> **CheckoutSessionCompletedEvent** = `Extract`\<`Stripe.Event`, \{ `type`: `"checkout.session.completed"`; \}\>

Defined in: [server/types.ts:73](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/server/types.ts#L73)

Convenience aliases for the subscription-lifecycle events, each narrowed to
its concrete `data.object` type. Handy for typing standalone handler
functions without re-deriving the `Extract<…>`.
