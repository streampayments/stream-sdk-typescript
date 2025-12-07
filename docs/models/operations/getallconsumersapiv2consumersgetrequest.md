# GetAllConsumersApiV2ConsumersGetRequest

## Example Usage

```typescript
import { GetAllConsumersApiV2ConsumersGetRequest } from "stream-sdk/models/operations";

let value: GetAllConsumersApiV2ConsumersGetRequest = {};
```

## Fields

| Field                                            | Type                                             | Required                                         | Description                                      |
| ------------------------------------------------ | ------------------------------------------------ | ------------------------------------------------ | ------------------------------------------------ |
| `page`                                           | *number*                                         | :heavy_minus_sign:                               | Page number, defaults to 1.                      |
| `limit`                                          | *number*                                         | :heavy_minus_sign:                               | Size of a page, defaults to 10. Maximum is 100.  |
| `searchTerm`                                     | *string*                                         | :heavy_minus_sign:                               | N/A                                              |
| `sortField`                                      | *string*                                         | :heavy_minus_sign:                               | Field to sort by, e.g., 'amount', 'scheduled_on' |
| `sortDirection`                                  | *string*                                         | :heavy_minus_sign:                               | Sorting direction ('asc' or 'desc')              |