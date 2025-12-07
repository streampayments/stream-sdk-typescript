# CouponCalculationMetadataDto

## Example Usage

```typescript
import { CouponCalculationMetadataDto } from "stream-sdk/models";

let value: CouponCalculationMetadataDto = {
  coupons: [
    {
      couponId: "<id>",
      name: "<value>",
      isPercentage: false,
      discountValue: "<value>",
      order: 645433,
      amountBeforeDiscount: "<value>",
      discountAmount: "<value>",
      amountAfterDiscount: "<value>",
    },
  ],
};
```

## Fields

| Field                                                        | Type                                                         | Required                                                     | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| `coupons`                                                    | [models.CouponMetadataDto](../models/couponmetadatadto.md)[] | :heavy_check_mark:                                           | N/A                                                          |