# STOP Logic Specification

Version 1.0  
EIM Operational Engine  
Specification Baseline — Version 1.0

## 1. Purpose

The STOP Logic Specification defines deterministic enforcement behavior when integrity violations occur within High-Integrity Operating Mode (HIOM).

STOP logic ensures that Assumption Events do not resolve silently and that reasoning gaps are surfaced before continuation.

## 2. Enforcement States

HIOM supports two enforcement states:

### 2.1 HARD STOP

Reasoning may not continue until the violation is resolved or formally overridden.  

**HARD STOP** conditions are triggered by:  

- Missing Input Assumption (MIA)
- Default Value Insertion (DVI)
- Undeclared Boundary Condition (UBC)
- Similarity Carryover Assumption (SCA)
- Undisclosed Derivation (UD)
- Life-safety Extrapolation Assumption (EA)

### 2.2 Validation Required

Reasoning may continue only after explicit acknowledgment of the identified risk.

Validation Required conditions are triggered by:  

- Contextual Inference Assumption (CIA)
- Non-life-safety Extrapolation Assumption (EA)  

Validation Required does not block reasoning but prevents silent acceptance.

## 3. Override Protocol

When a **HARD STOP** condition occurs, continuation requires:  

- Explicit override selection
- Structured justification statement
- Acknowledgment of potential risk implications
- Logged record of override event

Override does not remove the violation from the session log.  
Override authority remains with the engineer.

## 4. Life-Safety Sensitivity

If life-safety relevance has been declared at HIOM activation:  

- Certain Validation Required conditions may escalate to **HARD STOP**
- Extrapolation beyond validated ranges defaults to **HARD STOP**

This sensitivity is rule-based and deterministic within this baseline.

## 5. Logging Requirements

Each enforcement event must record:  

- Event type
- Triggering condition
- Timestamp
- Engineer response (resolve, override, acknowledge)

Logging in **Version 1.0** is local to the reasoning session.  
Enterprise escalation mechanisms are not defined in this baseline.

## 6. Boundary Conditions

STOP logic:  

- Does not evaluate correctness
- Does not compute engineering validity
- Does not substitute for professional judgment

It enforces structural reasoning integrity only.

## 7. Version Scope

This document defines complete derivation transparency requirements for **Specification Baseline Version 1.0**.  
Future revisions may introduce extended traceability or formalized derivation templates.
