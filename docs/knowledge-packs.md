# Knowledge Packs — Stunspot's Guide to Legal Mastery

This repository separates public navigation from model-ingestion files.

- `docs/` contains guidance and GitHub Pages navigation.
- `knowledge-packs/by-report/` contains the 15 canonical individual source reports.
- `knowledge-packs/compiled-packs/` contains 4 grouped upload packs.
- `knowledge-packs/omnibus/` contains 1 whole-corpus bundle.

Do not look for source reports under `docs/`. This repo intentionally does **not** use `docs/reports/`.

---

## Recommended Default

Use the **compiled packs** unless you have a specific reason not to.

The compiled packs preserve the canon's volume architecture while reducing file count from 15 to 4. For most AI project knowledge systems, that is the best balance between retrieval coverage, upload manageability, and conceptual structure.

---

## Pack Selection Matrix

| Pack Type | Files | Path | Best Use | Trade-Off |
|---|---:|---|---|---|
| Source reports | 15 | `knowledge-packs/by-report/` | Precise retrieval, selective upload, citation, report-level editing, narrow task focus. | Higher file count; broader systems may need many files loaded. |
| Compiled packs | 4 | `knowledge-packs/compiled-packs/` | Recommended default for AI/RAG systems, ChatGPT Projects, Claude Projects, NotebookLM-style tools, and agent knowledge. | Less granular than source reports, but much easier to manage. |
| Omnibus | 1 | `knowledge-packs/omnibus/` | One-file import, full-corpus archive, local search, long-context systems with strong attention handling. | Very large single file; weaker systems may retrieve less precisely. |

---

## Source Reports

Use source reports when you need precision. They are the canonical individual units.

