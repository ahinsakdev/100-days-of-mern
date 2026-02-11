# Day 20 – useState with Objects & Arrays

## What I Learned
- How React handles object and array state
- Why immutability is required
- How React detects state changes

## Key Concepts
- React re-renders when state reference changes
- Objects and arrays must not be mutated
- New copies should be created for updates

## Object State Updates
- Copy old object
- Override changed properties
- Keep rest unchanged

## Array State Updates
- Add items using spread
- Remove items using filter
- Update items using map

## Functional State Updates
- Used when next state depends on previous state
- Prevents bugs with batched updates

## Notes
- If UI doesn’t update, check for mutation
- Prefer simple and flat state structures
