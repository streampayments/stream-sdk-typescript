# SubscriptionCancel

## Example Usage

```typescript
import { SubscriptionCancel } from "stream-sdk/models";

let value: SubscriptionCancel = {};
```

## Fields

| Field                                                                                                                                                                    | Type                                                                                                                                                                     | Required                                                                                                                                                                 | Description                                                                                                                                                              |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `cancelRelatedInvoices`                                                                                                                                                  | *boolean*                                                                                                                                                                | :heavy_minus_sign:                                                                                                                                                       | Whether or not to cancel all the related invoices to this subscription. If False, only the subscription will be canceled but the related invoices will remain untouched. |