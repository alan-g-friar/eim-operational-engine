# Assumption Event Taxonomy

Version 1.0  
EIM Operational Engine  
Specification Baseline — Version 1.0

## 1. Definition of an Assumption Event

An Assumption Event occurs when any value, condition, constraint, dependency, or conclusion is introduced into engineering reasoning without being: 

- Explicitly declared  
- Deterministically derived, or  
- Externally verified and disclosed  

Assumption Events represent structural integrity gaps within HIOM and are subject to enforcement behavior defined in the STOP Logic Specification.  

## 2. Event Categories  
### 2.1 Missing Input Assumption (MIA)  

A required variable necessary for valid reasoning has not been explicitly provided.

Examples:  
- Protection setting referenced without declared pickup value
- Structural load calculation performed without material property declaration
- Environmental rating assumed without classification

Enforcement: **HARD STOP**

### 2.2 Default Value Insertion (DVI)  

A typical or experience-based value is introduced without explicit declaration or source disclosure.

Examples:  
- Standard ambient temperature assumed  
- Typical safety factor inserted  
- “Common” CT ratio applied  

Enforcement: **HARD STOP**  

### 2.3 Undeclared Boundary Condition (UBC)  

A limiting condition or operating constraint is implied but not explicitly declared.

Examples:  
- Continuous duty assumed  
- Upstream/downstream logic implied without confirmation  
- Redundancy assumption not declared

Enforcement: **HARD STOP**

### 2.4 Contextual Inference Assumption (CIA)

A conclusion is drawn based on similarity, narrative reasoning, or contextual interpretation without deterministic validation.

Examples:  
- “This is similar to previous project.”
- “This should trip first because it is upstream.”

Enforcement: **Validation Required (no silent acceptance)**

### 2.5 Similarity Carryover Assumption (SCA)

Parameters from previous sessions or projects are reused without explicit confirmation of equivalence.

Examples:  
- Reusing protection settings
- Copying environmental classification
- Applying prior project constraints

Enforcement: **HARD STOP**

### 2.6 Extrapolation Assumption (EA)

A value is extended beyond its validated range without supporting derivation or reference.

Examples:  
- Linear scaling beyond tested limits
- Operating beyond specified temperature range
- Capacity extension without structural validation

Enforcement:  
- **HARD STOP** if life-safety tier
- **Validation Required** otherwise

### 2.7 Undisclosed Derivation (UD)

A calculated result is presented without exposing its full derivation chain.  

Examples:  
- Final value shown without formula
- Omitted intermediate steps
- Constants used without source disclosure

Enforcement: **HARD STOP**

## 3. Enforcement Linkage

Each Assumption Event category maps to enforcement behavior defined in:  

- `STOP-Logic-Specification-v1.0.md` — deterministic enforcement behavior  

No Assumption Event may resolve silently within HIOM.

## 4. Version Scope

This taxonomy defines the complete set of Assumption Event categories for **Specification Baseline Version 1.0**.  
Future revisions may expand or refine categories.  
Any changes require explicit version increment.


