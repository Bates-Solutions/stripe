[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [server](../README.md) / getAccountId

# Function: getAccountId()

> **getAccountId**(`event`): `string` \| `undefined`

Defined in: [server/webhook.ts:363](https://github.com/Bates-Solutions/stripe/blob/3fa5db4b3d85da4031c1d76f0641e98a7929d5c3/src/server/webhook.ts#L363)

Extract the connected account ID from a webhook event, when present.

Events from a Connect webhook endpoint carry the connected account they
happened on (`event.account`). Pass it to `stripe.forAccount(id)` to act on
that account. Events on your own platform account return `undefined`.

## Parameters

### event

`Event`

## Returns

`string` \| `undefined`
