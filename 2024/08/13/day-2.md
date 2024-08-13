Suspect it might be related to excessive re-renders in a deeply nested component.

Will try using React DevTools to profile the application and identify the culprit.

The waterfall diagram should give some hints.

Identified the bottleneck, it was a missing `useMemo` hook!