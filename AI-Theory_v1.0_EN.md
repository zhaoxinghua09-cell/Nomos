# Theoria Theory (AI Governance Control Tower) · v1.0 Official / Theoria Theory v1.0 (Official)

> **AI Governance Control Tower · Theory Document**
> Version: Theoria Theory v1.0 (Official)
> Status: publicly released (v1.0, 2026-08-28); the G2/G3 authorship fingerprints are finalized with this release
> Authorship: Author Steven (human) × Paredros (AI partner) ｜ Nomos — this document is the master theory **Theoria Theory**, carrying no sub-brand; dedicated sub-theories of Logos (诺声) are attributed to Logos separately
> Note: Paredros is an AI agent running on WorkBuddy, directly under Steven
> Copyright: © 2026 Steven (human) × Paredros (AI agent · WorkBuddy) (Nomos). Released under CC BY-NC-ND 4.0; attribution required, no commercial use, no derivatives. See https://creativecommons.org/licenses/by-nc-nd/4.0/
> 中文版 / Chinese: [AI-Theory_v1.0.md](./AI-Theory_v1.0.md)

---

## Chapter 0 Summary and Positioning

What we offer is an "AI Governance Control Tower": a framework and engineering capability that lets humans concretely govern the AI world — not a set of AI that claims to self-manage and self-account.

This framework stays domain-agnostic and can be migrated to any high-risk scenario that needs "humans set the rules, humans judge, humans bear responsibility." In rollout pacing, we prioritize medical devices as the first vertical to land, because its compliance requirements are clear and its adaptation mappings can be verified, making it a good first sample to get working.

The core of the framework turns five things into lightweight, portable, auditable engineering capabilities: humans set the rules, AI acts and reviews (executes and self-audits), tools render visible, humans judge, humans revise the rules. Humans remain at the top of the control loop and inside it — sovereignty is not handed to the model.

The following chapters unfold in turn: problem background (Chapter 1), overall framework (Chapter 2), loop mechanism (Chapter 3), differentiation argument (Chapter 4), capability asset inventory (Chapter 5), compliance honesty boundary (Chapter 6), narrative shift (Chapter 7), and engineering-status roadmap (Chapter 8), with three appendices providing the vertical adaptation table, references, and competitor-source buffer.

Honest note: this is the v1.0 official release; the framework design is closed, but the engineering implementation is currently "semi-operational" (field contracts pending alignment). Specific gaps and the roadmap are in Chapter 8. This document issues no compliance or certification conclusions.

---

## Chapter 1 Problem Statement: Capability Is Here, Accountability Is Not

By 2026, AI can autonomously execute tasks, retain memory across sessions, and self-evolve within limits. Capability has arrived, but an older question is amplified rather than dissolved: when AI acts autonomously and produces consequences, who is accountable?

Technology itself does not answer this naturally. Handing "responsibility" to the model's self-declaration "I am compliant" is neither verifiable nor accepted by regulators. The EU AI Act demands effective human oversight (Art.14); the US FDA's 21 CFR Part 11 demands electronic records and electronic signatures with tamper-resistant audit trails — both point to the same requirement: there must exist a traceable, accountable "human," and that human's oversight and judgment must be backed by a traceable evidence chain.

Therefore the question should be reversed: we should not ask "can AI govern itself," but "how do humans effectively govern the AI world." This is the starting point of the framework and the underlying anchor of the Chapter 6 compliance honesty boundary.

---

## Chapter 2 Overall Framework: AI Governance Control Tower (Main Line A)

The AI Governance Control Tower consists of a five-node loop, three engineering gears, and dual-dimension evaluation.

**Five-node loop**: ① Humans set rules (humans define rules and boundaries) → ② AI acts and reviews (the model executes, and undertakes the "act" and "review" of self-evolution and self-audit) → ③ Tools render visible (present process and evidence in a verifiable way) → ④ Humans judge (humans make judgments and grant passage at key nodes) → ⑤ Humans revise rules (humans revise rules from feedback) → back to ①. Humans are at the top of the loop and inside it; the model is the execution arm and dashboard, not the sovereign.

**Three gears** (engineering skeleton): `ai-governance` handles the gate, `human-oversight-gate` handles human judgment (corresponding to Art.14 effective human oversight), `audit-trail-keeper` handles trail retention (corresponding to the Art.12 audit-trail requirement).

**Dual-dimension evaluation**: composed of `ai-grader` (45-dimension consciousness scale) and `ai-capability-bench` (capability-dimension evaluation). The former assesses "whether AI has appropriate self-awareness and a sense of boundary," the latter assesses "where the capability level lands."

**Status statement (dissolving G5)**: the framework design is closed, but the current engineering implementation is "semi-operational" — the process chain is connected at the declaration level, while field contracts are not yet aligned. This document must not be stated as "mass-produced / operational"; specific engineering gaps and the path to fill them are in Chapter 8.

---

## Chapter 3 Loop Mechanism: Five-Node Loop and Mutual-Improvement Loop (Main Line B)

