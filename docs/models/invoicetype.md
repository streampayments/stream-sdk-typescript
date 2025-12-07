# InvoiceType

Invoice type enum representing the payment structure/pattern of an invoice.

Type describes how the invoice is structured for payments (ONE_OFF, RECURRING, INSTALLMENTS, etc.).
This is determined at invoice creation and typically doesn't change. Different from InvoiceStatusEnum
which describes the current lifecycle state of the invoice.

## Example Usage

```typescript
import { InvoiceType } from "stream-sdk/models";

let value: InvoiceType = "INSTALLMENTS";
```

## Values

This is an open enum. Unrecognized values will be captured as the `Unrecognized<string>` branded type.

```typescript
"ONE_OFF" | "ONE_OFF_FUTURE" | "RECURRING" | "INSTALLMENTS" | Unrecognized<string>
```