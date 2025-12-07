# PaymentLinkDetailed

## Example Usage

```typescript
import { PaymentLinkDetailed } from "stream-sdk/models";

let value: PaymentLinkDetailed = {
  createdAt: new Date("2025-07-31T20:55:23.098Z"),
  updatedAt: new Date("2023-05-23T02:39:45.405Z"),
  id: "<value>",
  name: "<value>",
  amount: "334.09",
  originalAmount: "<value>",
  itemLevelDiscountedAmount: "<value>",
  currency: "Sri Lanka Rupee",
  status: "COMPLETED",
  organizationId: "<value>",
  userId: "<value>",
  items: [
    {
      createdAt: new Date("2023-10-22T21:06:09.572Z"),
      updatedAt: new Date("2025-03-07T14:51:48.415Z"),
      id: "<value>",
      productId: "<value>",
      quantity: 436490,
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
    },
  ],
  coupons: [],
};
```

## Fields

| Field                                                                                         | Type                                                                                          | Required                                                                                      | Description                                                                                   |
| --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| `createdAt`                                                                                   | [Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) | :heavy_check_mark:                                                                            | Creation timestamp of the object.                                                             |
| `updatedAt`                                                                                   | [Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) | :heavy_check_mark:                                                                            | Last modification timestamp of the object.                                                    |
| `id`                                                                                          | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `name`                                                                                        | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `description`                                                                                 | *string*                                                                                      | :heavy_minus_sign:                                                                            | N/A                                                                                           |
| `amount`                                                                                      | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `originalAmount`                                                                              | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `itemLevelDiscountedAmount`                                                                   | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `couponCalculationMetadata`                                                                   | [models.CouponCalculationMetadataDto](../models/couponcalculationmetadatadto.md)              | :heavy_minus_sign:                                                                            | Metadata about how coupons were applied to the payment link                                   |
| `currency`                                                                                    | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `maxNumberOfPayments`                                                                         | *number*                                                                                      | :heavy_minus_sign:                                                                            | N/A                                                                                           |
| `validUntil`                                                                                  | [Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) | :heavy_minus_sign:                                                                            | UTC datetime after which the payment link is no longer valid                                  |
| `confirmationMessage`                                                                         | *string*                                                                                      | :heavy_minus_sign:                                                                            | N/A                                                                                           |
| `recurringInterval`                                                                           | [models.SubscriptionRecurringInterval](../models/subscriptionrecurringinterval.md)            | :heavy_minus_sign:                                                                            | N/A                                                                                           |
| `recurringIntervalCount`                                                                      | *number*                                                                                      | :heavy_minus_sign:                                                                            | N/A                                                                                           |
| `status`                                                                                      | [models.PaymentLinkStatus](../models/paymentlinkstatus.md)                                    | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `organizationId`                                                                              | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `userId`                                                                                      | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `organizationConsumerId`                                                                      | *string*                                                                                      | :heavy_minus_sign:                                                                            | N/A                                                                                           |
| `deactivateMessage`                                                                           | *string*                                                                                      | :heavy_minus_sign:                                                                            | N/A                                                                                           |
| `customFields`                                                                                | Record<string, *any*>                                                                         | :heavy_minus_sign:                                                                            | N/A                                                                                           |
| `successRedirectUrl`                                                                          | *string*                                                                                      | :heavy_minus_sign:                                                                            | N/A                                                                                           |
| `failureRedirectUrl`                                                                          | *string*                                                                                      | :heavy_minus_sign:                                                                            | N/A                                                                                           |
| `customMetadata`                                                                              | Record<string, *any*>                                                                         | :heavy_minus_sign:                                                                            | Custom key-value metadata to be sent to payment gateway and returned in webhooks              |
| `contactInformationType`                                                                      | [models.ContactInformationType](../models/contactinformationtype.md)                          | :heavy_minus_sign:                                                                            | Type of contact information required for payment collection (PHONE or EMAIL)                  |
| `items`                                                                                       | [models.PaymentLinkItemDto](../models/paymentlinkitemdto.md)[]                                | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `coupons`                                                                                     | [models.CouponDto](../models/coupondto.md)[]                                                  | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `overridePaymentMethods`                                                                      | [models.PaymentMethodDto](../models/paymentmethoddto.md)                                      | :heavy_minus_sign:                                                                            | N/A                                                                                           |
| `url`                                                                                         | *string*                                                                                      | :heavy_minus_sign:                                                                            | N/A                                                                                           |
| `amountCollected`                                                                             | *string*                                                                                      | :heavy_minus_sign:                                                                            | Total amount collected from payments                                                          |