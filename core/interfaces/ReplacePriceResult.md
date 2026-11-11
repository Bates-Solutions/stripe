[**@bates-solutions/stripe API Reference v2.0.0**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / ReplacePriceResult

# Interface: ReplacePriceResult

Defined in: [core/services/prices.service.ts:119](https://github.com/Bates-Solutions/stripe/blob/604d8f5290f7d03ad00ba4783eb226f7df45973a/src/core/services/prices.service.ts#L119)

Result of [PricesService.replace](../classes/PricesService.md#replace).

## Properties

### previous

> **previous**: `Price`

Defined in: [core/services/prices.service.ts:123](https://github.com/Bates-Solutions/stripe/blob/604d8f5290f7d03ad00ba4783eb226f7df45973a/src/core/services/prices.service.ts#L123)

The old price, now inactive

***

### price

> **price**: `Price`

Defined in: [core/services/prices.service.ts:121](https://github.com/Bates-Solutions/stripe/blob/604d8f5290f7d03ad00ba4783eb226f7df45973a/src/core/services/prices.service.ts#L121)

The newly created, active price
