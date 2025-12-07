# FreezeSubscriptionApiV2SubscriptionsSubscriptionIdFreezePostRequest

## Example Usage

```typescript
import { FreezeSubscriptionApiV2SubscriptionsSubscriptionIdFreezePostRequest } from "stream-sdk/models/operations";

let value: FreezeSubscriptionApiV2SubscriptionsSubscriptionIdFreezePostRequest =
  {
    subscriptionId: "74d57333-aa7b-4b8a-b004-3c5643dbd6eb",
    body: {
      freezeStartDatetime: new Date("2025-08-16T04:59:47.255Z"),
    },
  };
```

## Fields

| Field                                                                                     | Type                                                                                      | Required                                                                                  | Description                                                                               |
| ----------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| `subscriptionId`                                                                          | *string*                                                                                  | :heavy_check_mark:                                                                        | N/A                                                                                       |
| `body`                                                                                    | [models.FreezeSubscriptionCreateRequest](../../models/freezesubscriptioncreaterequest.md) | :heavy_check_mark:                                                                        | N/A                                                                                       |