# UpdateSubscriptionFreezeApiV2SubscriptionsSubscriptionIdFreezeFreezeIdPutRequest

## Example Usage

```typescript
import { UpdateSubscriptionFreezeApiV2SubscriptionsSubscriptionIdFreezeFreezeIdPutRequest } from "stream-sdk/models/operations";

let value:
  UpdateSubscriptionFreezeApiV2SubscriptionsSubscriptionIdFreezeFreezeIdPutRequest =
    {
      subscriptionId: "94745766-a027-45a5-8e6b-2f595c21b5a9",
      freezeId: "74e70d7e-3f8b-4520-812a-f4fb4217ab9a",
      body: {
        freezeStartDatetime: new Date("2023-12-18T15:04:04.742Z"),
        freezeEndDatetime: new Date("2025-07-23T18:09:15.479Z"),
        notes: null,
      },
    };
```

## Fields

| Field                                                                                     | Type                                                                                      | Required                                                                                  | Description                                                                               |
| ----------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| `subscriptionId`                                                                          | *string*                                                                                  | :heavy_check_mark:                                                                        | N/A                                                                                       |
| `freezeId`                                                                                | *string*                                                                                  | :heavy_check_mark:                                                                        | N/A                                                                                       |
| `body`                                                                                    | [models.FreezeSubscriptionUpdateRequest](../../models/freezesubscriptionupdaterequest.md) | :heavy_check_mark:                                                                        | N/A                                                                                       |