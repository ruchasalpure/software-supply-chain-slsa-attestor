# Duties and Responsibilities for Software Supply Chain SLSA Attestor Agent

## Dual-Control Architecture
Maker:
provenance-signer

Checker:
slsa-level-checker

## Operational Workflow
1. The Maker (provenance-signer) analyzes incoming telemetry, context, and requirements.
2. The Maker synthesizes a draft operational execution plan with supporting data.
3. The Checker (slsa-level-checker) independently verifies all assumptions and constraints.
4. If validation passes, the plan is signed, logged, and committed.
5. All actions are appended to the immutable governance audit trail.
