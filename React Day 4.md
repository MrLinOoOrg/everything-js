React Day 4

- React Hook:Not magic just Arrays
- State is isolated and private
- only valid in top level
- State Design
- Rendering process
    - Dom Difference
        - Reconcilation Algro
    - Why react is faster?
    - only replace dom tree in initial state with appendChild()
- Trigger,Render,Commit
- Page Reflow
- React batches state updates
    - passing function and react adds it to a queue. eg setNumber(n => n + 1):
- Reference Equality
    - don't update state when object is same
    - Why Reference Equality?
        - deep compare and cause computation cost
    - To update state
    - Clone object and make a change
- not render object
    - false,underfine,null
- Ramda:Lenses
- Copy sentence with object spread operaor
    - for complex object use rada:lenses
    - Immer
- Update Array in State
    - update with map
- Delete Array in State
    - filter
- Rubber Duck Debugging
- Richard Feynman Techinque
    - Study
    - Teach
    - Fill the Gaps
    - Simpiliy
