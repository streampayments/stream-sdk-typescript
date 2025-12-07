# ListSubscriptionsApiV2SubscriptionsGetRequest

## Example Usage

```typescript
import { ListSubscriptionsApiV2SubscriptionsGetRequest } from "stream-sdk/models/operations";

let value: ListSubscriptionsApiV2SubscriptionsGetRequest = {
  filters: {},
};
```

## Fields

| Field                                                                     | Type                                                                      | Required                                                                  | Description                                                               |
| ------------------------------------------------------------------------- | ------------------------------------------------------------------------- | ------------------------------------------------------------------------- | ------------------------------------------------------------------------- |
| `filters`                                                                 | [models.SubscriptionListFilters](../../models/subscriptionlistfilters.md) | :heavy_check_mark:                                                        | N/A                                                                       |
| `page`                                                                    | *number*                                                                  | :heavy_minus_sign:                                                        | Page number, defaults to 1.                                               |
| `limit`                                                                   | *number*                                                                  | :heavy_minus_sign:                                                        | Size of a page, defaults to 10. Maximum is 100.                           |
| `sortField`                                                               | *string*                                                                  | :heavy_minus_sign:                                                        | Field to sort by, e.g., 'amount', 'scheduled_on'                          |
| `sortDirection`                                                           | *string*                                                                  | :heavy_minus_sign:                                                        | Sorting direction ('asc' or 'desc')                                       |