# ConsumerCreate

Consumer creation model.

## Example Usage

```typescript
import { ConsumerCreate } from "stream-sdk/models";

let value: ConsumerCreate = {
  name: "<value>",
};
```

## Fields

| Field                                                                            | Type                                                                             | Required                                                                         | Description                                                                      |
| -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| `name`                                                                           | *string*                                                                         | :heavy_check_mark:                                                               | Consumer name                                                                    |
| `phoneNumber`                                                                    | *string*                                                                         | :heavy_minus_sign:                                                               | Phone number                                                                     |
| `email`                                                                          | *string*                                                                         | :heavy_minus_sign:                                                               | Email address                                                                    |
| `externalId`                                                                     | *string*                                                                         | :heavy_minus_sign:                                                               | External ID                                                                      |
| `iban`                                                                           | *string*                                                                         | :heavy_minus_sign:                                                               | IBAN                                                                             |
| `alias`                                                                          | *string*                                                                         | :heavy_minus_sign:                                                               | Alias                                                                            |
| `comment`                                                                        | *string*                                                                         | :heavy_minus_sign:                                                               | Comment                                                                          |
| `preferredLanguage`                                                              | *string*                                                                         | :heavy_minus_sign:                                                               | Preferred language                                                               |
| `communicationMethods`                                                           | [models.ConsumerCommunicationMethod](../models/consumercommunicationmethod.md)[] | :heavy_minus_sign:                                                               | Communication methods                                                            |