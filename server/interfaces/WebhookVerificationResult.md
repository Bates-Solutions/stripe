[**@bates-solutions/stripe API Reference v2.0.0**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [server](../README.md) / WebhookVerificationResult

# Interface: WebhookVerificationResult

Defined in: [server/types.ts:83](https://github.com/Bates-Solutions/stripe/blob/604d8f5290f7d03ad00ba4783eb226f7df45973a/src/server/types.ts#L83)

Result of webhook signature verification.

## Properties

### error?

> `optional` **error?**: `string`

Defined in: [server/types.ts:87](https://github.com/Bates-Solutions/stripe/blob/604d8f5290f7d03ad00ba4783eb226f7df45973a/src/server/types.ts#L87)

Error message if invalid

***

### valid

> **valid**: `boolean`

Defined in: [server/types.ts:85](https://github.com/Bates-Solutions/stripe/blob/604d8f5290f7d03ad00ba4783eb226f7df45973a/src/server/types.ts#L85)

Whether the signature is valid
