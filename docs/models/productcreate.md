# ProductCreate

## Example Usage

```typescript
import { ProductCreate } from "stream-sdk/models";

let value: ProductCreate = {
  name: "<value>",
  price: 4510.03,
  type: "ONE_OFF",
};
```

## Fields

| Field                                                         | Type                                                          | Required                                                      | Description                                                   |
| ------------------------------------------------------------- | ------------------------------------------------------------- | ------------------------------------------------------------- | ------------------------------------------------------------- |
| `name`                                                        | *string*                                                      | :heavy_check_mark:                                            | Name of the product.                                          |
| `description`                                                 | *string*                                                      | :heavy_minus_sign:                                            | Description of the product.                                   |
| `price`                                                       | *models.ProductCreatePrice*                                   | :heavy_check_mark:                                            | Price of the product.                                         |
| `isOneTime`                                                   | *boolean*                                                     | :heavy_minus_sign:                                            | Will this product be used only one time in one invoice?       |
| `type`                                                        | [models.ProductType](../models/producttype.md)                | :heavy_check_mark:                                            | N/A                                                           |
| `recurringInterval`                                           | [models.RecurringInterval](../models/recurringinterval.md)    | :heavy_minus_sign:                                            | Represents the billing cycle interval if product is recurring |
| `recurringIntervalCount`                                      | *number*                                                      | :heavy_minus_sign:                                            | The billing cycle multiple if the product is recurring        |
| `isPriceExemptFromVat`                                        | *boolean*                                                     | :heavy_minus_sign:                                            | Is the price exempt from VAT?                                 |
| `isPriceInclusiveOfVat`                                       | *boolean*                                                     | :heavy_minus_sign:                                            | Is the price inclusive of VAT?                                |