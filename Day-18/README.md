# Day 18 – State & useState

## What I Learned
- Why React needs state
- What useState provides
- How state changes trigger re-render

## Key Concepts
- State is data that affects UI and can change
- useState returns current value and a setter
- Calling the setter causes the component to re-render

## Mental Model
- Component runs → UI is rendered
- State updates → component runs again
- React updates only changed DOM parts

## State vs Props
- State is owned by a component
- Props are passed to children
- Children should not modify state directly

## Notes
- Never mutate state directly
- Always use the setter function
