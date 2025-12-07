# PaymentResponse

## Example Usage

```typescript
import { PaymentResponse } from "stream-sdk/models";

let value: PaymentResponse = {
  id: "3a1ca8a1-3c10-4ac9-b741-eeb19a6b3c84",
  amount: "689.77",
  scheduledOn: "<value>",
  type: "INSTALLMENT",
  currentStatus: "PROCESSING",
};
```

## Fields

| Field                                                                                         | Type                                                                                          | Required                                                                                      | Description                                                                                   |
| --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| `id`                                                                                          | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `amount`                                                                                      | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `scheduledOn`                                                                                 | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `type`                                                                                        | [models.PaymentTypeEnum](../models/paymenttypeenum.md)                                        | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `paymentMethod`                                                                               | [models.PaymentMethod](../models/paymentmethod.md)                                            | :heavy_minus_sign:                                                                            | N/A                                                                                           |
| `currentStatus`                                                                               | [models.PaymentStatusEnum](../models/paymentstatusenum.md)                                    | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `payedAt`                                                                                     | [Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) | :heavy_minus_sign:                                                                            | N/A                                                                                           |
| `refundedAt`                                                                                  | [Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) | :heavy_minus_sign:                                                                            | N/A                                                                                           |
| `refundReason`                                                                                | [models.PaymentRefundReason](../models/paymentrefundreason.md)                                | :heavy_minus_sign:                                                                            | N/A                                                                                           |
| `refundNote`                                                                                  | *string*                                                                                      | :heavy_minus_sign:                                                                            | N/A                                                                                           |