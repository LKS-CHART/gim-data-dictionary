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
| `EVENT_TYPE_CD`| |
| `SERVICE_FROM_DK`||
| `FROM_SERVICE`||
| `FROM_SERVICE_CD`||
| `FROM_UNIT`||
| `FROM_LOCATION_SERVICE`||
| `SERVICE`||
| `SERVICE_CD` ||
| `UNIT`||
| `LOCATION_SERVICE`||
| `gim` ||
| `PALLIATIVE_ENTRY`||
| `PATIENT_DK`||
| `ATTENDING_PRACTITIONER_DK`||
| `ADT_DISCHARGE`||
| `CIHI_DISCHARGE`||
| `ICD10`| |
| `MRP_DIAGNOSIS`| |
| `age`| |
| `gender`| 1 for F, 0 otherwise |
| `PRACT_DK`| |
| `pre_gim_icu`||
| `post_gim_icu`| |
| `death`||
| `palliative_transfer`| |
| `OUTCOME_TYPE` | 1 if **ICU Transfer**, 2 if **Death**, 3 if **Palliative entry**, 4 if **Palliative discharge**, 5 if **Discharged** |
| `OUTCOME_ALL`| 1 if OUTCOME_TYPE is 1, 2, 3, or 4; 0 if OUTCOME_TYPE is 5 |
| `gim_to_outcome`||
| `ccc`||
| `outcome_no_ccc`| |
