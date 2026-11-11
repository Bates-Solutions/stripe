[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [server](../README.md) / getSubscriptionId

# Function: getSubscriptionId()

> **getSubscriptionId**(`event`): `string` \| `undefined`

Defined in: [server/webhook.ts:347](https://github.com/Bates-Solutions/stripe/blob/3fa5db4b3d85da4031c1d76f0641e98a7929d5c3/src/server/webhook.ts#L347)

Extract the Subscription ID from a webhook event, when present.

Works on `customer.subscription.*` events (the object is the subscription)
and on objects that reference a subscription (Checkout Sessions, Invoices).

## Parameters

### event

`Event`

## Returns

`string` \| `undefined`
