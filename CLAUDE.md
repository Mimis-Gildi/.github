# CLAUDE.md

This is the **Mímis Gildi Community** repository -- the org-level `.github` repository.

## What This Is

Organization-wide defaults for all Mímis Gildi repositories.
Community health files, org profile, issue/PR templates, and contributor guidance.

This is not where shared actions or tooling live -- that's [fluffle].
The "required" workflows live here, sourced from the `fluffle`.

## What Belongs Here

| Content            | Location                           | Purpose                                   |
|--------------------|------------------------------------|-------------------------------------------|
| Org profile        | `profile/README.md`                | Renders on the org's GitHub page.         |
| Code of conduct    | `CODE_OF_CONDUCT.md`               | Default for all repos.                    |
| Contributing guide | `CONTRIBUTING.md`                  | Default for all repos.                    |
| Security policy    | `SECURITY.md`                      | Default for all repos.                    |
| Support info       | `SUPPORT.md`                       | Default for all repos.                    |
| Funding            | `FUNDING.yml`                      | Sponsorship config.                       |
| Issue templates    | `.github/ISSUE_TEMPLATE/`          | Default templates for all repos.          |
| PR template        | `.github/PULL_REQUEST_TEMPLATE.md` | Default for all repos.                    |
| Greeting messages  | `.github/messages/`                | Used by welcome-first-contributor action. |

## What Does NOT Belong Here

- Shared GitHub [actions] -- those live in [fluffle].
- Reusable workflows -- those also live in [fluffle].
- Project-specific configuration -- each repo owns its own.

## What is shared from HERE

- Required workflows -- [.github/workflows/](.github/workflows).

## How Defaults Work

Files here cascade to every repo in the org that doesn't have its own version.
A repo overrides by creating the same file locally.

This repo must be **public** for defaults to cascade.

## Build

No build. Static content only.
Examples and templates for builds can be found in [fluffle].

## Trunk-Based Development

Same as all Mímis Gildi repos: linear history, feature branches merge to `main`.

### Exceptions

Structural changes and experimentation before `v1.0.0` can be pushed to `main` as an exception. 

[fluffle]: https://github.com/Mimis-Gildi/fluffle "Our fluffle's ways."
[actions]: https://github.com/features/actions 
