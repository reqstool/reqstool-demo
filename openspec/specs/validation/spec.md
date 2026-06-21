# Validation Specification

## Purpose

Requirement and SVC content is owned by reqstool (single source of truth). This spec references
reqstool requirement and SVC IDs only; titles and descriptions are injected at read time via
`reqstool enrich` (or the openspecui hook). See `docs/reqstool/`. This capability demonstrates a
requirement whose implementation has a bug, causing its automated test to fail — the
**failing-test** status case.

## Requirements

### Requirement: REQ_FAILING_TEST
The system SHALL implement REQ_FAILING_TEST.

#### Scenario: SVC_040
The system SHALL pass SVC_040.
