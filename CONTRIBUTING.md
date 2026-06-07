# Contributing

Thanks for your interest! This document covers shared guidelines for all baxyz repositories. Each repo may add its own `CONTRIBUTING.md` with project-specific details.

## Workspace setup

See [`baxyz/.dev`](https://github.com/baxyz/.dev) for the multi-root workspace and the unified DevContainer.

## Pull Requests

1. Fork & branch off `main` — `git switch -c feat/short-description`
2. Make focused commits — see commit format below
3. Push and open a PR
4. Wait for CI green

## Commit messages

[Conventional Commits](https://www.conventionalcommits.org/) with a **gitmoji**:

```
<type>(<scope>): <emoji> <description>
```

- Description ≤72 chars, lowercase, imperative mood, no trailing period
- Always include exactly ONE emoji

Type → emoji table: see [`baxyz/.dev/AGENTS.md`](https://github.com/baxyz/.dev/blob/main/AGENTS.md).

## Reporting bugs / suggesting features

Open an issue in the relevant repo. Use the provided templates.

## Security

See [`SECURITY.md`](./SECURITY.md) — please **do not** open public issues for vulnerabilities.
