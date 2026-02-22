# Day 30 – JSON Responses & Handling POST Data

## What I Learned
- How to send JSON responses
- How request body works in Node
- How to manually parse incoming data

## Key Concepts
- JSON.stringify() is required
- Request body arrives in chunks
- req.on("data") collects chunks
- req.on("end") signals completion

## What I Implemented
- JSON response handling
- POST endpoint
- Manual body parsing

## Why This Matters
- Express middleware automates this
- Understanding raw Node improves backend clarity