# Specification Index

Version 1.0  
EIM Operational Engine  
Specification Baseline — Version 1.0  

## Overview

- This document defines the structural components that comprise the Version 1.0 Specification Baseline for the **EIM Operational Engine**.
- Each referenced specification is frozen within the declared scope of this baseline.
- Future revisions will be explicitly versioned.
- The **EIM Operational Engine** defines a deterministic enforcement layer intended to support high-integrity engineering reasoning through explicit constraint instrumentation.

## 1. High-Integrity Operating Mode (HIOM)

File: - `HIOM-Definition.md` — definition of High-Integrity Operating Mode  

Defines the operational reasoning state within which integrity enforcement applies.

HIOM establishes:  

- Explicit activation and deactivation rules
- The boundary between exploratory reasoning and enforced engineering reasoning
- The structural purpose of integrity instrumentation
- The non-authoritative nature of the framework

## 2. Assumption Event Taxonomy v1.0

File: - `Assumption-Event-Taxonomy-v1.0.md` — classification of enforceable assumption events  

Defines the formal classification of Assumption Events detected within HIOM.

Includes categories such as:  

- Missing Input Assumption
- Default Value Insertion
- Undeclared Boundary Condition
- Similarity Carryover
- Contextual Inference
- Extrapolation
- Undisclosed Derivation

Each category maps to defined enforcement behavior.

## 3. Required Variable Framework v1.0

File: - `Required-Variable-Framework-v1.0.md` — engineer-led variable declaration model  

Defines the engineer-led declaration model for required project variables.

Specifies:  

- Required variable tiers
- Life-safety variable designation
- Engine suggestion boundaries
- Change control requirements
- Enforcement linkage to Assumption Events

## 4. STOP Logic Specification v1.0

File: - `STOP-Logic-Specification-v1.0.md` — deterministic enforcement behavior

Defines deterministic enforcement behavior when integrity violations are detected.

Specifies:  

- **HARD STOP** conditions
- Structured override requirements
- Validation-required conditions
- Logging expectations
- Mode sensitivity boundaries

## 5. Derivation Transparency Specification v1.0

File: - `Derivation-Transparency-Specification-v1.0.md` — formal derivation exposure requirements  

Defines formal requirements for exposing derivation chains.

Includes:  

- Input disclosure
- Unit consistency requirements
- Formula transparency
- Intermediate step visibility
- External tool origin disclosure
- Enforcement linkage to STOP logic

## 6. Scope Boundaries

This Specification Baseline does not include:  

- Escalation hierarchies
- Behavioral pattern analytics
- Adaptive rigor scaling
- Similarity scoring systems
- Deployment or runtime implementation architecture

These areas may be defined in future revisions.

## 7. Version Scope

This document defines complete derivation transparency requirements for **Specification Baseline Version 1.0**.  
Future revisions may introduce extended traceability or formalized derivation templates.
