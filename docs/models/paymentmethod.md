# PaymentMethod

## Example Usage

```typescript
import { PaymentMethod } from "stream-sdk/models";

let value: PaymentMethod = "CARD";
```

## Values

This is an open enum. Unrecognized values will be captured as the `Unrecognized<string>` branded type.

```typescript
"MADA" | "MASTERCARD" | "VISA" | "APPLE_PAY" | "AMEX" | "CASH" | "PGW_CARD_UNSPECIFIED" | "BANK_TRANSFER" | "CARD" | "QURRAH" | Unrecognized<string>
```