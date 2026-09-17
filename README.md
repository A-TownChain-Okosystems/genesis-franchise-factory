# Genesis Franchise Factory — Migration Notice

> **Canonical location:** The Franchise Factory is being integrated into `A-TownChain-Okosystems/genesis-engine`.

The implementation is being moved from this standalone repository into the Genesis Engine repository so the Engine becomes the canonical development and integration surface for Franchise Factory production orchestration.

Canonical target:

- `genesis-engine/franchise_factory/`
- GFF Core / AD-20
- ATC-9900 DAO
- AD-43 Lifecycle Manager
- 17 AI workflow catalogue
- typed artifact/provenance contracts
- Game Factory graph
- tests and quality gates

`genesis-chronicles` remains independent and is not a dependency of the Franchise Factory.

## Migration state

This repository is retained temporarily as the migration source. Do **not** start new implementation work here once the Genesis Engine migration PR is accepted.

Target PR: `genesis-engine#12` — `feat: integrate Franchise Factory into Genesis Engine`.

The source repository will be retired only after the complete specification corpus, evidence, tests and required repository metadata have been verified in the Genesis Engine location.
