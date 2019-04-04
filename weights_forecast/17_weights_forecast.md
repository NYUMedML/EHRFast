| index | variable | beta coef | unadjusted OR | TP | TN | FP | FN | AUC Single | 
| --- | --- | --- | --- | --- | --- | --- | --- | --- | 
| 0 | demographics_GENDER_Male |-4.556| 0.005 [0.004, 0.006]| 51.0 | 987509.0 | 575811.0 | 18023.0 | 0.317| 
| 1 | demographics_age[between_20_and_30] |-1.877| 0.080 [0.067, 0.096]| 124.0 | 1439545.0 | 123775.0 | 17950.0 | 0.464| 
| 2 | demographics_age[between_10_and_20] |-1.478| 0.041 [0.029, 0.059]| 31.0 | 1501113.0 | 62207.0 | 18043.0 | 0.481| 
| 3 | demographics_age[between_30_and_40] |-1.155| 0.180 [0.163, 0.199]| 395.0 | 1390644.0 | 172676.0 | 17679.0 | 0.456| 
| 4 | demographics_age[between_50_and_60] |0.983| 2.152 [2.087, 2.220]| 6207.0 | 1257661.0 | 305659.0 | 11867.0 | 0.574| 
| 5 | demographics_age[between_1_and_10] |-0.965| 0.007 [0.003, 0.019]| 4.0 | 1516338.0 | 46982.0 | 18070.0 | 0.485| 
| 6 | demographics_age[between_60_and_70] |0.762| 1.571 [1.521, 1.623]| 5079.0 | 1251880.0 | 311440.0 | 12995.0 | 0.541| 
| 7 | Diagnosis:Encounter for gynecological examination (general) (routine) without abnormal findings Z01.419[count>0] |0.677| 4.642 [4.453, 4.840]| 2711.0 | 1506073.0 | 57247.0 | 15363.0 | 0.557| 
| 8 | demographics_age[between_70_and_80] |0.503| 0.962 [0.920, 1.006]| 2193.0 | 1367071.0 | 196249.0 | 15881.0 | 0.498| 
| 9 | demographics_age[between_40_and_50] |0.482| 1.321 [1.273, 1.371]| 3451.0 | 1326365.0 | 236955.0 | 14623.0 | 0.520| 
| 10 | Diagnosis:Digestive system disease screening sid:391277002 391475007[count>0] |0.325| 3.609 [3.429, 3.799]| 1667.0 | 1520519.0 | 42801.0 | 16407.0 | 0.532| 
| 11 | demographics_RACE_White |0.226| 1.347 [1.304, 1.391]| 12820.0 | 556039.0 | 1007281.0 | 5254.0 | 0.532| 
| 12 | Diagnosis:Observation of pattern of menstrual cycle sid:248968007 161718009[count>0] |0.215| 3.075 [2.821, 3.352]| 551.0 | 1547495.0 | 15825.0 | 17523.0 | 0.510| 
| 13 | Diagnosis:Overweight (finding) sid:238131007 275947003[count>0] |-0.182| 0.916 [0.858, 0.978]| 965.0 | 1472665.0 | 90655.0 | 17109.0 | 0.498| 
| 14 | Diagnosis:Structure of eye proper sid:81745001 244486005[count>0] |0.172| 1.389 [1.295, 1.491]| 818.0 | 1511740.0 | 51580.0 | 17256.0 | 0.506| 
| 15 | demographics_ETHNICITY_Not of Spanish/Hispanic Origin |-0.154| 0.918 [0.888, 0.950]| 4520.0 | 1146907.0 | 416413.0 | 13554.0 | 0.492| 
| 16 | demographics_ETHNICITY_Unknown |-0.150| 0.713 [0.656, 0.774]| 585.0 | 1493222.0 | 70098.0 | 17489.0 | 0.494| 
| 17 | ProcedureCPT:234 Pathology 80500[count>0] |0.145| 2.421 [2.301, 2.548]| 1665.0 | 1500440.0 | 62880.0 | 16409.0 | 0.526| 
| 18 | Diagnosis:Atherosclerosis (morphologic abnormality) sid:38716007 10273003[count>0] |-0.145| 0.471 [0.430, 0.517]| 476.0 | 1478498.0 | 84822.0 | 17598.0 | 0.486| 
| 19 | Diagnosis:Disorder of mediastinum sid:49483002 240705002[count>0] |-0.141| 0.589 [0.560, 0.619]| 1658.0 | 1334409.0 | 228911.0 | 16416.0 | 0.473| 
| 20 | Diagnosis:Patient encounter status (finding) sid:305058001 185324002[count>0] |0.128| 1.485 [1.442, 1.530]| 7479.0 | 1059711.0 | 503609.0 | 10595.0 | 0.546| 
| 21 | Diagnosis:Structure of pelvic region of trunk sid:609617007 90264002[count>0] |0.119| 1.721 [1.668, 1.776]| 5757.0 | 1229477.0 | 333843.0 | 12317.0 | 0.552| 
| 22 | Diagnosis:Disorder of the genitourinary system sid:42030000 175176000[count>0] |0.105| 1.404 [1.356, 1.453]| 4221.0 | 1284519.0 | 278801.0 | 13853.0 | 0.528| 
| 23 | Diagnosis:Genital observation sid:300479008 249230006[count>2] |0.101| 1.410 [1.340, 1.484]| 1656.0 | 1458955.0 | 104365.0 | 16418.0 | 0.512| 
| 24 | Diagnosis:Structure of abdominal segment of trunk sid:609616003 609615004[count>0] |0.099| 1.202 [1.166, 1.239]| 6811.0 | 1040166.0 | 523154.0 | 11263.0 | 0.521| 
| 25 | Diagnosis:Clinical finding sid:404684003 250171008[count>2] |-0.098| 0.842 [0.812, 0.872]| 14120.0 | 298140.0 | 1265180.0 | 3954.0 | 0.486| 
| 26 | Diagnosis:Lower urinary tract finding (finding) sid:106100005 249300001[count>0] |0.098| 1.400 [1.326, 1.479]| 1418.0 | 1473712.0 | 89608.0 | 16656.0 | 0.511| 
| 27 | Diagnosis:Disorder of colon sid:128524007 1045000[count>0] |-0.097| 1.051 [0.985, 1.122]| 962.0 | 1483967.0 | 79353.0 | 17112.0 | 0.501| 
| 28 | Diagnosis:© 2002-2018 International Health Terminology Standards Development Organisation (IHTSDO). All rights reserved. SNOMED CT®, was originally created by The College of American Pathologists. "SNOMED" and "SNOMED CT" are registered trademarks of the IHTSDO. sid:138875005 254291000[count>10] |-0.097| 0.903 [0.877, 0.930]| 8983.0 | 746591.0 | 816729.0 | 9091.0 | 0.487| 
| 29 | Diagnosis:Pain in left foot M79.672[count>0] |0.088| 1.308 [1.230, 1.390]| 1111.0 | 1488773.0 | 74547.0 | 16963.0 | 0.507| 
| 30 | Diagnosis:Female genitalia observations sid:248842004 248870002[count>0] |0.088| 2.816 [2.712, 2.925]| 3366.0 | 1445838.0 | 117482.0 | 14708.0 | 0.556| 
| 31 | Diagnosis:Respiratory finding (finding) sid:106048009 106058008[count>0] |0.088| 0.897 [0.866, 0.928]| 4235.0 | 1165538.0 | 397782.0 | 13839.0 | 0.490| 
| 32 | Diagnosis:Finding of upper limb (finding) sid:116307009 102558002[count>0] |0.082| 1.217 [1.162, 1.275]| 2031.0 | 1416010.0 | 147310.0 | 16043.0 | 0.509| 
| 33 | Diagnosis:Structure of pelvic region of trunk sid:609617007 90264002[count>2] |0.082| 1.670 [1.609, 1.734]| 3386.0 | 1373720.0 | 189600.0 | 14688.0 | 0.533| 
| 34 | Diagnosis:Traumatic and/or non-traumatic injury of anatomical site (disorder) sid:609411003 127294003[count>2] |-0.078| 0.660 [0.615, 0.709]| 796.0 | 1461361.0 | 101959.0 | 17278.0 | 0.489| 
| 35 | Diagnosis:Disease (disorder) sid:64572001 173300003[count>2] |-0.073| 0.758 [0.736, 0.781]| 10920.0 | 518759.0 | 1044561.0 | 7154.0 | 0.468| 
| 36 | Diagnosis:Observation of the extremities sid:302293008 116307009[count>0] |0.072| 1.092 [1.056, 1.128]| 4954.0 | 1161565.0 | 401755.0 | 13120.0 | 0.509| 
| 37 | Diagnosis:Dizziness and giddiness R42[count>0] |0.068| 1.255 [1.168, 1.348]| 792.0 | 1508244.0 | 55076.0 | 17282.0 | 0.504| 
| 38 | Diagnosis:Finding of pelvic region of trunk sid:609625009 124734007[count>10] |0.066| 1.541 [1.438, 1.650]| 869.0 | 1513692.0 | 49628.0 | 17205.0 | 0.508| 
| 39 | Diagnosis:Procedure by intent (procedure) sid:362961001 169443000[count>0] |0.061| 2.668 [2.591, 2.747]| 8728.0 | 1157981.0 | 405339.0 | 9346.0 | 0.612| 
| 40 | Diagnosis:Disorder of integument (disorder) sid:128598002 38164009[count>0] |0.059| 1.083 [1.036, 1.131]| 2324.0 | 1375852.0 | 187468.0 | 15750.0 | 0.504| 
| 41 | Diagnosis:Female genitalia observations sid:248842004 248870002[count>2] |0.056| 2.826 [2.682, 2.978]| 1581.0 | 1512035.0 | 51285.0 | 16493.0 | 0.527| 
| 42 | Diagnosis:General well-being sid:82832008 102464007[count>0] |0.056| 0.926 [0.890, 0.963]| 3020.0 | 1284850.0 | 278470.0 | 15054.0 | 0.494| 
| 43 | Diagnosis:Clinical imaging sid:363679005 169283005[count>2] |0.056| 2.394 [2.292, 2.500]| 2399.0 | 1469386.0 | 93934.0 | 15675.0 | 0.536| 
| 44 | Diagnosis:Disorder of cartilage sid:50927007 53417006[count>0] |0.054| 1.620 [1.548, 1.694]| 2180.0 | 1441261.0 | 122059.0 | 15894.0 | 0.521| 
| 45 | Diagnosis:Chronic disease (disorder) sid:27624003 177010002[count>0] |-0.053| 0.762 [0.725, 0.801]| 1715.0 | 1374305.0 | 189015.0 | 16359.0 | 0.487| 
| 46 | Diagnosis:Musculoskeletal and connective tissue disorder sid:312225001 239949003[count>0] |0.051| 1.482 [1.432, 1.534]| 4251.0 | 1294664.0 | 268656.0 | 13823.0 | 0.532| 
| 47 | Diagnosis:Finding of cardiovascular measurement sid:366157005 366158000[count>0] |-0.051| 0.769 [0.739, 0.800]| 3001.0 | 1241710.0 | 321610.0 | 15073.0 | 0.480| 
| 48 | Diagnosis:Prolapse (morphologic abnormality) sid:29696001 59984009[count>0] |0.051| 1.607 [1.496, 1.726]| 804.0 | 1519303.0 | 44017.0 | 17270.0 | 0.508| 
| 49 | Diagnosis:Soft tissue lesion (disorder) sid:239953001 239954007[count>2] |-0.050| 0.900 [0.855, 0.946]| 1654.0 | 1405896.0 | 157424.0 | 16420.0 | 0.495| 
| 50 | Diagnosis:Family history of disorder (situation) sid:281666001 160301004[count>0] |0.047| 1.839 [1.750, 1.934]| 1731.0 | 1478204.0 | 85116.0 | 16343.0 | 0.521| 
| 51 | Diagnosis:Current or specified time sid:410512000 15240007[count>0] |0.046| 1.270 [1.223, 1.319]| 3394.0 | 1322541.0 | 240779.0 | 14680.0 | 0.517| 
| 52 | Diagnosis:Degeneration (morphologic abnormality) sid:33359002 182257006[count>0] |0.040| 1.288 [1.237, 1.341]| 2847.0 | 1365126.0 | 198194.0 | 15227.0 | 0.515| 
| 53 | Diagnosis:Abdominal mass (finding) sid:271860004 300404004[count>0] |-0.040| 1.547 [1.480, 1.617]| 2276.0 | 1430131.0 | 133189.0 | 15798.0 | 0.520| 
| 54 | Diagnosis:Administrative statuses (finding) sid:307824009 185391001[count>2] |0.037| 1.757 [1.704, 1.811]| 6629.0 | 1175663.0 | 387657.0 | 11445.0 | 0.559| 
| 55 | Diagnosis:Malignant neoplasm of unspecified site of unspecified female breast C50.919[count>2] |0.034| 2.589 [2.385, 2.811]| 605.0 | 1542683.0 | 20637.0 | 17469.0 | 0.510| 
| 56 | Diagnosis:Cardiovascular measurement - observation sid:310611001 252059006[count>0] |-0.033| 0.769 [0.739, 0.800]| 3001.0 | 1241710.0 | 321610.0 | 15073.0 | 0.480| 
| 57 | Diagnosis:Sudden onset AND/OR short duration sid:424124008 255212004[count>0] |-0.030| 0.840 [0.802, 0.879]| 2050.0 | 1356630.0 | 206690.0 | 16024.0 | 0.491| 
| 58 | Diagnosis:Screening for disorder (procedure) sid:312851005 171228002[count>0] |0.030| 2.243 [2.164, 2.325]| 3834.0 | 1395784.0 | 167536.0 | 14240.0 | 0.552| 
| 59 | Diagnosis:At birth sid:255399007 190268003[count>0] |-0.029| 0.644 [0.587, 0.707]| 454.0 | 1503204.0 | 60116.0 | 17620.0 | 0.493| 
