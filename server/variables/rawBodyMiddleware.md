[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [server](../README.md) / rawBodyMiddleware

# Variable: rawBodyMiddleware

> `const` **rawBodyMiddleware**: `RequestHandler`

Defined in: [server/middleware/express.ts:138](https://github.com/Bates-Solutions/stripe/blob/3fa5db4b3d85da4031c1d76f0641e98a7929d5c3/src/server/middleware/express.ts#L138)

Raw body parser middleware for Express.

Captures the raw body before JSON parsing for signature verification.

## Example

```typescript
import express from 'express';
import { rawBodyMiddleware } from '@bates-solutions/stripe/server';

const app = express();
app.use('/webhook', rawBodyMiddleware);
```
