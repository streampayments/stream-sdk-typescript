# ProductDto

## Example Usage

```typescript
import { ProductDto } from "stream-sdk/models";

let value: ProductDto = {
  createdAt: new Date("2023-02-28T01:04:05.676Z"),
  updatedAt: new Date("2024-04-18T15:08:08.966Z"),
  id: "<value>",
  name: "<value>",
  type: "ONE_OFF",
  recurringIntervalCount: 942423,
  price: "674.85",
  isActive: false,
  isOneTime: false,
  isPriceExemptFromVat: false,
  isPriceInclusiveOfVat: false,
  priceExcludingVat: "<value>",
  vatAmount: "<value>",
};
```

## Fields

| Field                                                                                         | Type                                                                                          | Required                                                                                      | Description                                                                                   |
| --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| `createdAt`                                                                                   | [Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) | :heavy_check_mark:                                                                            | Creation timestamp of the object.                                                             |
| `updatedAt`                                                                                   | [Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) | :heavy_check_mark:                                                                            | Last modification timestamp of the object.                                                    |
| `id`                                                                                          | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `name`                                                                                        | *string*                                                                                      | :heavy_check_mark:                                                                            | Name of the product.                                                                          |
| `description`                                                                                 | *string*                                                                                      | :heavy_minus_sign:                                                                            | Description of the product.                                                                   |
| `type`                                                                                        | [models.ProductType](../models/producttype.md)                                                | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `recurringInterval`                                                                           | [models.RecurringInterval](../models/recurringinterval.md)                                    | :heavy_minus_sign:                                                                            | Represents the billing cycle interval if product is recurring                                 |
| `recurringIntervalCount`                                                                      | *number*                                                                                      | :heavy_check_mark:                                                                            | The billing cycle multiple if the product is recurring                                        |
| `price`                                                                                       | *string*                                                                                      | :heavy_check_mark:                                                                            | Total price including VAT.                                                                    |
| `currency`                                                                                    | [models.Currency](../models/currency.md)                                                      | :heavy_minus_sign:                                                                            | Price currency of the product.                                                                |
| `isActive`                                                                                    | *boolean*                                                                                     | :heavy_check_mark:                                                                            | Can this product be used in invoices or subscriptions?                                        |
| `isOneTime`                                                                                   | *boolean*                                                                                     | :heavy_check_mark:                                                                            | Shows if the product was created to be used once, and not to be added to product cataloge     |
| `isPriceExemptFromVat`                                                                        | *boolean*                                                                                     | :heavy_check_mark:                                                                            | Is the price exempt from VAT?                                                                 |
| `isPriceInclusiveOfVat`                                                                       | *boolean*                                                                                     | :heavy_check_mark:                                                                            | Is the price inclusive of VAT?                                                                |
| `priceExcludingVat`                                                                           | *string*                                                                                      | :heavy_check_mark:                                                                            | Price excluding VAT.                                                                          |
| `vatAmount`                                                                                   | *string*                                                                                      | :heavy_check_mark:                                                                            | VAT amount.                                                                                   |
| `isUsedInFinalizedInvoice`                                                                    | *boolean*                                                                                     | :heavy_minus_sign:                                                                            | Is the product used in a finalized invoice?                                                   |