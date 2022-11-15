# Typescript Language Server Import Bug

```
yarn install
```

## Import issues

App.tsx - try to auto fix import `View`.

We expect

```ts
import { View } from "react-native";
```

but we are seeing

```ts
import React from "react";
```

App.test.tsx - same issue
