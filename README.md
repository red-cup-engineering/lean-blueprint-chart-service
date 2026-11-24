# Lean Blueprint chart service

<!-- 561-group-standards:badges:start -->
[![Red Cup Engineering](https://img.shields.io/badge/561%20Group-Red%20Cup%20Engineering-c0392b)](https://github.com/red-cup-engineering)
[![License: MIT](https://img.shields.io/badge/license-MIT-c0392b)](LICENSE)
[![Indigenous data: CARE](https://img.shields.io/badge/Indigenous%20data-CARE-4b6f44)](https://github.com/red-cup-engineering/.github/blob/main/GOVERNANCE.md)
[![Tips welcome](https://img.shields.io/badge/tips-welcome-d4a017)](https://github.com/561-group/.github/blob/main/TIPS.md)
<!-- 561-group-standards:badges:end -->

This package owns the dependency-free reader that joins a Lean declaration
catalog to a Lean Blueprint claim graph. It supplies graph-shape and
Lean-witness findings without importing the retired MetroPlat aggregate.

The reader observes source files only. It does not run Lean or LaTeX and does
not claim that a declaration compiles; callers bind its chart to their own
build and audit gates.
