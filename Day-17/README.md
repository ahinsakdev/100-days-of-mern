# Day 17 – React Components & Props

## What I Learned
- Components are functions that return UI
- Props are inputs passed from parent to child
- Data flows one way in React (top to bottom)

## Key Concepts
- Reusable UI pieces should be components
- Props are read-only and should not be mutated
- Parent owns data, child renders it

## Mental Model
- Component = function
- Props = function arguments
- JSX = return value

## How This Will Be Used in Projects
- App component will manage data
- Child components will receive data via props
- UI will be built by composing small components

## Notes
- If UI repeats, extract a component
- If child needs data, pass it via props
