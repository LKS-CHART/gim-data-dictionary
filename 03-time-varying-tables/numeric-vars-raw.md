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
| `ENCOUNTER_NUM` | |
| `time_window` | |


The variables below also have a corresponding **indicator variable** and a **time elapsed since** variable.

- The **indicator variable** name is suffixed with `_measured` and will be a 1 if the variable was measured in that time window or a 0 if the value was imputed.

- The **time elapsed since** name is suffixed with `_measured_last` and will indicate the number of time (in hours) elapsed since the previous available measure.

For example, for the variable `alcohol_sciwascore`, there are the corresponding variables `alcohol_sciwascore_measured` and `alcohol_sciwascore_measured_last`.

| Column name |  Description |
| ----------- | ------------ |
| `alcohol_sciwascore` | |
| `diabetic_spocglucresult` | |
| `in_out_acatheter` | |
| `in_out_aivpb1` | |
| `in_out_aothoutput` | |
| `in_out_atmsincontinent` | |
| `in_out_siv23and13` | |
| `in_out_sivnormalsaline` | |
| `in_out_sotherintake` | |
| `lab_abaso` | |
| `lab_abe` | |
| `lab_acet` | |
| `lab_aeos` | |
| `lab_agap` | |
| `lab_ahion` | |
| `lab_alact` | |
| `lab_alb` | |
| `lab_alp` | |
| `lab_alt` | |
| `lab_alymp` | |
| `lab_amono` | |
| `lab_amy` | |
| `lab_aneut` | |
| `lab_ao` | |
| `lab_apco2` | |
| `lab_aph` | |
| `lab_apo2` | |
| `lab_asa` | |
| `lab_ast` | |
| `lab_atco2` | |
| `lab_b12` | |
| `lab_bc` | |
| `lab_bnps` | |
| `lab_ca` | |
| `lab_cacra` | |
| `lab_cai` | |
| `lab_caicr` | |
| `lab_ck` | |
| `lab_cl` | |
| `lab_co2` | |
| `lab_cr` | |
| `lab_crp` | |
| `lab_esr1` | |
| `lab_etoh` | |
| `lab_fe` | |
| `lab_fer` | |
| `lab_glob` | |
| `lab_glpoc` | |
| `lab_glur` | |
| `lab_hba1` | |
| `lab_hct` | |
| `lab_hgb` | |
| `lab_ical` | |
| `lab_igab` | |
| `lab_ivsd` | |
| `lab_iwbcr` | |
| `lab_k` | |
| `lab_la` | |
| `lab_ld` | |
| `lab_lip` | |
| `lab_lvedd` | |
| `lab_lvesd` | |
| `lab_masa` | |
| `lab_mch` | |
| `lab_mchc` | |
| `lab_mcv` | |
| `lab_metaa` | |
| `lab_mg` | |
| `lab_mpv` | |
| `lab_mvsa` | |
| `lab_myela` | |
| `lab_na` | |
| `lab_orcai` | |
| `lab_orglu` | |
| `lab_orhc` | |
| `lab_ork` | |
| `lab_orna` | |
| `lab_osm` | |
| `lab_ph` | |
| `lab_plt` | |
| `lab_po4` | |
| `lab_pwd` | |
| `lab_rbc` | |
| `lab_rdw` | |
| `lab_reta` | |
| `lab_rinr` | |
| `lab_rpt` | |
| `lab_rptt` | |
| `lab_sat` | |
| `lab_spg` | |
| `lab_tbil` | |
| `lab_tibc` | |
| `lab_tni` | |
| `lab_tpr` | |
| `lab_tsh` | |
| `lab_ucl` | |
| `lab_uk` | |
| `lab_una` | |
| `lab_uosm` | |
| `lab_urea` | |
| `lab_uuro` | |
| `lab_vbe` | |
| `lab_vhion` | |
| `lab_vlact` | |
| `lab_vpco2` | |
| `lab_vph` | |
| `lab_vpo2` | |
| `lab_vtco2` | |
| `shift_assess_scvhrtrate` | |
| `shift_assess_spninstymov1` | |
| `shift_assess_spninstymov2` | |
| `shift_assess_spnintstyrest1` | |
| `shift_assess_spnintstyrest2` | |
| `shift_assess_srpfio2b` | |
| `shift_assess_srpo2lmin` | |
| `skin_abradenscore` | |
| `vital_sbpdiastolic` | |
| `vital_sbpsystolic` | |
| `vital_sfio2` | |
| `vital_so2saturation` | |
| `vital_spainintmove` | |
| `vital_spainintrest` | |
| `vital_spulse` | |
| `vital_srespirations` | |
| `vital_stemperature` | |
