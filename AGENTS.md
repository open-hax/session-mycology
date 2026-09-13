# Session Mycology — Agent Guidance

Session reflection, lesson, spore candidate, incubation, and promotion events.

## Quick commands

```bash
# Build (ESM library)
pnpm build

# Tests
pnpm test

# Lint
pnpm lint:kondo

# Dev watch
pnpm watch

# Clean
pnpm clean
```

## Architecture

- Pure CLJS library with ESM exports: buildEvent, schemaRegistry, currentSchemas
- Schema facts live in `eta-mu.session-mycology.law.reflection`
- Canonical CLI surface: `eta-mu session ...`

## Dependencies

- Maven: malli 0.16.4
- npm: shadow-cljs
- Node built-ins: child_process, fs, path, os
- No workspace or sibling dependencies

## License

GPL-3.0-or-later
