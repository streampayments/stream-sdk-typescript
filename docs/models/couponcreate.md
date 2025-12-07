# CouponCreate

## Example Usage

```typescript
import { CouponCreate } from "stream-sdk/models";

let value: CouponCreate = {
  name: "<value>",
  discountValue: 5350.8,
};
```

## Fields

| Field                                                                | Type                                                                 | Required                                                             | Description                                                          |
| -------------------------------------------------------------------- | -------------------------------------------------------------------- | -------------------------------------------------------------------- | -------------------------------------------------------------------- |
| `name`                                                               | *string*                                                             | :heavy_check_mark:                                                   | Name of the coupon.                                                  |
| `discountValue`                                                      | *models.CouponCreateDiscountValue*                                   | :heavy_check_mark:                                                   | Discount value of the coupon (either percentage or fixed).           |
| `isPercentage`                                                       | *boolean*                                                            | :heavy_minus_sign:                                                   | True if the discount is a percentage, False if it is a fixed amount. |
| `isActive`                                                           | *boolean*                                                            | :heavy_minus_sign:                                                   | Indicates if the coupon is active upon creation.                     |