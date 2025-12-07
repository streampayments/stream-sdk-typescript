# PaymentRefundRequest

## Example Usage

```typescript
import { PaymentRefundRequest } from "stream-sdk/models";

let value: PaymentRefundRequest = {
  refundReason: "DUPLICATE",
};
```

## Fields

| Field                                                          | Type                                                           | Required                                                       | Description                                                    |
| -------------------------------------------------------------- | -------------------------------------------------------------- | -------------------------------------------------------------- | -------------------------------------------------------------- |
| `refundReason`                                                 | [models.PaymentRefundReason](../models/paymentrefundreason.md) | :heavy_check_mark:                                             | N/A                                                            |
| `refundNote`                                                   | *string*                                                       | :heavy_minus_sign:                                             | N/A                                                            |