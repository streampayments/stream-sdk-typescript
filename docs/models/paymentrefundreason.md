# PaymentRefundReason

## Example Usage

```typescript
import { PaymentRefundReason } from "stream-sdk/models";

let value: PaymentRefundReason = "FRAUDLENT";
```

## Values

This is an open enum. Unrecognized values will be captured as the `Unrecognized<string>` branded type.

```typescript
"REQUESTED_BY_CUSTOMER" | "DUPLICATE" | "FRAUDLENT" | "OTHER" | Unrecognized<string>
```