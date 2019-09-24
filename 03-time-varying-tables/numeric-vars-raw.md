---
layout: default
title: Numeric Variables (raw)
parent: Time-varying Tables
nav_order: 2
---

# Numeric Variables (raw)

- **Filenames**: 
    -	Train: `train_numeric_variables.csv`
    -	Valid: `valid_numeric_variables.csv`
    -	Test: `test_numeric_variables.csv`


- **Table Purpose**: This includes numeric results for laboratory measurements and vital signs. It has the following variables: ENCOUNTER_NUM, variable, result_time, numeric value. The numeric value is given in hours since admission. Vital signs are prefixed with the word "vital_", while labs are prefixed with the word "lab_". Each row represents one measurement per patient, per variable. The values from the variable column is the value used to name columns in the [pre-processed data](./numeric-vars-preproc). Result times less than 0 are measurements that would have taken place before the patient was in the GIM ward (e.g. while in the emergency department).
 
- **Number of rows**: 
    - Train: 5,030,004
    -	Valid: 685,621
    -	Test: 270,357

- **Links to**: `ENCOUNTER_NUM`
 
 
## Table columns
 
| Column name |  Description |
| ----------- | ------------ |
| `ENCOUNTER_NUM` | Identifier used for each encounter. |
| `variable` | Measure (vital sign, lab). Corresponds to the ones used in the [pre-processed data](./numeric-vars-preproc). | 
| `result_time` | Time measure was recorded in hourse since admission. |
| `numeric_value` | Value of vital sign or lab. | 
