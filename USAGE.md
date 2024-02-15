<!-- Start SDK Example Usage [usage] -->
```typescript
import { SDK } from "Petstore";

async function run() {
    const sdk = new SDK();

    const res = await sdk.pets.createPets({
        id: 596804,
        name: "<value>",
    });

    if (res.statusCode == 200) {
        // handle response
    }
}

run();

```
<!-- End SDK Example Usage [usage] -->