# Language

## Example Usage

```typescript
import { Language } from "stream-sdk/models";

let value: Language = "EN";
```

## Values

This is an open enum. Unrecognized values will be captured as the `Unrecognized<string>` branded type.

```typescript
"AR" | "EN" | Unrecognized<string>
```