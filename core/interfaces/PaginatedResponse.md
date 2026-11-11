[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / PaginatedResponse

# Interface: PaginatedResponse\<T\>

Defined in: [core/types/index.ts:51](https://github.com/Bates-Solutions/stripe/blob/fa8bcb341ddb431baa1770084df3a0ac3fee6fff/src/core/types/index.ts#L51)

Common paginated response

## Type Parameters

### T

`T`

## Properties

### data

> **data**: `T`[]

Defined in: [core/types/index.ts:52](https://github.com/Bates-Solutions/stripe/blob/fa8bcb341ddb431baa1770084df3a0ac3fee6fff/src/core/types/index.ts#L52)

***

### hasMore

> **hasMore**: `boolean`

Defined in: [core/types/index.ts:54](https://github.com/Bates-Solutions/stripe/blob/fa8bcb341ddb431baa1770084df3a0ac3fee6fff/src/core/types/index.ts#L54)

Whether more records are available

***

### nextCursor?

> `optional` **nextCursor?**: `string`

Defined in: [core/types/index.ts:56](https://github.com/Bates-Solutions/stripe/blob/fa8bcb341ddb431baa1770084df3a0ac3fee6fff/src/core/types/index.ts#L56)

Cursor to pass as `startingAfter` for the next page
