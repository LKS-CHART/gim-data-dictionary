---
layout: default
title: Medication Administrations (pre-processed)
parent: Time-varying Tables
nav_order: 7
---

# Medication Administrations (pre-processed)

- **Filenames**: 
    -	Train: TBD
    -	Valid: TBD
    -	Test: TBD


- **Table Purpose**: Contains all medication administrations by AHFS class. The AHFS code can be extracted from the numeric values in the variable name. Refer to [this guide](http://www.mgh.org/Content/Uploads/UP%20Health%20System%20-%20Marquette/files/formulary/AHFS%20Pharmacologic-Therapeutic%20Classification%20(2012).pdf) to see what each AHFS code corresponds to. A value one 1 is used when a medication from the corresponding AHFS class was administered in the 8 hour window; 0 otherwise.

- **Number of rows**: 
    - Train: 16,976
    -	Valid: 2,405
    -	Test: 958

- **Links to**: `ENCOUNTER_NUM`, `time_window`
 
 
## Table columns
 
| Column name |  Description |
| ----------- | ------------ |
| `ENCOUNTER_NUM` | Identifier used for each encounter. |
| `time_window` | 8-hour window since time of admission. |
| `med_[]` | 1 if medication with corresponding AHFS code was administered; 0 otherwise. | 
| `med_NA` | | 

