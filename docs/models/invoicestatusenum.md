# InvoiceStatusEnum

Invoice status enum representing the lifecycle/state of an invoice.

Status describes the current stage of an invoice in its lifecycle (DRAFT → CREATED → SENT → ACCEPTED → COMPLETED).
This changes over time as the invoice progresses. Different from InvoiceType which describes the payment structure.

## Example Usage

```typescript
import { InvoiceStatusEnum } from "stream-sdk/models";

let value: InvoiceStatusEnum = "SENT";
```

## Values

This is an open enum. Unrecognized values will be captured as the `Unrecognized<string>` branded type.

```typescript
"DRAFT" | "CREATED" | "SENT" | "ACCEPTED" | "REJECTED" | "COMPLETED" | "CANCELED" | "EXPIRED" | Unrecognized<string>
```