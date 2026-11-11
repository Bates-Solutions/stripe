[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / buildAuthorizeUrl

# Function: buildAuthorizeUrl()

> **buildAuthorizeUrl**(`options`): `string`

Defined in: [core/services/oauth.service.ts:91](https://github.com/Bates-Solutions/stripe/blob/3fa5db4b3d85da4031c1d76f0641e98a7929d5c3/src/core/services/oauth.service.ts#L91)

Build the URL that sends a user to Stripe to connect their existing Stripe
account to your platform (Connect OAuth, Standard accounts). Pure function,
no network call, so it works without an API key.

## Parameters

### options

[`BuildAuthorizeUrlOptions`](../interfaces/BuildAuthorizeUrlOptions.md)

## Returns

`string`

## Throws

When `clientId` or `state` is missing

## Example

```typescript
const url = buildAuthorizeUrl({
  clientId: process.env.STRIPE_CONNECT_CLIENT_ID!,
  state: csrfToken, // random per attempt; store it server side to check in the callback
  redirectUri: 'https://app.example.com/stripe/callback',
});
// redirect the user to `url`
```

## See

https://docs.stripe.com/connect/oauth-reference
