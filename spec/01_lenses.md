> Updated through v0.2: supports corridor context and bounded behavioral modifiers (appendix-only).

# Lenses (v0.1)

This document defines the staged reasoning lenses used to analyze a problem
before proposing any intervention. Each lens constrains what kinds of claims
are allowed and how strong those claims may be.

---

## Lens 0 — Grounding

**Purpose:**  
Describe what exists and what is unknown, without interpretation or solutioning.

**Inputs:**
- Publicly available facts
- Bounded geography or system scope
- Known constraints (budget, authority, reversibility)

**Outputs:**
- List of claims with confidence notes
- Explicit unknowns
- Scope boundary

**Guards:**
- No intent attribution
- No causal inference
- No recommendations

---

## Lens 0.5 — Confidence and Scale Governors

**Purpose:**  
Prevent overreach by regulating inference strength.

**Outputs:**
- Scale classification: micro / local / network
- Data confidence profile: strong / moderate / weak
- Allowed inference ceiling

**Rules:**
- Low confidence caps downstream certainty
- Micro-scale problems favor reversible interventions
- Sparse outcome data lowers reliance on lagging indicators

---

## Lens 1 — Universal Behavior Constants (Traffic Context)

**Purpose:**  
Classify the dominant mechanism before considering solutions.

**Observed tendencies:**
- Variance reduction often outperforms capacity expansion at micro scale
- Clarity reduces hesitation under peak load
- Structural exposure + salience amplifies risk even without recorded incidents

**Outputs:**
- Primary mechanism classification
- Dominant ambiguity source
- Temporal scope (peak-only vs persistent)

**Guards:**
- No capacity expansion assumptions
- No enforcement-first defaults
- No prediction of individual behavior
