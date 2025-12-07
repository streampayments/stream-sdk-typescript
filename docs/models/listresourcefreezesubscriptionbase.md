# ListResourceFreezeSubscriptionBase

## Example Usage

```typescript
import { ListResourceFreezeSubscriptionBase } from "stream-sdk/models";

let value: ListResourceFreezeSubscriptionBase = {
  data: [
    {
      createdAt: new Date("2024-07-25T15:49:37.942Z"),
      updatedAt: new Date("2025-10-30T18:26:09.922Z"),
      id: "90182f4e-a2e0-4ded-a4f1-3bdc679a99b2",
      freezeStartDatetime: new Date("2025-06-17T03:33:14.439Z"),
      subscriptionId: "0862d108-d1cf-47ae-bd03-02c24a0196cd",
      invoiceId: "a7f1de6e-863d-4c61-a1fa-c9fea88831f7",
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

| Field                                                                  | Type                                                                   | Required                                                               | Description                                                            |
| ---------------------------------------------------------------------- | ---------------------------------------------------------------------- | ---------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| `data`                                                                 | [models.FreezeSubscriptionBase](../models/freezesubscriptionbase.md)[] | :heavy_check_mark:                                                     | N/A                                                                    |
| `pagination`                                                           | [models.Pagination](../models/pagination.md)                           | :heavy_check_mark:                                                     | N/A                                                                    |