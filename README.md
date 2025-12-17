🧭 The Deterministic Toolsmith
Engineering for Safe First Decisions in Unfamiliar Systems

Hi. I’m Dee.

I build deterministic, offline analysis systems for software, infrastructure, and AI platforms where the cost of the wrong first change is high.

This work exists for one reason:

Capable teams routinely damage unfamiliar systems by acting on confidence they have not earned.

🔒 Design Doctrine

Every system I build follows the same non-negotiable constraints:

Identical input produces identical output

Conclusions are derived only from observable evidence

Confidence is explicitly bounded

Refusal and silence are valid outcomes

If a conclusion cannot be justified safely, it is not produced.

🛠️ What These Systems Do

These tools analyze repositories, infrastructure definitions, and AI pipelines without executing them.

They are designed to answer a narrow but critical question:

Where can pressure be applied safely, and where must it not?

Operational guarantees:

Offline execution

No credentials

No network access

No side effects

They optimize for decision safety, not activity, coverage, or output volume.

📦 Selected Work
VectorScan

Open Source · AI and RAG Safety · Python

Static analysis for vector databases and RAG systems.

Detects exposure, permission drift, and data-leakage risk

Structural signals only

Explicitly refuses to speculate on runtime behavior

🔗 https://github.com/Dee66/VectorScan

ComputeScan

Infrastructure Analysis · FinOps and Reliability

Offline analysis of Terraform and infrastructure definitions.

Identifies compute oversizing, scaling misconfiguration, and cost risk

Designed for ML platforms and cost-sensitive environments

Ignores performance claims that cannot be verified statically

CostPilot

In Progress · Deterministic FinOps

A deterministic engine for bounding cloud cost regressions before deployment.

Predicts cost impact from infrastructure deltas

Produces auditable, reproducible reports

Does not apply changes without bounded confidence

🔁 Determinism in Practice

Static, offline analysis with absolute determinism.

Same input → same output → same hash

<p align="center"> <img src="computescan_terminal.gif" alt="Deterministic offline analysis example" width="850"> </p>
🧪 Current Focus: The Litmus Engine

An open-source engine that formalizes senior-grade repository review.

Litmus exists to answer one question before any action is taken:

Where is it safe to apply pressure, and where would that be irresponsible?

It produces:

Explicit Safe-to-Change Surfaces

Bounded conclusions with visible limits

Documented refusals when no safe move exists

Explanations of where less disciplined tools would mislead

Litmus does not replace human judgment.
It exists to prevent tools from counterfeiting it.

📬 Contact

Architectural discussion via GitHub issues on relevant repositories

Professional context:
LinkedIn – Deon Prinsloo
