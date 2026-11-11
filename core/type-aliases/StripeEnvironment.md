[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / StripeEnvironment

# Type Alias: StripeEnvironment

> **StripeEnvironment** = `"test"` \| `"live"`

Defined in: [core/types/index.ts:7](https://github.com/Bates-Solutions/stripe/blob/fa8bcb341ddb431baa1770084df3a0ac3fee6fff/src/core/types/index.ts#L7)

Stripe environment, derived from the API key prefix.

Stripe has no separate sandbox host — a `sk_test_…` key operates in test
mode and a `sk_live_…` key operates in live mode.
