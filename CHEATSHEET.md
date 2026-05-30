https://github.com/ayushbishtdev/ai-governance-compliance-officer-career/tree/main/data# AI Governance Compliance Officer — One-Page Cheatsheet (May 2026)

---

## Regulatory Frameworks at a Glance

| Framework | Jurisdiction | Key Function for This Role | Enforcement Trigger |
|---|---|---|---|
| EU AI Act Article 26 | EU (extraterritorial) | Deployer obligations: human oversight, log retention, FRIA, incident reporting | 02 Aug 2026 (high-risk systems) |
| EU AI Act Article 56 | EU | AI ethics board / quality management system audit | Active from Aug 2026 |
| NIST AI RMF 1.0 | US federal | Govern → Map → Measure → Manage cycle for algorithmic risk | Voluntary; de facto standard for US enterprise |
| ISO/IEC 42001:2023 | International | AI Management System (AIMS) — certifiable by accredited body | Active; increasingly required in vendor contracts |
| India DPDP Act | India | Purpose limitation, data minimization, algorithmic transparency for personal data | Enforceable; penalty-bearing |
| Colorado SB 205 | US (Colorado) | High-risk AI deployer obligations at state level | Active |
| NYC Local Law 144 | US (NYC) | Automated employment decision tool auditing | Active |

---

## NIST AI RMF: Four Functions Summarised

| Function | What the Compliance Officer Does |
|---|---|
| **Govern** | Establish risk tolerances; define accountability; set model retraining triggers |
| **Map** | Classify AI systems by risk tier; build the system inventory; identify stakeholders |
| **Measure** | Run bias testing (Fairlearn, IBM AI Fairness 360); quantify socio-technical impacts; track fairness metrics |
| **Manage** | Execute the post-market monitoring loop; run shadow AI discovery; manage incident reporting |

---

## EU AI Act Article 26 — 11 Deployer Duties (Quick Reference)

1. Use the system per the provider's instructions of use
2. Assign human oversight to competent natural persons
3. Ensure input data is sufficiently relevant and representative
4. Monitor operations continuously post-deployment
5. Retain event logs for minimum six months
6. Report serious incidents within 15 days
7. Conduct Fundamental Rights Impact Assessments (FRIAs) for high-risk systems
8. Maintain live AI system risk register with conformity status
9. Manage vendor and third-party AI due diligence (GPAI documentation review)
10. Design and verify human-in-the-loop and human-on-the-loop controls
11. Run the Article 4 organisation-wide AI literacy programme (for EU operators)

---

## Role Definitions — Quick Reference

**AI Governance Compliance Officer**
Second line of defence. Owns evidence artefacts. Reports to CRO / CCO / Audit Committee. Signs Article 26 attestations. Does not build models.

**Responsible AI Officer (CRAIO)**
Second line of defence. Owns the full risk portfolio. Typically holds board-level veto for high-risk deployments. Secretariat of the AI Ethics Board.

**Chief AI Officer (CAIO)**
First line of defence. Owns AI strategy and P&L. Reports to CEO/COO. Cannot simultaneously hold the Article 26 sign-off role — structural conflict of interest.

**AI Audit Engineer**
Third line of defence (Internal Audit). Executes algorithmic forensic testing and automated evidence curation. Cannot audit a model they helped build.

**AI Ethics Consultant**
External or internal advisory. Designs frameworks and conducts specific audits. Does not own the continuous daily governance cadence (that is the Officer's role).

---

## Certification Decision Tree

```
Do you want an AI governance compliance officer role?
│
├─ YES
│   ├─ AIGP (IAPP) ─────────────────── Start here. Mandatory ATS signal.
│   ├─ ISO/IEC 42001 Lead Auditor ──── Second. Proves you can operate an AIMS.
│   ├─ NIST AI RMF training ────────── Third. Required for US-headquartered firms.
│   └─ CRISC / CISA (ISACA) ────────── Supplement if you have an audit background.
│
└─ Do you already hold CIPP/E?
    ├─ YES → Do NOT let it lapse. Stack AIGP on top. Lead with AIGP in interviews.
    └─ NO  → Skip CIPP; go straight to AIGP. CIPP alone routes you to the legal pool.
```

---

## AI Ethics Board: 7-Seat Composition

| Seat | Title | Line of Defence | Key Contribution |
|---|---|---|---|
| 1 (Chair) | Chief Risk Officer | Second / Independent | Revenue-independent veto authority |
| 2 | AI Governance Compliance Officer | Second | Evidence curation, Article 26 sign-off |
| 3 | Lead ML Engineer | First | Technical model defence |
| 4 | Chief Data Officer | First | Training data lineage, DPDP/GDPR compliance |
| 5 | CISO | Second | Agentic threat vectors, prompt injection defence |
| 6 | Legal Counsel | Advisory | Real-time regulatory interpretation |
| 7 | Business Unit Lead | First | Commercial intended purpose representative |

**Failure modes to avoid:** CEO as chair (revenue conflict), legal-only composition (no MLOps challenge), external ethicists without accountability (recommendations ignored).

**Charter requirement:** Explicit binding veto power over any model entering production. Must be in corporate bylaws, not just committee guidance.

---

## Salary Quick Reference (May 2026)

| Geography | IC / Mid | Senior | Director / Lead | Regulated Premium |
|---|---|---|---|---|
| US | $135K–$162K base | $185K–$210K base | $250K–$285K base | +15–22% |
| Germany | €95K–€115K total | €130K–€155K total | €160K–€175K total | Frankfurt/Munich bid-up |
| India GCC | ₹28L–₹35L total | ₹40L–₹50L total | ₹55L–₹65L total | Cross-jurisdictional premium |
| India Domestic | ₹15L–₹20L total | ₹20L–₹25L total | — | Not GCC-level |

---

## 90-Day Entry Plan

**Days 1–30: Regulatory Grounding**
- Read EU AI Act Article 26 in full. Map all 11 duties to your organisation's current practices.
- Read NIST AI RMF 1.0 in full. Identify which of the four functions (Govern/Map/Measure/Manage) your organisation currently executes.
- Begin AIGP exam preparation (IAPP study materials).

**Days 31–60: Operational Fluency**
- Build your first AI system inventory: list every model in scope, its Annex III risk tier, and its current conformity status.
- Write or review one model card for an existing deployed system.
- Run a shadow AI discovery exercise: survey network logs for undocumented LLM API calls.

**Days 61–90: Credentials and Networking**
- Sit for the AIGP exam.
- Book the ISO/IEC 42001 Lead Auditor course.
- Identify the reporting line for the AI Ethics Board; schedule its first meeting if none exists.
- Deliver a board-level risk register covering all in-scope systems.

---

*Sources: All figures and role definitions trace to source articles at agileleadershipdayindia.org (May 2026). See repo README for full citation list.*
