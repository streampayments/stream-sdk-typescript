# PaymentLinkStatus

## Example Usage

```typescript
import { PaymentLinkStatus } from "stream-sdk/models";

let value: PaymentLinkStatus = "INACTIVE";
```

## Values

This is an open enum. Unrecognized values will be captured as the `Unrecognized<string>` branded type.

```typescript
"INACTIVE" | "ACTIVE" | "COMPLETED" | Unrecognized<string>
```