# How to Use This Canon

*Stunspot's Guide to Legal Mastery* is optimized for model-facing use. It can be read by humans, but its main value is as structured legal-reasoning substrate for AI assistants, RAG systems, project knowledge bases, long-context workspaces, and legal-workflow design.

It should make a model more disciplined about law. It should not make a model pretend to be a lawyer.

---

## Core Use Principle

Use the canon to improve **reasoning structure**, **terminology**, **issue spotting**, **authority discipline**, **proof analysis**, **procedural awareness**, **diagnosis**, and **artifact design**.

Do **not** use it as a live legal authority database. Legal conclusions require current, jurisdiction-specific verification from primary sources, citators, local rules, procedural records, and qualified professional judgment.

A good model response using this canon should say things like:

- "This depends on jurisdiction and forum."
- "That source may be persuasive, but it is not controlling without a binding authority link."
- "The relevant question is not whether the reading is plausible, but whether this institution can legitimately adopt it."
- "That may be true historically, but the issue is whether it can be proven with admissible evidence at this procedural stage."
- "The desired right may exist, but the remedy, timing, standing, or enforcement route may fail."
- "This is a diagnostic defect, not a rhetorical problem."

---

## Recommended Upload Strategy

| Use Case | Recommended Format | Why |
|---|---|---|
| Most AI project knowledge systems | `knowledge-packs/compiled-packs/` | Four files preserve volume structure while keeping upload count manageable. |
| Narrow specialist task | `knowledge-packs/by-report/` | Upload only the reports relevant to the task; improves retrieval precision and citation anchors. |
| Long-context full-corpus analysis | `knowledge-packs/omnibus/` | One file contains the full canon; best for systems with strong long-context handling. |
| Repository browsing or human orientation | `docs/` plus `MANIFEST.md` | `docs/` explains the corpus; `MANIFEST.md` maps filenames to generated paths. |
| Corpus audit or ingestion pipeline | `manifest.json` | Machine-readable paths, sizes, counts, and source-to-output mappings. |

For most systems, start with the four compiled packs. Add individual source reports only when you need report-level retrieval precision or a smaller task-specific context.

---

## Human Reading Paths

### If you want the conceptual spine

Read A-D:

1. A. Legal Reality, Sovereign Power, and Jurisprudential Foundations
2. B. Sources of Law, Authority Hierarchies, and Doctrinal Architecture
3. C. Interpretation, Legal Reasoning, and Argument Architecture
4. D. Facts, Evidence, Proof, and Epistemic Burdens

This path teaches the canon's root discipline: law is not just text; authority is not just relevance; interpretation is not free semantic creativity; facts are not proof until the legal system admits and uses them.

### If you are focused on litigation

Read B-F, then N-O:

- B for authority ranking
- C for argument architecture
- D for proof burdens
- E for procedure, forum, remedies, and finality
- F for advocacy and adversarial strategy
- N for failure diagnosis
- O for research, writing, and work-product execution

### If you are focused on contracts or deal work

Read A-C, G-H, L, N-O:

- A for legal reality and private ordering boundaries
- B for mandatory authority and source hierarchy
- C for interpretive resilience
- G for counseling and preventive risk governance
- H for transactional architecture
- L for fiduciary and professional constraints
- N-O for failure diagnosis and artifact execution

### If you are building legal AI or RAG workflows

Read B-D and O first, then A, E, L, and N:

- B prevents source-authority flattening.
- C prevents plausible-but-unadoptable interpretation.
- D prevents fact/proof collapse.
- O gives research, citation, artifact, and workflow discipline.
- A supplies the jurisprudential operating system.
- E supplies procedural posture and forum control.
- L supplies ethical constraints, including AI-use risks.
- N supplies diagnostic failure modes.

---

## Model Instructions for AI/RAG Systems

When this canon is loaded into an AI system, use instructions like the following:

```text
Treat Stunspot's Guide to Legal Mastery as a legal-reasoning framework and terminology canon, not as a live-law oracle.

When answering legal questions:
1. Identify jurisdiction, forum, procedural posture, source type, currentness, and authority rank before treating any proposition as controlling.
2. Distinguish semantic relevance from binding authority.
3. Separate primary authority, delegated authority, procedural authority, persuasive authority, secondary authority, soft law, and private ordering instruments.
4. Distinguish allegation, evidence, admissibility, credibility, weight, inference, presumption, found fact, record fact, burden of production, burden of persuasion, standard of proof, and standard of review.
5. Preserve procedure, remedy, review, enforcement, finality, and ethics constraints.
6. Cite or name the canon report used when it supplies conceptual framing.
7. State what live-law verification is still required.
8. Do not invent citations, holdings, local rules, deadlines, statutory language, or jurisdiction-specific conclusions.
```

For high-stakes legal use, add a stricter instruction:

```text
If the question asks for a jurisdiction-specific legal conclusion, require live verification from current primary authority and citator treatment before giving a confident answer. If live verification is unavailable, provide a structured issue map, likely control points, and verification checklist instead of a definitive legal conclusion.
```

---

## RAG Configuration Notes

The corpus is Markdown-native and intentionally repetitive in its doctrinal phrasing. That repetition helps retrieval: key concepts recur across reports so a model can recover the right frame from multiple entry points.

Recommended ingestion practices:

- Preserve file paths as metadata.
- Preserve report letter codes A-O.
- Chunk by heading hierarchy when possible.
- Keep tables intact when your ingestion system supports table-aware chunking.
- Store `MANIFEST.md` or `manifest.json` alongside the corpus as a path map.
- Treat source reports as canonical units and compiled packs as convenience bundles.
- Prefer retrieving from source reports for citation-heavy tasks.
- Prefer compiled packs for broad reasoning tasks where file-count limits matter.
- Avoid mixing source reports and compiled packs in the same retrieval index unless you deduplicate or track provenance, because the compiled packs repeat source-report text.

Suggested metadata fields:

```json
{
  "canon": "Stunspot's Guide to Legal Mastery",
  "version": "1.0",
  "report_code": "A-O where applicable",
  "volume": "Vol. 1-4 where applicable",
  "pack_type": "source_report | compiled_pack | omnibus",
  "repo_path": "knowledge-packs/..."
}
```

---

## Legal Verification Checklist

Before relying on an output shaped by this canon, verify:

- governing jurisdiction
- deciding forum
- procedural posture
- source type and authority rank
- current version of statutes, regulations, rules, and guidance
- negative treatment of cases
- local rules and judge-specific orders
- factual record and admissibility
- burden and standard of proof
- standard of review
- remedy availability
- ethical constraints
- client objective and practical enforceability

If those facts are unknown, the correct output is usually a structured issue map or research plan, not a confident legal answer.

---

## Citation and Attribution

Use `CITATION.cff` for repository citation metadata. For internal notes, cite source reports by title and repository path, for example:

```text
Stunspot's Guide to Legal Mastery, Report C, "Interpretation, Legal Reasoning, and Argument Architecture," knowledge-packs/by-report/c-interpretation-legal-reasoning-and-argument-architecture.md
```

For model outputs, prefer concept-level citation to the relevant report and live-law citation to verified primary sources. The canon can supply the reasoning frame; current law must still be checked.
