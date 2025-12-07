# AppCommonDtosSharedConsumer

## Example Usage

```typescript
import { AppCommonDtosSharedConsumer } from "stream-sdk/models";

let value: AppCommonDtosSharedConsumer = {
  id: "<value>",
  preferredLanguage: "AR",
};
```

## Fields

| Field                                    | Type                                     | Required                                 | Description                              |
| ---------------------------------------- | ---------------------------------------- | ---------------------------------------- | ---------------------------------------- |
| `id`                                     | *string*                                 | :heavy_check_mark:                       | N/A                                      |
| `phoneNumber`                            | *string*                                 | :heavy_minus_sign:                       | N/A                                      |
| `email`                                  | *string*                                 | :heavy_minus_sign:                       | N/A                                      |
| `preferredLanguage`                      | [models.Language](../models/language.md) | :heavy_check_mark:                       | N/A                                      |