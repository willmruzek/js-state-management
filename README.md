# js-state-management
Exploring different state management tools

## Chosen tools
- Redux + Redux Toolkit (RTK)
- XState (local state management)
- XState (global state management)
- Effect

## FAQ

### Why isn't X on the list?

Many existing (simple) state solutions only tackle one side-effect: state. There are more side-effects than just a change in state, such as HTTP calls, database calls, logging, etc. I think the best state management solution also handles all other side-effects.
