# Data-extraction codebook

A standardised form guided extraction into the evidence table (the extracted
records are reproduced in `../data/`). Missing data are recorded as `NR`
(not reported) and were **not** imputed.

## Fields

| Field | Definition |
|-------|------------|
| `study_id` | Review-specific identifier (S01–S36). |
| `study` | Short citation of the source as used in the manuscript. |
| `country` | Country / setting of the study (blank for normative work). |
| `design` | Study design (e.g., cross-sectional, qualitative, meta-analysis, legal-normative). |
| `sample_or_population` | Sample size (n) or population descriptor. |
| `exposure_outcome` | Exposure → outcome pairing. |
| `object` | Object of shariah appraisal (normative studies). |
| `shariah_lens` | Shariah concepts engaged (e.g., maysir, gharar, riba, israf/tabzīr). |
| `maqasid_dimension` | Maqāṣid dimensions implicated (māl, dīn, nafs, ʿaql). |
| `key_finding` | Principal finding / conclusion as extracted. |
| `quality_rating` | Overall quality (High / Medium / Low). |

## Appraisal instruments

- **MMAT 2018** (Mixed Methods Appraisal Tool; Hong et al., 2018) for empirical
  studies.
- **JBI Text and Opinion checklist** for legal-normative scholarship.
- Reported at the overall level as **high**, **medium**, or **low**.

## Certainty of evidence

Confidence in each theme was graded with **GRADE-CERQual** (Lewin et al., 2018)
across methodological limitations, coherence, adequacy of data, and relevance,
yielding a rating of high / moderate / low / very low per finding; see
`../data/certainty-of-evidence.csv`.

## Synthesis

Synthesis was narrative, following **SWiM** (Campbell et al., 2020), and
thematic (Braun & Clarke, 2006). Because comparable effect sizes for pinjol
outcomes are scarce (predominantly `NR`), no quantitative meta-analysis was
performed.
