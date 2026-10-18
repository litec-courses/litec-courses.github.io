# Working Rules

## Content

- Write visible portal content in German. Keep technical documentation in English.
- List only public GitHub Pages URLs. Never link private repositories.
- Keep all five years visible, including years without published courses.
- Do not add exams, solutions, internal notes, credentials, or personal data.
- Treat every generated Pages artifact as public.

## Design and publishing

- Keep layout, styles, assets, validation, and publishing logic in the pinned `course-tooling` package.
- Configure portal content only in `portal.yml`.
- Pin the package and reusable workflow to the same immutable `course-tooling` tag.
- Keep search-engine exclusion enabled; it is not access control.

## Verification and Git

- Run `bun run pages:build` after configuration changes.
- Report checks that were not run.
- Ask for approval before committing, pushing, or publishing.
- Use Conventional Commits.
- Do not use subagents unless explicitly requested.
