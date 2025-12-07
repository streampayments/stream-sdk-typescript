# CouponDto

## Example Usage

```typescript
import { CouponDto } from "stream-sdk/models";

let value: CouponDto = {
  createdAt: new Date("2023-11-21T16:38:11.399Z"),
  updatedAt: new Date("2024-05-22T07:05:01.549Z"),
  id: "<value>",
  name: "<value>",
  discountValue: "<value>",
  isPercentage: false,
  isActive: true,
};
```

## Fields

| Field                                                                                         | Type                                                                                          | Required                                                                                      | Description                                                                                   |
| --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| `createdAt`                                                                                   | [Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) | :heavy_check_mark:                                                                            | Creation timestamp of the object.                                                             |
| `updatedAt`                                                                                   | [Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) | :heavy_check_mark:                                                                            | Last modification timestamp of the object.                                                    |
| `id`                                                                                          | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `name`                                                                                        | *string*                                                                                      | :heavy_check_mark:                                                                            | Name of the coupon.                                                                           |
| `discountValue`                                                                               | *string*                                                                                      | :heavy_check_mark:                                                                            | Discount value of the coupon (either percentage or fixed).                                    |
| `isPercentage`                                                                                | *boolean*                                                                                     | :heavy_check_mark:                                                                            | True if the discount is a percentage, False if it is a fixed amount.                          |
| `isActive`                                                                                    | *boolean*                                                                                     | :heavy_check_mark:                                                                            | Indicates if the coupon is currently active.                                                  |