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
| `img_porchest1v` | Imaging order - PORTABLE Chest|
| `img_ctthrabdplc` | Imaging order - CT Thorax Abdomen Pelvis with Contrast|
| `img_ctthrabdplc` | Imaging order - CT Thorax Abdomen Pelvis|
| `img_radchest2v` | Imaging order - XRAY Chest PA and LAT|
| `img_usabdlimited` | Imaging order - US Abdomen Limited|
| `img_ctthoraxpe` | Imaging order - CT Thorax Rule Out Pulmonary Embolus|
| `img_mriheado` | Imaging order - MRI Head|
| `img_radabdo2v` | Imaging order - XRAY Abdomen AP and LAT|
| `img_ctthoraxnoc` | Imaging order - CT Thorax|
| `img_usabdcomplete` | Imaging order - US Abdomen Complete|
| `img_ctperfusionstrok` | Imaging order - CT Perfusion Stroke|
| `img_ctabdoplcont` | Imaging order - CT Abdomen and Pelvis|
| `img_ctheadnocont` | Imaging order - CT Head no Contrast|
| `img_usdopvenextb` | Imaging order - US Doppler  Venous Lower Extremity Bilateral- R/O DVT|
| `img_ctabdonocont` | Imaging order - CT Abdomen|
| `img_radpelvisap` | Imaging order - XRAY Pelvis AP|
| `img_radabdo1v` | Imaging order - XRAY Abdomen|
| `img_ctabdoplwcon` | Imaging order - CT Abdomen Pelvis with Contrast|
| `img_usabdpelvis` | Imaging order - US Abdomen and  Pelvis|
| `img_cardioliteprrs` | Imaging order - Cardiolite and Persantine Scan with Rest|
| `img_radlumspin3v` | Imaging order - XRAY Lumbar Spine 3 Views|
| `img_porabdomen1v` | Imaging order - PORTABLE Abdomen|
| `img_int0180` | Imaging order - Interventional Radiological Procedure Request|
| `img_ctabdopelphas` | Imaging order - CT Abdomen Pelvis Triphasic Study|
| `img_mrispineo` | Imaging order - MRI Spine|
| `img_usdopportal` | Imaging order - US Doppler Portal Vein|
| `img_radchest1v` | Imaging order - XRAY Chest|
| `img_mriabdomeno` | Imaging order - MRI Abdomen|
| `img_ctheadwithcon` | Imaging order - CT Head with Contrast|
| `img_radhipunilt2v` | Imaging order - XRAY Hip Unilateral Left AP and LAT|
| `img_usdopabdoart` | Imaging order - US Doppler Abdomen Renal Arterial or Venous|
| `img_ctheadangio` | Imaging order - CT Head Angio (Circle of Willis)|
| `img_ctthoraxc` | Imaging order - CT Thorax with Contrast|
| `img_porabdomen2v` | Imaging order - PORTABLE XRAY Abdomen AP and LAT|
| `img_gastricdeglut` | Imaging order - XRAY Deglutition Study|
| `img_bonewholebody` | Imaging order - Bone Scan Whole Body|
| `img_radkneert2v` | Imaging order - XRAY Knee Right AP and LAT|
| `img_ctneckc` | Imaging order - CT Neck|
| `img_ctextremity` | Imaging order - CT Extremity|
| `img_spllumbarpunct` | Imaging order - XRAY Lumbar Puncture|
| `img_usfaceneck` | Imaging order - US Face and Neck|
| `img_ctneckcont` | Imaging order - CT Neck with Contrast|
| `img_ctheadwwocon` | Imaging order - CT Head with and without Contrast|
| `img_ctheadcarotids` | Imaging order - CT Head and Carotids|
| `img_ctrenalcolic` | Imaging order - CT Abdomen Rule Out Renal Colic|
| `img_radkneelt2v` | Imaging order - XRAY Knee Left AP and LAT|
| `img_radcervspin3v` | Imaging order - XRAY Cervical Spine AP, Lateral and Open Mouth Odontoid View|
| `img_usguidedbiopsy` | Imaging order - US Guided Biopsy|
| `img_radhipunirt2v` | Imaging order - XRAY Hip Unilateral Right AP and LAT|
| `img_ctpelvisc` | Imaging order - CT Pelvis|
| `img_radfootleft3v` | Imaging order - XRAY Foot Left 3 Views|
| `img_splercp` | Imaging order - XRAY ERCP|
| `img_usabdpelltd` | Imaging order - US Abdomen and Pelvis Limited|
| `img_uspeltrvagftri` | Imaging order - US Pelvis Transvaginal (First Trimester)|
| `img_radskulorbits` | Imaging order - XRAY Skull Orbits|
| `img_ctspinelcont` | Imaging order - CT Spine Lumbar without contrast|
| `img_ussofttissueuni` | Imaging order - US Soft Tissue Unilateral|
| `img_usextremityl` | Imaging order - US Extremity Left (Soft Tissue)|
| `img_radchest3v` | Imaging order - XRAY Chest 3 Views|
| `img_usextremityr` | Imaging order - US Extremity Right (Soft Tissue)|
| `img_hemodiacathins` | |
| `img_ang0090` | Imaging order - Angiography Procedure Request|
| `img_nva3` | Imaging order - NVA Abscess Drain Abdomen|
| `img_radfootrt3v` | Imaging order - XRAY Foot Right 3 Views|
| `img_radshoulderrt2v` | Imaging order - XRAY Shoulder Right 3 Views|
| `img_ctheadcspnc` | |
| `img_survmetastatic` | Imaging order - XRAY Metastatic Survey|
| `img_radhipbilat4v` | Imaging order - XRAY Hip Bilateral 4 Views|
| `img_cardiolitepr` | Imaging order - Cardiolite Persantine|
| `img_lungvq` | Imaging order - V/Q Scan|
| `img_radshoulderlt3v` | Imaging order - XRAY Shoulder Left 3 Views|
| `img_radanklert3v` | Imaging order - XRAY Ankle Right 3 Views|
| `img_radkneelt4v` | Imaging order - XRAY Knee Left 4 Views|
| `img_splngtubeins` | |
| `img_usdopliver` | Imaging order - US Doppler Liver Disease Screening|
| `img_radkneert4v` | Imaging order - XRAY Knee Right 4 Views|
| `img_radtibfibrt2v` | |
| `img_radanklelt3v` | Imaging order - XRAY Ankle Left 3 Views|
| `img_radthorspin2v` | Imaging order - XRAY Thoracic Spine 2 Views|
| `img_mrabrain` | Imaging order - MRA Brain|
| `img_ctenterography` | Imaging order - CT Enterography|
| `img_ctspinecervical` | Imaging order - CT Spine Cervical without contrast|
| `img_radkneebil4v` | Imaging order - XRAY Knee Bilateral 4 Views|
| `img_usdopvnexuni` | Imaging order - US Doppler Vein and Extremity Unilateral|
| `img_usdopvnexbi` | Imaging order - US Doppler  Vein and Extremity Bilateral|
| `img_mriextremityo` | Imaging order - MRI Extremity Unilateral|
| `img_mripelviso` | Imaging order - MRI Pelvis|
| `img_nva9` | Imaging order - NVA Abscess Drain Thorax|
| `img_mracarotids` | Imaging order - MRA Carotids|
| `img_ctthld` | Imaging order - CT Thoarax Low Dose|
| `img_ctaaa` | Imaging order - CT Abdominal Aneurysm|
| `img_intpcin` | Imaging order - PICC Insertion Double Lumen|
| `img_intpcsl` | Imaging order - PICC Insertion Single Lumen|
| `img_usabdltdpelvltd` | Imaging order - US Abdomen Limited and Pelvis Limited|
| `img_mri0733` | Imaging order - MRI0733|
| `img_mri0759` | Imaging order - MRI0759|
| `img_mri0701` | Imaging order - MRI0701|
| `img_mri0700` | Imaging order - MRI0700|
| `img_mri0824` | Imaging order - MRI0824|
| `img_mri0832` | Imaging order - MRI0832|
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


