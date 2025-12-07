# CouponMetadataDto

## Example Usage

```typescript
import { CouponMetadataDto } from "stream-sdk/models";

let value: CouponMetadataDto = {
  couponId: "<id>",
  name: "<value>",
  isPercentage: false,
  discountValue: "<value>",
  order: 621855,
  amountBeforeDiscount: "<value>",
  discountAmount: "<value>",
  amountAfterDiscount: "<value>",
};
```

## Fields

| Field                  | Type                   | Required               | Description            |
| ---------------------- | ---------------------- | ---------------------- | ---------------------- |
| `couponId`             | *string*               | :heavy_check_mark:     | N/A                    |
| `name`                 | *string*               | :heavy_check_mark:     | N/A                    |
| `isPercentage`         | *boolean*              | :heavy_check_mark:     | N/A                    |
| `discountValue`        | *string*               | :heavy_check_mark:     | N/A                    |
| `order`                | *number*               | :heavy_check_mark:     | N/A                    |
| `amountBeforeDiscount` | *string*               | :heavy_check_mark:     | N/A                    |
| `discountAmount`       | *string*               | :heavy_check_mark:     | N/A                    |
| `amountAfterDiscount`  | *string*               | :heavy_check_mark:     | N/A                    |