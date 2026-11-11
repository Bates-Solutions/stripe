[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / TimeRange

# Interface: TimeRange

Defined in: [core/types/index.ts:37](https://github.com/Bates-Solutions/stripe/blob/c9f04229824430326404a02bd17b0a539a09cfb3/src/core/types/index.ts#L37)

A time range filter, e.g. on an object's `created` time. Each bound is a
`Date` or Unix seconds; omit a bound to leave that side open.

## Example

```typescript
// Everything created in March 2026 (UTC)
const march = { gte: new Date('2026-03-01T00:00:00Z'), lt: new Date('2026-04-01T00:00:00Z') };
```

## Properties

### gt?

> `optional` **gt?**: `number` \| `Date`

Defined in: [core/types/index.ts:41](https://github.com/Bates-Solutions/stripe/blob/c9f04229824430326404a02bd17b0a539a09cfb3/src/core/types/index.ts#L41)

Strictly after

***

### gte?

> `optional` **gte?**: `number` \| `Date`

Defined in: [core/types/index.ts:39](https://github.com/Bates-Solutions/stripe/blob/c9f04229824430326404a02bd17b0a539a09cfb3/src/core/types/index.ts#L39)

On or after

***

### lt?

> `optional` **lt?**: `number` \| `Date`

Defined in: [core/types/index.ts:45](https://github.com/Bates-Solutions/stripe/blob/c9f04229824430326404a02bd17b0a539a09cfb3/src/core/types/index.ts#L45)

Strictly before

***

### lte?

> `optional` **lte?**: `number` \| `Date`

Defined in: [core/types/index.ts:43](https://github.com/Bates-Solutions/stripe/blob/c9f04229824430326404a02bd17b0a539a09cfb3/src/core/types/index.ts#L43)

On or before
