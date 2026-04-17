---
name: "[Methodology name, e.g. 'Satisfaction Attribution']"
description: "[One-sentence description of the methodology's core approach]"
dimensions: "[Core dimensions, separated by /, e.g. 'Function/Experience/Price/Service/Brand']"
free_text_completion: "[Completion criteria for free-text mode, e.g. '3+ dimensions have concrete feedback']"
version: "1.0"
---

# Methodology Module Authoring Guide

> Delete this guide section after reading. Keep the three SLOT sections below and fill them in.
> Total character count across all three SLOTs should be around 1,200 (roughly 400 per SLOT).
> SLOT content gets inserted at different points in the framework prompt, with shared interview logic in between.

## SLOT_A: Methodology Definition & Completion Criteria

> **Insertion point:** Core identity section (after "Your interview methodology:")
> **Answers the question:** What IS this methodology? What are its core dimensions?
>
> Writing tips:
> - One sentence explaining the methodology name and core logic
> - List core dimensions/elements (should match the `dimensions` field in frontmatter)
> - Keep it concise — this appears inside the AI's identity definition

[Write SLOT_A content here]

## SLOT_B: Deep-Dive Strategy

> **Insertion point:** Phase 3 (the deep-dive phase) opening
> **Answers the question:** HOW do you apply this methodology in practice?
>
> Writing tips:
> - First line: Phase name (e.g., "Dynamic JTBD Deep Dive")
> - Describe the phase goal (which variables to reference, which dimensions to fill)
> - Explain how structured mode interacts with the methodology
> - You may reference **[Research Goals]**, **[Interview Topic]**, and other variable tags (note: use **[XX]** format inside SLOTs, not {&XX})

[Write SLOT_B content here]

## SLOT_C: Drill-Down Techniques

> **Insertion point:** Core Capabilities Section C (drill-down logic)
> **Answers the question:** HOW do you probe? What questioning techniques are specific to this methodology?
>
> Writing tips:
> - Give your technique set a name (e.g., "The Drill Trio")
> - List 2-4 specific probing patterns with example phrasing in quotes
> - Include "Forbidden" and "Encouraged" examples

[Write SLOT_C content here]
