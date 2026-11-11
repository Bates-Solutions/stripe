[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / CreatePaymentOptions

# Interface: CreatePaymentOptions

Defined in: [core/types/index.ts:71](https://github.com/Bates-Solutions/stripe/blob/3fa5db4b3d85da4031c1d76f0641e98a7929d5c3/src/core/types/index.ts#L71)

Options for creating a payment (PaymentIntent)

## Properties

### amount

> **amount**: `number`

Defined in: [core/types/index.ts:73](https://github.com/Bates-Solutions/stripe/blob/3fa5db4b3d85da4031c1d76f0641e98a7929d5c3/src/core/types/index.ts#L73)

Amount in the smallest currency unit (e.g. cents)

***

### confirm?

> `optional` **confirm?**: `boolean`

Defined in: [core/types/index.ts:84](https://github.com/Bates-Solutions/stripe/blob/3fa5db4b3d85da4031c1d76f0641e98a7929d5c3/src/core/types/index.ts#L84)

Confirm the PaymentIntent immediately after creation.

#### Default

```ts
false
```

***

### currency?

> `optional` **currency?**: [`CurrencyCode`](../type-aliases/CurrencyCode.md)

Defined in: [core/types/index.ts:75](https://github.com/Bates-Solutions/stripe/blob/3fa5db4b3d85da4031c1d76f0641e98a7929d5c3/src/core/types/index.ts#L75)

ISO currency code (default: `usd`)

***

### customerId?

> `optional` **customerId?**: `string`

Defined in: [core/types/index.ts:77](https://github.com/Bates-Solutions/stripe/blob/3fa5db4b3d85da4031c1d76f0641e98a7929d5c3/src/core/types/index.ts#L77)

Customer to attach the payment to

***

### description?

> `optional` **description?**: `string`

Defined in: [core/types/index.ts:86](https://github.com/Bates-Solutions/stripe/blob/3fa5db4b3d85da4031c1d76f0641e98a7929d5c3/src/core/types/index.ts#L86)

Arbitrary description shown in the Stripe dashboard

***

### idempotencyKey?

> `optional` **idempotencyKey?**: `string`

Defined in: [core/types/index.ts:92](https://github.com/Bates-Solutions/stripe/blob/3fa5db4b3d85da4031c1d76f0641e98a7929d5c3/src/core/types/index.ts#L92)

Idempotency key (defaults to a generated UUID)

***

### metadata?

> `optional` **metadata?**: `Record`\<`string`, `string`\>

Defined in: [core/types/index.ts:90](https://github.com/Bates-Solutions/stripe/blob/3fa5db4b3d85da4031c1d76f0641e98a7929d5c3/src/core/types/index.ts#L90)

Key/value metadata attached to the PaymentIntent

***

### paymentMethod?

> `optional` **paymentMethod?**: `string`

Defined in: [core/types/index.ts:79](https://github.com/Bates-Solutions/stripe/blob/3fa5db4b3d85da4031c1d76f0641e98a7929d5c3/src/core/types/index.ts#L79)

Payment method to charge (e.g. `pm_…`)

***

### receiptEmail?

> `optional` **receiptEmail?**: `string`

Defined in: [core/types/index.ts:88](https://github.com/Bates-Solutions/stripe/blob/3fa5db4b3d85da4031c1d76f0641e98a7929d5c3/src/core/types/index.ts#L88)

Email address to send the receipt to
