# Day 34 – Middleware in Express

## What I Learned
- What middleware is
- How next() works
- Order of middleware execution
- Difference between normal and error middleware

## Key Concepts
- Middleware runs between request and response
- next() passes control
- Error middleware has 4 parameters
- Order of declaration matters

## What I Implemented
- Global logger middleware
- Route-specific middleware
- Custom middleware file
- Basic error-handling middleware

## Why This Matters
- Middleware controls request flow
- Essential for authentication, logging, validation
- Required for production-ready apps