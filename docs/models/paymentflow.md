# PaymentFlow

## Example Usage

```typescript
import { PaymentFlow } from "stream-sdk/models";

let value: PaymentFlow = "MANUAL";
```

## Values

This is an open enum. Unrecognized values will be captured as the `Unrecognized<string>` branded type.

```typescript
"ALL" | "AUTO" | "MANUAL" | Unrecognized<string>
```