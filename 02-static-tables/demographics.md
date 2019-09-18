---
layout: default
title: Demographic Variables
parent: Static Tables
nav_order: 4
---

# Baseline Values

- **Filenames**: 
    -	Train: TBD
    -	Valid: TBD
    -	Test: TBD


- **Table Purpose**:  Contains patient demographics. 
 
- **Number of rows**: 
    - Train: 16,976
    -	Valid: 2,405
    -	Test: 958

- **Links to**: `ENCOUNTER_NUM`
 
 
## Table columns
 
| Column name |  Description |
| ----------- | ------------ |
| `ENCOUNTER_NUM` | Identifier used for each encounter. | 
| `marital`| The possible values are `marital_divorced_widowed`, `marital_parterned`, `marital_single`, and `marital_unknown_other`.  |
| `province` | Possible values are Ontario or Other. |
| `language` | |
| `religion` | | 
| `age` | Age in years, at time of admission. |
| `gender` | 1 for F, 0 for M. |