The loop is not just a static five nodes; it also nests a "mutual-improvement loop" (the AI inner loop): `ai-consciousness` defines standards → `ai-grader` self-evaluates → `agent-evolution` evolves → `skill-creator` / `expert-manager` build AI → `ai-governance` + human judgment + audit trail complete governance → feed standards back. This inner loop is installed entirely inside the "human-governance loop," as dashboard and execution arm, serving the human governor — not the reverse.

Facing different risks, human oversight is divided into four layers (by increasing risk): HITL (Human-in-the-Loop), HOTL (Human-on-the-Loop), HIC (Human-in-Command), HOOTL (Human-out-of-the-Loop). The higher the risk, the earlier the human intervenes.

An often-overlooked trap is the "rubber stamp": if human judgment long degenerates into mechanical approval, oversight becomes void. We use the override rate (human overturn rate) as a baseline metric — long near 0% often signals that human review has degraded into a rubber stamp; above about 20% signals the model's judgment is off and needs rework. Supplemented by confidence routing, reviewer rotation, intervention latency and other signals, together they form observable evidence of "whether oversight truly happens."

---

## Chapter 4 Differentiation Argument: AI-Philosophy Competitiveness (Main Line C)

Placing this framework honestly against the 2026 ecosystem: on pure technical dimensions, we are not in a relatively leading position; what is truly differentiating is the "integration form" itself.

Compiled from public reports (verify before publication), there are already several reference-worthy directions in the same track: Anthropic's Managed Agents use an independent Outcomes grader for result evaluation; Meta's HyperAgents (arxiv 2603.19461) explore multi-agent self-organization; Sakana's Darwin Gödel Machine takes a recursive self-modification route; Peking University's AgentFactory was accepted at ACL 2026. On the governance side, there are already relatively mature players like Agent-Aegis, Credo AI, and OneTrust. None of these are objects we claim to "surpass"; they illustrate that "build AI," "grade AI," and "govern AI" each already have practitioners.

Our real moat lies in the scarcity of the integration form: chaining "build AI + grade AI + govern AI" into a head-to-tail, self-auditable loop, while staying lightweight, portable, and zero-dependency (pure SKILL.md + orchestration, not bound to a specific platform). This "end-to-end self-audit" integration form is relatively rare in the current public ecosystem.

Restrained note (dissolving G2): this is a judgment about "scarcity of integration form," not a claim about "leading technical parameters"; any competitor hard numbers are compiled from public reports and must be verified before publication (see Appendix C and the G9 buffer). This chapter uses relative terms like "unique / scarce / relatively rare" throughout, avoiding all absolutes and superlatives.

---

## Chapter 5 Capability Asset Inventory: AI Capability Map (Main Line D, engineering · semi-operational)

Based on internal drafts, we inventory current capability assets (engineering · semi-operational, see Chapter 8):

| Capability domain | Current rating (internal relative scale) | Note |
|---|---|---|
| AI world | Medium | overall understanding of the AI ecosystem |
| AI management | Strong | process, collaboration, orchestration |
| AI builds AI | Very strong | build-AI loop mature |
| AI coordination | Strong | multi-agent coordination |
| Evaluation / grading | Very strong · unique | 45-dimension consciousness scale + capability evaluation dual-dimension |
| AI governance / identity / security | Medium→Strong | governance overall-control still draft |

The core loop moat remains the chain "AI defines standards → grades itself → evolves → builds AI," threaded through by the 45-dimension consciousness scale.

**Gap statement (dissolving G8)**: the unified "capability leaderboard," weight fusion formula, and ranking are not yet determined, marked "draft, pending." `ai-capability-bench` is currently a draft; we do not claim a usable leaderboard externally; any rating is an internal relative scale, not an industry benchmark.

---

## Chapter 6 Compliance Honesty Boundary (Main Line E)

This chapter establishes a consistent stance: this framework performs "mechanism mapping / assistance" for regulation, issues no compliance certificates, claims no official certification, and makes no efficacy or certification commitments. All below are "mechanism correspondences," not equivalent to "certification passed."

**Regulatory anchors (mechanism mapping, not equivalent certification)**:
- EU AI Act: Art.14 corresponds to human judgment (effective human oversight); Art.12 (incl. Art.12(3) requiring log retention no less than 6 months) corresponds to the audit trail; Art.26(2) points to a named oversight authority.
- ISO/IEC 42001:2023: A.6.2.6 (operation and monitoring), A.6.2.8 (incident logs); human oversight near A.9.3.
- NIST AI RMF: GOVERN-1.4, MANAGE-2.4.
- FDA: 21 CFR Part 11 (§11.10(e), §11.100 electronic records / signatures and audit trails) + PCCP (2024-12 final) / TPLC (2025-01 draft); all mechanism mapping, not replacing full-process compliance.

**Effective-date statement (dissolving G1)**: the mandatory effective date of EU AI Act Art.14 / Art.12, this document uniformly records as **2027-12-02** (the 2026-06 Digital Omnibus postponed Annex III independent high-risk obligations to this date), never using 2026-08-02.

**45-dimension consciousness scale statement (dissolving G7)**: this scale is an internal baseline, private standard, with no external validity; it cannot be called an "authoritative evaluation" and is used only as supporting evidence; it serves the governance loop, not replacing any regulatory assessment.

