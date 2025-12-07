# SubscriptionItemCreateDto

## Example Usage

```typescript
import { SubscriptionItemCreateDto } from "stream-sdk/models";

let value: SubscriptionItemCreateDto = {
  productId: "<value>",
  quantity: 935747,
};
```

## Fields

| Field                                                 | Type                                                  | Required                                              | Description                                           |
| ----------------------------------------------------- | ----------------------------------------------------- | ----------------------------------------------------- | ----------------------------------------------------- |
| `productId`                                           | *string*                                              | :heavy_check_mark:                                    | N/A                                                   |
| `quantity`                                            | *number*                                              | :heavy_check_mark:                                    | Quantity must be greater than 0                       |
| `coupons`                                             | *string*[]                                            | :heavy_minus_sign:                                    | coupons to apply to this specific item for discounts. |