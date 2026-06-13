# Audit Log

## Victoria Free Public Transport Experiment 2026

### Survey Data Cleaning and Quality Assurance Log

**Project:** Victoria Free Public Transport Experiment 2026
**Dataset:** Free Public Transport Survey (Analytic Dataset)
**Version:** 1.0
**Date:** 7 June 2026
**Prepared by:** Professor Hussein Dia, Swinburne University of Technology

---

## Purpose

This audit log documents data cleaning, validation and correction procedures applied to the survey dataset used for analysis and reporting.

The original raw survey export remains unchanged and archived separately. All modifications described below were applied only to the analytic dataset used for statistical, spatial and reporting purposes.

---

## Survey Eligibility Screening

The following exclusion criteria were applied:

* Respondent did not reside in Victoria.
* Respondent was under 18 years of age.
* Respondent did not provide initial consent.
* Respondent did not progress beyond the eligibility section.
* Respondent elected not to have their responses recorded at survey completion.

Following eligibility screening and respondent withdrawals:

* Raw records: 1,101
* Eligible respondents: 1,045
* Final analytic sample: 1,028

---

## Postcode Validation

A postcode validation review was undertaken prior to spatial analysis and postcode mapping.

Two records were identified where respondents had confirmed Victorian residency during eligibility screening but entered postcodes corresponding to New South Wales locations.

Review of the responses indicated that the entered values differed by a single leading digit from valid Victorian postcodes, suggesting likely data-entry errors.

The following corrections were applied to the analytic dataset only:

| Original Postcode | Corrected Postcode | Victorian Location      | Reason                                                                          |
| ----------------- | ------------------ | ----------------------- | ------------------------------------------------------------------------------- |
| 2146              | 3146               | Glen Iris, VIC          | Respondent confirmed Victorian residency. Likely single-digit data-entry error. |
| 2325              | 3325               | Derrinallum region, VIC | Respondent confirmed Victorian residency. Likely single-digit data-entry error. |

No other postcode corrections were required.

---

## Data Integrity

The original raw dataset has been retained without modification.

All corrections were applied only to the analytic dataset used for:

* Postcode mapping;
* Geographic analysis;
* Metropolitan versus regional classification;
* Statistical reporting.

The corrections affect 2 of 1,028 records (0.19% of the analytic sample) and are not expected to materially influence survey findings.

---

## Transparency Statement

All data cleaning decisions have been documented to ensure transparency, reproducibility and consistency with accepted research data management practices.

Future versions of this audit log may be updated if additional data validation activities are undertaken during subsequent phases of the project.

---

**End of Audit Log**
