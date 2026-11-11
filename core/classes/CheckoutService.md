[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / CheckoutService

# Class: CheckoutService

Defined in: [core/services/checkout.service.ts:76](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/core/services/checkout.service.ts#L76)

Checkout service wrapping Stripe [Checkout Sessions](https://docs.stripe.com/api/checkout/sessions).

## Example

```typescript
const session = await stripe.checkout.create({
  mode: 'subscription',
  customerId: 'cus_123',
  lineItems: [{ price: 'price_123', quantity: 1 }],
  successUrl: 'https://app.example.com/billing?success=true',
  cancelUrl: 'https://app.example.com/billing?canceled=true',
});

redirect(session.url);
```

## Constructors

### Constructor

> **new CheckoutService**(`client`): `CheckoutService`

Defined in: [core/services/checkout.service.ts:77](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/core/services/checkout.service.ts#L77)

#### Parameters

##### client

`Stripe`

#### Returns

`CheckoutService`

## Methods

### create()

> **create**(`options`): `Promise`\<`Session`\>

Defined in: [core/services/checkout.service.ts:87](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/core/services/checkout.service.ts#L87)

Create a Checkout Session.

#### Parameters

##### options

[`CreateCheckoutSessionOptions`](../interfaces/CreateCheckoutSessionOptions.md)

Session creation options

#### Returns

`Promise`\<`Session`\>

The created session (use `session.url` to redirect the customer)

#### Throws

When required fields are missing

***

### expire()

> **expire**(`sessionId`): `Promise`\<`Session`\>

Defined in: [core/services/checkout.service.ts:138](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/core/services/checkout.service.ts#L138)

Expire an open Checkout Session so it can no longer be completed.

#### Parameters

##### sessionId

`string`

#### Returns

`Promise`\<`Session`\>

***

### get()

> **get**(`sessionId`): `Promise`\<`Session`\>

Defined in: [core/services/checkout.service.ts:127](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/core/services/checkout.service.ts#L127)

Retrieve a Checkout Session by ID.

#### Parameters

##### sessionId

`string`

#### Returns

`Promise`\<`Session`\>

***

### list()

> **list**(`options?`): `Promise`\<[`PaginatedResponse`](../interfaces/PaginatedResponse.md)\<`Session`\>\>

Defined in: [core/services/checkout.service.ts:149](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/core/services/checkout.service.ts#L149)

List Checkout Sessions with cursor-based pagination.

#### Parameters

##### options?

[`ListCheckoutSessionsOptions`](../interfaces/ListCheckoutSessionsOptions.md)

#### Returns

`Promise`\<[`PaginatedResponse`](../interfaces/PaginatedResponse.md)\<`Session`\>\>
