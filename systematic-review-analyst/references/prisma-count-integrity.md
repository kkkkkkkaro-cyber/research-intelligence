# PRISMA 2020 Count Integrity

## 1. Understand what each number represents

Keep these quantities separate:

- **Records identified:** records retrieved from information sources.
- **Records removed before screening:** for example, duplicates or records removed for other documented reasons.
- **Records screened:** records entering the screening stage.
- **Records excluded:** records excluded at the screening stage.
- **Reports sought for retrieval:** reports for which full text was sought.
- **Reports not retrieved:** full texts that could not be obtained.
- **Reports assessed for eligibility:** reports actually assessed against full-text criteria.
- **Reports excluded:** full-text reports excluded, with reasons.
- **Studies included:** unique studies included in the review.
- **Reports of included studies:** publications/reports describing those studies.

A study may have multiple reports. Do not automatically equate reports and studies.

## 2. Reconcile the arithmetic

A basic records-stage check:

```text
Records screened
= Records identified
- Records removed before screening
```

A basic screening-stage check:

```text
Records screened
= Records excluded
+ Reports sought for retrieval
```

A basic full-text-stage check:

```text
Reports sought for retrieval
= Reports not retrieved
+ Reports assessed for eligibility
```

A basic eligibility-stage check:

```text
Reports assessed for eligibility
= Reports excluded
+ Reports of included studies
```

These equations are reconciliation checks, not permission to infer missing values. Complex workflows, multiple sources, automation, and linked reports may require additional accounting.

## 3. Do not conflate common research counts

The following are not automatically PRISMA counts:
- Search result totals copied from a database interface.
- Number of files in a reference manager.
- Number of papers in a candidate bibliography.
- Number of papers prioritised for close reading.
- Number of studies cited in the final narrative.
- Number of papers retained after an informal relevance sort.

For example, "159 candidate papers" and "86 prioritised papers" can be reported as internal literature-management figures only if their definitions are clear. They cannot be inserted into a PRISMA flow as screened or included counts without a documented mapping to the actual workflow.

## 4. Missing or inconsistent counts

When counts are unavailable:
1. Locate original database exports.
2. Reconstruct the record inventory.
3. Deduplicate using a documented method.
4. Recover screening decisions from logs or annotations.
5. Reconcile stage totals.
6. If reconstruction is impossible, disclose the limitation and avoid presenting a falsely precise flow.

Never back-calculate a plausible number to make the diagram balance.

## 5. Search dates and database coverage

Report the last date each source was searched. If the date is unknown, use a transparent placeholder during drafting and resolve it before submission. Do not infer a date from file creation or modification metadata unless that metadata reliably documents the actual search.

## 6. PRISMA is reporting guidance

Use the current official PRISMA 2020 checklist and the appropriate flow diagram. Select the diagram that matches the review's sources and workflow. A completed checklist does not prove that the underlying search or screening was exhaustive or unbiased.
