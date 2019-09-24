---
layout: default
title: Encounters
parent: Static Tables
nav_order: 2
---

# Encounters

 - **Filename**: TBD
    -	Train: `train_encounters.csv`
    -	Valid: `valid_encounters.csv`
    -	Test: `test_encounters.csv`
    
 - **Table Purpose**: Master table containing all patient encounters (i.e., visits).
 
 - **Number of rows**:
    - Train: 16,976
    -	Valid: 2,405
    -	Test: 985
 
 - **Links to**: `ENCOUNTER_NUM`
 
## Tables columns
 
| Column name |  Description |
| ----------- | ------------ |
| `ENCOUNTER_NUM`| Identifier used for each encounter. |
| `FROM_SERVICE`| The service before transfer to GIM. |
| `FROM_SERVICE_CD`| The `FROM_SERVICE` code. |
| `FROM_UNIT`| The unit where the patient was transferred from. |
| `FROM_LOCATION_SERVICE`| The service associated with `FROM_UNIT` |
| `PALLIATIVE_ENTRY`| the date and time of entry to palliative care |
| `PATIENT_DK`| patient identifier |
| `ADT_DISCHARGE`| The discharge disposition in the EHR. |
| `ICD10`| ICD code of the Most Responsible Diagnosis |
| `MRP_DIAGNOSIS`| Most responsible diagnosis |
| `age`| Patient age at time of admission |
| `pre_gim_icu`| Flag for patient having been in the ICU prior to GIM entry |
| `post_gim_icu`| Flag for patient entering ICU after GIM |
| `death`| Flag for mortality |
| `palliative_transfer`| flag for palliative transfer |
| `OUTCOME_TYPE` | 1 if **ICU Transfer**, 2 if **Death**, 3 if **Palliative entry**, 4 if **Palliative discharge**, 5 if **Discharged** |
| `OUTCOME_ALL`| 1 if OUTCOME_TYPE is 1, 2, 3, or 4; 0 if OUTCOME_TYPE is 5 |
| `ccc`| Flag indicating if comfort care order was placed | 
| `outcome_no_ccc`| OUTCOME_TYPE except where (death == 1 and ccc == 1 and OUTCOME_TYPE == 2), then `outcome_no_ccc` = 3. Deaths that are "expected" (based on comfort care order) are grouped with palliative entry. |
| `gim_to_outcome`| Time from GIM entry to outcome in **days**. |
| `time_to_event` | Time from GIM entry to outcome in **hours**. |
