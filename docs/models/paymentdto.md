# PaymentDto

## Example Usage

```typescript
import { PaymentDto } from "stream-sdk/models";

let value: PaymentDto = {
  id: "<value>",
  amount: "875.62",
  currency: "Liberian Dollar",
  scheduledOn: new Date("2024-05-19T01:54:05.828Z"),
  invoicePaymentNumber: 355892,
  type: "INSTALLMENT",
  currentStatus: "FAILED_INITIATION",
};
```

## Fields

| Field                                                                                         | Type                                                                                          | Required                                                                                      | Description                                                                                   |
| --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| `id`                                                                                          | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `amount`                                                                                      | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `currency`                                                                                    | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `scheduledOn`                                                                                 | [Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `invoicePaymentNumber`                                                                        | *number*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `type`                                                                                        | [models.PaymentTypeEnum](../models/paymenttypeenum.md)                                        | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `paymentMethod`                                                                               | [models.PaymentMethod](../models/paymentmethod.md)                                            | :heavy_minus_sign:                                                                            | N/A                                                                                           |
| `currentStatus`                                                                               | [models.PaymentStatusEnum](../models/paymentstatusenum.md)                                    | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `payedAt`                                                                                     | [Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) | :heavy_minus_sign:                                                                            | N/A                                                                                           |
| `settledAt`                                                                                   | [Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) | :heavy_minus_sign:                                                                            | N/A                                                                                           |
| `refundedAt`                                                                                  | [Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) | :heavy_minus_sign:                                                                            | N/A                                                                                           |
| `pdfLink`                                                                                     | *string*                                                                                      | :heavy_minus_sign:                                                                            | N/A                                                                                           |
| `paidToAccountId`                                                                             | *string*                                                                                      | :heavy_minus_sign:                                                                            | N/A                                                                                           |