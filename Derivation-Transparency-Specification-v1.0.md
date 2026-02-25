# Derivation Transparency Specification  

Version 1.0  
EIM Operational Engine  
Specification Baseline — Version 1.0

## 1. Purpose  

The Derivation Transparency Specification defines the requirements for exposing calculation chains within High-Integrity Operating Mode (HIOM).  

Its purpose is to prevent hidden or opaque computation from influencing engineering reasoning without explicit visibility.  

## 2. Mandatory Derivation Disclosure  

Any calculated result introduced within HIOM must expose:  

- All input variables used
- Units for each variable
- The formula or governing relationship applied
- Substitution of numerical values
- Intermediate calculation steps where applicable
- Final result with units
- Rounding or approximation disclosure (if applied)  

Presentation of final results alone is not sufficient.

## 3. Constant and Reference Disclosure

If a constant, standard value, or industry parameter is used, it must be:  

- Explicitly labeled
- Identified as declared or referenced
- Accompanied by source reference if applicable

Implicit or typical values are treated as Default Value Insertion events.

## 4. External Tool Outputs

If results originate from:  

- Simulation software
- Protection coordination tools
- Manufacturer calculators
- External spreadsheets

The following must be disclosed:  

- Tool identity
- Version (if known)
- Input parameters used

The EIM Operational Engine does not validate the tool. It validates transparency of origin.

## 5. Dependency Traceability

If a derived result depends on prior derived values:  

- The upstream derivation chain must remain accessible.
- No derived value may reference hidden intermediate steps.

Chained derivations must remain expandable and reviewable.

## 6. Enforcement Linkage

Failure to meet derivation transparency requirements triggers:

Undisclosed Derivation (UD)  
→ **HARD STOP** under

- `STOP-Logic-Specification-v1.0.md` — deterministic enforcement behavior  

## 7. Boundary Conditions

This specification:  

- Does not verify mathematical correctness
- Does not replace independent validation
- Does not substitute for peer review

It enforces structural visibility only.

## 8. Version Scope

This document defines complete derivation transparency requirements for **Specification Baseline Version 1.0**.  
Future revisions may introduce extended traceability or formalized derivation templates.
