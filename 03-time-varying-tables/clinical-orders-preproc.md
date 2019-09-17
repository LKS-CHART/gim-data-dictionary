---
layout: default
title: Clinical Orders (pre-processed)
parent: Time-varying Tables
nav_order: 5
---

# Clinical Orders (pre-processed)

- **Filenames**: 
    -	Train: TBD
    -	Valid: TBD
    -	Test: TBD


- **Table Purpose**: Contains all clinical orders along with the time the order was started and the time the order was completed. The format of the variable names describes the type of order, followed by an underscore, followed by the order name. For example, diet_regular is a diet order for regular food.  

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
| `img_porchest1v` | | 
| `img_ctthrabdplc` | | 
| `img_radchest2v` | | 
| `img_usabdlimited` | | 
| `img_ctthoraxpe` | | 
| `img_mriheado` | | 
| `img_radabdo2v` | | 
| `img_ctthoraxnoc` | | 
| `img_usabdcomplete` | | 
| `img_ctperfusionstrok` | | 
| `img_ctabdoplcont` | | 
| `img_ctheadnocont` | | 
| `img_usdopvenextb` | | 
| `img_ctabdonocont` | | 
| `img_radpelvisap` | | 
| `img_radabdo1v` | | 
| `img_ctabdoplwcon` | | 
| `img_usabdpelvis` | | 
| `img_cardioliteprrs` | | 
| `img_radlumspin3v` | | 
| `img_porabdomen1v` | | 
| `img_int0180` | | 
| `img_ctabdopelphas` | | 
| `img_mrispineo` | | 
| `img_usdopportal` | | 
| `img_radchest1v` | | 
| `img_mriabdomeno` | | 
| `img_ctheadwithcon` | | 
| `img_radhipunilt2v` | | 
| `img_usdopabdoart` | | 
| `img_ctheadangio` | | 
| `img_ctthoraxc` | | 
| `img_porabdomen2v` | | 
| `img_gastricdeglut` | | 
| `img_bonewholebody` | | 
| `img_radkneert2v` | | 
| `img_ctneckc` | | 
| `img_ctextremity` | | 
| `img_spllumbarpunct` | | 
| `img_usfaceneck` | | 
| `img_ctneckcont` | | 
| `img_ctheadwwocon` | | 
| `img_ctheadcarotids` | | 
| `img_ctrenalcolic` | | 
| `img_radkneelt2v` | | 
| `img_radcervspin3v` | | 
| `img_usguidedbiopsy` | | 
| `img_radhipunirt2v` | | 
| `img_ctpelvisc` | | 
| `img_radfootleft3v` | | 
| `img_splercp` | | 
| `img_usabdpelltd` | | 
| `img_uspeltrvagftri` | | 
| `img_radskulorbits` | | 
| `img_ctspinelcont` | | 
| `img_ussofttissueuni` | | 
| `img_usextremityl` | | 
| `img_radchest3v` | | 
| `img_usextremityr` | | 
| `img_hemodiacathins` | | 
| `img_ang0090` | | 
| `img_nva3` | | 
| `img_radfootrt3v` | | 
| `img_radshoulderrt2v` | | 
| `img_ctheadcspnc` | | 
| `img_survmetastatic` | | 
| `img_radhipbilat4v` | | 
| `img_cardiolitepr` | | 
| `img_lungvq` | | 
| `img_radshoulderlt3v` | | 
| `img_radanklert3v` | | 
| `img_radkneelt4v` | | 
| `img_splngtubeins` | | 
| `img_usdopliver` | | 
| `img_radkneert4v` | | 
| `img_radtibfibrt2v` | | 
| `img_radanklelt3v` | | 
| `img_radthorspin2v` | | 
| `img_mrabrain` | | 
| `img_ctenterography` | | 
| `img_ctspinecervical` | | 
| `img_radkneebil4v` | | 
| `img_usdopvnexuni` | | 
| `img_usdopvnexbi` | | 
| `img_mriextremityo` | | 
| `img_mripelviso` | | 
| `img_nva9` | | 
| `img_mracarotids` | | 
| `img_ctthld` | | 
| `img_ctaaa` | | 
| `img_intpcin` | | 
| `img_intpcsl` | | 
| `img_usabdltdpelvltd` | | 
| `img_mri0733` | | 
| `img_mri0759` | | 
| `img_mri0701` | | 
| `img_mri0700` | | 
| `img_mri0824` | | 
| `img_mri0832` | | 
| `diet_tube_feed` | | 
| `diet_regular_other` | | 
| `diet_oral` | | 
| `diet_renal` | | 
| `diet_diabetic` | | 
| `diet_cardiac` | | 
| `diet_npo` | | 
| `diet_regular` | | 
| `diet_clear_fluids` | | 
| `diet_nutrition_supplement` | | 
| `telemetry` | | 
| `consult_physio` | | 
| `consult_general` | | 
| `consult_stroke` | | 
| `consult_social` | | 
| `consult_speech` | | 
| `consult_dietitian` | | 
| `consult_chaplain` | | 
| `consult_physiotherapist` | | 
| `consult_acute` | | 
| `consult_gastroenterology` | | 
| `consult_respiratory` | | 
| `consult_occupational` | | 
| `consult_psychiatry` | | 
| `consult_wound` | | 
| `consult_physiotherapy` | | 
| `consult_geriatric` | | 
| `consult_pharmacist` | | 
| `consult_chiropodist` | | 
| `consult_addiction` | | 
| `consult_research` | | 
| `cardio_ecg` | | 
| `cardio_vascularlab` | | 
| `cardio_echo` | | 
| `cardio_holter` | | 
| `cardio_peripheralvascular` | | 
| `resp_oxygen` | | 
| `resp_pulmonaryfunctiontest` | | 
| `resp_bipapcpap` | | 
| `resp_respiratoryintervention` | | 
| `resp_chesttube` | | 
| `resp_ventilator` | | 
| `act_sitter` | | 
| `act_constantcare` | | 
| `act_opcophysrestr` | | 
| `act_restrictions` | | 
| `code_gmc` | | 
| `code_ccc` | | 
| `code_full` | | 
| `code_als` | | 
| `opcociwacare` | | 
| `opcohephiaptt` | | 
| `opcoivinslow` | | 
| `opcoivinshi` | | 
| `opcochfdiuret` | | 
| `trans_infusefrozenplasma` | | 
| `trans_transfusepackedredbloodcells` | | 
| `trans_transfuseplatelets` | | 
| `trans_infusealbumin25` | | 
| `trans_transfusionother` | | 
| `trans_infuseivimmuneglobulin` | | 
| `trans_prothrombincomplexconcentratepcc` | | 
| `wound_dressingswoundcare` | | 
| `wound_skincare` | | 
| `neuro_eeg` | | 
| `neuro_emg` | |

