---
layout: default
title: Outcomes
parent: Time-varying Tables
nav_order: 8
---

# Outcomes

- **Filenames**: 
    -	Train: TBD
    -	Valid: TBD
    -	Test: TBD


- **Table Purpose**: : Contains the outcome variables. OUTCOME_ALL is a binary variable indicating whether the outcome occurs or not for the encounter. OUTCOME_TYPE describes the type of outcome. The remaining outcome variables describe whether the outcome occurs within a given time frame. For example, outcome_all_24 will be a 1 if the encounter experiences the outcome within 24 hours and 0 otherwise. 

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
| `OUTCOME_TYPE` |  1 if **ICU Transfer**, 2 if **Death**, 3 if **Palliative entry**, 4 if **Palliative discharge**, 5 if **Discharged**  |
| `OUTCOME_ALL` |  1 if OUTCOME_TYPE is 1, 2, 3, or 4; 0 if OUTCOME_TYPE is 5  |
| `outcome_type_24` | |
| `outcome_type_48` | |
| `outcome_type_72` | |
| `outcome_all_24` | 1 if patient experiences any outcome (i.e., `OUTCOME_ANY == 1`) **in the next 24 hours**; 0 otherwise | 
| `outcome_all_48` | 1 if patient experiences any outcome (i.e., `OUTCOME_ANY == 1`) **in the next 48 hours**; 0 otherwise | 
| `outcome_all_72` | 1 if patient experiences any outcome (i.e., `OUTCOME_ANY == 1`) **in the next 72 hours**; 0 otherwise | 
| `outcome_icu_24` | 1 if patient transfers to the ICU **in the next 24 hours**; 0 otherwise |
| `outcome_icu_48` | 1 if patient transfers to the ICU **in the next 48 hours**; 0 otherwise |
| `outcome_icu_72` | 1 if patient transfers to the ICU **in the next 72 hours**; 0 otherwise |
| `outcome_udeath_24` | 1 if patient has an _unexpected death_ (i.e., `outcome_no_ccc == 2`) **in the next 24 hours**; 0 otherwise |
| `outcome_udeath_48` | 1 if patient has an _unexpected death_ (i.e., `outcome_no_ccc == 2`) **in the next 48 hours**; 0 otherwise |
| `outcome_udeath_72` | 1 if patient has an _unexpected death_ (i.e., `outcome_no_ccc == 2`) **in the next 72 hours**; 0 otherwise |
| `outcome_pal_24` | 1 if patient transfers to palliative care or has an _expected death_ (i.e., `outcome_no_ccc %in% 3:4`) **in the next 24 hours**; 0 otherwise |
| `outcome_pal_48` | 1 if patient transfers to palliative care or has an _expected death_ (i.e., `outcome_no_ccc %in% 3:4`) **in the next 48 hours**; 0 otherwise |
| `outcome_pal_72` | 1 if patient transfers to palliative care or has an _expected death_ (i.e., `outcome_no_ccc %in% 3:4`) **in the next 72 hours**; 0 otherwise |

