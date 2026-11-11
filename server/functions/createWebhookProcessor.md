[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [server](../README.md) / createWebhookProcessor

# Function: createWebhookProcessor()

> **createWebhookProcessor**(`config`): (`rawBody`, `signature`) => `Promise`\<\{ `error?`: `string`; `event?`: `Event`; `success`: `boolean`; \}\>

Defined in: [server/webhook.ts:256](https://github.com/Bates-Solutions/stripe/blob/3fa5db4b3d85da4031c1d76f0641e98a7929d5c3/src/server/webhook.ts#L256)

Create a webhook handler that verifies and processes raw webhook requests.

## Parameters

### config

[`WebhookConfig`](../interfaces/WebhookConfig.md)

Webhook configuration

## Returns

A function that processes a raw webhook request

(`rawBody`, `signature`) => `Promise`\<\{ `error?`: `string`; `event?`: `Event`; `success`: `boolean`; \}\>

## Example

```typescript
const handleWebhook = createWebhookProcessor({
  signingSecret: process.env.STRIPE_WEBHOOK_SECRET!,
  handlers: {
    'payment_intent.succeeded': async (event) => {
      await fulfillOrder(event.data.object);
    },
  },
});

const result = await handleWebhook(rawBody, signature);
```
