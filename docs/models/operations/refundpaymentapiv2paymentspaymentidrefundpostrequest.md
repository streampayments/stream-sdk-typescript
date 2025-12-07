# RefundPaymentApiV2PaymentsPaymentIdRefundPostRequest

## Example Usage

```typescript
import { RefundPaymentApiV2PaymentsPaymentIdRefundPostRequest } from "stream-sdk/models/operations";

let value: RefundPaymentApiV2PaymentsPaymentIdRefundPostRequest = {
  paymentId: "2a639947-0216-489f-ab5a-a13422ab38e4",
  body: {
    refundReason: "OTHER",
  },
};
```

## Fields

| Field                                                               | Type                                                                | Required                                                            | Description                                                         |
| ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- |
| `paymentId`                                                         | *string*                                                            | :heavy_check_mark:                                                  | N/A                                                                 |
| `body`                                                              | [models.PaymentRefundRequest](../../models/paymentrefundrequest.md) | :heavy_check_mark:                                                  | N/A                                                                 |