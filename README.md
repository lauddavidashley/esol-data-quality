# ESOL Data Quality

Investigating how data quality and molecular representation affect
machine-learning predictions of aqueous solubility, using the ESOL
(Delaney) dataset of 1,144 molecules.

## Status
Work in progress.

## So far
- Audited the dataset for duplicated SMILES: 16 duplicate groups
  (32 records), 12 with conflicting measured values.
- Classified duplicates by cause: naming variants, replicate
  measurements, different compounds sharing one SMILES (isomers),
  and conflicting values.

## Next
- Duplicate-aware train/test split
- Model comparison (Linear Regression, Random Forest, XGBoost)