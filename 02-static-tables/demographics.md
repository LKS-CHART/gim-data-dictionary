---
layout: default
title: Demographic Variables
parent: Static Tables
nav_order: 4
---

# Baseline Values

- **Filenames**: 
    -	Train: `train_demographics.csv`
    -	Valid: `valid_demographics.csv`
    -	Test: `test_demographics.csv`


- **Table Purpose**:  Contains patient demographics. 
 
- **Number of rows**: 
    - Train: 16,976
    -	Valid: 2,405
    -	Test: 985

- **Links to**: `ENCOUNTER_NUM`
 
 
## Table columns
 
| Column name |  Description |
| ----------- | ------------ |
| `ENCOUNTER_NUM` | Identifier used for each encounter. | 
| `marital`| The possible values are `marital_divorced_widowed`, `marital_parterned`, `marital_single`, and `marital_unknown_other`.  |
| `province` | Possible values are Ontario or Other. |
| `language` | Primary language spoken by patient. |
| `religion` | Religion of patient. | 
| `age` | Age in years, at time of admission. |
| `gender` | 1 for F, 0 for M. |
