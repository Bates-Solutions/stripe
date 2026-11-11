[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [server](../README.md) / ParsedWebhookRequest

# Interface: ParsedWebhookRequest

Defined in: [server/types.ts:93](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/server/types.ts#L93)

A parsed and verified webhook request.

## Properties

### event

> **event**: `Event`

Defined in: [server/types.ts:99](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/server/types.ts#L99)

The parsed event

***

### rawBody

> **rawBody**: `string`

Defined in: [server/types.ts:95](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/server/types.ts#L95)

The raw request body

***

### signature

> **signature**: `string`

Defined in: [server/types.ts:97](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/server/types.ts#L97)

The signature from the `stripe-signature` header
