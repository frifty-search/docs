# Updating in usescase/index.tsx

As you have added new a use-case, you need to import it to the index.tsx. \
Right now, your index.tsx may look like this (it might change according to the number of use-cases that have been added to the App)

```tsx
import DumbCharades from "./dumbCharades"; 
export { DumbCharades };
```

Add the newly created use-case in usecases/index.tsx

```tsx
import DumbCharades from "./dumbCharades";
// Add this import from the new created usecase
import AgeCalculator from "./ageCalculator";

// updating the export 
export { DumbCharades, AgeCalculator };
```
