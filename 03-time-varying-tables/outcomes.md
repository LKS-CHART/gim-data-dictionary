---
layout: default
title: Outcomes
parent: Time-varying Tables
nav_order: 8
---

# Medication Administrations (pre-processed)

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
| `ENCOUNTER_NUM` | |
| `time_window` | |
| `OUTCOME_ALL` | |
| `OUTCOME_TYPE` | |
| `outcome_type_24` | |
| `outcome_type_48` | |
| `outcome_type_72` | |
| `outcome_all_24` | |
| `outcome_all_48` | |
| `outcome_all_72` | |
| `outcome_icu_24` | |
| `outcome_icu_48` | |
| `outcome_icu_72` | |
| `outcome_udeath_24` | |
| `outcome_udeath_48` | |
| `outcome_udeath_72` | |
| `outcome_pal_24` | |
| `outcome_pal_48` | |
| `outcome_pal_72`  | | 
