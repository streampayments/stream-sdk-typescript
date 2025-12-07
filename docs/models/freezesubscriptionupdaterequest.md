# FreezeSubscriptionUpdateRequest

## Example Usage

```typescript
import { FreezeSubscriptionUpdateRequest } from "stream-sdk/models";

let value: FreezeSubscriptionUpdateRequest = {
  freezeStartDatetime: new Date("2025-08-02T06:09:06.942Z"),
  freezeEndDatetime: new Date("2023-12-12T04:52:10.671Z"),
  notes: "<value>",
};
```

## Fields

| Field                                                                                         | Type                                                                                          | Required                                                                                      | Description                                                                                   |
| --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| `freezeStartDatetime`                                                                         | [Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) | :heavy_check_mark:                                                                            | freeze_start_datetime is always provided even if it dont change                               |
| `freezeEndDatetime`                                                                           | [Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) | :heavy_check_mark:                                                                            | freeze_end_datetime is optional, if provided, it must be greater than freeze_start_datetime   |
| `notes`                                                                                       | *string*                                                                                      | :heavy_check_mark:                                                                            | N/A                                                                                           |