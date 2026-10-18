# LiTec Courses

Public portal for the course materials published by the `litec-courses` organization.

The portal groups courses by year and links only to explicitly published GitHub Pages sites. Course repositories remain private. Layout, styling, validation, and deployment are provided by the pinned `course-tooling` release.

The published site will be available at <https://litec-courses.github.io/>.

## Development

```bash
bun install --frozen-lockfile
bun run pages:build
bun run pages:preview
```

The generated site is public but asks search engines not to index it. Do not add private repository URLs, internal notes, exams, solutions, credentials, or personal data.
