# PaymentStatusEnum

## Example Usage

```typescript
import { PaymentStatusEnum } from "stream-sdk/models";

let value: PaymentStatusEnum = "SETTLED";
```

## Values

This is an open enum. Unrecognized values will be captured as the `Unrecognized<string>` branded type.

```typescript
"PENDING" | "PROCESSING" | "FAILED_INITIATION" | "SUCCEEDED" | "FAILED" | "CANCELED" | "UNDER_REVIEW" | "EXPIRED" | "SETTLED" | "REFUNDED" | Unrecognized<string>
```