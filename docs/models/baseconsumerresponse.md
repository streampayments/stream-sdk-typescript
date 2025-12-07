# BaseConsumerResponse

## Example Usage

```typescript
import { BaseConsumerResponse } from "stream-sdk/models";

let value: BaseConsumerResponse = {
  id: "<value>",
  name: "<value>",
  isDeleted: true,
  createdAt: new Date("2025-09-23T06:43:34.882Z"),
  branch: {
    id: "<value>",
    name: "<value>",
  },
  communicationMethods: [],
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