# Orphadata HPO-Disease Explorer

A single-file, offline-capable web UI for browsing the Orphanet HPO–disease
phenotype associations dataset. Search by disease name, ORPHA code, HPO ID,
or phenotype term, and view each disorder's full phenotype profile grouped
by frequency (Obligate, Very frequent, Frequent, Occasional, Very rare,
Excluded).

## Data source

The dataset is sourced from Orphadata:

https://sciences.orphadata.com/phenotypes/

Licensed under [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/legalcode).

## Usage

Open `index.html` directly in a browser, or visit the deployed GitHub Pages
site. No build step or server required — all data is embedded in the page.

## Updating the data

1. Download the latest `HPO_disease.xml` (or equivalent) from the Orphadata
   phenotypes page above.
2. Regenerate `index.html` with the parsing/build script.
3. Commit and push — GitHub Pages will redeploy automatically.
