# Thermoresponsive Hydrogel Data Curation and Workflow Engineering

## Overview

This independent portfolio project aims to build a reproducible Python workflow for organising, checking and analysing experimental data from **synthetic thermoresponsive hydrogels**.

Using an openly available [Zenodo dataset (record 21902628)](https://zenodo.org/records/21902628), the project will investigate how **sterilisation treatments** relate to hydrogel characterisation, rheological behaviour, sol–gel transitions and 3D-printing evidence.

The focus is **materials-data curation and workflow engineering**, rather than predictive modelling at this stage.

## Project objectives

1. **Source audit:** catalogue the original archives, files and data formats.
2. **Schema design:** organise polymer systems, experimental treatments, measurements and files into consistent tables.
3. **Data quality control:** identify missing values, duplicates, inconsistent labels, unclear units and other issues.
4. **Standardisation:** prepare comparable data while retaining original values, units and context.
5. **Provenance and linkage:** trace each processed record to its source, and distinguish verified sample links from unconfirmed associations.
6. **Image curation:** inventory available printing images, check quality and record imaging metadata where provided.
7. **Workflow automation:** develop Python notebooks and validation reports that can run reproducibly from a fresh session.
8. **Exploratory analysis:** visualise measured rheological behaviour and other scientifically justified comparisons.

## Data source

- **Zenodo:** https://zenodo.org/records/21902628
- **Scientific focus:** sterilisation effects on thermoresponsive hydrogels
- **Data types to audit:** rheology, sol–gel tests, polymer characterisation, 3D printing and biological evaluation

Availability of raw SEM/TEM micrographs **has not been established** and will be checked during the source audit.

## Planned workflow

`Source registry → File inventory → Experimental schema → Quality checks → Standardisation → Verified record linkage → Exploratory analysis → Reproducibility checks`

## Tools

Python · pandas · NumPy · Matplotlib · Jupyter Notebook · Git · GitHub

## Scientific data integrity

- Preserve raw files and original reported measurements.
- Document transformations, units, assumptions and uncertainties.
- Keep missing values visible; do not invent measurements or sample identities.
- Separate experimental observations from computed image features and derived metrics.
- Do not treat filename similarity as proof that records belong to the same physical sample.

## Project status

**Planning / source-acquisition stage.** Data processing, validation results and findings will be added as the project progresses.

