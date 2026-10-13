# Research Data Package — Monetised Play and Indebted Borrowing: Online Gaming and the Rise of Online Lending (Pinjol) in Indonesia

This repository hosts the **full research-data package** for the systematic review:

> **Monetised Play and Indebted Borrowing: Online Gaming and the Rise of Online Lending (Pinjol) in Indonesia — A PRISMA 2020 Systematic Review Through the Maqāṣid al-Sharīʿah**

It is provided so that readers, reviewers, and other researchers can inspect and
reproduce the review's evidence base, in line with the publisher's research-data
policy.

> **Anonymity notice.** This repository accompanies a manuscript that is under
> **double-anonymized peer review**. Author names, affiliations, and contact
> details are deliberately withheld until the review process concludes. No
> author-identifying information is contained in this repository.

## Contents

| Path | Description |
|------|-------------|
| `data/included-studies.csv` | **Tidy extraction table** for the 36 studies extracted in full (S01–S36): category, identity, context, design, sample, exposure → outcome, shariah lens, maqāṣid dimension, key finding, quality rating. |
| `data/table2-international-empirical.csv` | Table 2 of the manuscript — 16 international empirical studies. |
| `data/table3-indonesian-empirical.csv` | Table 3 — 8 Indonesian empirical studies. |
| `data/table4-legal-normative-maqasid.csv` | Table 4 — 12 legal-normative / Islamic-economics studies (RQ3). |
| `data/eligibility-criteria.csv` | PICOC → PICOS eligibility criteria. |
| `data/quality-appraisal.csv` | MMAT 2018 / JBI quality appraisal summary (high / medium / low). |
| `data/certainty-of-evidence.csv` | GRADE-CERQual certainty appraisal by theme. |
| `data/prisma-flow.csv` | PRISMA 2020 record counts, stage by stage. |
| `search/search-strategies.md` | Concept blocks, information sources, retrieval date, and the **verbatim** database search strings. |
| `search/screening-log.md` | Screening and exclusion log with reasons (E1–E9) and the PRISMA narrative. |
| `protocol/inclusion-exclusion-codes.md` | Operational inclusion criteria and the full E1–E9 exclusion codes. |
| `protocol/codebook.md` | Data-extraction codebook (field list used for the evidence table). |
| `DATA-AVAILABILITY-STATEMENT.md` | The statement to cite in the manuscript / submission. |

## Data dictionary

`data/included-studies.csv` is the combined tidy view of Tables 2–4. Columns:

- `study_id` — review-specific identifier, S01–S36.
- `category` — *International empirical*, *Indonesian empirical*, or *Legal-normative (maqāṣid)*.
- `study` — short citation as used in the manuscript.
- `country` — study setting (blank for normative work).
- `design` — study design.
- `sample_or_population` — sample size or population descriptor.
- `exposure_outcome` — exposure → outcome pairing (empirical studies).
- `object` / `shariah_lens` / `maqasid_dimension` — normative fields (RQ3 studies).
- `key_finding` — principal finding / conclusion as extracted.
- `quality_rating` — High / Medium / Low (MMAT 2018 or JBI Text and Opinion).

`NR` = *not reported* in the extracted source. Values were not imputed.

## How the review was produced (summary)

A PRISMA 2020 systematic review with a pre-specified protocol, two-stage
screening (title–abstract, then full text), narrative synthesis following SWiM,
thematic analysis following Braun & Clarke, methodological appraisal with the
MMAT 2018 and the JBI Text and Opinion checklist, and certainty appraisal with
GRADE-CERQual. RQ3 was appraised against the maqāṣid al-Sharīʿah. Searches were
run in Google Scholar, Garuda, DOAJ, and PubMed, supplemented by hand-searching
and backward/forward citation chaining; retrieval date **12 October 2026**.
See `search/` for the verbatim strings and `protocol/` for the codebook.

## Licensing and reuse

Data files in this repository are released under the **Creative Commons
Attribution 4.0 International (CC BY 4.0)** licence — see `LICENSE`. Please
attribute the corresponding article (below) when reusing the data.

## How to cite

While the article is under anonymous review, please cite the review by its
title and this repository:

> Monetised Play and Indebted Borrowing: Online Gaming and the Rise of Online Lending (Pinjol) in Indonesia — A PRISMA 2020 Systematic Review Through the Maqāṣid al-Sharīʿah. Research data package. https://github.com/Zrio88/gaming-pinjol-maqasid-slr

A machine-readable citation file is provided in `CITATION.cff`.
