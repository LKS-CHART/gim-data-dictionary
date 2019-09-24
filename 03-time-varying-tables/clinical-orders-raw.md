---
layout: default
title: Clinical Orders (raw)
parent: Time-varying Tables
nav_order: 4
---

# Clinical Orders (raw)

- **Filenames**: 
    -	Train: `train_clinical_orders.csv`
    -	Valid: `valid_clinical_orders.csv`
    -	Test: `test_clinical_orders.csv`


- **Table Purpose**: This includes the start and stop times for all clinical orders in the data. The data includes the following variables: ENCOUNTER_NUM, variable, order_start, order_end.  The variables order_start and order_end are provided in hours in admission to the GIM ward. The prefix to each value in the variable column describes the type of order (e.g: diet, telemetry, neuro, cardio, etc…). The values from the variable column is the value used to name columns in the [pre-processed data](./clinical-orders-preproc). Start and end times less than 0 are measurements that would have taken place before the patient was in the GIM ward (e.g. while in the emergency department). 
 
- **Number of rows**: 
    - Train: 107,983
    -	Valid: 15,394
    -	Test: 5,869

- **Links to**: `ENCOUNTER_NUM`
 
 
## Table columns
 
| Column name |  Description |
| ----------- | ------------ |
| `ENCOUNTER_NUM` | Identifier used for each encounter. |
| `variable` | Clinical order. Prefix describes order type. Orders correspond to the ones described [here](./clinical-orders-preproc). | 
| `order_start` | Start time of order (as hours since admission to GIM ward). |
| `order_end` | End time of order (as hours since admission to GIM ward). |
