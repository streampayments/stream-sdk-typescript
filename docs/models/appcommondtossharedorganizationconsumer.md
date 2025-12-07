# AppCommonDtosSharedOrganizationConsumer

## Example Usage

```typescript
import { AppCommonDtosSharedOrganizationConsumer } from "stream-sdk/models";

let value: AppCommonDtosSharedOrganizationConsumer = {
  id: "<value>",
  name: "<value>",
  preferredLanguage: "AR",
};
```

## Fields

| Field                                                                            | Type                                                                             | Required                                                                         | Description                                                                      |
| -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| `id`                                                                             | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `name`                                                                           | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `alias`                                                                          | *string*                                                                         | :heavy_minus_sign:                                                               | N/A                                                                              |
| `email`                                                                          | *string*                                                                         | :heavy_minus_sign:                                                               | N/A                                                                              |
| `phoneNumber`                                                                    | *string*                                                                         | :heavy_minus_sign:                                                               | N/A                                                                              |
| `preferredLanguage`                                                              | [models.Language](../models/language.md)                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `consumer`                                                                       | [models.AppCommonDtosSharedConsumer](../models/appcommondtossharedconsumer.md)   | :heavy_minus_sign:                                                               | N/A                                                                              |
| `isDeleted`                                                                      | *boolean*                                                                        | :heavy_minus_sign:                                                               | N/A                                                                              |
| `communicationMethods`                                                           | [models.ConsumerCommunicationMethod](../models/consumercommunicationmethod.md)[] | :heavy_minus_sign:                                                               | N/A                                                                              |