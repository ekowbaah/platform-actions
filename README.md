# platform-actions
Least-privilege reusable GitHub Actions for consistent delivery pipelines.

Available composite actions:

- `actions/rust-ci`: formatting, Clippy, and tests
- `actions/node-ci`: deterministic install, tests, and build
- `actions/sbom`: dependency inventory for npm or Cargo repositories

Consumers should pin this repository to an immutable release SHA and declare only the permissions required by their job. Every third-party action used here is itself pinned to a full commit SHA.
