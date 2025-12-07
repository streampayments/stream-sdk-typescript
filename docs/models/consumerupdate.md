# ConsumerUpdate

Consumer update model that inherits from ConsumerCreate but makes all fields optional.

## Example Usage

```typescript
import { ConsumerUpdate } from "stream-sdk/models";

let value: ConsumerUpdate = {};
```

## Fields

| Field                                                                            | Type                                                                             | Required                                                                         | Description                                                                      |
| -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| `name`                                                                           | *string*                                                                         | :heavy_minus_sign:                                                               | N/A                                                                              |
| `phoneNumber`                                                                    | *string*                                                                         | :heavy_minus_sign:                                                               | N/A                                                                              |
| `email`                                                                          | *string*                                                                         | :heavy_minus_sign:                                                               | N/A                                                                              |
| `externalId`                                                                     | *string*                                                                         | :heavy_minus_sign:                                                               | N/A                                                                              |
| `iban`                                                                           | *string*                                                                         | :heavy_minus_sign:                                                               | N/A                                                                              |
| `alias`                                                                          | *string*                                                                         | :heavy_minus_sign:                                                               | N/A                                                                              |
| `comment`                                                                        | *string*                                                                         | :heavy_minus_sign:                                                               | N/A                                                                              |
| `preferredLanguage`                                                              | *string*                                                                         | :heavy_minus_sign:                                                               | Preferred language                                                               |
| `communicationMethods`                                                           | [models.ConsumerCommunicationMethod](../models/consumercommunicationmethod.md)[] | :heavy_minus_sign:                                                               | N/A                                                                              |