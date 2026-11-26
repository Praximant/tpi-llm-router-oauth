# Guidelines

## Simplicity is the golden rule

Things can be complex when needed, but never complicated.

Before every commit, recheck simplicity:

- Review the design and its trade-offs in light of the new changes.
- Ask whether a different design would make the whole thing simpler.
- Cut what the change doesn't need (code, config, flags, migrations, tests)
  and reuse what exists instead of adding new pieces.
- Sometimes it is worth starting over from scratch.
