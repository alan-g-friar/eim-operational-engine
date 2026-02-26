# EIM Operational Engine
## Specification Baseline — Version 1.0  
### Experimental Implementation Framework

**Author:** Alan Friar  
**Organization:** EnBra Group  
**Version:** 1.0  
**Date:** 2026-02-25  

## Overview

This repository contains the canonical, timestamped publication of the Specification Baseline for the EIM Operational Engine.

The EIM Operational Engine defines a structured enforcement architecture designed to support high-integrity engineering reasoning in environments where incorrect conclusions may carry asymmetric risk.

It builds upon principles described in:

> *The Missing Engineer-Grade AI: Operating Contracts for Real-World Assistance (2026)*  
> *Shared Cognitive State in Human–LLM Interaction: Failure Modes, Risk Surfaces, and Structural Implications (2026)*

Those publications define structural risks and behavioral operating contracts. This repository translates those principles into a deterministic enforcement framework intended for practical implementation.

This work is design-oriented and implementation-architectural in nature. It does not represent a deployed product, certified system, or production-ready platform.

## Purpose

The EIM Operational Engine introduces a High-Integrity Operating Mode (HIOM).

HIOM is an explicitly activated reasoning state intended for engineering workflows where reasoning affects real-world systems.

When active, the framework:

- Surfaces hidden assumptions  
- Requires explicit variable declaration  
- Enforces derivation transparency  
- Prevents silent scope drift  
- Applies deterministic STOP logic when structural violations occur  
- Requires structured justification for overrides

The framework does not make decisions, guarantee safety outcomes, or replace engineering authority. It instruments reasoning discipline and creates traceability under constrained conditions.

## Scope of Specification Baseline Version 1.0

Version 1.0 defines the following components:
	
- High-Integrity Operating Mode (HIOM)  
- Assumption Event Taxonomy v1.0  
- Required Variable Framework v1.0  
- STOP Logic Specification v1.0  
- Derivation Transparency Specification v1.0  
- Explicit Engineering Mode activation and boundary rules

This baseline defines a complete enforcement architecture within its stated limits.

Version 1.0 does not include:

- Automatic hierarchical escalation  
- Behavioral pattern analytics  
- Adaptive rigor scaling  
- Enterprise governance systems  
- Similarity scoring engines  
- Deployment or runtime implementation code

Future revisions may expand scope through explicitly versioned specification updates.

## Planned Extension Areas

The following areas are identified for potential future specification revisions:

### Behavioral Integrity Escalation Framework (Planned v1.1)
	
- Detection of repeated override patterns  
- Threshold-based flag generation  
- Configurable life-safety sensitivity weighting  
- Visibility tiers for multi-level engineering review  
- Flag-only escalation model with no automatic enforcement

This extension is not part of Specification Baseline Version 1.0.

## Relationship to Prior Publications

This repository operationalizes principles defined in:

Friar, A. (2026). *The Missing Engineer-Grade AI: Operating Contracts for Real-World Assistance*.
Friar, A. (2026). *Shared Cognitive State in Human–LLM Interaction: Failure Modes, Risk Surfaces, and Structural Implications*.

Those works remain doctrinal and informational. This repository defines an experimental enforcement architecture derived from those principles.

## Contents

- `Assumption-Event-Taxonomy-v1.0.md` — classification of enforceable assumption events
- `Derivation-Transparency-Specification-v1.0.md` — formal derivation exposure requirements
- `HIOM-Definition-v1.0.md` — definition of High-Integrity Operating Mode
- `Required-Variable-Framework-v1.0.md` — engineer-led variable declaration model  
- `STOP-Logic-Specification-v1.0.md` — deterministic enforcement behavior  
- `Specification-Index-v1.0.md` — structural index of all baseline components  

## Citation

If referencing this work, please cite as:

Friar, A. (2026). *EIM Operational Engine: Specification Baseline Version 1.0*.  
GitHub repository: https://github.com/alan-g-friar/eim-operational-engine

## Status

This repository represents **Specification Baseline Version 1.0**.  
Future revisions will be versioned explicitly and committed separately.  
The framework is experimental and intended for architectural exploration, peer review, and structured prototyping.
