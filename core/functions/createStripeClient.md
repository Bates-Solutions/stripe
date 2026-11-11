[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / createStripeClient

# Function: createStripeClient()

> **createStripeClient**(`config`): [`StripeClient`](../classes/StripeClient.md)

Defined in: [core/client.ts:222](https://github.com/Bates-Solutions/stripe/blob/fa8bcb341ddb431baa1770084df3a0ac3fee6fff/src/core/client.ts#L222)

Create a new Stripe client instance.

## Parameters

### config

[`StripeClientConfig`](../interfaces/StripeClientConfig.md)

Client configuration

## Returns

[`StripeClient`](../classes/StripeClient.md)

Configured Stripe client

## Example

```typescript
const stripe = createStripeClient({
  apiKey: process.env.STRIPE_SECRET_KEY!,
});
```
