# AGENTS.md

## Agent skills

### Issue tracker

Issues live in GitHub Issues on `Mettyoutan/matthew-portfolio`. See `docs/agents/issue-tracker.md`.

### Domain docs

Single-context: `GLOSSARY.md` at the repo root and ADRs in `docs/adr/`. See `docs/agents/domain.md`.

## Project rules

- Stack: Next.js 16 (App Router), TypeScript, Tailwind CSS v4.
- Use the `tailwind-design-system` skill for theme tokens, component variants, and CSS-first configuration.
- All site copy lives in `src/content/site.ts`. Do not hardcode copy in components.
- Verify with `npm run lint` and `npm run build` before claiming a task done.
