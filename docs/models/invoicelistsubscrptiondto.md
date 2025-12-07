# InvoiceListSubscrptionDto

## Example Usage

```typescript
import { InvoiceListSubscrptionDto } from "stream-sdk/models";

let value: InvoiceListSubscrptionDto = {
  id: "<value>",
  recurringInterval: "WEEK",
  recurringIntervalCount: 552212,
  status: "ACTIVE",
  currentPeriodStart: new Date("2025-09-10T09:47:22.198Z"),
  cancelAtPeriodEnd: true,
};
```

## Fields

| Field                                                                                         | Type                                                                                          | Required                                                                                      | Description                                                                                   |
| --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| `id`                                                                                          | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `recurringInterval`                                                                           | [models.SubscriptionRecurringInterval](../models/subscriptionrecurringinterval.md)            | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `recurringIntervalCount`                                                                      | *number*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `status`                                                                                      | [models.SubscriptionStatus](../models/subscriptionstatus.md)                                  | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `currentPeriodStart`                                                                          | [Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `currentPeriodEnd`                                                                            | [Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) | :heavy_minus_sign:                                                                            | N/A                                                                                           |
| `cancelAtPeriodEnd`                                                                           | *boolean*                                                                                     | :heavy_check_mark:                                                                            | N/A                                                                                           |