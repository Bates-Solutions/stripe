[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [server](../README.md) / LambdaWebhookHandler

# Type Alias: LambdaWebhookHandler

> **LambdaWebhookHandler** = (`event`, `context`) => `void` \| `Promise`\<`void`\>

Defined in: [server/middleware/lambda.ts:42](https://github.com/Bates-Solutions/stripe/blob/d2bb14f0921c772ec3367df6bd73049477224ac3/src/server/middleware/lambda.ts#L42)

Handler for a Lambda webhook event.

## Parameters

### event

[`WebhookEvent`](WebhookEvent.md)

### context

[`WebhookEventContext`](../interfaces/WebhookEventContext.md)

## Returns

`void` \| `Promise`\<`void`\>
