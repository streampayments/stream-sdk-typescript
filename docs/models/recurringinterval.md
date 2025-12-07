# RecurringInterval

## Example Usage

```typescript
import { RecurringInterval } from "stream-sdk/models";

let value: RecurringInterval = "YEAR";
```

## Values

This is an open enum. Unrecognized values will be captured as the `Unrecognized<string>` branded type.

```typescript
"WEEK" | "MONTH" | "SEMESTER" | "YEAR" | Unrecognized<string>
```