# Search Strategy Design and Logging

## 1. Build concept blocks

Start with the review question. Identify the core concepts and list synonyms for each. Example structure:

| Concept | Example terms |
|---|---|
| Virtual entity | "virtual idol" OR "virtual influencer" OR VTuber OR "virtual human" |
| Tourism context | tourism OR travel OR destination OR "travel planning" |
| Audience response | fandom OR engagement OR immersion OR intention |

These are illustrative terms, not a validated search string. Adapt them to the discipline, research question, and database indexing.

## 2. Boolean construction

- OR combines synonyms within a concept.
- AND combines distinct concepts.
- Quotation marks search phrases where supported.
- Truncation and wildcard syntax vary by database.
- Field restrictions (title, abstract, keywords) vary by platform.

A generic structure is:

```text
("term A" OR "synonym A" OR "synonym B")
AND
("term B" OR "synonym C")
AND
("term C" OR "synonym D")
```

Do not assume the same syntax works unchanged in Scopus, ScienceDirect, Web of Science, or other databases.

## 3. Database-specific adaptation

For every database, record:
- Database and platform/interface.
- Exact query as executed.
- Fields searched.
- Search date and time zone if relevant.
- Date range and language filters.
- Document-type or subject filters.
- Result count displayed.
- Number of records successfully exported.
- Export format and batch details.
- Any platform-imposed export limits or query changes.

A displayed result count and an exported-record count may differ. Record both when relevant.

## 4. Search log template

| Database | Exact query saved? | Search date | Filters | Results displayed | Records exported | Notes |
|---|---|---|---|---:|---:|---|
| Scopus | To confirm | To confirm | To confirm | — | — | — |
| ScienceDirect | To confirm | To confirm | To confirm | — | — | — |

Never populate unknown counts with estimates. Keep the original exports so that counts can be reconstructed.

## 5. Search refinement

Pilot the search by checking whether a set of known relevant studies is retrieved. If key papers are missing:
- Inspect terminology used in their titles, abstracts, and keywords.
- Add synonyms only when conceptually justified.
- Consider whether the search is too narrow or too broad.
- Document material changes to the query.

Avoid adding broad terms merely to increase the result count.

## 6. Search scope decisions

Date ranges, language limits, and document-type restrictions need a rationale. For example, an English-only search may introduce language bias. A recent time window may be appropriate for a fast-moving technology topic but can exclude foundational theory. State these trade-offs.

## 7. Reporting

Provide the complete strategy for each database in an appendix or supplement where possible. A short summary query in the methods section is not a substitute for the full executed strategy.
