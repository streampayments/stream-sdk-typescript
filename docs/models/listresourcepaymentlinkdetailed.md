# ListResourcePaymentLinkDetailed

## Example Usage

```typescript
import { ListResourcePaymentLinkDetailed } from "stream-sdk/models";

let value: ListResourcePaymentLinkDetailed = {
  data: [
    {
      createdAt: new Date("2023-11-25T14:11:37.342Z"),
      updatedAt: new Date("2024-08-10T08:23:08.498Z"),
      id: "<value>",
      name: "<value>",
      amount: "172.90",
      originalAmount: "<value>",
      itemLevelDiscountedAmount: "<value>",
      currency: "Nuevo Sol",
      status: "COMPLETED",
      organizationId: "<value>",
      userId: "<value>",
      items: [
        {
          createdAt: new Date("2023-10-22T21:06:09.572Z"),
          updatedAt: new Date("2025-03-07T14:51:48.415Z"),
          id: "<value>",
          productId: "<value>",
          quantity: 436490,
          originalAmount: "<value>",
          discountedAmount: "<value>",
          product: {
            createdAt: new Date("2025-08-16T23:53:27.130Z"),
            updatedAt: new Date("2024-08-14T15:39:30.361Z"),
            id: "<value>",
            name: "<value>",
            type: "ONE_OFF",
            recurringIntervalCount: 647873,
            price: "131.35",
            isActive: false,
            isOneTime: true,
            isPriceExemptFromVat: true,
            isPriceInclusiveOfVat: false,
            priceExcludingVat: "<value>",
            vatAmount: "<value>",
          },
        },
      ],
      coupons: [
        {
          createdAt: new Date("2024-11-07T05:05:59.670Z"),
          updatedAt: new Date("2024-04-13T00:40:17.680Z"),
          id: "<value>",
          name: "<value>",
          discountValue: "<value>",
          isPercentage: false,
          isActive: false,
        },
      ],
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

| Field                                                            | Type                                                             | Required                                                         | Description                                                      |
| ---------------------------------------------------------------- | ---------------------------------------------------------------- | ---------------------------------------------------------------- | ---------------------------------------------------------------- |
| `data`                                                           | [models.PaymentLinkDetailed](../models/paymentlinkdetailed.md)[] | :heavy_check_mark:                                               | N/A                                                              |
| `pagination`                                                     | [models.Pagination](../models/pagination.md)                     | :heavy_check_mark:                                               | N/A                                                              |