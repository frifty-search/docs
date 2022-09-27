# Updating in components/utils/renderApps.utils.tsx

As you have added new a use-case, you need to import it to the components/utils/renderApps.utils.tsx. \
Right now, your renderApps.utils.tsx may look like this (it might change according to the number of use-cases that have been added to the App)

```tsx
import React from "react";
import { DumbCharades } from "../../usecases";
import { Apps } from "../../utils/api.utils";
import { AppName } from "../../utils/appName.utils";

export const renderApps = ({ appId, data }: Apps): React.ReactNode => {
  switch (appId) {
    case AppName.DUMBCHARADES:
      return <DumbCharades data={data} />;
    }
  }
};

```

It's an util function that take appId and related data as arguements and renders the component accordingly

Add the newly created use-case in renderApps.utils.tsx&#x20;

```tsx
import React from "react";
import { DumbCharades, AgeCalculator } from "../../usecases";
import { Apps } from "../../utils/api.utils";
import { AppName } from "../../utils/appName.utils";

export const renderApps = ({ appId, data }: Apps): React.ReactNode => {
  switch (appId) {
    case AppName.DUMBCHARADES:
      return <DumbCharades data={data} />;
    case AppName.AGECALCULATOR:
      return <AgeCalculator data={data} />;
  }
};

```
