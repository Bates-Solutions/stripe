[**@bates-solutions/stripe API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [server](../README.md) / rawBodyMiddleware

# Variable: rawBodyMiddleware

> `const` **rawBodyMiddleware**: `RequestHandler`

Defined in: [server/middleware/express.ts:138](https://github.com/Bates-Solutions/stripe/blob/99b551ac8e746685da58308357282a60f729ff9d/src/server/middleware/express.ts#L138)

Raw body parser middleware for Express.

Captures the raw body before JSON parsing for signature verification.

## Example

```typescript
import express from 'express';
import { rawBodyMiddleware } from '@bates-solutions/stripe/server';

const app = express();
app.use('/webhook', rawBodyMiddleware);
```
