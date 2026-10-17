# Contributing to Akinrion

## Where things live
- **Tasks, bugs, sprints:** [Linear](https://linear.app/akinrion) (team key `AKI`)
- **Specs, research, decisions:** Notion workspace "Akinrion"
- **Code and technical docs:** GitHub, in each repo (`/docs` for ADRs and API docs)

## Workflow
1. Pick or create a Linear issue (e.g. `AKI-12`).
2. Branch from `main`: `aki-12-short-description` (use the branch name Linear suggests).
3. Make small, focused commits.
4. Open a pull request using the template and reference the issue (`Closes AKI-12`).
5. Get at least one review, make sure CI passes, then squash-merge.

## Commit messages
Short imperative subject (under 72 chars), e.g. `Add transaction reversal endpoint`. Explain the why in the body when it is not obvious.

## Roles
| Role | Typical access |
|---|---|
| Owner / Admin | Manages org, billing, access |
| Maintainer | Write access, reviews and merges PRs |
| Contributor | Write access via team, opens PRs |
| Guest / Reviewer | Read or comment on specific repos or pages |

Access is granted through GitHub teams (`engineering`, `design`, `product`), not to individuals.

## Decisions
Significant technical or product decisions go in the Notion Decision log (ADR format): context, options, decision, consequences.
