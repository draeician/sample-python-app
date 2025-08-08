---
id: T-0001
title: Initialize basic CI for Python
type: chore
priority: P2
depends_on: []
status: done
owner: unassigned
estimate: 2h
acceptance:
  - "On pull_request, GitHub Actions runs pytest and reports status"
  - "A minimal tests/test_smoke.py exists and passes"
auto_policy: review_required
---

## Description
Set up a basic GitHub Actions CI for Python with pytest and a smoke test.

## Deliverables
- .github/workflows/ci.yml
- tests/test_smoke.py
