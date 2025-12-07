# SubscriptionStatus

## Example Usage

```typescript
import { SubscriptionStatus } from "stream-sdk/models";

let value: SubscriptionStatus = "CANCELED";
```

## Values

This is an open enum. Unrecognized values will be captured as the `Unrecognized<string>` branded type.

```typescript
"INACTIVE" | "ACTIVE" | "EXPIRED" | "CANCELED" | "FROZEN" | Unrecognized<string>
```