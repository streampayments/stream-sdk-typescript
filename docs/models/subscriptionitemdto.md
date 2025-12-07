# SubscriptionItemDto

## Example Usage

```typescript
import { SubscriptionItemDto } from "stream-sdk/models";

let value: SubscriptionItemDto = {
  createdAt: new Date("2025-06-16T21:10:54.556Z"),
  updatedAt: new Date("2024-06-12T09:45:07.541Z"),
  id: "<value>",
  productId: "<value>",
  subscriptionId: "<value>",
  quantity: 201440,
  originalAmount: "<value>",
  discountedAmount: "<value>",
  product: {
    createdAt: new Date("2025-08-16T23:53:27.130Z"),
    updatedAt: new Date("2024-08-14T15:39:30.361Z"),
    id: "<value>",
    name: "<value>",
    type: "ONE_OFF",
    recurringIntervalCount: 647873,
    price: "131.35",
    isActive: false,
    isOneTime: true,
    isPriceExemptFromVat: true,
    isPriceInclusiveOfVat: false,
    priceExcludingVat: "<value>",
    vatAmount: "<value>",
  },
};
```

## Fields

| Field                                                                                         | Type                                                                                          | Required                                                                                      | Description                                                                                   |
| --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| `createdAt`                                                                                   | [Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) | :heavy_check_mark:                                                                            | Creation timestamp of the object.                                                             |
| `updatedAt`                                                                                   | [Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) | :heavy_check_mark:                                                                            | Last modification timestamp of the object.                                                    |
| `id`                                                                                          | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `productId`                                                                                   | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `subscriptionId`                                                                              | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `quantity`                                                                                    | *number*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `originalAmount`                                                                              | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `discountedAmount`                                                                            | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `couponCalculationMetadata`                                                                   | [models.CouponCalculationMetadataDto](../models/couponcalculationmetadatadto.md)              | :heavy_minus_sign:                                                                            | Metadata about how coupons were applied to this item                                          |
| `product`                                                                                     | [models.ProductDto](../models/productdto.md)                                                  | :heavy_check_mark:                                                                            | N/A                                                                                           |