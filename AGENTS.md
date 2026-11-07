# AGENTS.md — baxyz `.github`

This repository inherits the [canonical workspace rules](https://github.com/baxyz/.dev/blob/main/AGENTS.md). Only project-specific details are documented here.

## Scope

- Workspace-wide GitHub configuration (community health files, issue/PR templates)
- Dependabot configuration

## Scopes (Conventional Commits)

Defined in `scopes.json` — `templates`, `deps`, `ci`, `docs`, `security`, `ai`.
`.vscode/settings.json` mirrors the same list for the editor's Conventional Commits extension UI.

## License

AGPL-3.0-only, the workspace default.

## Rules

- No runtime code.
- Keep community files (CONTRIBUTING, CODE_OF_CONDUCT, SECURITY) up to date with actual practices.
- No `profile/README.md` here: `baxyz` is a user account, so its profile lives in the [`baxyz/baxyz`](https://github.com/baxyz/baxyz) repository.
