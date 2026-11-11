[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [server](../README.md) / WebhookEventContext

# Interface: WebhookEventContext

Defined in: [server/middleware/lambda.ts:33](https://github.com/Bates-Solutions/stripe/blob/c9f04229824430326404a02bd17b0a539a09cfb3/src/server/middleware/lambda.ts#L33)

Context passed to Lambda webhook handlers with auto-extracted entity IDs.

## Properties

### chargeId?

> `optional` **chargeId?**: `string`

Defined in: [server/middleware/lambda.ts:35](https://github.com/Bates-Solutions/stripe/blob/c9f04229824430326404a02bd17b0a539a09cfb3/src/server/middleware/lambda.ts#L35)

***

### customerId?

> `optional` **customerId?**: `string`

Defined in: [server/middleware/lambda.ts:36](https://github.com/Bates-Solutions/stripe/blob/c9f04229824430326404a02bd17b0a539a09cfb3/src/server/middleware/lambda.ts#L36)

***

### paymentIntentId?

> `optional` **paymentIntentId?**: `string`

Defined in: [server/middleware/lambda.ts:34](https://github.com/Bates-Solutions/stripe/blob/c9f04229824430326404a02bd17b0a539a09cfb3/src/server/middleware/lambda.ts#L34)
