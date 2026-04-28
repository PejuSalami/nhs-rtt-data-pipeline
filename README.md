# NHS RTT Waiting Times Pipeline

## About This Project

This project evaluates the current (as at Feb 2026) referral to
treatment pathways across 514 NHS trusts in England, grouped by
specialty. This includes:

- **Incomplete Pathways** — patients on the waiting list, waiting to be seen
- **Incomplete Pathways with DTA** — elective patients waiting for a
  bed to become available so they can be admitted
- **Completed Pathways (Admitted)** — patients who waited and were
  admitted as inpatients
- **Completed Pathways (Non-Admitted)** — patients who waited and were
  treated in the outpatient clinic
- **New RTT Periods** — new pathways started in that period

## Why It Matters

Analysis of this dataset revealed that 583,856 patients were waiting
over the standard 18 weeks for Trauma and Orthopaedic treatment alone.
A patient waiting this long will possibly experience worsening pain,
deteriorating mobility, and may seek private treatment at personal cost.

## Tools Used

Python was used to read, clean, transform and analyse the data.

- **Pandas** — data extraction, cleaning and transformation of the
  raw NHS England dataset
- **Matplotlib** — visualisation of findings using a bar chart

## Key Findings

Analysis revealed that Trauma and Orthopaedics had a significantly
large number of patients waiting over 18 weeks. It was also notable
that Gynaecology had approximately 333,850 patients waiting beyond
the 18-week standard.

## What's Next

The next phase of this project is to load the cleaned dataset into
Snowflake to build a cloud data warehouse, enabling analysts to carry
out deeper analytics on the data.
