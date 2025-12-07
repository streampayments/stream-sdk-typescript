# ListResourceConsumerResponse

## Example Usage

```typescript
import { ListResourceConsumerResponse } from "stream-sdk/models";

let value: ListResourceConsumerResponse = {
  data: [
    {
      id: "<value>",
      name: "<value>",
      isDeleted: false,
      createdAt: new Date("2024-02-24T23:43:56.657Z"),
      branch: {
        id: "<value>",
        name: "<value>",
      },
      communicationMethods: [
        "WHATSAPP",
      ],
      preferredLanguage: "<value>",
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

| Field                                                      | Type                                                       | Required                                                   | Description                                                |
| ---------------------------------------------------------- | ---------------------------------------------------------- | ---------------------------------------------------------- | ---------------------------------------------------------- |
| `data`                                                     | [models.ConsumerResponse](../models/consumerresponse.md)[] | :heavy_check_mark:                                         | N/A                                                        |
| `pagination`                                               | [models.Pagination](../models/pagination.md)               | :heavy_check_mark:                                         | N/A                                                        |