# ListCouponsApiV2CouponsGetRequest

## Example Usage

```typescript
import { ListCouponsApiV2CouponsGetRequest } from "stream-sdk/models/operations";

let value: ListCouponsApiV2CouponsGetRequest = {};
```

## Fields

| Field                                               | Type                                                | Required                                            | Description                                         |
| --------------------------------------------------- | --------------------------------------------------- | --------------------------------------------------- | --------------------------------------------------- |
| `page`                                              | *number*                                            | :heavy_minus_sign:                                  | Page number, defaults to 1.                         |
| `limit`                                             | *number*                                            | :heavy_minus_sign:                                  | Size of a page, defaults to 10. Maximum is 100.     |
| `searchTerm`                                        | *string*                                            | :heavy_minus_sign:                                  | Search by coupon name.                              |
| `active`                                            | *boolean*                                           | :heavy_minus_sign:                                  | Filter by active or inactive coupons.               |
| `isPercentage`                                      | *boolean*                                           | :heavy_minus_sign:                                  | Filter by percentage-based or fixed-amount coupons. |
| `sortField`                                         | *string*                                            | :heavy_minus_sign:                                  | Field to sort by, e.g., 'amount', 'scheduled_on'    |
| `sortDirection`                                     | *string*                                            | :heavy_minus_sign:                                  | Sorting direction ('asc' or 'desc')                 |