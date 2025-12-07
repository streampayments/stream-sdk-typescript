<!-- Start SDK Example Usage [usage] -->
```typescript
import { StreamSDK } from "stream-sdk";

const streamSDK = new StreamSDK();

async function run() {
  const result = await streamSDK.consumers.create({
    jwtBearer: process.env["STREAMSDK_JWT_BEARER"] ?? "",
  }, {
    name: "<value>",
  });

  console.log(result);
}

run();

```
<!-- End SDK Example Usage [usage] -->