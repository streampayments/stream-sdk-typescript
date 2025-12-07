# ListResourceProductDto

## Example Usage

```typescript
import { ListResourceProductDto } from "stream-sdk/models";

let value: ListResourceProductDto = {
  data: [],
  pagination: {
    totalCount: 39682,
    maxPage: 53121,
    currentPage: 507109,
    limit: 753614,
    hasNextPage: false,
    hasPreviousPage: false,
  },
};
```

## Fields

| Field                                          | Type                                           | Required                                       | Description                                    |
| ---------------------------------------------- | ---------------------------------------------- | ---------------------------------------------- | ---------------------------------------------- |
| `data`                                         | [models.ProductDto](../models/productdto.md)[] | :heavy_check_mark:                             | N/A                                            |
| `pagination`                                   | [models.Pagination](../models/pagination.md)   | :heavy_check_mark:                             | N/A                                            |