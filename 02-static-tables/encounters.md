---
layout: default
title: Encounters
parent: Static Tables
nav_order: 2
---

# Encounters

 - **Filename**: TBD

 - **Table Purpose**: Master table containing all patient encounters (i.e., visits).
 
 - **Number of rows**: 20,366
 
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
| `PATIENT_DK`| the date and time of entry to palliative care|
| `ADT_DISCHARGE`| The discharge disposition in the EHR. |
| `ICD10`| ICD code of the Most Responsible Diagnosis |
| `MRP_DIAGNOSIS`| Most responsible diagnosis |
| `age`| Patient age |
| `pre_gim_icu`| Flag for patient having been in the ICU prior to GIM entry |
| `post_gim_icu`| Flag for patient entering ICU |
| `death`| Flag for mortality |
| `palliative_transfer`| flag for palliative transfer |
| `OUTCOME_TYPE` | 1 if **ICU Transfer**, 2 if **Death**, 3 if **Palliative entry**, 4 if **Palliative discharge**, 5 if **Discharged** |
| `OUTCOME_ALL`| 1 if OUTCOME_TYPE is 1, 2, 3, or 4; 0 if OUTCOME_TYPE is 5 |
| `gim_to_outcome`| time from GIM entry to outcome |
| `ccc`| Flag indicating if comfort care order was placed | 
| `outcome_no_ccc`| OUTCOME_TYPE except where (death == 1 and ccc == 1 and OUTCOME_TYPE == 2), then `outcome_no_ccc` = 3. Deaths that are "expected" (based on comfort care order) are grouped with palliative entry. |
