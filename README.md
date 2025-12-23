# The Dual-Self Systems Model: A Principled Framework for Stability-Plasticity

Current artificial intelligence systems face a fundamental dilemma: rapid adaptation to new tasks often erases foundational knowledge (catastrophic forgetting), while protecting foundation models prevents personalization. This repository presents the Operational Blueprint, an architectural framework that addresses this challenge through explicit time-scale separation.

**The Ultimate Synthesis**

This framework integrates insights from dual-process cognitive theory, predictive processing, and continual learning research into a unified computational architecture. It offers a prescriptive methodology for AI engineering that ensures:

**Structural Alignment:** 

Foundational values and world knowledge are protected by freezing Self A, providing an architectural guarantee against reward hacking.

**Mitigated Catastrophic Forgetting:**

A multi-layered defense (Frozen Backbone + LoRA + EWC) reduces forgetting to a predicted 12%, compared to 65% in monolithic systems.

**Explicit Arbitration:** 

The use of $\alpha/\beta$ routing weights transforms the stability-plasticity tradeoff into an interpretable and loggable design parameter.

**Repository Contents**

Manuscript_v2.pdf: 

The full 2025 version 2.0 manuscript detailing the theoretical foundations and 20+ falsifiable predictions.

Dual_Self_Model.ipynb: 

**A Google Colab-ready implementation of the Operational Blueprint demonstrating all five core scenarios**

**Production_Readiness_Checklist:** 

A definitive guide for transitioning the architecture to high-stakes production environments (Section 6.9).

Scientific Rigor: Falsification Criteria

To ensure this framework is a testable science, we establish the following conditions under which the model would be rejected (Section 5.5):

## Scientific Rigor: Falsification Criteria

To ensure this framework is a testable science, we establish the following conditions under 

which the model would be rejected (Section 5.5):

| Test Category | Rejection Rule | Theoretical Implication |
| :--- | :--- | :--- | 
| **Architectural Advantage** |Forgetting Rate $\ge$ Monolithic | Separation provides no benefit. |
| **Neural Dissociation** | Identical network signatures| Undermines biological plausibility. |
| **Construct Incoherence**| Negative behavioral/neural correlation | Framework is incoherent.|
