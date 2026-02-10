# Day 19 – React Events & State Updates

## What I Learned
- How React handles events
- How user actions update state
- How state changes re-render UI

## Key Concepts
- Events trigger functions, not UI updates
- State updates cause re-render
- The component owning state should update it

## Events + State Flow
- User action → event handler
- Handler updates state using setter
- React re-renders component
- UI reflects new state

## Props & Event Handling
- Parent passes handler to child via props
- Child calls handler on event
- Parent decides how state changes

## Notes
- Always pass function references to events
- Avoid mutating state directly
