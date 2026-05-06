# Contributing to aria

You are responsible for one feature at a time. Own it from PR to deploy.

## Branch naming

| Prefix | Use for |
|--------|---------|
| `feat/<initials>/<short-name>` | New feature |
| `fix/<initials>/<short-name>` | Bug fix |
| `chore/<initials>/<short-name>` | Refactor, deps, docs, tooling |

Example: `feat/cm/login-form`.

## Pull requests

1. Create a feature branch off `main`.
2. Push your branch and open a PR.
3. Fill in every section of the PR template.
4. Request review from the other contributor. The maintainer reviews any sensitive change.
5. Address comments. Resolve every conversation thread.
6. Once approved, **squash-merge** and **delete the branch**.

## Rules

- `main` is protected: no direct pushes, no force-pushes, no deletions.
- Every PR needs at least 1 approving review.
- All review threads must be resolved before merge.
- Imperative commit messages: "add login form", not "added login form" or "adding login form".
- Keep PRs small. If a PR is over 400 lines of diff, consider splitting.

## Reviewer rotation

Default reviewers: each contributor reviews the other's PRs. The maintainer ([@KakkoiDev](https://github.com/KakkoiDev)) is auto-requested via CODEOWNERS for changes to:

- Auth code
- Infrastructure / deployment configs
- Secrets, environment variables
- `.github/` (CODEOWNERS, PR templates, workflows)

## Local dev

See [README.md](README.md).

## Help

Ping [`#dev`](https://discord.com/invite/YrtdssGUJa) on Discord. No question is too small.
