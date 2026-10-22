# Repository State Observation Service

<!-- 561-group-standards:badges:start -->
[![Red Cup Engineering](https://img.shields.io/badge/561%20Group-Red%20Cup%20Engineering-c0392b)](https://github.com/red-cup-engineering)
[![License: MIT](https://img.shields.io/badge/license-MIT-c0392b)](LICENSE)
[![Indigenous data: CARE](https://img.shields.io/badge/Indigenous%20data-CARE-4b6f44)](https://github.com/red-cup-engineering/.github/blob/main/GOVERNANCE.md)
[![Tips welcome](https://img.shields.io/badge/tips-welcome-d4a017)](https://github.com/561-group/.github/blob/main/TIPS.md)
<!-- 561-group-standards:badges:end -->

A directly contractible, purpose-specific software operation developed by the
Software Development Services Section. It observes `git status --short
--branch` through the separately owned Git Services Section. It never invokes Git
directly and it advertises no mutation effect.

The returned product contains the exact nested provider evidence, parsed branch
and worktree entries, and a digest of the raw status output. It is evidence for
a customer decision, not a claim that the repository or a proposed change is
good.
