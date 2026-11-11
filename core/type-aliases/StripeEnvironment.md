[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / StripeEnvironment

# Type Alias: StripeEnvironment

> **StripeEnvironment** = `"test"` \| `"live"`

Defined in: [core/types/index.ts:7](https://github.com/Bates-Solutions/stripe/blob/c9f04229824430326404a02bd17b0a539a09cfb3/src/core/types/index.ts#L7)

Stripe environment, derived from the API key prefix.

Stripe has no separate sandbox host — a `sk_test_…` key operates in test
mode and a `sk_live_…` key operates in live mode.
