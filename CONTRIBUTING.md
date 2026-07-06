# Contributing

Thanks for helping improve Subnautica 2 Trainer.

## Before you start

- Search existing issues and PRs to avoid duplicate work.
- Keep changes focused — one module or one doc fix per PR when possible.
- Do not commit personal paths, Steam IDs, or license keys.

## Development setup

```powershell
dotnet restore
dotnet build
dotnet test
```

## Code style

- C#: follow `.editorconfig` (4 spaces, file-scoped namespaces where applicable).
- Commit messages: imperative mood (`Fix oxygen tick rate`, not `Fixed`).
- UI strings: English in source; translations via `loc/` JSON files.

## Offset updates

When the game patches:

1. Document the build ID in the PR description.
2. Place offsets in `src/Modules/Offsets/build-xxxx.json`.
3. Add a short note in `docs/changelog.md`.

## Pull request checklist

- [ ] Builds cleanly on Windows x64
- [ ] No secrets or machine-specific paths
- [ ] README or docs updated if behavior changed
- [ ] Screenshots only in `assets/` or `docs/images/`

## Community

Be respectful. Issues about multiplayer cheating or bypassing paid content will be closed without discussion.
