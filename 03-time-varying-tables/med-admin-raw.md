---
layout: default
title: Medication Administrations (raw)
parent: Time-varying Tables
nav_order: 6
---

# Medication Administrations (raw)

- **Filenames**: 
    -	Train: `train_medication_admin.csv`
    -	Valid: `valid_medication_admin.csv`
    -	Test: `test_medication_admin.csv`


- **Table Purpose**: This table includes administrations of medications by medication class. The data includes the following variables: ENCOUNTER_NUM, variable, admin_time, and route. The variable `admin_time` is measured in hours since admission. The `route` variable describes the method of administration. The values from the variable column is the value used to name columns in the [pre-processed data](./med-admin-preproc). Medication admin times less than 0 are measurements that would have taken place before the patient was in the GIM ward (e.g. while in the emergency department).  
 
- **Number of rows**: 
    - Train: 1,666,594
    - Valid: 267,388
    - Test: 102,762

- **Links to**: `ENCOUNTER_NUM`
 
 
## Table columns
 
| Column name |  Description |
| ----------- | ------------ |
| `ENCOUNTER_NUM` | Identifier used for each encounter. |
| `variable` | Administered medication. Medications correspond to the ones used in the [pre-processed data](./med-admin-preproc). | 
| `admin_time` | Time medication was administered in hours since admisssion. | 
| `route` | Method of administration. Possible values are TBD. | 
