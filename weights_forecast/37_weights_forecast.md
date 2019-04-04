| index | variable | beta coef | unadjusted OR | TP | TN | FP | FN | AUC Single | 
| --- | --- | --- | --- | --- | --- | --- | --- | --- | 
| 0 | demographics_GENDER_Female |-6.235| 0.000 [0.000, 0.001]| 3.0 | 544779.0 | 1068620.0 | 3909.0 | 0.169| 
| 1 | demographics_age[between_70_and_80] |2.488| 3.493 [3.267, 3.735]| 1281.0 | 1416037.0 | 197362.0 | 2631.0 | 0.603| 
| 2 | demographics_age[between_80_and_90] |2.429| 3.075 [2.809, 3.367]| 549.0 | 1532071.0 | 81328.0 | 3363.0 | 0.545| 
| 3 | demographics_age[between_60_and_70] |2.194| 2.244 [2.103, 2.396]| 1414.0 | 1288454.0 | 324945.0 | 2498.0 | 0.580| 
| 4 | demographics_age[between_90_and_100] |1.687| 1.901 [1.442, 2.508]| 51.0 | 1602268.0 | 11131.0 | 3861.0 | 0.503| 
| 5 | demographics_age[between_20_and_30] |-1.480| 0.000 [0.000, 0.000]| 0.0 | 1489268.0 | 124131.0 | 3912.0 | 0.462| 
| 6 | demographics_age[between_30_and_40] |-1.243| 0.013 [0.006, 0.028]| 6.0 | 1439377.0 | 174022.0 | 3906.0 | 0.447| 
| 7 | Diagnosis:Elevated PSA sid:396152005 396151003[count>0] |1.150| 16.162 [14.518, 17.992]| 382.0 | 1602668.0 | 10731.0 | 3530.0 | 0.545| 
| 8 | demographics_age[between_50_and_60] |0.917| 0.607 [0.554, 0.666]| 529.0 | 1283033.0 | 330366.0 | 3383.0 | 0.465| 
| 9 | demographics_age[between_1_and_10] |-0.811| 0.000 [0.000, 0.000]| 0.0 | 1566413.0 | 46986.0 | 3912.0 | 0.485| 
| 10 | demographics_age[between_10_and_20] |-0.686| 0.013 [0.003, 0.051]| 2.0 | 1551089.0 | 62310.0 | 3910.0 | 0.481| 
| 11 | demographics_RACE_African American (Black) |0.549| 1.511 [1.376, 1.658]| 509.0 | 1468039.0 | 145360.0 | 3403.0 | 0.520| 
| 12 | demographics_RACE_Unknown |-0.506| 0.512 [0.442, 0.593]| 186.0 | 1470096.0 | 143303.0 | 3726.0 | 0.479| 
| 13 | Diagnosis:Clinical finding sid:404684003 250171008[count>2] |-0.462| 0.746 [0.693, 0.803]| 2985.0 | 303471.0 | 1309928.0 | 927.0 | 0.476| 
| 14 | demographics_age[between_40_and_50] |-0.282| 0.115 [0.092, 0.143]| 80.0 | 1365425.0 | 247974.0 | 3832.0 | 0.433| 
| 15 | Diagnosis:Assessment sid:129265001 185469009[count>2] |-0.252| 0.383 [0.336, 0.436]| 241.0 | 1377280.0 | 236119.0 | 3671.0 | 0.458| 
| 16 | Diagnosis:Postprocedural state finding (finding) sid:128926000 10593005[count>0] |-0.248| 1.045 [0.921, 1.187]| 257.0 | 1511724.0 | 101675.0 | 3655.0 | 0.501| 
| 17 | Diagnosis:Disorder of trunk sid:128121009 280133005[count>2] |0.238| 1.523 [1.429, 1.623]| 1658.0 | 1087924.0 | 525475.0 | 2254.0 | 0.549| 
| 18 | ProcedureCPT:Therapeutic exercises 97110[count>0] |0.233| 1.316 [1.090, 1.590]| 111.0 | 1578382.0 | 35017.0 | 3801.0 | 0.503| 
| 19 | ProcedureCPT:automated, without microscopy 81003[count>0] |0.217| 1.687 [1.416, 2.010]| 130.0 | 1581176.0 | 32223.0 | 3782.0 | 0.507| 
| 20 | Lab:Platelet mean volume [Entitic volume] in Blood 28542-9[normedValue_sd_between_-0.5,0.5] |-0.214| 0.954 [0.820, 1.110]| 176.0 | 1537497.0 | 75902.0 | 3736.0 | 0.499| 
| 21 | Diagnosis:Overweight (finding) sid:238131007 275947003[count>0] |-0.210| 0.731 [0.627, 0.852]| 172.0 | 1517921.0 | 95478.0 | 3740.0 | 0.492| 
| 22 | Lab:Urobilinogen [Units/volume] in Urine by Test strip 19161-9[normedValue_sd_between_-0.5,0.5] |0.187| 1.360 [1.195, 1.547]| 246.0 | 1537514.0 | 75885.0 | 3666.0 | 0.508| 
| 23 | Diagnosis:Disease (disorder) sid:64572001 173300003[count>0] |-0.179| 1.286 [1.172, 1.411]| 3397.0 | 263178.0 | 1350221.0 | 515.0 | 0.516| 
| 24 | ProcedureCPT:Other diagnostic procedures (interview, evaluation, consultation) ccs group 227 0074T[count>0] |-0.178| 0.617 [0.554, 0.688]| 364.0 | 1383510.0 | 229889.0 | 3548.0 | 0.475| 
| 25 | Diagnosis:Structure of skin and/or mucous membrane sid:707862002 276327007[count>2] |-0.171| 0.753 [0.667, 0.850]| 283.0 | 1461958.0 | 151441.0 | 3629.0 | 0.489| 
| 26 | Diagnosis:Neoplasm sid:55342001 109355002[count>0] |0.169| 0.875 [0.804, 0.952]| 646.0 | 1315886.0 | 297513.0 | 3266.0 | 0.490| 
| 27 | Diagnosis:Disorder of digestive organ sid:76712006 235856003[count>0] |-0.159| 0.942 [0.868, 1.022]| 706.0 | 1307740.0 | 305659.0 | 3206.0 | 0.496| 
| 28 | Diagnosis:Mycotic disease sid:3218000 110276005[count>0] |0.153| 1.035 [0.826, 1.298]| 77.0 | 1582706.0 | 30693.0 | 3835.0 | 0.500| 
| 29 | Diagnosis:Genitourinary finding sid:118238000 300479008[count>0] |0.152| 1.539 [1.437, 1.648]| 1155.0 | 1268153.0 | 345246.0 | 2757.0 | 0.541| 
| 30 | Diagnosis:Inflammation of specific body organs (disorder) sid:363169009 236781003[count>0] |0.148| 0.953 [0.883, 1.028]| 858.0 | 1245951.0 | 367448.0 | 3054.0 | 0.496| 
| 31 | Diagnosis:Disorder of head sid:118934005 192640001[count>2] |-0.143| 0.733 [0.659, 0.815]| 374.0 | 1410028.0 | 203371.0 | 3538.0 | 0.485| 
| 32 | Diagnosis:Traumatic and/or non-traumatic injury of anatomical site (disorder) sid:609411003 127294003[count>0] |0.141| 1.395 [1.278, 1.524]| 586.0 | 1432510.0 | 180889.0 | 3326.0 | 0.519| 
| 33 | Diagnosis:© 2002-2018 International Health Terminology Standards Development Organisation (IHTSDO). All rights reserved. SNOMED CT®, was originally created by The College of American Pathologists. "SNOMED" and "SNOMED CT" are registered trademarks of the IHTSDO. sid:138875005 254291000[count>10] |-0.139| 0.900 [0.846, 0.959]| 1959.0 | 763176.0 | 850223.0 | 1953.0 | 0.487| 
| 34 | Diagnosis:Colorectal cancer sid:363510005 93854002[count>2] |-0.133| 0.719 [0.530, 0.975]| 42.0 | 1589402.0 | 23997.0 | 3870.0 | 0.498| 
| 35 | Diagnosis:Effusion (morphologic abnormality) sid:41699000 125310008[count>0] |0.132| 1.762 [1.429, 2.173]| 90.0 | 1592123.0 | 21276.0 | 3822.0 | 0.505| 
| 36 | Diagnosis:Disorder of neck sid:118939000 186414001[count>0] |0.128| 1.133 [1.040, 1.235]| 621.0 | 1383076.0 | 230323.0 | 3291.0 | 0.508| 
| 37 | demographics_ETHNICITY_Not of Spanish/Hispanic Origin |-0.122| 0.921 [0.857, 0.990]| 994.0 | 1177759.0 | 435640.0 | 2918.0 | 0.492| 
| 38 | ProcedureCPT:226 Other diagnostic radiology and related techniques 0286T[count>0] |-0.120| 0.575 [0.498, 0.665]| 193.0 | 1479935.0 | 133464.0 | 3719.0 | 0.483| 
| 39 | Diagnosis:Organic erectile dysfunction sid:198036002 236752004[count>2] |0.116| 4.205 [3.241, 5.457]| 58.0 | 1607646.0 | 5753.0 | 3854.0 | 0.506| 
| 40 | Diagnosis:Patient encounter status (finding) sid:305058001 185324002[count>2] |-0.110| 0.589 [0.533, 0.651]| 434.0 | 1331266.0 | 282133.0 | 3478.0 | 0.468| 
| 41 | Diagnosis:Clinical history and observations sid:250171008 105499002[count>10] |-0.101| 0.960 [0.861, 1.072]| 352.0 | 1462779.0 | 150620.0 | 3560.0 | 0.498| 
| 42 | Diagnosis:Atherosclerosis of native coronary artery of transplanted heart with other forms of angina pectoris I25.758[count>0] |0.095| 3.268 [2.747, 3.887]| 133.0 | 1596208.0 | 17191.0 | 3779.0 | 0.512| 
| 43 | Diagnosis:Disorder of body system (disorder) sid:362965005 283985007[count>10] |-0.093| 1.190 [1.115, 1.270]| 1422.0 | 1090258.0 | 523141.0 | 2490.0 | 0.520| 
| 44 | Diagnosis:Disorder of pelvis (disorder) sid:609620004 42643001[count>2] |-0.093| 1.595 [1.437, 1.770]| 395.0 | 1507247.0 | 106152.0 | 3517.0 | 0.518| 
| 45 | Diagnosis:Inflammation of specific body organs (disorder) sid:363169009 236781003[count>2] |0.093| 0.898 [0.815, 0.989]| 469.0 | 1400909.0 | 212490.0 | 3443.0 | 0.494| 
| 46 | Diagnosis:Pain in left lower limb sid:287047008 12237111000119107[count>0] |0.088| 1.198 [1.008, 1.425]| 133.0 | 1567364.0 | 46035.0 | 3779.0 | 0.503| 
| 47 | Lab:Basophils/100 leukocytes in Blood 30180-4[normedValue_sd_between_-0.5,0.5] |-0.083| 0.862 [0.761, 0.976]| 265.0 | 1487944.0 | 125455.0 | 3647.0 | 0.495| 
| 48 | Diagnosis:Enlargement sid:442021009 56246009[count>0] |0.081| 1.131 [0.994, 1.288]| 244.0 | 1523788.0 | 89611.0 | 3668.0 | 0.503| 
| 49 | Diagnosis:Atherosclerosis of native coronary artery of transplanted heart with angina pectoris with documented spasm I25.751[count>0] |0.081| 3.268 [2.747, 3.887]| 133.0 | 1596208.0 | 17191.0 | 3779.0 | 0.512| 
| 50 | ProcedureCPT:Other diagnostic procedures (interview, evaluation, consultation) ccs group 227 0074T[count>2] |-0.080| 0.574 [0.499, 0.659]| 212.0 | 1466891.0 | 146508.0 | 3700.0 | 0.482| 
| 51 | Diagnosis:Observation of region of thorax sid:298705000 298720006[count>10] |-0.080| 1.339 [1.216, 1.475]| 470.0 | 1464137.0 | 149262.0 | 3442.0 | 0.514| 
| 52 | Diagnosis:Procedure by intent (procedure) sid:362961001 169443000[count>0] |0.077| 0.342 [0.310, 0.378]| 451.0 | 1168729.0 | 444670.0 | 3461.0 | 0.420| 
| 53 | Diagnosis:Laboratory test (procedure) sid:15220000 103766003[count>0] |0.075| 2.295 [2.151, 2.449]| 1480.0 | 1275277.0 | 338122.0 | 2432.0 | 0.584| 
| 54 | Diagnosis:Abnormal (qualifier value) sid:263654008 12380008[count>0] |-0.072| 0.931 [0.846, 1.026]| 471.0 | 1406657.0 | 206742.0 | 3441.0 | 0.496| 
| 55 | Diagnosis:Disorder of large intestine (disorder) sid:119523007 235766003[count>0] |0.071| 1.244 [1.098, 1.411]| 262.0 | 1525410.0 | 87989.0 | 3650.0 | 0.506| 
| 56 | Diagnosis:Genitourinary finding sid:118238000 300479008[count>2] |0.070| 1.608 [1.484, 1.743]| 732.0 | 1411347.0 | 202052.0 | 3180.0 | 0.531| 
| 57 | ProcedureCPT:Enteral and parenteral nutrition [223.]ccs group16.34 96.6[count>2] |-0.070| 0.785 [0.738, 0.836]| 2031.0 | 679411.0 | 933988.0 | 1881.0 | 0.470| 
| 58 | Diagnosis:Atherosclerosis of native coronary artery of transplanted heart with unspecified angina pectoris I25.759[count>0] |0.067| 3.268 [2.747, 3.887]| 133.0 | 1596208.0 | 17191.0 | 3779.0 | 0.512| 
| 59 | Diagnosis:Cholesterol measurement (procedure) sid:77068002 104584009[count>0] |-0.067| 1.191 [1.029, 1.379]| 188.0 | 1547796.0 | 65603.0 | 3724.0 | 0.504| 
