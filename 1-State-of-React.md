# 1 - State of React, Jared Palmer
- Hooks make React "more JavaScript", moving into a more and more pure JS world for data fetching
- We use Spinners everywhere, but they're not always necessary
- How many "loading" states / spinners do we have throughout the app? Basically in every component that fetches data
- React Suspense allows us to suspend rendering of components until a condition is met, and show a `fallback` until then (commonly a Spinner)
- This means we don't need to manage tedious loading state everywhere anymore
- Suspense utilises react-cache 