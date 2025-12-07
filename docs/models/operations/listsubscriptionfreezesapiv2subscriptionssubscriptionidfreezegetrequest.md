# ListSubscriptionFreezesApiV2SubscriptionsSubscriptionIdFreezeGetRequest

## Example Usage

```typescript
import { ListSubscriptionFreezesApiV2SubscriptionsSubscriptionIdFreezeGetRequest } from "stream-sdk/models/operations";

let value:
  ListSubscriptionFreezesApiV2SubscriptionsSubscriptionIdFreezeGetRequest = {
    subscriptionId: "008139b4-d490-4b14-a7b6-b65ed1b21f14",
  };
```

## Fields

| Field                                            | Type                                             | Required                                         | Description                                      |
| ------------------------------------------------ | ------------------------------------------------ | ------------------------------------------------ | ------------------------------------------------ |
| `subscriptionId`                                 | *string*                                         | :heavy_check_mark:                               | N/A                                              |
| `page`                                           | *number*                                         | :heavy_minus_sign:                               | Page number, defaults to 1.                      |
| `limit`                                          | *number*                                         | :heavy_minus_sign:                               | Size of a page, defaults to 10. Maximum is 100.  |
| `sortField`                                      | *string*                                         | :heavy_minus_sign:                               | Field to sort by, e.g., 'amount', 'scheduled_on' |
| `sortDirection`                                  | *string*                                         | :heavy_minus_sign:                               | Sorting direction ('asc' or 'desc')              |