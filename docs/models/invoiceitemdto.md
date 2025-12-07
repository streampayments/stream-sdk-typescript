# InvoiceItemDto

## Example Usage

```typescript
import { InvoiceItemDto } from "stream-sdk/models";

let value: InvoiceItemDto = {
  createdAt: new Date("2025-03-06T18:59:37.754Z"),
  updatedAt: new Date("2025-09-13T08:29:59.270Z"),
  id: "<value>",
  productId: "<value>",
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
  quantity: 636018,
  originalAmount: "<value>",
  discountedAmount: "<value>",
};
```

## Fields

| Field                                                                                         | Type                                                                                          | Required                                                                                      | Description                                                                                   |
| --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| `createdAt`                                                                                   | [Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) | :heavy_check_mark:                                                                            | Creation timestamp of the object.                                                             |
| `updatedAt`                                                                                   | [Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) | :heavy_check_mark:                                                                            | Last modification timestamp of the object.                                                    |
| `id`                                                                                          | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `productId`                                                                                   | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `product`                                                                                     | [models.ProductDto](../models/productdto.md)                                                  | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `quantity`                                                                                    | *number*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `originalAmount`                                                                              | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `discountedAmount`                                                                            | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `couponCalculationMetadata`                                                                   | [models.CouponCalculationMetadataDto](../models/couponcalculationmetadatadto.md)              | :heavy_minus_sign:                                                                            | Metadata about how coupons were applied to this item                                          |