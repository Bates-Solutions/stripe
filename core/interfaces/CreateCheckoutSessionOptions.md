[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / CreateCheckoutSessionOptions

# Interface: CreateCheckoutSessionOptions

Defined in: [core/services/checkout.service.ts:24](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/core/services/checkout.service.ts#L24)

Options for creating a Checkout Session

## Properties

### cancelUrl

> **cancelUrl**: `string`

Defined in: [core/services/checkout.service.ts:37](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/core/services/checkout.service.ts#L37)

URL to redirect to on cancel

***

### clientReferenceId?

> `optional` **clientReferenceId?**: `string`

Defined in: [core/services/checkout.service.ts:43](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/core/services/checkout.service.ts#L43)

Your own reference id echoed back on the session

***

### customerEmail?

> `optional` **customerEmail?**: `string`

Defined in: [core/services/checkout.service.ts:41](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/core/services/checkout.service.ts#L41)

Prefill the email for a new customer (ignored when `customerId` is set)

***

### customerId?

> `optional` **customerId?**: `string`

Defined in: [core/services/checkout.service.ts:39](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/core/services/checkout.service.ts#L39)

Existing customer to attach the session to

***

### idempotencyKey?

> `optional` **idempotencyKey?**: `string`

Defined in: [core/services/checkout.service.ts:47](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/core/services/checkout.service.ts#L47)

Idempotency key (defaults to a generated UUID)

***

### lineItems

> **lineItems**: [`CheckoutLineItem`](CheckoutLineItem.md)[]

Defined in: [core/services/checkout.service.ts:33](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/core/services/checkout.service.ts#L33)

Line items (price + quantity)

***

### metadata?

> `optional` **metadata?**: `Record`\<`string`, `string`\>

Defined in: [core/services/checkout.service.ts:45](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/core/services/checkout.service.ts#L45)

Key/value metadata attached to the session

***

### mode?

> `optional` **mode?**: `Mode`

Defined in: [core/services/checkout.service.ts:31](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/core/services/checkout.service.ts#L31)

Checkout mode.

#### Default

```ts
'subscription'
```

***

### successUrl

> **successUrl**: `string`

Defined in: [core/services/checkout.service.ts:35](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/core/services/checkout.service.ts#L35)

URL to redirect to on success
