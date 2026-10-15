# platform-actions
Least-privilege reusable GitHub Actions for consistent delivery pipelines.

Available composite actions:

- `actions/rust-ci`: formatting, Clippy, and tests
- `actions/node-ci`: deterministic install, tests, and build

Consumers should pin this repository to an immutable release SHA. The roadmap adds dependency review, SBOMs, signed provenance, container scanning, and protected deployment gates.
