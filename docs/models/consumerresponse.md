# ConsumerResponse

## Example Usage

```typescript
import { ConsumerResponse } from "stream-sdk/models";

let value: ConsumerResponse = {
  id: "<value>",
  name: "<value>",
  isDeleted: true,
  createdAt: new Date("2024-02-10T14:10:19.125Z"),
  branch: {
    id: "<value>",
    name: "<value>",
  },
  communicationMethods: [
    "EMAIL",
  ],
  preferredLanguage: "<value>",
};
```

## Fields

| Field                                                                                         | Type                                                                                          | Required                                                                                      | Description                                                                                   |
| --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| `id`                                                                                          | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `name`                                                                                        | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `phoneNumber`                                                                                 | *string*                                                                                      | :heavy_minus_sign:                                                                            | N/A                                                                                           |
| `email`                                                                                       | *string*                                                                                      | :heavy_minus_sign:                                                                            | N/A                                                                                           |
| `externalId`                                                                                  | *string*                                                                                      | :heavy_minus_sign:                                                                            | N/A                                                                                           |
| `consumer`                                                                                    | [models.AppConsumerV2DtosConsumer](../models/appconsumerv2dtosconsumer.md)                    | :heavy_minus_sign:                                                                            | N/A                                                                                           |
| `iban`                                                                                        | *string*                                                                                      | :heavy_minus_sign:                                                                            | N/A                                                                                           |
| `isDeleted`                                                                                   | *boolean*                                                                                     | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `alias`                                                                                       | *string*                                                                                      | :heavy_minus_sign:                                                                            | N/A                                                                                           |
| `createdAt`                                                                                   | [Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `branch`                                                                                      | [models.Branch](../models/branch.md)                                                          | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `comment`                                                                                     | *string*                                                                                      | :heavy_minus_sign:                                                                            | N/A                                                                                           |
| `communicationMethods`                                                                        | [models.ConsumerCommunicationMethod](../models/consumercommunicationmethod.md)[]              | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `preferredLanguage`                                                                           | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |
| `lastInvoiceActivity`                                                                         | [models.LastInvoiceActivity](../models/lastinvoiceactivity.md)                                | :heavy_minus_sign:                                                                            | N/A                                                                                           |