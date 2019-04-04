| index | variable | beta coef | unadjusted OR | TP | TN | FP | FN | AUC Single | 
| --- | --- | --- | --- | --- | --- | --- | --- | --- | 
| 0 | demographics_GENDER_Male |-4.696| 0.000 [0.000, 0.000]| 0.0 | 1053730.0 | 575987.0 | 972.0 | 0.323| 
| 1 | ProcedureCPT:Other diagnostic radiology and related techniques ccs group 226 0028T[count>2] |-1.600| 0.424 [0.301, 0.596]| 34.0 | 1501229.0 | 128488.0 | 938.0 | 0.478| 
| 2 | Diagnosis:No abnormality detected - examination result (finding) sid:282332003 282332003[count>0] |-1.490| 0.000 [0.000, 0.000]| 0.0 | 1549987.0 | 79730.0 | 972.0 | 0.476| 
| 3 | Diagnosis:Heart disease in mother complicating pregnancy, childbirth AND/OR puerperium (disorder) sid:78381004 267207004[count>2] |1.356| 145.282 [58.146, 362.995]| 5.0 | 1629659.0 | 58.0 | 967.0 | 0.503| 
| 4 | Diagnosis:Cyst of ovary (disorder) sid:79883001 237060003[count>0] |1.039| 28.409 [24.150, 33.419]| 181.0 | 1616695.0 | 13022.0 | 791.0 | 0.589| 
| 5 | demographics_RACE_Unknown |-1.009| 0.552 [0.414, 0.735]| 49.0 | 1486662.0 | 143055.0 | 923.0 | 0.481| 
| 6 | ProcedureCPT:233 Laboratory 80002[count>10] |-0.963| 0.709 [0.549, 0.915]| 63.0 | 1484530.0 | 145187.0 | 909.0 | 0.488| 
| 7 | ProcedureCPT:Other diagnostic ultrasound ccs group 197 0346T[count>2] |-0.946| 0.888 [0.592, 1.331]| 24.0 | 1584536.0 | 45181.0 | 948.0 | 0.498| 
| 8 | demographics_age[between_30_and_40] |0.925| 2.248 [1.925, 2.624]| 203.0 | 1458433.0 | 171284.0 | 769.0 | 0.552| 
| 9 | Diagnosis:Disorder of ovary (disorder) sid:5552004 10661008[count>0] |0.889| 21.505 [18.346, 25.208]| 191.0 | 1611392.0 | 18325.0 | 781.0 | 0.593| 
| 10 | Diagnosis:Bacterial infectious disease (disorder) sid:87628006 301811001[count>0] |-0.885| 1.019 [0.708, 1.466]| 30.0 | 1580334.0 | 49383.0 | 942.0 | 0.500| 
| 11 | Diagnosis:Encounter for gynecological examination (general) (routine) without abnormal findings Z01.419[count>0] |-0.802| 3.090 [2.560, 3.729]| 125.0 | 1555425.0 | 74292.0 | 847.0 | 0.542| 
| 12 | Diagnosis:Serum lipids high (finding) sid:166816003 166830008[count>0] |0.778| 1.068 [0.892, 1.278]| 139.0 | 1409449.0 | 220268.0 | 833.0 | 0.504| 
| 13 | demographics_age[between_1_and_10] |-0.688| 0.000 [0.000, 0.000]| 0.0 | 1582733.0 | 46984.0 | 972.0 | 0.486| 
| 14 | Diagnosis:Mechanical abnormality (morphologic abnormality) sid:107658001 107666005[count>0] |-0.663| 0.334 [0.241, 0.461]| 38.0 | 1452569.0 | 177148.0 | 934.0 | 0.465| 
| 15 | demographics_age[between_20_and_30] |0.632| 1.665 [1.372, 2.022]| 116.0 | 1507076.0 | 122641.0 | 856.0 | 0.522| 
| 16 | Diagnosis:Genital observation sid:300479008 249230006[count>0] |0.611| 3.970 [3.491, 4.515]| 384.0 | 1399514.0 | 230203.0 | 588.0 | 0.627| 
| 17 | Diagnosis:Administrative statuses (finding) sid:307824009 185391001[count>10] |-0.594| 1.328 [1.030, 1.711]| 64.0 | 1547557.0 | 82160.0 | 908.0 | 0.508| 
| 18 | Diagnosis:Procedure on trunk (procedure) sid:118694006 180292008[count>2] |0.585| 2.537 [2.144, 3.002]| 163.0 | 1509816.0 | 119901.0 | 809.0 | 0.547| 
| 19 | Diagnosis:Observation of appearance of skin sid:225545000 185823004[count>0] |0.578| 4.382 [2.870, 6.691]| 22.0 | 1621150.0 | 8567.0 | 950.0 | 0.509| 
| 20 | Diagnosis:Disorder of toe (disorder) sid:128619003 195302000[count>0] |0.572| 1.967 [1.300, 2.975]| 23.0 | 1609878.0 | 19839.0 | 949.0 | 0.506| 
| 21 | Diagnosis:Subject of record or other provider of history sid:419358007 410604004[count>0] |-0.558| 0.763 [0.513, 1.135]| 25.0 | 1575206.0 | 54511.0 | 947.0 | 0.496| 
| 22 | Lab:Erythrocytes [#/volume] in Blood by Automated count 789-8[normedValue_sd_between_1,3] |0.554| 0.505 [0.271, 0.943]| 10.0 | 1596878.0 | 32839.0 | 962.0 | 0.495| 
| 23 | Diagnosis:Color of skin (observable entity) sid:364533002 225548003[count>0] |0.552| 6.358 [4.080, 9.909]| 20.0 | 1624350.0 | 5367.0 | 952.0 | 0.509| 
| 24 | Diagnosis:Enlargement sid:442021009 56246009[count>0] |0.548| 1.315 [1.031, 1.677]| 70.0 | 1538878.0 | 90839.0 | 902.0 | 0.508| 
| 25 | Diagnosis:Observation of brain sid:299718000 106165002[count>2] |-0.543| 0.596 [0.409, 0.867]| 28.0 | 1552415.0 | 77302.0 | 944.0 | 0.491| 
| 26 | Diagnosis:Disorders of skin caused by physical agents sid:373591006 200999007[count>0] |0.522| 2.740 [1.585, 4.739]| 13.0 | 1621695.0 | 8022.0 | 959.0 | 0.504| 
| 27 | Diagnosis:Care regimes education (procedure) sid:392155009 15502008[count>0] |0.521| 6.993 [4.487, 10.900]| 20.0 | 1624836.0 | 4881.0 | 952.0 | 0.509| 
| 28 | Diagnosis:Cyst of abdomen sid:446064000 236011003[count>0] |0.514| 12.213 [10.415, 14.321]| 189.0 | 1598131.0 | 31586.0 | 783.0 | 0.588| 
| 29 | ProcedureCPT:Diagnostic ultrasound of heart (echocardiogram) ccs group 193 0399T[count>0] |-0.502| 0.869 [0.589, 1.283]| 26.0 | 1579757.0 | 49960.0 | 946.0 | 0.498| 
| 30 | Diagnosis:MD - Metabolic disorders sid:75934005 106000008[count>0] |-0.502| 0.728 [0.622, 0.854]| 190.0 | 1222117.0 | 407600.0 | 782.0 | 0.473| 
| 31 | Diagnosis:Examination of body system (procedure) sid:284366008 164135002[count>0] |0.501| 4.362 [3.724, 5.111]| 191.0 | 1543205.0 | 86512.0 | 781.0 | 0.572| 
| 32 | Diagnosis:Post-viral disorder (disorder) sid:123948009 191727003[count>2] |0.481| 4.619 [2.301, 9.271]| 8.0 | 1626794.0 | 2923.0 | 964.0 | 0.503| 
| 33 | Diagnosis:Clinical history and observations sid:250171008 105499002[count>2] |-0.474| 0.819 [0.706, 0.949]| 230.0 | 1182071.0 | 447646.0 | 742.0 | 0.481| 
| 34 | Diagnosis:Chondromalacia patellae, unspecified knee M22.40[count>0] |0.468| 3.429 [1.629, 7.218]| 7.0 | 1626277.0 | 3440.0 | 965.0 | 0.503| 
| 35 | Diagnosis:Disorder of cellular component of blood sid:414022008 414023003[count>2] |0.465| 1.737 [1.348, 2.239]| 64.0 | 1566178.0 | 63539.0 | 908.0 | 0.513| 
| 36 | Diagnosis:Finding of abnormal level of heavy metals in blood R78.79[count>2] |0.456| 2.773 [1.760, 4.368]| 19.0 | 1618082.0 | 11635.0 | 953.0 | 0.506| 
| 37 | Diagnosis:Traumatic and/or non-traumatic injury of anatomical site (disorder) sid:609411003 127294003[count>0] |0.452| 0.976 [0.799, 1.193]| 108.0 | 1444772.0 | 184945.0 | 864.0 | 0.499| 
| 38 | Diagnosis:Neuropathy of upper limb sid:609599003 16644004[count>0] |0.439| 2.333 [1.542, 3.529]| 23.0 | 1612960.0 | 16757.0 | 949.0 | 0.507| 
| 39 | demographics_age[between_40_and_50] |0.430| 1.890 [1.634, 2.185]| 243.0 | 1385367.0 | 244350.0 | 729.0 | 0.550| 
| 40 | Diagnosis:Mastodynia N64.4[count>0] |0.427| 3.287 [2.153, 5.018]| 22.0 | 1618315.0 | 11402.0 | 950.0 | 0.508| 
| 41 | Diagnosis:Finding of sensation of lower limb (finding) sid:713314006 10601006[count>0] |-0.423| 0.737 [0.583, 0.931]| 76.0 | 1461411.0 | 168306.0 | 896.0 | 0.487| 
| 42 | Lab:Calcium [Mass/volume] in Serum or Plasma 17861-6[normedValue_sd_between_-1,-0.5] |0.422| 1.888 [1.327, 2.686]| 32.0 | 1600856.0 | 28861.0 | 940.0 | 0.508| 
| 43 | Diagnosis:Colorectal cancer sid:363510005 93854002[count>0] |-0.416| 0.738 [0.507, 1.075]| 28.0 | 1566759.0 | 62958.0 | 944.0 | 0.495| 
| 44 | Diagnosis:Vascular headache (disorder) sid:128187005 37796009[count>0] |0.415| 3.118 [2.332, 4.168]| 48.0 | 1603006.0 | 26711.0 | 924.0 | 0.516| 
| 45 | Diagnosis:Disorder of trunk sid:128121009 280133005[count>2] |0.409| 1.584 [1.395, 1.798]| 427.0 | 1090383.0 | 539334.0 | 545.0 | 0.554| 
| 46 | Diagnosis:Joint observation sid:118952005 248520009[count>0] |0.401| 1.110 [0.959, 1.285]| 238.0 | 1261317.0 | 368400.0 | 734.0 | 0.509| 
| 47 | Diagnosis:Encounter for other general counseling and advice on contraception Z30.09[count>0] |0.391| 7.266 [4.282, 12.330]| 14.0 | 1626446.0 | 3271.0 | 958.0 | 0.506| 
| 48 | Diagnosis:Primary malignant neoplasm sid:372087000 109267002[count>0] |-0.390| 0.685 [0.418, 1.123]| 16.0 | 1590851.0 | 38866.0 | 956.0 | 0.496| 
| 49 | Diagnosis:Esophageal finding sid:300284004 300286002[count>0] |0.389| 1.066 [0.851, 1.335]| 83.0 | 1498451.0 | 131266.0 | 889.0 | 0.502| 
| 50 | Diagnosis:Bronchial observation sid:301229001 102581000[count>2] |0.388| 0.941 [0.627, 1.411]| 24.0 | 1587010.0 | 42707.0 | 948.0 | 0.499| 
| 51 | Lab:MCH [Entitic mass] by Automated count 785-6[normedValue_sd_between_-0.5,0.5] |0.376| 1.759 [1.439, 2.150]| 107.0 | 1522630.0 | 107087.0 | 865.0 | 0.522| 
| 52 | Diagnosis:Pain in unspecified forearm M79.639[count>0] |0.370| 1.612 [1.270, 2.046]| 73.0 | 1551553.0 | 78164.0 | 899.0 | 0.514| 
| 53 | Diagnosis:Pregnancy, childbirth and puerperium observations sid:248982007 248994003[count>2] |-0.369| 1.910 [1.213, 3.009]| 19.0 | 1612883.0 | 16834.0 | 953.0 | 0.505| 
| 54 | ProcedureCPT:Emergency dept visit 99283[count>0] |0.368| 2.324 [1.658, 3.257]| 35.0 | 1603937.0 | 25780.0 | 937.0 | 0.510| 
| 55 | Lab:Glucose [Mass/volume] in Serum or Plasma 2345-7[normedValue_sd_between_-1,-0.5] |0.368| 1.731 [1.341, 2.235]| 63.0 | 1566994.0 | 62723.0 | 909.0 | 0.513| 
| 56 | Diagnosis:Disorder of back (disorder) sid:33308003 192970008[count>2] |-0.367| 0.659 [0.478, 0.908]| 39.0 | 1532525.0 | 97192.0 | 933.0 | 0.490| 
| 57 | Diagnosis:Vascular headache, not elsewhere classified G44.1[count>0] |0.364| 1.948 [1.448, 2.620]| 46.0 | 1589189.0 | 40528.0 | 926.0 | 0.511| 
| 58 | Diagnosis:Observation of the extremities sid:302293008 116307009[count>2] |-0.361| 0.957 [0.810, 1.131]| 167.0 | 1339426.0 | 290291.0 | 805.0 | 0.497| 
| 59 | Diagnosis:Musculoskeletal disorder of the neck (disorder) sid:111235007 95420006[count>0] |-0.338| 0.699 [0.449, 1.089]| 20.0 | 1582165.0 | 47552.0 | 952.0 | 0.496| 
