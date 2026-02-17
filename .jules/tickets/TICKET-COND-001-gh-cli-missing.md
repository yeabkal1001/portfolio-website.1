# TICKET-COND-001: GitHub CLI (gh) Missing

**Status**: BLOCKED
**Agent**: Conductor (Agent-1)
**Date**: 2026-02-17

## Description
The GitHub CLI (`gh`) is not available in the current environment. This prevents the Conductor from performing automated PR tracking and status checks as specified in the standard operating procedures.

## Impact
- PR tracking must be done manually or via alternative git commands if possible.
- Automated health checks for PRs are disabled.

## Proposed Resolution
- Check if `gh` can be installed in the environment.
- Use `git` commands and branch names to infer PR status where possible.
- Update `pr-tracking.md` manually based on known agent activity.
