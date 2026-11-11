[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / StripeClientConfig

# Interface: StripeClientConfig

Defined in: [core/client.ts:35](https://github.com/Bates-Solutions/stripe/blob/c9f04229824430326404a02bd17b0a539a09cfb3/src/core/client.ts#L35)

Configuration options for the Stripe client

## Properties

### apiKey

> **apiKey**: `string`

Defined in: [core/client.ts:39](https://github.com/Bates-Solutions/stripe/blob/c9f04229824430326404a02bd17b0a539a09cfb3/src/core/client.ts#L39)

Stripe secret API key (e.g. `sk_test_…` or `sk_live_…`)

***

### apiVersion?

> `optional` **apiVersion?**: `string`

Defined in: [core/client.ts:45](https://github.com/Bates-Solutions/stripe/blob/c9f04229824430326404a02bd17b0a539a09cfb3/src/core/client.ts#L45)

Pin a specific Stripe API version. Omit to use the version configured on
your Stripe account.

***

### connectClientId?

> `optional` **connectClientId?**: `string`

Defined in: [core/client.ts:65](https://github.com/Bates-Solutions/stripe/blob/c9f04229824430326404a02bd17b0a539a09cfb3/src/core/client.ts#L65)

Your platform's Connect client ID (`ca_…`). Used as the default by
`oauth.deauthorize`.

***

### maxNetworkRetries?

> `optional` **maxNetworkRetries?**: `number`

Defined in: [core/client.ts:51](https://github.com/Bates-Solutions/stripe/blob/c9f04229824430326404a02bd17b0a539a09cfb3/src/core/client.ts#L51)

Number of times the Stripe SDK retries failed requests.

#### Default

```ts
1
```

***

### stripeAccount?

> `optional` **stripeAccount?**: `string`

Defined in: [core/client.ts:59](https://github.com/Bates-Solutions/stripe/blob/c9f04229824430326404a02bd17b0a539a09cfb3/src/core/client.ts#L59)

Act as this connected account (`acct_…`) on every call: the SDK sends it
as the `Stripe-Account` header. Anything that isn't an `acct_…` ID throws
`StripeValidationError`. Usually you don't set this yourself; use
[StripeClient.forAccount](../classes/StripeClient.md#foraccount) on your platform client instead.
