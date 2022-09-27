# Updating the utils/appName.utils.tsx

As you have added new a use-case, you need to import it to the utils/appName.utils.tsx. \
Right now, your appName.utils.tsx may look like this (it might change according to the number of use-cases that have been added to the App)

```tsx
export const AppName = {
  DUMBCHARADES: 1,
};
```

It's an object whose keys are the AppNames and values are AppIds

Add the newly created use-case in appName.utils.tsx

```tsx
export const AppName = {
  DUMBCHARADES: 1,
  AGECALCULATOR: 2,
};

```

