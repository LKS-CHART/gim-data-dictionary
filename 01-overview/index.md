---
layout: default
title: Overview
nav_order: 1
has_children: false
permalink: /overview
has_toc: true
---

# Overview
{:toc}

## Format

Data are provided as CSV files.

## Split

Sets of three datasets (training, validation and test) were created from all inpatient encounters which gave rise to an admission to the general internal medicine (GIM) ward. 

- The **training set** is defined by all encounters where the admission time to GIM (GIM_START_TS) is strictly less than December 1, 2017 00:00:00. 
- The **validation set** consists of all encounters that occur after December 1, 2017 00:00:00 and strictly less than December 1, 2018 00:00:00. 
- Finally, the **test set** is defined as all encounters that occur after December 1, 2018 00:00:00.


## Data variables

The top occurring/most important variables were selected in consultation with a GIM staff physician. Variables included in the dataset include: 

-	Numeric values
    -	9 vital signs
    -	100 labs
    -	7 shift assessment variables 
    -	7 intake-outtake variables
    -	1 ulcer variable, 1 alcohol scale, 1 diabetes variable
-	Clinical orders (165)
    -	Imaging, Telemetry, Consults, cardio, diet, respiration, activities, codes, protocols, transfusions, wound care, neuro
-	Medication administrations  
    - Medications are grouped into medication AHFS classes.  


## Pre-processing

The dataset is provided in both a _preprocessed_ format and as _raw_ data tables. Pre-processing is described below.

- Time-varying data is binned into **8-hour windows** starting from the time the patient enters the GIM ward. The timeline ends when the patient experiences one of the outcomes.

- For numeric data (e.g., labs, vitals), we take the _average measurement_ within each window. We then add an _indicator_ for whether or not the variable was measured in that window. We also add a _time since last measured_ variable that keeps track of how long it has been since the variable was last recorded. Numeric data rae then trimmed and normalized between 0 and 1.

-	For orders, we created an indicator (1 vs 0) for whether or not the order was active during that window.

-	For medication administrations, we grouped medications into classes and then created an indicator for whether or not the medication class was administered in that time window.

- **Missing data**: For numeric data, we used _last observation carried forward_ with _mean imputation_ until a first observation is recorded. For orders, we impute a zero. 

## Outcomes

Outcome is defined as the first occurrence of any of the following events (i.e. if a patient transfers to the ICU and then dies, their outcome will be ICU transfer). The following patient outcomes will be available at the patient encounter level:
1.	ICU transfer - Patient transfers from GIM to ICU.
2.	Death - Patient dies while on GIM.
3.	Palliative entry - Patient gets transferred to palliative care.
4.	Palliative discharge - Patient gets discharge to a palliative care unit
5.	Discharged - Patient is discharged from hospital

We also capture the following outcomes in a separate table.
-	ICD diagnosis
-	Sepsis (sepsis defined based on SIRS criteria)
-	Respiratory failure (respiratory failure based on ventilator order)

## Tables

Where applicable, we provide both raw and pre-processed forms of the data.

### Static tables

| Table | Raw | Pre-processed |
| ----- | --- | ------------- |
| Encounters | [link](../02-static-tables/encounters) | --- |
| Baseline values | [link](../02-static-tables/baseline-values) | --- |
| Demographics | [link](../02-static-tables/demographics) | --- |

### Time-varying tables

| Table | Raw | Pre-processed |
| ----- | --- | ------------- |
| Numeric values | [link](../03-time-varying-tables/numeric-vars-raw) | [link](../03-time-varying-tables/numeric-vars-preproc) |
| Clinical orders | [link](../03-time-varying-tables/clinical-orders-raw) | [link](../03-time-varying-tables/clinical-orders-preproc) |
| Medication administrations | [link](../03-time-varying-tables/med-admin-raw) | [link](../03-time-varying-tables/med-admin-preproc) |
| Outcomes | [link](../03-time-varying-tables/outcomes) | -- |
| Alternate outcomes | [link](../03-time-varying-tables/alternate-outcomes) | -- |



