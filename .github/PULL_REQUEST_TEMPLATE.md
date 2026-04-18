<!-- PR title convention: imperative + scope, e.g. "Fix rate-limit in _apiQueue" -->

## Summary

<!-- What changed and why, in 1-3 sentences. -->

## Type of change

- [ ] Bug fix
- [ ] New feature
- [ ] Refactor / cleanup
- [ ] Docs / tooling
- [ ] Cross-repo (Meridian) — link sibling PRs below

## Meridian impact

- [ ] Self-contained to this repo
- [ ] Touches cross-project behavior — linked issues: <link>
- [ ] Bumps shared conventions in `meridian/MERIDIAN_CONVENTIONS.md`
- [ ] Triggers codebase-summary regeneration
      (>10 files changed OR message contains `[major]` / `[refactor]` /
      `[architecture]` / `[summary]` / `[breaking]`)

## Test plan

<!-- Commands you ran + what you verified. Paste the pass/fail output. -->

- [ ]
- [ ]

## Screenshots / recordings

<!-- Only for UI-visible changes. -->

## Checklist

- [ ] I have NOT run `git add -A` in a repo with unrelated WIP
- [ ] Secrets are NOT in this diff
- [ ] New public functions have at least one test
- [ ] Styling uses CSS variables only (UI repos)
- [ ] LLM calls go through the central queue (no direct provider calls)
