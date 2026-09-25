# 01 — POC Specification

**Document status:** POC Spec  
**Version:** v0.4 (draft target)  
**Date:** 2026-09-25

## POC Goal

Validate that one secure runtime can execute a bounded coding workflow end-to-end with policy control, verification, and audit.

## POC Success Criteria (Exit Criteria)

A POC is successful only if all are true:

1. Runs one complete coding request flow: plan → implement → verify → summarize.
2. Uses at least 2 model providers via one canonical model interface.
3. Enforces tool restrictions (filesystem/process/git) via policy checks.
4. Uses isolated worktree execution for code-modifying tasks.
5. Produces structured artifacts (plan, diff, test report, final summary).
6. Produces structured audit events for model/tool/policy actions.
7. Supports approval gate for at least one sensitive operation.

## POC In-Scope

- local runtime
- desktop or CLI entrypoint (minimum one)
- planner + coding flow
- policy guard for filesystem/process/network
- basic model routing
- test/build verification loop

## POC Out-of-Scope

- enterprise SSO/RBAC
- full control plane
- complex multi-region deployment
- full long-term memory systems

## POC Deliverables

- runnable demo path
- architecture notes
- known gaps
- measured latency/cost/success metrics
- MVP recommendations

## Transition to MVP

When exit criteria are met and key gaps are documented, move to `02-poc-results-and-mvp-specification.md`.
