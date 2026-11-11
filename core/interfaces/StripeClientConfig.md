[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / StripeClientConfig

# Interface: StripeClientConfig

Defined in: [core/client.ts:34](https://github.com/Bates-Solutions/stripe/blob/861ee1d28dc4956ccb17a2772dd84e4464ae56f1/src/core/client.ts#L34)

Configuration options for the Stripe client

## Properties

### apiKey

> **apiKey**: `string`

Defined in: [core/client.ts:38](https://github.com/Bates-Solutions/stripe/blob/861ee1d28dc4956ccb17a2772dd84e4464ae56f1/src/core/client.ts#L38)

Stripe secret API key (e.g. `sk_test_…` or `sk_live_…`)

***

### apiVersion?

> `optional` **apiVersion?**: `string`

Defined in: [core/client.ts:44](https://github.com/Bates-Solutions/stripe/blob/861ee1d28dc4956ccb17a2772dd84e4464ae56f1/src/core/client.ts#L44)

Pin a specific Stripe API version. Omit to use the version configured on
your Stripe account.

***

### connectClientId?

> `optional` **connectClientId?**: `string`

Defined in: [core/client.ts:64](https://github.com/Bates-Solutions/stripe/blob/861ee1d28dc4956ccb17a2772dd84e4464ae56f1/src/core/client.ts#L64)

Your platform's Connect client ID (`ca_…`). Used as the default by
`oauth.deauthorize`.

***

### maxNetworkRetries?

> `optional` **maxNetworkRetries?**: `number`

Defined in: [core/client.ts:50](https://github.com/Bates-Solutions/stripe/blob/861ee1d28dc4956ccb17a2772dd84e4464ae56f1/src/core/client.ts#L50)

Number of times the Stripe SDK retries failed requests.

#### Default

```ts
1
```

***

### stripeAccount?

> `optional` **stripeAccount?**: `string`

Defined in: [core/client.ts:58](https://github.com/Bates-Solutions/stripe/blob/861ee1d28dc4956ccb17a2772dd84e4464ae56f1/src/core/client.ts#L58)

Act as this connected account (`acct_…`) on every call: the SDK sends it
as the `Stripe-Account` header. Anything that isn't an `acct_…` ID throws
`StripeValidationError`. Usually you don't set this yourself; use
[StripeClient.forAccount](../classes/StripeClient.md#foraccount) on your platform client instead.
