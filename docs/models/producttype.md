# ProductType

## Example Usage

```typescript
import { ProductType } from "stream-sdk/models";

let value: ProductType = "ONE_OFF";
```

## Values

This is an open enum. Unrecognized values will be captured as the `Unrecognized<string>` branded type.

```typescript
"RECURRING" | "ONE_OFF" | Unrecognized<string>
```