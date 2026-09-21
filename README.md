# LicenseMedic

> Portable agent for detecting repositories without recognizable license documentation.

## What it does

LicenseMedic inspects project structure for a license file and reports when no recognizable license document is present.

### Diagnostic fingerprint

**License evidence → distribution signal → explanation → documentation action**

## Why this agent is distinct

LicenseMedic focuses on repository-level licensing visibility. It does not attempt to determine legal compatibility between every dependency and every distribution scenario.

Its purpose is simpler and more auditable: identify whether the repository visibly declares a license.

## Workflow

```text
Repository
    ↓
License-file detector
    ↓
Licensing visibility rule
    ↓
Evidence
    ↓
Documentation recommendation
```

## Verification

Included are OpenGAP-compatible passport metadata, license-focused fixture coverage, explainability and duty contracts, four framework adapters, and automated adapter verification.

OpenGAP validation passed and all four generated framework exports have been exercised successfully.

## Design principle

**Visibility before interpretation.** The agent detects whether licensing evidence exists without pretending to provide legal advice.

## Medic family

LicenseMedic provides the licensing-documentation perspective within the portable Medic family.