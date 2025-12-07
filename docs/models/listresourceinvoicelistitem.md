# ListResourceInvoiceListItem

## Example Usage

```typescript
import { ListResourceInvoiceListItem } from "stream-sdk/models";

let value: ListResourceInvoiceListItem = {
  data: [
    {
      createdAt: new Date("2025-06-28T09:11:26.005Z"),
      updatedAt: null,
      id: "<value>",
      userId: "<value>",
      organizationId: "<value>",
      organizationConsumerId: "<value>",
      accountId: "<value>",
      branchId: "<value>",
      orgInvoiceNumber: 143565,
      totalAmount: "<value>",
      originalAmount: "<value>",
      itemLevelDiscountedAmount: "<value>",
      status: "COMPLETED",
      paymentMethod: "OPENBANKING",
      allowedPaymentFlow: "ALL",
      paidAmount: "<value>",
      organizationConsumer: {
        id: "<value>",
        name: "<value>",
        preferredLanguage: "EN",
      },
      totalNumberOfPayments: 799209,
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

| Field                                                    | Type                                                     | Required                                                 | Description                                              |
| -------------------------------------------------------- | -------------------------------------------------------- | -------------------------------------------------------- | -------------------------------------------------------- |
| `data`                                                   | [models.InvoiceListItem](../models/invoicelistitem.md)[] | :heavy_check_mark:                                       | N/A                                                      |
| `pagination`                                             | [models.Pagination](../models/pagination.md)             | :heavy_check_mark:                                       | N/A                                                      |