# SubscriptionRecurringInterval

## Example Usage

```typescript
import { SubscriptionRecurringInterval } from "stream-sdk/models";

let value: SubscriptionRecurringInterval = "YEAR";
```

## Values

This is an open enum. Unrecognized values will be captured as the `Unrecognized<string>` branded type.

```typescript
"WEEK" | "MONTH" | "QUARTER" | "YEAR" | Unrecognized<string>
```