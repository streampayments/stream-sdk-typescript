# UpdateSubscriptionApiV2SubscriptionsSubscriptionIdPutRequest

## Example Usage

```typescript
import { UpdateSubscriptionApiV2SubscriptionsSubscriptionIdPutRequest } from "stream-sdk/models/operations";

let value: UpdateSubscriptionApiV2SubscriptionsSubscriptionIdPutRequest = {
  subscriptionId: "e0eee586-12cc-482e-b7ce-ee9006c72ee1",
  body: {
    items: [
      {
        productId: "<value>",
        quantity: 629587,
      },
    ],
    coupons: [
      "<value 1>",
      "<value 2>",
    ],
  },
};
```

## Fields

| Field                                                           | Type                                                            | Required                                                        | Description                                                     |
| --------------------------------------------------------------- | --------------------------------------------------------------- | --------------------------------------------------------------- | --------------------------------------------------------------- |
| `subscriptionId`                                                | *string*                                                        | :heavy_check_mark:                                              | N/A                                                             |
| `body`                                                          | [models.SubscriptionUpdate](../../models/subscriptionupdate.md) | :heavy_check_mark:                                              | N/A                                                             |