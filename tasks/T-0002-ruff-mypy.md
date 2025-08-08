---
id: T-0002
title: Add ruff + mypy to CI
type: chore
priority: P2
depends_on: []
status: queued
owner: unassigned
estimate: 2h
acceptance:
  - "CI runs ruff (lint) and fails on violations"
  - "CI runs mypy (types) and fails on errors"
  - "PR template mentions ruff/mypy checks"
auto_policy: review_required
---

## Description
Add ruff and mypy checks to the CI pipeline alongside pytest.

## Deliverables
- pyproject.toml (ruff + mypy config)
- Updated .github/workflows/ci.yml to run ruff and mypy
- PR template mentions ruff/mypy