| Code | Report | Path |
|---|---|---|
| A | Legal Reality, Sovereign Power, and Jurisprudential Foundations | [`knowledge-packs/by-report/a-legal-reality-sovereign-power-and-jurisprudential-foundations.md`](https://github.com/Stunspot/stunspots-guide-to-legal-mastery/blob/main/knowledge-packs/by-report/a-legal-reality-sovereign-power-and-jurisprudential-foundations.md) |
| B | Sources of Law, Authority Hierarchies, and Doctrinal Architecture | [`knowledge-packs/by-report/b-sources-of-law-authority-hierarchies-and-doctrinal-architecture.md`](https://github.com/Stunspot/stunspots-guide-to-legal-mastery/blob/main/knowledge-packs/by-report/b-sources-of-law-authority-hierarchies-and-doctrinal-architecture.md) |
| C | Interpretation, Legal Reasoning, and Argument Architecture | [`knowledge-packs/by-report/c-interpretation-legal-reasoning-and-argument-architecture.md`](https://github.com/Stunspot/stunspots-guide-to-legal-mastery/blob/main/knowledge-packs/by-report/c-interpretation-legal-reasoning-and-argument-architecture.md) |
| D | Facts, Evidence, Proof, and Epistemic Burdens | [`knowledge-packs/by-report/d-facts-evidence-proof-and-epistemic-burdens.md`](https://github.com/Stunspot/stunspots-guide-to-legal-mastery/blob/main/knowledge-packs/by-report/d-facts-evidence-proof-and-epistemic-burdens.md) |
| E | Procedure, Remedies, and Forum Control | [`knowledge-packs/by-report/e-procedure-remedies-and-forum-control.md`](https://github.com/Stunspot/stunspots-guide-to-legal-mastery/blob/main/knowledge-packs/by-report/e-procedure-remedies-and-forum-control.md) |
| F | Litigation Strategy, Advocacy, and Adversarial Control | [`knowledge-packs/by-report/f-litigation-strategy-advocacy-and-adversarial-control.md`](https://github.com/Stunspot/stunspots-guide-to-legal-mastery/blob/main/knowledge-packs/by-report/f-litigation-strategy-advocacy-and-adversarial-control.md) |
| G | Client Counseling, Risk Governance, and Preventive Law | [`knowledge-packs/by-report/g-client-counseling-risk-governance-and-preventive-law.md`](https://github.com/Stunspot/stunspots-guide-to-legal-mastery/blob/main/knowledge-packs/by-report/g-client-counseling-risk-governance-and-preventive-law.md) |
| H | Transactional Architecture, Contract Design, and Private Ordering | [`knowledge-packs/by-report/h-transactional-architecture-contract-design-and-private-ordering.md`](https://github.com/Stunspot/stunspots-guide-to-legal-mastery/blob/main/knowledge-packs/by-report/h-transactional-architecture-contract-design-and-private-ordering.md) |
| I | Public Law, Rights Enforcement, and Administrative Governance | [`knowledge-packs/by-report/i-public-law-rights-enforcement-and-administrative-governance.md`](https://github.com/Stunspot/stunspots-guide-to-legal-mastery/blob/main/knowledge-packs/by-report/i-public-law-rights-enforcement-and-administrative-governance.md) |
| J | Private Law, Civil Obligation, and Liability Systems | [`knowledge-packs/by-report/j-private-law-civil-obligation-and-liability-systems.md`](https://github.com/Stunspot/stunspots-guide-to-legal-mastery/blob/main/knowledge-packs/by-report/j-private-law-civil-obligation-and-liability-systems.md) |
| K | Criminal Law, Punishment, and State Coercion | [`knowledge-packs/by-report/k-criminal-law-punishment-and-state-coercion.md`](https://github.com/Stunspot/stunspots-guide-to-legal-mastery/blob/main/knowledge-packs/by-report/k-criminal-law-punishment-and-state-coercion.md) |
| L | Professional Responsibility, Fiduciary Duty, and Legal Ethics | [`knowledge-packs/by-report/l-professional-responsibility-fiduciary-duty-and-legal-ethics.md`](https://github.com/Stunspot/stunspots-guide-to-legal-mastery/blob/main/knowledge-packs/by-report/l-professional-responsibility-fiduciary-duty-and-legal-ethics.md) |
| M | Power, Inequality, Access to Justice, and Institutional Legitimacy | [`knowledge-packs/by-report/m-power-inequality-access-to-justice-and-institutional-legitimacy.md`](https://github.com/Stunspot/stunspots-guide-to-legal-mastery/blob/main/knowledge-packs/by-report/m-power-inequality-access-to-justice-and-institutional-legitimacy.md) |
| N | Legal Failure Modes, Case Pathology, and Diagnostic Repair | [`knowledge-packs/by-report/n-legal-failure-modes-case-pathology-and-diagnostic-repair.md`](https://github.com/Stunspot/stunspots-guide-to-legal-mastery/blob/main/knowledge-packs/by-report/n-legal-failure-modes-case-pathology-and-diagnostic-repair.md) |
| O | Legal Research, Writing, Workflows, and Practice Artifacts | [`knowledge-packs/by-report/o-legal-research-writing-workflows-and-practice-artifacts.md`](https://github.com/Stunspot/stunspots-guide-to-legal-mastery/blob/main/knowledge-packs/by-report/o-legal-research-writing-workflows-and-practice-artifacts.md) |

---

## Compiled Packs

Use compiled packs for most model-ingestion workflows.

| Volume | Coverage | Path |
|---|---|---|
| Vol. 1 | A-D — Foundations of Law, Authority, and Judgment | [`knowledge-packs/compiled-packs/knowledge-vol-1-a-d-foundations-of-law-authority-and-judgment.md`](https://github.com/Stunspot/stunspots-guide-to-legal-mastery/blob/main/knowledge-packs/compiled-packs/knowledge-vol-1-a-d-foundations-of-law-authority-and-judgment.md) |
| Vol. 2 | E-K — Core Operating Domains of Legal Practice | [`knowledge-packs/compiled-packs/knowledge-vol-2-e-k-core-operating-domains-of-legal-practice.md`](https://github.com/Stunspot/stunspots-guide-to-legal-mastery/blob/main/knowledge-packs/compiled-packs/knowledge-vol-2-e-k-core-operating-domains-of-legal-practice.md) |
| Vol. 3 | L-M — Constraint, Specialization, and Legitimacy Layers | [`knowledge-packs/compiled-packs/knowledge-vol-3-l-m-constraint-specialization-and-legitimacy-layers.md`](https://github.com/Stunspot/stunspots-guide-to-legal-mastery/blob/main/knowledge-packs/compiled-packs/knowledge-vol-3-l-m-constraint-specialization-and-legitimacy-layers.md) |
| Vol. 4 | N-O — Diagnosis, Failure Modes, and Execution Systems | [`knowledge-packs/compiled-packs/knowledge-vol-4-n-o-diagnosis-failure-modes-and-execution-systems.md`](https://github.com/Stunspot/stunspots-guide-to-legal-mastery/blob/main/knowledge-packs/compiled-packs/knowledge-vol-4-n-o-diagnosis-failure-modes-and-execution-systems.md) |

Recommended loading order:

1. Vol. 1 first, because it defines the primitives.
2. Vol. 2 next, because it covers the major operating domains.
3. Vol. 3 next, because it constrains legal power through ethics and legitimacy.
4. Vol. 4 last, because it converts the canon into diagnosis and execution.

---

## Omnibus

| Pack | Path | Best Use |
|---|---|---|
| Legal Mastery — Omnibus | [`knowledge-packs/omnibus/knowledge-legal-mastery-omnibus.md`](https://github.com/Stunspot/stunspots-guide-to-legal-mastery/blob/main/knowledge-packs/omnibus/knowledge-legal-mastery-omnibus.md) | Full-canon import, local archive, large-context analysis, single-file storage. |

Use the omnibus when your system handles large single files well. If your system struggles with large documents, prefer compiled packs or source reports.

---

## Avoiding Duplicate Retrieval

The compiled packs and omnibus repeat source-report content. That is intentional for upload convenience, but it can create duplicate retrieval hits if you index every format together.

For RAG systems:

- Index **source reports only** when citation precision matters.
- Index **compiled packs only** when broad reasoning and file-count simplicity matter.
- Index **omnibus only** when your system is built for long single-file corpora.
- Do not index source reports, compiled packs, and omnibus together unless your retrieval pipeline tracks pack type and deduplicates repeated text.

---

## High-Stakes Legal Caution

These packs improve legal reasoning structure. They do not provide live law. Always verify jurisdiction, currentness, controlling authority, negative treatment, procedural posture, local rules, evidence, remedy, and ethical constraints before relying on any output.
