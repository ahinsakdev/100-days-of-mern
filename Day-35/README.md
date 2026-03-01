# Day 35 – Async Controllers & Error Handling

## What I Learned
- Why backend controllers must handle async logic
- How to use try/catch with async/await
- How next(error) forwards errors to middleware
- How centralized error handling works

## Key Concepts
- Async functions can throw errors
- Express does not automatically catch async errors
- Error middleware must have 4 parameters
- next(error) passes control to error handler

## What I Implemented
- Async controller example
- Centralized error-handling middleware
- Optional async wrapper pattern

## Why This Matters
- Prevents server crashes
- Required when using database
- Production-ready backend structure