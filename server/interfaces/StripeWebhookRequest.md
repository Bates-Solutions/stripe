[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [server](../README.md) / StripeWebhookRequest

# Interface: StripeWebhookRequest

Defined in: [server/middleware/express.ts:8](https://github.com/Bates-Solutions/stripe/blob/fa8bcb341ddb431baa1770084df3a0ac3fee6fff/src/server/middleware/express.ts#L8)

Extended Express Request carrying Stripe webhook data.

## Extends

- `Request`

## Properties

### rawBody?

> `optional` **rawBody?**: `string`

Defined in: [server/middleware/express.ts:10](https://github.com/Bates-Solutions/stripe/blob/fa8bcb341ddb431baa1770084df3a0ac3fee6fff/src/server/middleware/express.ts#L10)

The raw request body as a string

***

### stripeEvent?

> `optional` **stripeEvent?**: `Event`

Defined in: [server/middleware/express.ts:12](https://github.com/Bates-Solutions/stripe/blob/fa8bcb341ddb431baa1770084df3a0ac3fee6fff/src/server/middleware/express.ts#L12)

The parsed Stripe webhook event
