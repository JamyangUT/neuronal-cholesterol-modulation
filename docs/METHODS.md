# Documented Methods

This page summarizes the July 2025 internship report. It documents the original study and is not a newly performed experiment.

## Study models and exposure

The study used Neuro2a, a mouse neuroblastoma cell line, and HN2, described in the report as a hybrid hippocampal/mouse neuroblastoma cell line. The experimental design compared increasing lovastatin concentrations at 24- and 48-hour exposure durations.

The report describes routine DMEM-based cell culture with serum and antibiotics. The complete experimental batch records, cell-line authentication information, and treatment-level sample manifest are not included in the repository.

## Assays and measurements

| Measurement | Assay | Readout recorded in the report |
| --- | --- | --- |
| Cell viability | MTT | Absorbance at 570 nm |
| Total protein | BCA with a BSA calibration curve | Absorbance at 562 nm |
| Cholesterol | Amplex Red Cholesterol Assay | Excitation 545 nm; emission 590 nm |

Cell preparations were sonicated for downstream assays. Cholesterol measurements were normalized to total protein content from the BCA assay. The report lists SkanIt RE for MSS 2.4.2 for protein-assay acquisition and SoftMax Pro 7.0.2 for fluorescence acquisition.

These tool and acquisition details are historical report information, not a complete protocol validated for reuse.

## Replicates and statistical analysis

The report specifies three technical replicates and four biological replicates for both cell models. Plots present mean ± standard error of the mean (SEM), with n=4 in the captions. Analysis and visualization used GraphPad Prism 10 and unpaired t-tests against control conditions.

The original raw readings, biological-replicate identifiers, Prism files, and complete statistical outputs are not included. Assumptions, effect sizes, confidence intervals, and handling of multiple concentration/time comparisons cannot be audited from the summary alone.

## Reproducibility status

This is an experimental research showcase. Reanalysis would require raw plate measurements, calibration curves, blank corrections, replicate grouping, treatment annotations, and original statistical settings. No synthetic dataset or reconstructed numerical results have been substituted for those files.
