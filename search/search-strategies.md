# Information sources and search strategy

## Information sources

Searches were executed in:

- **Google Scholar** (first ten pages per string)
- **Garuda** (Garba Rujukan Digital)
- **DOAJ** (Directory of Open Access Journals)
- **PubMed**

supplemented by hand-searching of core journal tables of contents and by
backward/forward citation chaining.

**Documented retrieval date:** 12 October 2026.

**Transparency note.** Scopus and Web of Science were not subscribed at the
authors' institution and were substituted by the databases listed above. The
Google Scholar and Garuda interfaces do not export hit counts, so the hit column
is recorded as `NR`; the counts reported in `../data/prisma-flow.csv` refer to
records **exported for screening**. Verbatim strings per database are recorded
below.

## Concept blocks

The search strategy combined four concept blocks:

| Block | Terms (concept level) |
|-------|-----------------------|
| **GAME** | game, gaming, esport |
| **MONETISATION** | loot box, gacha, microtransaction, top-up |
| **DEBT** | online loan, pinjol, BNPL, debt, financial harm |
| **SHARIAH** | maqāṣid, riba, maysir, israf |

## Verbatim search strings

### 1. Main Scopus Advanced Search string

```text
TITLE-ABS-KEY(
("online game*" OR "video game*" OR "mobile game*" OR gaming OR esport*)
  AND
  ("loot box*" OR gacha OR microtransaction* OR "in-game purchase*"
    OR "in-game spending" OR "virtual item*" OR "in-app purchase*"
    OR "battle pass*" OR "top-up")
  AND
  ("online loan*" OR "online lending" OR "peer-to-peer lending" OR "P2P lending"
    OR "payday loan*" OR pinjol OR "buy now pay later" OR BNPL
    OR indebtedness OR "consumer debt" OR "financial distress"
    OR "financial harm*" OR "problem* gambling")
)
AND (LIMIT-TO (PUBYEAR, 2021) OR LIMIT-TO (PUBYEAR, 2022)
   OR LIMIT-TO (PUBYEAR, 2023) OR LIMIT-TO (PUBYEAR, 2024)
   OR LIMIT-TO (PUBYEAR, 2025) OR LIMIT-TO (PUBYEAR, 2026))
```

### 2. Shariah-anchored string (run in parallel for RQ3)

```text
TITLE-ABS-KEY(
(game* OR gaming OR "loot box*" OR gacha OR microtransaction*)
  AND
  (maqasid OR "maqāṣid" OR shari* OR "Islamic law" OR "Islamic economics"
    OR riba OR maysir OR gharar OR israf OR tabzir)
)
```

## Publication window

2015–2026, in Indonesian and English. A minority of foundational pre-2021 works
is retained by citation chaining, such that ≥80% of included scholarly sources
are dated ≥2021. Exclusion code **E9** governs sources outside the date window.
