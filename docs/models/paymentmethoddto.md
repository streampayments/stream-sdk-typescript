# PaymentMethodDto

## Example Usage

```typescript
import { PaymentMethodDto } from "stream-sdk/models";

let value: PaymentMethodDto = {};
```

## Fields

| Field                    | Type                     | Required                 | Description              |
| ------------------------ | ------------------------ | ------------------------ | ------------------------ |
| `visa`                   | *boolean*                | :heavy_minus_sign:       | visa is enabled          |
| `mastercard`             | *boolean*                | :heavy_minus_sign:       | mastercard is enabled    |
| `amex`                   | *boolean*                | :heavy_minus_sign:       | amex is enabled          |
| `bankTransfer`           | *boolean*                | :heavy_minus_sign:       | bank_transfer is enabled |
| `installment`            | *boolean*                | :heavy_minus_sign:       | installment is enabled   |