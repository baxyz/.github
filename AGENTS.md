# AGENTS.md — baxyz `.github`

This repository inherits the [canonical workspace rules](https://github.com/baxyz/.dev/blob/main/AGENTS.md). Only project-specific details are documented here.

## Scope

- Workspace-wide GitHub configuration (community health files, issue/PR templates)
- Dependabot configuration
- Profile README (`profile/README.md`)

## Scopes (Conventional Commits)

Defined in `scopes.json` — `profile`, `templates`, `deps`, `ci`, `docs`, `security`.
`.vscode/settings.json` mirrors the same list for the editor's Conventional Commits extension UI.

## License

AGPL-3.0-only, the workspace default.

## Rules

- No runtime code.
- Keep community files (CONTRIBUTING, CODE_OF_CONDUCT, SECURITY) up to date with actual practices.
- `profile/README.md` is the public face of the baxyz account — keep it accurate and concise.
