[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / CreatePaymentOptions

# Interface: CreatePaymentOptions

Defined in: [core/types/index.ts:71](https://github.com/Bates-Solutions/stripe/blob/fa8bcb341ddb431baa1770084df3a0ac3fee6fff/src/core/types/index.ts#L71)

Options for creating a payment (PaymentIntent)

## Properties

### amount

> **amount**: `number`

Defined in: [core/types/index.ts:73](https://github.com/Bates-Solutions/stripe/blob/fa8bcb341ddb431baa1770084df3a0ac3fee6fff/src/core/types/index.ts#L73)

Amount in the smallest currency unit (e.g. cents)

***

### confirm?

> `optional` **confirm?**: `boolean`

Defined in: [core/types/index.ts:84](https://github.com/Bates-Solutions/stripe/blob/fa8bcb341ddb431baa1770084df3a0ac3fee6fff/src/core/types/index.ts#L84)

Confirm the PaymentIntent immediately after creation.

#### Default

```ts
false
```

***

### currency?

> `optional` **currency?**: [`CurrencyCode`](../type-aliases/CurrencyCode.md)

Defined in: [core/types/index.ts:75](https://github.com/Bates-Solutions/stripe/blob/fa8bcb341ddb431baa1770084df3a0ac3fee6fff/src/core/types/index.ts#L75)

ISO currency code (default: `usd`)

***

### customerId?

> `optional` **customerId?**: `string`

Defined in: [core/types/index.ts:77](https://github.com/Bates-Solutions/stripe/blob/fa8bcb341ddb431baa1770084df3a0ac3fee6fff/src/core/types/index.ts#L77)

Customer to attach the payment to

***

### description?

> `optional` **description?**: `string`

Defined in: [core/types/index.ts:93](https://github.com/Bates-Solutions/stripe/blob/fa8bcb341ddb431baa1770084df3a0ac3fee6fff/src/core/types/index.ts#L93)

Arbitrary description shown in the Stripe dashboard

***

### idempotencyKey?

> `optional` **idempotencyKey?**: `string`

Defined in: [core/types/index.ts:99](https://github.com/Bates-Solutions/stripe/blob/fa8bcb341ddb431baa1770084df3a0ac3fee6fff/src/core/types/index.ts#L99)

Idempotency key (defaults to a generated UUID)

***

### metadata?

> `optional` **metadata?**: `Record`\<`string`, `string`\>

Defined in: [core/types/index.ts:97](https://github.com/Bates-Solutions/stripe/blob/fa8bcb341ddb431baa1770084df3a0ac3fee6fff/src/core/types/index.ts#L97)

Key/value metadata attached to the PaymentIntent

***

### offSession?

> `optional` **offSession?**: `boolean`

Defined in: [core/types/index.ts:91](https://github.com/Bates-Solutions/stripe/blob/fa8bcb341ddb431baa1770084df3a0ac3fee6fff/src/core/types/index.ts#L91)

The customer is not present (charging a saved payment method). Use with
`confirm: true`. If the bank asks for authentication, Stripe then fails
the payment (`authentication_required`) instead of leaving it in
`requires_action`.

***

### paymentMethod?

> `optional` **paymentMethod?**: `string`

Defined in: [core/types/index.ts:79](https://github.com/Bates-Solutions/stripe/blob/fa8bcb341ddb431baa1770084df3a0ac3fee6fff/src/core/types/index.ts#L79)

Payment method to charge (e.g. `pm_…`)

***

### receiptEmail?

> `optional` **receiptEmail?**: `string`

Defined in: [core/types/index.ts:95](https://github.com/Bates-Solutions/stripe/blob/fa8bcb341ddb431baa1770084df3a0ac3fee6fff/src/core/types/index.ts#L95)

Email address to send the receipt to
