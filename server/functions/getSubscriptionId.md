[**@bates-solutions/stripe API Reference v2.0.0**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [server](../README.md) / getSubscriptionId

# Function: getSubscriptionId()

> **getSubscriptionId**(`event`): `string` \| `undefined`

Defined in: [server/webhook.ts:347](https://github.com/Bates-Solutions/stripe/blob/604d8f5290f7d03ad00ba4783eb226f7df45973a/src/server/webhook.ts#L347)

Extract the Subscription ID from a webhook event, when present.

Works on `customer.subscription.*` events (the object is the subscription)
and on objects that reference a subscription (Checkout Sessions, Invoices).

## Parameters

### event

`Event`

## Returns

`string` \| `undefined`