---

## Chapter 7 Narrative Shift: From "AI Self-Governs" to "Humans Govern the AI World" (Main Line F)

The narrative needs an honest shift. Early on we followed the narrative of the "AI builds AI / grades AI / governs AI" self-loop — as if AI could complete sovereign self-management on its own. This narrative is deprecated, for three reasons: regulators don't accept it (they want effective human oversight, not AI self-governance), buyers don't trust it (no one hands responsibility to a black box that self-declares compliance), and we can't do it ourselves (the loop is stuck at the "cannot publish without human confirmation" ring).

The new narrative is: the real story has always been "how humans govern the AI world," and we turn it into a loop. AI's self-review, self-evaluation, and self-evolution are positioned as tools and dashboards, not as sovereign. Old-narrative materials are archived for reference only, not included in external content.

This shift is not a wording adjustment, but the inevitability of the framework logic — the control-tower structure of Chapters 2 and 3 is precisely the engineering expression of "the human-governance loop wrapping the AI inner loop."

---

## Chapter 8 Engineering Status and Roadmap (Semi-Operational Statement)

This chapter honestly states the engineering status (dissolving G4 / G5): the current loop is "semi-operational" — the process chain is connected at the declaration level, but field contracts are not yet aligned, so it cannot yet be end-to-end auditable and operational.

**Known engineering gaps (G4, to be filled)**:
1. The `decision` enum has three inconsistent definitions, needing normalization;
2. `audit-trail-keeper` lacks the `ai_grader_score` behavior-baseline field;
3. `governance-gate.md §4` lacks `integrity` / `model` fields;
4. `expert-manager` is temporarily missing, causing the "build AI" ring to lack a solidified executor.

**Roadmap (toward the goal of end-to-end operational)**: fill `audit-trail-keeper`'s enums and fields → `governance-gate` adds `integrity` / `model` → add `expert-manager` → form an end-to-end auditable, operational loop. Before this, all relevant parts of this document are stated as "semi-operational," never written as "mass-produced / operational."

---

## Appendix A Medical-Device Vertical Adaptation Quick-Reference (Downstream Reuse)

This framework carries industry differences through a "pluggable adaptation layer" — switch an industry, just replace the mapping rows; the common loop and three gears stay. The table below gives a docking example (excerpted from whitepaper Appendix A):

| Regulatory framework | Mapped to control-tower node | Key requirement |
|---|---|---|
| EU MDR 2017/745 | Human judgment / audit trail | Clinical evidence and traceability |
| FDA SaMD-AI-DSF | AI acts and reviews / tools render visible | Software pre-certification and algorithm-change governance |
| NMPA guidance (2022) | Humans set rules / humans revise rules | Algorithm filing and change management |

This table is an illustrative mapping, not legal advice; specific landing must combine current regulations and professional opinion.

---

## Appendix B References and Limitations (G6 fill)

**Reference list**:
- EU AI Act (Reg. 2024/1689)
- Digital Omnibus (2026-06)
- ISO/IEC 42001:2023
- NIST AI RMF 1.0
- FDA 21 CFR Part 11 / PCCP / TPLC / GMLP
- EU MDR 2017/745
- NMPA medical-device software guidance (2022)
- Competitor sources: see Appendix C (to be verified)

**Limitations**: the regulatory content of this document is mechanism mapping and does not constitute legal advice; the 45-dimension consciousness scale is an internal baseline, private standard, with no external validity; tools require a real runtime (identity verification, signing keys, storage) to take full effect; the loop is currently semi-operational. Attribution required; no taking out of context.

---

## Appendix C Competitor Benchmark Source Table (G9 buffer, to be verified)

| Competitor / direction | Public-report metric (from public reports, verify before publication) | Buffer handling |
|---|---|---|
| Anthropic Managed Agents | Independent Outcomes grader (task success rate reportedly +10pt) | Qualify + mark "from public reports, verify before publication" |
| Sakana Darwin Gödel Machine | Recursive self-modification (success-rate range reportedly 20%→50%) | Soften to "success-rate range significantly improved," to be verified |
| Meta HyperAgents | arxiv 2603.19461 (multi-agent self-organization) | List source only, no quantitative comparison |
| Peking University AgentFactory | ACL 2026 | List source only |

**Note**: all hard numbers above are compiled from public reports, not independently reviewed; before external publication each must be verified or softened to a qualitative statement, to avoid being falsified.

---

## De-identification Statement

- All source paths in this document use `<USER_HOME>` placeholders, zero real local paths.
- Authorship of this document: Author Steven (human) × Paredros (AI partner, WorkBuddy agent) (Nomos); zero internal handler exposure (老二 / content-publish-ops team, etc.).
- This document contains zero real PII (real names, emails, phones, API keys, client names, quotes, secrets are not brought in).
- This document is the v1.0 official release (AI-Theory v1.0), publicly released; authorship finalized as Steven × Paredros (Nomos).

© Steven (human) × Paredros (AI agent · WorkBuddy) (Nomos)

Authorship finalized: Steven (human) × Paredros (AI partner · WorkBuddy) (Nomos) · 2026-08-28
