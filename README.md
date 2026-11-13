# .github

Organisation-wide GitHub configuration for Polkadot-Community-Foundation.

## Ruleset workflows

Workflows here are required on pull requests across the organisation by
organisation rulesets. They run from this repository, so a pull request can't
change them.

- `.github/workflows/outside-contribution-review.yml`, required by the
  `pcf-outside-contribution-review` ruleset: a pull request from someone without
  write access to the repository needs two approvals from people with write
  access on its current head commit. A maintainer re-runs the check after the
  last approval.
