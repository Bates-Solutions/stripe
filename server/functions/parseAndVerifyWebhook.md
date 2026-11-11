[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [server](../README.md) / parseAndVerifyWebhook

# Function: parseAndVerifyWebhook()

> **parseAndVerifyWebhook**(`rawBody`, `signature`, `signingSecret`, `options?`): `Promise`\<[`ParsedWebhookRequest`](../interfaces/ParsedWebhookRequest.md)\>

Defined in: [server/webhook.ts:188](https://github.com/Bates-Solutions/stripe/blob/c9f04229824430326404a02bd17b0a539a09cfb3/src/server/webhook.ts#L188)

Verify and parse a webhook request.

## Parameters

### rawBody

`string`

The raw request body string

### signature

`string`

The `stripe-signature` header value

### signingSecret

`string`

Your webhook signing secret

### options?

[`VerifyOptions`](../interfaces/VerifyOptions.md)

Verification options

## Returns

`Promise`\<[`ParsedWebhookRequest`](../interfaces/ParsedWebhookRequest.md)\>

The parsed and verified webhook request

## Throws

Error if verification or parsing fails

## Example

```typescript
const { event } = parseAndVerifyWebhook(
  rawBody,
  signature,
  process.env.STRIPE_WEBHOOK_SECRET!
);
```
