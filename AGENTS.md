# Repository State Observation Service

This child enterprise owns one purpose: observe repository state. It chooses
its Git operation, contracts the Git Services Section, and returns a digest-bound
observation. A caller may supply a repository root and bounded wait, but never
Git argv, an executable, environment overrides, or mutation authority.

The child is directly contractable. Its parent section may broker its service
without absorbing its records or authority. Only this child writes below its
`data/`; supplier receipts remain supplier-owned.

