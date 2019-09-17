---
layout: default
title: Numeric Variables (pre-processed)
parent: Time-varying Tables
nav_order: 3
---

# Numeric Variables (pre-processed)

- **Filenames**: 
    -	Train: TBD
    -	Valid: TBD
    -	Test: TBD


- **Table Purpose**:  : Contains all numeric variables (e.g. vitals and labs) in 8 hour windows. For each numeric result we include a corresponding binary variable is used to indicate if that measure was taken in the 8 hour window and a counter variable used to describe how many 8 hour windows since the last measurement (e.g. vital_pulse, vital_pulse_measured, and vital_pulse_last_measured)
 
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


The variables below also have a corresponding **indicator variable** and a **time elapsed since** variable.

- The **indicator variable** name is suffixed with `_measured` and will be a 1 if the variable was measured in that time window or a 0 if the value was imputed.

- The **time elapsed since** name is suffixed with `_measured_last` and will indicate the number of time (in hours) elapsed since the previous available measure.

For example, for the variable `alcohol_sciwascore`, there are the corresponding variables `alcohol_sciwascore_measured` and `alcohol_sciwascore_measured_last`.

| Column name |  Description |
| ----------- | ------------ |
| `lab_hba1` | A1c. |
| `lab_abaso` | Abs.Basophils |
| `lab_aeos` | Abs.Eosinophils |
| `lab_igab` | Abs.IG |
| `lab_alymp` | Abs. Lymphocytes |
| `lab_metaa` | Abs.Metamyelocytes M.Diff |
| `lab_amono` | Abs.Monocytes |
| `lab_myela` | Abs.Myelocytes M.Diff |
| `lab_aneut` | Abs.Neutrophils |
| `lab_acet` | Acetaminophen Level |
| `lab_alb` | Albumin |
| `lab_alp` | ALP |
| `lab_alt` | ALT |
| `lab_amy` | Amylase |
| `lab_agap` | Anion Gap |
| `lab_ao` | Aortic Root |
| `lab_rptt` | aPTT |
| `lab_rptt` | APTT |
| `lab_ast` | AST |
| `lab_abe` | Base Excess Art. |
| `lab_vbe` | Base Excess Ven. |
| `lab_atco2` | Bicarbonate Arterial |
| `lab_vtco2` | Bicarbonate Venous |
| `lab_bc` | Bilirubin Direct |
| `lab_tbil` | Bilirubin Total |
| `skin_abradenscore` | Braden Score Total |
| `lab_caicr` | Ca, Ionized (pH 7.4) corr |
| `lab_cacra` | Ca, Ionized (pH 7.4) corr. |
| `lab_ca` | Calcium |
| `lab_ical` | Calcium Ionized Arterial |
| `lab_orcai` | Calcium, Ionized O.R. Arterial |
| `in_out_acatheter` | Catheter |
| `lab_cl` | Chloride |
| `lab_ucl` | Chloride Random |
| `lab_ck` | CK |
| `lab_crp` | C-Reactive Protein |
| `lab_cr` | Creatinine |
| `lab_esr1` | ESR |
| `lab_etoh` | Ethanol |
| `lab_fer` | Ferritin |
| `vital_sfio2` | FiO2 % |
| `lab_glob` | Globulin,calc. |
| `lab_orglu` | Glucose O.R. Arterial |
| `lab_glpoc` | Glucose POC (Lifescan) |
| `lab_glpoc` | Glucose POC (Lifescan/Abbott) |
| `lab_glpoc` | Glucose POC (Lifescan/Abbott/Nova) |
| `lab_glur` | Glucose Random |
| `lab_orglu` | Glucose, Syringe Arterial |
| `lab_hct` | HCT |
| `shift_assess_scvhrtrate` | Heart Rate |
| `lab_orhc` | Hematocrit O.R. Arterial calculation |
| `lab_hgb` | HGB |
| `lab_ahion` | H ion Arterial |
| `lab_vhion` | H ion Venous |
| `lab_rinr` | INR |
| `lab_cai` | Ionized Calcium |
| `lab_fe` | Iron Total |
| `in_out_siv23and13` | IV Dextrose 3.3%/NaCl 0.3% |
| `in_out_aivpb1` | IV Piggy Back #1 |
| `lab_ivsd` | IV Septum |
| `in_out_sivnormalsaline` | IV Sodium Chloride 0.9% (NaCL) |
| `lab_alact` | Lactate Arterial |
| `lab_vlact` | Lactate Venous |
| `lab_ld` | LD |
| `lab_la` | Left Atrium |
| `lab_lip` | Lipase |
| `lab_lvedd` | LV Diastole |
| `lab_lvesd` | LV Systole |
| `lab_mg` | Magnesium |
| `lab_mch` | MCH |
| `lab_mchc` | MCHC |
| `lab_mcv` | MCV |
| `lab_masa` | Meas. O2 Sat.Art |
| `lab_mvsa` | Meas. O2 Sat.Ven. |
| `lab_mpv` | MPV |
| `lab_nrbc` | nRBC |
| `lab_bnps` | NT-proBNP |
| `shift_assess_srpo2lmin` | O2 L/Min |
| `vital_so2saturation` | O2 Saturation (%) |
| `lab_uosm` | Osmolality |
| `lab_osm` | Osmolality Serum |
| `in_out_sotherintake` | Other Intake |
| `in_out_aothoutput` | Other Output |
| `vital_spainintrest` | Pain Intensity at Rest |
| `shift_assess_spnintstyrest1` | Pain Intensity at Rest (0-10) #1 |
| `shift_assess_spnintstyrest2` | Pain Intensity at Rest (0-10) #2 |
| `vital_spainintmove` | Pain Intensity with Movement |
| `shift_assess_spninstymov1` | Pain Intensity With Movement (0-10) #1 |
| `shift_assess_spninstymov2` | Pain Intensity With Movement (0-10) #2 |
| `lab_apco2` | pCO2 Arterial |
| `lab_vpco2` | pCO2 Venous |
| `lab_ph` | pH |
| `lab_aph` | pH Arterial |
| `lab_po4` | Phosphorus |
| `lab_vph` | pH Venous |
| `lab_plt` | PLT |
| `lab_apo2` | pO2 Arterial |
| `lab_vpo2` | pO2 Venous |
| `diabetic_spocglucresult` | POC Glucose Result (mmol/L) |
| `lab_pwd` | Posterior Wall |
| `lab_k` | Potassium |
| `lab_ork` | Potassium O.R. Arterial |
| `lab_uk` | Potassium Random |
| `lab_tpr` | Protein Total Serum |
| `lab_rpt` | PT |
| `vital_spulse` | Pulse |
| `lab_rbc` | RBC |
| `lab_rdw` | RDW |
| `shift_assess_srpfio2b` | Resp FiO2 Percent |
| `vital_srespirations` | Respirations |
| `lab_reta` | Retics |
| `lab_asa` | Salicylate Level |
| `lab_sat` | Saturation |
| `vital_sbpdiastolic` | sbp |
| `vital_sbpsystolic` | sbp |
| `lab_na` | Sodium |
| `lab_una` | Sodium |
| `lab_orna` | Sodium O.R. Arterial |
| `lab_spg` | Specific Gravity |
| `vital_stemperature` | Temperature |
| `vital_stemperature` | Temperature (c) |
| `lab_tibc` | TIBC |
| `in_out_atmsincontinent` | Times Incontinent |
| `lab_co2` | Total CO2 |
| `lab_tpr` | Total Protein Serum |
| `alcohol_sciwascore` | Total Score |
| `lab_tni` | Troponin I Serum |
| `lab_tsh` | TSH |
| `lab_urea` | Urea |
| `lab_uuro` | Urobilinogen |
| `lab_b12` | Vitamin B12 Level |
| `lab_iwbcr` | WBC |
