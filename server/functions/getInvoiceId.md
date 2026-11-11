[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [server](../README.md) / getInvoiceId

# Function: getInvoiceId()

> **getInvoiceId**(`event`): `string` \| `undefined`

Defined in: [server/webhook.ts:373](https://github.com/Bates-Solutions/stripe/blob/3fa5db4b3d85da4031c1d76f0641e98a7929d5c3/src/server/webhook.ts#L373)

Extract the Invoice ID from a webhook event, when present.

Works on `invoice.*` events (the object is the invoice) and on objects that
reference an invoice (e.g. Checkout Sessions, PaymentIntents).

## Parameters

### event

`Event`

## Returns

`string` \| `undefined`
