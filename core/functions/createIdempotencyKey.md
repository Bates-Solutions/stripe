[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / createIdempotencyKey

# Function: createIdempotencyKey()

> **createIdempotencyKey**(): `string`

Defined in: [core/utils.ts:105](https://github.com/Bates-Solutions/stripe/blob/c9f04229824430326404a02bd17b0a539a09cfb3/src/core/utils.ts#L105)

Create a unique idempotency key for Stripe API requests.

Uses the WebCrypto `randomUUID`, so it runs on any modern runtime (Node 22+,
Deno, Bun, Cloudflare Workers) — not just Node.

## Returns

`string`

UUID string

## Example

```typescript
const key = createIdempotencyKey();
// "550e8400-e29b-41d4-a716-446655440000"
```
