# InvoicePaymentMethodDto

## Example Usage

```typescript
import { InvoicePaymentMethodDto } from "stream-sdk/models";

let value: InvoicePaymentMethodDto = {
  mada: true,
  visa: false,
  mastercard: true,
  amex: true,
  bankTransfer: true,
  installment: true,
};
```

## Fields

| Field                    | Type                     | Required                 | Description              |
| ------------------------ | ------------------------ | ------------------------ | ------------------------ |
| `mada`                   | *boolean*                | :heavy_check_mark:       | mada is enabled          |
| `visa`                   | *boolean*                | :heavy_check_mark:       | visa is enabled          |
| `mastercard`             | *boolean*                | :heavy_check_mark:       | mastercard is enabled    |
| `amex`                   | *boolean*                | :heavy_check_mark:       | amex is enabled          |
| `bankTransfer`           | *boolean*                | :heavy_check_mark:       | bank_transfer is enabled |
| `installment`            | *boolean*                | :heavy_check_mark:       | installment is enabled   |