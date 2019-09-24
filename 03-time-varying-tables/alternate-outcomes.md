---
layout: default
title: Alternate Outcomes
parent: Time-varying Tables
nav_order: 9
---

# Alternate Outcomes

- **Filenames**: 
    -	Train: `train_alternate_outcome_timeseries_8hr.csv`
    -	Valid: `valid_alternate_outcome_timeseries_8hr.csv`
    -	Test: `test_alternate_outcome_timeseries_8hr.csv`

- **Table Purpose**: Alternate outcomes (i.e., sepsis, respiratory failure) for every encounter in 8 hour time windows.

- **Number of rows**: 
    - Train: 362,179
    -	Valid: 52,181
    -	Test: 20,538

- **Links to**: `ENCOUNTER_NUM`, `window`
 
## Table columns
 
| Column name |  Description |
| ----------- | ------------ |
| `ENCOUNTER_NUM` | Identifier used for each encounter. |
| `window` | 8-hour window since time of admission. |
| `sepsis_24` | 1 if patient experiences sepsis **in the next 24 hours**, 0 otherwise. |
| `sepsis_48` | 1 if patient experiences sepsis **in the next 48 hours**, 0 otherwise.  |
| `sepsis_72` | 1 if patient experiences sepsis **in the next 72 hours**, 0 otherwise.  |
| `resp_24` |  1 if patient experiences respiratory failure **in the next 24 hours**, 0 otherwise.  | 
| `resp_48` | 1 if patient experiences respiratory failure **in the next 48 hours**, 0 otherwise.   |
| `resp_72` | 1 if patient experiences respiratory failure **in the next 72 hours**, 0 otherwise.  | 
