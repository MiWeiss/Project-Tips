## Design Practices particularly important in PF2.
Remember what we discussed in class
- Don't put your UI Code (GUI or TUI) in the same classes as your model (e.g. game logic)
- Make classes immutable, whenever reasonable. 
- Use proper encapsulation: don't make stuff `public` if it does not have to be public and use `getters` and `setters`
    to access fields.
- Use inheritance when designing your software architecture (after all, this is an 'Object Oriented Programming' class).
- No god classes, no large methods.
