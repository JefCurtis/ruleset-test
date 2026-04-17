# ruleset-test

Sandbox for verifying GitHub path-scoped rulesets.

Testing whether two rulesets on `main` with different path scopes behave as expected:

- **Strict**: `schemas/**` — require PR, approvals, CODEOWNERS
- **Loose**: `playbook/**` — require PR only, no approvals

See `notes.md` for test results.
