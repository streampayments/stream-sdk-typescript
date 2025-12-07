# ProductListFilters

## Example Usage

```typescript
import { ProductListFilters } from "stream-sdk/models";

let value: ProductListFilters = {};
```

## Fields

| Field                                                                              | Type                                                                               | Required                                                                           | Description                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `searchTerm`                                                                       | *string*                                                                           | :heavy_minus_sign:                                                                 | Serach by product name or description.                                             |
| `active`                                                                           | *boolean*                                                                          | :heavy_minus_sign:                                                                 | Filter by active or inactive product. Removing this flag will return all products. |
| `type`                                                                             | [models.ProductType](../models/producttype.md)                                     | :heavy_minus_sign:                                                                 | Filter by product type.                                                            |