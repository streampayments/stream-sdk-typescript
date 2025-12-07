# ListResourceSubscriptionDetailed

## Example Usage

```typescript
import { ListResourceSubscriptionDetailed } from "stream-sdk/models";

let value: ListResourceSubscriptionDetailed = {
  data: [
    {
      createdAt: new Date("2024-07-18T06:58:35.974Z"),
      updatedAt: new Date("2025-08-23T01:26:20.312Z"),
      id: "<value>",
      amount: "898.01",
      originalAmount: "<value>",
      itemLevelDiscountedAmount: "<value>",
      remainingDays: 260250,
      currency: "CFA Franc BEAC",
      recurringInterval: "QUARTER",
      recurringIntervalCount: 143454,
      status: "CANCELED",
      currentPeriodStart: new Date("2023-05-22T06:11:17.754Z"),
      currentPeriodEnd: new Date("2024-01-02T09:54:22.984Z"),
      currentCycleNumber: 61657,
      cancelAtPeriodEnd: false,
      userId: "<value>",
      organizationConsumerId: "<value>",
    },
  ],
  pagination: {
    totalCount: 39682,
    maxPage: 53121,
    currentPage: 507109,
    limit: 753614,
    hasNextPage: false,
    hasPreviousPage: false,
  },
};
```

## Fields

| Field                                                              | Type                                                               | Required                                                           | Description                                                        |
| ------------------------------------------------------------------ | ------------------------------------------------------------------ | ------------------------------------------------------------------ | ------------------------------------------------------------------ |
| `data`                                                             | [models.SubscriptionDetailed](../models/subscriptiondetailed.md)[] | :heavy_check_mark:                                                 | N/A                                                                |
| `pagination`                                                       | [models.Pagination](../models/pagination.md)                       | :heavy_check_mark:                                                 | N/A                                                                |