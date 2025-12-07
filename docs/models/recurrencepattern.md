# RecurrencePattern

## Example Usage

```typescript
import { RecurrencePattern } from "stream-sdk/models";

let value: RecurrencePattern = "Year";
```

## Values

This is an open enum. Unrecognized values will be captured as the `Unrecognized<string>` branded type.

```typescript
"Hour" | "Day" | "Week" | "Fortnight" | "Month" | "Quarter" | "Half-Year" | "Year" | Unrecognized<string>
```