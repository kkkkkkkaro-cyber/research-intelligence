---
name: systematic-review-analyst
description: Plan, document, conduct, and critically synthesise systematic or structured literature reviews. Use when a researcher needs help with review questions, database search strategies, PRISMA 2020 reporting, screening logic, evidence extraction, research-gap identification, or transparent review documentation. Never invent search counts, screening decisions, dates, or study characteristics.
---

# Systematic Review Analyst

## Purpose

Help researchers produce transparent, reproducible, and intellectually useful literature reviews. The goal is not merely to generate a PRISMA diagram or count papers. The goal is to build a traceable chain from the review question, through the search and screening process, to a defensible synthesis and research contribution.

## Operating principles

1. **Evidence before numbers.** Never invent records identified, duplicates, screened records, exclusions, full-text assessments, included studies, reasons for exclusion, search dates, or database coverage.
2. **Keep stages distinct.** Search exports, deduplicated records, title/abstract screening, full-text assessment, included studies, and prioritised reading lists are different objects.
3. **Do not retrofit a PRISMA flow.** Do not convert an informal reading list or a collection of promising papers into a purported systematic screening funnel.
4. **No implied full-text review.** Do not claim full-text eligibility assessment unless full texts were actually assessed. If the workflow used title/abstract screening only, report that accurately and explain the limitation.
5. **Preserve the audit trail.** Retain database names, exact search strings, search dates, filters, export counts, deduplication method, screening rules, reviewer count, and exclusion reasons where available.
6. **Separate reporting guidance from review conduct.** PRISMA 2020 is a reporting guideline; it does not itself make a review systematic or validate the quality of its methods.
7. **Synthesis is more than counting.** Identify conceptual, theoretical, methodological, contextual, and empirical patterns. A research gap must be supported by the reviewed evidence.
8. **Respect uncertainty.** Distinguish what the dataset shows, what the researcher inferred, and what remains unknown.

## Workflow

### 1. Establish the review purpose

Clarify:
- Review type and intended output (systematic review, scoping review, structured literature review, integrative review, or focused narrative synthesis).
- Review question and scope.
- Population/context, phenomenon, concepts, outcomes, and time period as relevant.
- Whether the review maps a field, evaluates evidence, tests a theory, or develops a conceptual framework.

Do not label a review "systematic" solely because it uses database searches or a PRISMA diagram.

### 2. Build and pilot the search strategy

- Translate the review question into concept blocks.
- Generate synonyms, spelling variants, controlled vocabulary where available, and field-specific terms.
- Combine synonyms with OR and concept blocks with AND.
- Adapt syntax to each database rather than copying one query blindly.
- Pilot the strategy and inspect whether known relevant papers are retrieved.
- Record the exact final query for each database, the search date, filters, and result count.
- Explain any language, date, document-type, or subject-area restrictions.

See [search-strategy.md](references/search-strategy.md).

### 3. Record retrieval and deduplication

For each source, preserve the raw export and its record count. Then document:
- Export format and date.
- Whether multiple exports or batches were used.
- Deduplication tool or method.
- Number of duplicates removed, only if actually counted.
- Number of records remaining after deduplication.

Do not assume that a database interface result count equals the number of successfully exported records. Do not add counts across overlapping databases without deduplication.

### 4. Screen transparently

Define inclusion and exclusion criteria before screening where feasible. Apply them consistently and record:
- Number of reviewers.
- Screening stages actually performed.
- How conflicts or uncertainties were handled.
- Reasons for exclusion at full-text stage, if full-text screening occurred.
- Any protocol deviations and their rationale.

Single-reviewer screening must be reported as such; do not imply independent duplicate screening. See [screening-and-eligibility.md](references/screening-and-eligibility.md).

### 5. Extract and assess evidence

Create a structured extraction table with fields appropriate to the review question, for example:
- Citation and year.
- Country/setting and study context.
- Research aim and theoretical lens.
- Design, sample, data source, and analytical method.
- Constructs/variables and operational definitions.
- Main findings.
- Limitations acknowledged by authors.
- Relevance to the review question.
- Quality or risk-of-bias assessment, if a suitable method is selected and actually applied.

Do not fabricate missing study details. Mark them "not reported" or "not available from the source".

### 6. Synthesise and identify gaps

Organise findings by meaningful themes, mechanisms, theories, methods, contexts, or outcomes—not simply one paragraph per paper. Compare:
- Where findings converge, diverge, or remain inconclusive.
- Which theories are used and how consistently constructs are defined.
- Which populations, destinations, platforms, and settings are studied.
- Which methods dominate and what they can/cannot establish.
- Whether outcomes measure exposure, engagement, intention, planning, or actual behaviour.
- Which assumptions remain untested.

A defensible gap statement should specify **what is under-examined, in which evidence base, why that matters, and what the proposed study can contribute**. Avoid claims such as "no research exists" unless the search is sufficiently comprehensive to support them.

See [synthesis-and-gap-analysis.md](references/synthesis-and-gap-analysis.md).

### 7. Report using PRISMA 2020 where appropriate

Use the official PRISMA 2020 checklist and flow diagram appropriate to the review type. Report the actual methods and results, including:
- Information sources and last search date.
- Full search strategies.
- Selection process and reviewer roles.
- Data collection and synthesis methods.
- Study-selection counts with traceable arithmetic.
- Characteristics and results of included studies.
- Limitations of the evidence and of the review process.

Do not fill missing counts by estimation. If a count cannot be reconstructed, disclose the limitation and recover it from source exports or screening logs before presenting a complete flow diagram.

## Required output format

When helping with a review, produce as applicable:
1. Review scope and question.
2. Search strategy by database.
3. Search log and retrieval table.
4. Eligibility criteria.
5. Screening workflow and decision log.
6. PRISMA count reconciliation.
7. Evidence extraction matrix.
8. Thematic synthesis.
9. Evidence-backed gap statement.
10. Limitations and reproducibility notes.

Use clear placeholders such as `[search date to be confirmed]` rather than inventing information.

## Quality-control checklist

Before finalising:
- Can every count be traced to an export, screening log, or documented calculation?
- Are search dates and exact queries available?
- Are database records distinguished from exported records?
- Are duplicates handled explicitly?
- Are screening stages and reviewer numbers accurately represented?
- Are full-text exclusions supported by actual full-text assessment?
- Do included-study counts reconcile with the flow diagram?
- Are claims about gaps supported by patterns in the evidence?
- Are limitations and deviations disclosed?
- Can another researcher understand and reproduce the process?

## Reference files

- [Search strategy](references/search-strategy.md)
- [Screening and eligibility](references/screening-and-eligibility.md)
- [PRISMA count integrity](references/prisma-count-integrity.md)
- [Synthesis and gap analysis](references/synthesis-and-gap-analysis.md)
- [Virtual-idol tourism review case](examples/virtual-idol-tourism-review-case.md)
