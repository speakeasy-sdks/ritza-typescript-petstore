<!-- Start SDK Example Usage -->


```typescript
import { SDK } from "Petstore";

(async() => {
  const sdk = new SDK();

  const res = await sdk.pets.createPets();

  if (res.statusCode == 200) {
    // handle response
  }
})();
```
<!-- End SDK Example Usage -->