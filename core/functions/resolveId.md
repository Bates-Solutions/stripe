[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / resolveId

# Function: resolveId()

> **resolveId**(`value`): `string` \| `undefined`

Defined in: [core/utils.ts:221](https://github.com/Bates-Solutions/stripe/blob/3fa5db4b3d85da4031c1d76f0641e98a7929d5c3/src/core/utils.ts#L221)

Resolve a Stripe reference that may be either an ID string or an expanded
object, to its ID.

Stripe fields like `customer` / `subscription` / `product` are a bare ID
string unless expanded, in which case they are the full object. This
collapses both forms.

## Parameters

### value

`string` \| \{ `id?`: `string`; \} \| `null` \| `undefined`

## Returns

`string` \| `undefined`

## Example

```typescript
resolveId('cus_1');          // 'cus_1'
resolveId({ id: 'cus_1' });  // 'cus_1'
resolveId(null);             // undefined
```
