[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [server](../README.md) / getSubscriptionId

# Function: getSubscriptionId()

> **getSubscriptionId**(`event`): `string` \| `undefined`

Defined in: [server/webhook.ts:347](https://github.com/Bates-Solutions/stripe/blob/fa8bcb341ddb431baa1770084df3a0ac3fee6fff/src/server/webhook.ts#L347)

Extract the Subscription ID from a webhook event, when present.

Works on `customer.subscription.*` events (the object is the subscription)
and on objects that reference a subscription (Checkout Sessions, Invoices).

## Parameters

### event

`Event`

## Returns

`string` \| `undefined`
