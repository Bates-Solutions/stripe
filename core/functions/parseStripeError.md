[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / parseStripeError

# Function: parseStripeError()

> **parseStripeError**(`error`): [`StripeError`](../classes/StripeError.md)

Defined in: [core/errors.ts:263](https://github.com/Bates-Solutions/stripe/blob/3fa5db4b3d85da4031c1d76f0641e98a7929d5c3/src/core/errors.ts#L263)

Parse a Stripe SDK error (or any thrown value) into a typed exception.

Understands both `stripe-node` error instances and plain objects in
Stripe's API error shape. See the error guide for the full code map.

## Parameters

### error

`unknown`

## Returns

[`StripeError`](../classes/StripeError.md)
