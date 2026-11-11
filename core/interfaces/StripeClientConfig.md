[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / StripeClientConfig

# Interface: StripeClientConfig

Defined in: [core/client.ts:23](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/core/client.ts#L23)

Configuration options for the Stripe client

## Properties

### apiKey

> **apiKey**: `string`

Defined in: [core/client.ts:27](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/core/client.ts#L27)

Stripe secret API key (e.g. `sk_test_…` or `sk_live_…`)

***

### apiVersion?

> `optional` **apiVersion?**: `string`

Defined in: [core/client.ts:33](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/core/client.ts#L33)

Pin a specific Stripe API version. Omit to use the version configured on
your Stripe account.

***

### maxNetworkRetries?

> `optional` **maxNetworkRetries?**: `number`

Defined in: [core/client.ts:39](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/core/client.ts#L39)

Number of times the Stripe SDK retries failed requests.

#### Default

```ts
1
```
