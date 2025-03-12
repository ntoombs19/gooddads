# Add Spatie Typescript Transformer to Laravel/Inertia Project

- **Status:** Active
- **Last Modified:** 2025-03-11
- **Tags:** Laravel, Inertia.js, TypeScript, Developer Experience

## Context and Problem Statement

Maintaining consistency between backend Laravel models and frontend TypeScript definitions in an Inertia.js application has become challenging. How can we automate type generation from Laravel models to improve type safety and development efficiency?

## Decision Drivers

- Improved developer experience through automatic synchronization of backend and frontend types
- Reduced manual maintenance overhead
- Enhanced type safety and fewer runtime errors

## Decision Outcome

Chosen option: **"Integrate Spatie Typescript Transformer"**, because it provides automatic and reliable generation of TypeScript definitions directly from Laravel PHP classes.

### Positive Consequences

- Increased developer productivity by automating type synchronization
- Reduction in manual errors and discrepancies between backend and frontend
- Improved IDE autocompletion and code confidence on the frontend

### Negative Consequences

- Additional build step to regenerate types upon backend changes
- Minor increase in project complexity due to introduction of a new dependency

## Links

- [Spatie Typescript Transformer Documentation](https://spatie.be/docs/typescript-transformer/v2/introduction)