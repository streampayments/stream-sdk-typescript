# Pagination

## Example Usage

```typescript
import { Pagination } from "stream-sdk/models";

let value: Pagination = {
  totalCount: 271635,
  maxPage: 56105,
  currentPage: 536064,
  limit: 64883,
  hasNextPage: true,
  hasPreviousPage: true,
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `totalCount`       | *number*           | :heavy_check_mark: | N/A                |
| `maxPage`          | *number*           | :heavy_check_mark: | N/A                |
| `currentPage`      | *number*           | :heavy_check_mark: | N/A                |
| `limit`            | *number*           | :heavy_check_mark: | N/A                |
| `hasNextPage`      | *boolean*          | :heavy_check_mark: | N/A                |
| `hasPreviousPage`  | *boolean*          | :heavy_check_mark: | N/A                |