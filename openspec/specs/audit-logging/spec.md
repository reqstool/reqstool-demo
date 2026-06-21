# Audit Logging Specification

## Purpose

Requirement and SVC content is owned by reqstool (single source of truth). This spec references
reqstool requirement and SVC IDs only; titles and descriptions are injected at read time via
`reqstool enrich` (or the openspecui hook). See `docs/reqstool/`. This capability demonstrates a
requirement and SVC that exist but have no verifying test at all — the **missing-test** status
case.

## Requirements

### Requirement: REQ_MISSING_TEST
The system SHALL implement REQ_MISSING_TEST.

#### Scenario: SVC_060
The system SHALL pass SVC_060.
