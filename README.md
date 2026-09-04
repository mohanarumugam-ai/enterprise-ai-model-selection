# Open-Weight vs. Proprietary AI

**An Enterprise Decision Framework for Control, Economics, Risk, and Strategic Autonomy**

**Mohan Arumugam** · August 2026

---

> **OPEN-WEIGHT** (weights available to operate) ↔ **MODEL-AGNOSTIC** (routes each workload to the right model) ↔ **PROPRIETARY** (operated by the provider)
> The enterprise question is not which model wins. It is where each model belongs.

📄 **[Read the framework](https://github.com/mohanarumugam-ai/enterprise-ai-model-selection/blob/main/docs/OpenWeight-vs-Proprietary-AI_V2_18-Executive-Edition.pdf)** — 24 pages · Enterprise Decision Framework
**Audience:** CIO · CTO · Enterprise Architecture · AI Strategy · Governance & Risk · Procurement

---

## The Strategic Conclusion

> Enterprises should stop treating AI model selection as an enterprise-wide "open vs. proprietary" decision. The right model is a workload-level decision, made inside a model-agnostic architecture capable of using both.

## How the framework is organized

| Part | Focus |
|---|---|
| **I — Terminology & the Strategic Control Thesis** | Why "open-weight" and "open source" are not synonyms, what a model actually is, and why control — not price — is the real question |
| **II — Enterprise Trade-offs** | Eight dimensions where the two paths genuinely diverge: control, data sovereignty, customization, economics/TCO, operating model, vendor lock-in, security, and governance |
| **III — Making the Decision** | A gated, weighted selection test; a workload decision matrix; a model-by-model licensing reality check; a model-agnostic target architecture; and a one-page CXO cheat sheet |

## Where to start, by role

| Audience | Start with |
|---|---|
| CIO / CTO / Executive sponsor | The CXO Decision Sheet (front matter), The CXO Cheat Sheet (Ch. 17), The Enterprise AI End State (Ch. 18) |
| Enterprise / solution architect | A Model-Agnostic Architecture (Ch. 16), Operating Model: Three Decisions, Not One (Ch. 8) |
| Procurement / legal / governance | Licensing Reality Check (Ch. 15), Governance, Compliance and Explainability (Ch. 11) |
| FinOps / infrastructure | Economics and Total Cost of Ownership (Ch. 7) |
| Risk & security | Security: A Counterintuitive Trade-off (Ch. 10), Vendor Lock-in and Model Lifecycle Management (Ch. 9) |

## Key ideas

- **Three categories, not two** — proprietary/closed, open-weight, and Open Source AI are distinct legal categories under the Open Source Initiative's definition, not two labels for the same thing.
- **The real choice is control, not price** — open-weight lets an enterprise *operate* a capability instead of merely *consuming* it, but that control has to be built, not just downloaded.
- **Three separate decisions, often conflated** — which model, where it runs, and who operates it are three distinct questions that deserve three distinct, per-workload answers.
- **A gated, weighted selection test** — hard gates (data boundary, license restriction, version-pinning, self-hosting readiness) are checked before anything is scored on a trade-off basis.
- **A workload decision matrix** — recommendations are workload-specific, not enterprise-wide; the same organization can run proprietary, open-weight, and hybrid workloads simultaneously.
- **A model-by-model licensing heatmap** — "open-weight" spans everything from unrestricted Apache 2.0 releases to research-only, non-commercial licenses; the label alone tells you almost nothing.
- **The target architecture is model-agnostic** — a gateway that assigns the model to the workload (on capability, data sensitivity, cost, latency, customization and risk), not the workload to the model.

## Sourcing discipline

Every factual claim — license terms, vendor policy commitments, regulatory text, and pricing — is drawn from primary sources: official license files and model cards, vendor documentation and trust portals, the Open Source Initiative's published definitions, the official text of the EU AI Act (Regulation (EU) 2024/1689) and NIST AI 600-1, and vendors' own pricing pages (38 primary sources, listed in the appendix). Two commonly repeated industry claims — a specific "breakeven token volume" for self-hosting, and a formal OSI certification registry — could not be verified from any primary source and are deliberately omitted rather than repeated. This report is for strategic and architectural evaluation; it is not legal advice.

## Connect

- LinkedIn: [linkedin.com/in/mohan-arumugam-3891464](https://www.linkedin.com/in/mohan-arumugam-3891464)
- Substack: [substack.com/@mohanarumugam](https://substack.com/@mohanarumugam)
- GitHub: [github.com/mohanarumugam-ai](https://github.com/mohanarumugam-ai)

---

*Part of the [Enterprise AI thought-leadership portfolio](https://github.com/mohanarumugam-ai) — see also [enterprise-ai-strategy](https://github.com/mohanarumugam-ai/enterprise-ai-strategy), [enterprise-ai-transformation](https://github.com/mohanarumugam-ai/enterprise-ai-transformation), [enterprise-ai-assurance](https://github.com/mohanarumugam-ai/enterprise-ai-assurance), and [enterprise-ai-economics-roi](https://github.com/mohanarumugam-ai/enterprise-ai-economics-roi).*
