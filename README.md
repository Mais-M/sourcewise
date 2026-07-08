# SourceWise

**SourceWise** is an audit-first Competitive Intelligence and OSINT assistant in Hebrew.

It is designed to support structured, ethical, and evidence-based research workflows — not to invent company facts or generate unsupported business claims.

> **No source = no fact.**

If a claim cannot be supported by a precise and verifiable source, it should not be presented as fact. Instead, it must be moved to:

> **דורש אימות — לא סופק מקור מדויק**  
> Requires verification — no precise source was provided.

---

## Live Demo

A public prototype demo of SourceWise is available through the project website link.

SourceWise is a methodological prototype. It does not generate factual company intelligence without sources. When no evidence is provided, it produces a research plan, an empty Evidence Register, and a Requires Verification section.
## Demo Output

A sample methodological output is available here:

[sourcewise-methodological-demo.html](./sourcewise-methodological-demo.html)

This demo shows the intended behavior when no company-specific sources are provided: SourceWise does not generate unsupported factual claims. Instead, it produces a research plan, an empty Evidence Register, and a Requires Verification section.

---

## Purpose

SourceWise was created as a methodological prototype for Competitive Intelligence and OSINT analysis.

The goal is not to replace an analyst, but to help analysts, students, researchers, and business users work in a more structured and responsible way.

SourceWise helps transform scattered questions and unverified assumptions into an auditable research process.

---

## What SourceWise Helps With

SourceWise can support the creation of:

- Key Intelligence Topics, KIT
- Key Intelligence Questions, KIQ
- OSINT source collection plans
- Competitor mapping structures
- SWOT analysis frameworks
- Battlecard structures
- Evidence Register templates
- Requires Verification sections
- Confidence levels and limitations
- Separation between facts, interpretations, assumptions, and recommendations

---

## What SourceWise Does Not Do

SourceWise is not a factual authority.

It should not:

- invent market data
- invent sources or citations
- fabricate URLs
- present revenue, ARR, MAU, valuation, market share, IPO timelines, growth rates, or acquisition values without evidence
- mark unsupported claims as verified
- use course materials as factual evidence about a company

The uploaded course materials are used as methodology, examples, ethical guidance, and prompt-engineering guidance only.

They are not factual evidence about any specific company.

---

## Core Reliability Rule

Every factual or numeric claim must be supported by a complete Evidence Register entry.

The Evidence Register should include:

| Claim | Full source title | Publisher | Publication date | URL / retrievable identifier | Evidence type | Confidence level | Limitation |
|---|---|---|---|---|---|---|---|

If these fields cannot be completed, the claim should not appear as a factual statement in the final report.

---

## Expected Behavior

When the user provides verified sources, SourceWise can help organize and analyze them into a structured competitive intelligence report.

When the user does not provide sources, SourceWise should not generate a factual company report.

Instead, it should generate a methodological research plan that includes:

- KIT
- KIQ
- source collection plan
- suggested OSINT source categories
- empty Evidence Register template
- Requires Verification list

This behavior is intentional.

It helps prevent hallucinated business intelligence and unsupported claims.

---

## Methodological Foundations

SourceWise is based on principles from:

- Competitive Intelligence
- OSINT using public sources
- KIT / KIQ methodology
- Battlecard development
- Evidence-based analysis
- Prompt engineering strategies
- AI agent ethics
- Transparency, privacy, accountability, and responsible use

---

## Why This Matters

In competitive intelligence, a convincing report is not enough.

A useful intelligence output must be:

- traceable
- source-based
- transparent about uncertainty
- clear about limitations
- ethically collected
- auditable by another person

SourceWise was built around this idea.

A beautiful report without evidence is not intelligence.  
It is only persuasive text.

---

## Current Status

SourceWise is a prototype / work in progress.

The current version focuses on enforcing an audit-first workflow and preventing unsupported factual claims.

The project demonstrates how AI agents can be designed not only to generate outputs, but also to respect methodological, ethical, and evidentiary boundaries.

---

## Disclaimer

SourceWise is a research-support prototype.

It does not provide investment, legal, financial, or strategic advice.

All factual outputs should be independently verified before use.
