# Agent Instructions

## Semantic Release and Compliance

When working on this repository:
- Semantic releases are managed by `semantic-release` and the `@semantic-release/github` plugin.
- Release workflows are defined in `.github/workflows/release.yml`.
- PR titles must comply with conventional commit format: `^(feat|fix)(\([^)]+\)): .+$`.
- Ensure PR titles use `feat` or `fix` and include a scope.
- Compliance checks are defined in `.github/workflows/compliance.yml`.
