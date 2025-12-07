# CouponUpdate

## Example Usage

```typescript
import { CouponUpdate } from "stream-sdk/models";

let value: CouponUpdate = {};
```

## Fields

| Field                                                                | Type                                                                 | Required                                                             | Description                                                          |
| -------------------------------------------------------------------- | -------------------------------------------------------------------- | -------------------------------------------------------------------- | -------------------------------------------------------------------- |
| `name`                                                               | *string*                                                             | :heavy_minus_sign:                                                   | Updated name of the coupon.                                          |
| `discountValue`                                                      | *models.CouponUpdateDiscountValue*                                   | :heavy_minus_sign:                                                   | Updated discount value (either percentage or fixed).                 |
| `isPercentage`                                                       | *boolean*                                                            | :heavy_minus_sign:                                                   | True if the discount is a percentage, False if it is a fixed amount. |
| `isActive`                                                           | *boolean*                                                            | :heavy_minus_sign:                                                   | Whether the coupon should be active or inactive.                     |