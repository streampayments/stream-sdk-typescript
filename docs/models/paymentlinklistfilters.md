# PaymentLinkListFilters

## Example Usage

```typescript
import { PaymentLinkListFilters } from "stream-sdk/models";

let value: PaymentLinkListFilters = {};
```

## Fields

| Field                                                                                         | Type                                                                                          | Required                                                                                      | Description                                                                                   |
| --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| `statuses`                                                                                    | [models.PaymentLinkStatus](../models/paymentlinkstatus.md)[]                                  | :heavy_minus_sign:                                                                            | Filter by subscription status                                                                 |
| `fromDate`                                                                                    | [Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) | :heavy_minus_sign:                                                                            | datetime is created_at                                                                        |
| `toDate`                                                                                      | [Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) | :heavy_minus_sign:                                                                            | datetime is created_at                                                                        |
| `fromPrice`                                                                                   | *models.PaymentLinkListFiltersFromPrice*                                                      | :heavy_minus_sign:                                                                            | limit list by min payment link total amount inclusive                                         |
| `toPrice`                                                                                     | *models.PaymentLinkListFiltersToPrice*                                                        | :heavy_minus_sign:                                                                            | limit list by max payment link total amount inclusive                                         |
| `productIds`                                                                                  | *string*[]                                                                                    | :heavy_minus_sign:                                                                            | Product ids that need to be in the list of payment links                                      |