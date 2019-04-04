| index | variable | beta coef | unadjusted OR | TP | TN | FP | FN | AUC Single | 
| --- | --- | --- | --- | --- | --- | --- | --- | --- | 
| 0 | demographics_age[between_80_and_90] |2.120| 4.270 [3.792, 4.808]| 337.0 | 1548729.0 | 83829.0 | 1458.0 | 0.568| 
| 1 | demographics_age[between_70_and_80] |2.050| 3.833 [3.479, 4.223]| 635.0 | 1428546.0 | 204012.0 | 1160.0 | 0.614| 
| 2 | demographics_age[between_10_and_20] |-1.765| 0.000 [0.000, 0.000]| 0.0 | 1570248.0 | 62310.0 | 1795.0 | 0.481| 
| 3 | demographics_age[between_90_and_100] |1.710| 2.828 [2.023, 3.954]| 35.0 | 1621160.0 | 11398.0 | 1760.0 | 0.506| 
| 4 | demographics_age[between_30_and_40] |-1.402| 0.047 [0.025, 0.087]| 10.0 | 1458530.0 | 174028.0 | 1785.0 | 0.449| 
| 5 | demographics_age[between_60_and_70] |1.360| 1.770 [1.601, 1.956]| 559.0 | 1300274.0 | 332284.0 | 1236.0 | 0.554| 
| 6 | Diagnosis:Abnormal head movements R25.0[count>0] |1.356| 11.434 [9.239, 14.151]| 90.0 | 1625056.0 | 7502.0 | 1705.0 | 0.523| 
| 7 | demographics_age[between_20_and_30] |-1.304| 0.041 [0.018, 0.091]| 6.0 | 1508467.0 | 124091.0 | 1789.0 | 0.464| 
| 8 | demographics_age[between_40_and_50] |-1.247| 0.114 [0.082, 0.159]| 36.0 | 1384409.0 | 248149.0 | 1759.0 | 0.434| 
| 9 | demographics_age[between_1_and_10] |-1.246| 0.000 [0.000, 0.000]| 0.0 | 1585577.0 | 46981.0 | 1795.0 | 0.486| 
| 10 | demographics_GENDER_Female |-1.194| 0.400 [0.364, 0.439]| 768.0 | 568935.0 | 1063623.0 | 1027.0 | 0.388| 
| 11 | ProcedureCPT:218 Psychological and psychiatric evaluation and therapy 90791[count>2] |1.055| 5.289 [3.637, 7.690]| 28.0 | 1627681.0 | 4877.0 | 1767.0 | 0.506| 
| 12 | Diagnosis:Unspecified abdominal pain R10.9[count>2] |0.938| 1.414 [1.033, 1.935]| 40.0 | 1606656.0 | 25902.0 | 1755.0 | 0.503| 
| 13 | Diagnosis:Movement disorder (disorder) sid:60342002 229247004[count>0] |0.882| 7.413 [5.675, 9.683]| 56.0 | 1625497.0 | 7061.0 | 1739.0 | 0.513| 
| 14 | Diagnosis:Benign epithelial neoplasm of skin sid:254658001 201091002[count>0] |0.778| 2.522 [1.898, 3.352]| 49.0 | 1614593.0 | 17965.0 | 1746.0 | 0.508| 
| 15 | Diagnosis:Mammography finding (finding) sid:129714008 129715009[count>0] |-0.722| 0.522 [0.396, 0.688]| 52.0 | 1544335.0 | 88223.0 | 1743.0 | 0.487| 
| 16 | Diagnosis:Primary localized osteoarthrosis sid:201829007 201831003[count>2] |0.712| 2.582 [1.765, 3.778]| 27.0 | 1622960.0 | 9598.0 | 1768.0 | 0.505| 
| 17 | Diagnosis:Disorder of right cardiac ventricle sid:415992005 233891009[count>0] |0.677| 2.474 [1.976, 3.096]| 80.0 | 1602341.0 | 30217.0 | 1715.0 | 0.513| 
| 18 | Diagnosis:Disorder of affect sid:46206005 13746004[count>0] |0.635| 2.103 [1.769, 2.501]| 139.0 | 1569906.0 | 62652.0 | 1656.0 | 0.520| 
| 19 | Diagnosis:Atrial arrhythmia (disorder) sid:17366009 233891009[count>10] |0.611| 3.769 [3.011, 4.718]| 80.0 | 1612599.0 | 19959.0 | 1715.0 | 0.516| 
| 20 | Lab:Prothrombin time (PT) 5902-2[normedValue_sd_between_-0.5,0.5] |0.549| 1.790 [1.465, 2.186]| 102.0 | 1579386.0 | 53172.0 | 1693.0 | 0.512| 
| 21 | Diagnosis:Hip injury sid:125600009 211330003[count>0] |0.527| 4.198 [2.888, 6.103]| 28.0 | 1626419.0 | 6139.0 | 1767.0 | 0.506| 
| 22 | Diagnosis:Adiposity sid:414916001 414920002[count>0] |-0.526| 0.549 [0.415, 0.725]| 51.0 | 1549973.0 | 82585.0 | 1744.0 | 0.489| 
| 23 | Diagnosis:Acquired musculoskeletal deformity (disorder) sid:40668007 240226003[count>0] |-0.521| 0.667 [0.401, 1.108]| 15.0 | 1612179.0 | 20379.0 | 1780.0 | 0.498| 
| 24 | Diagnosis:Family history of cancer (situation) sid:275937001 160292002[count>0] |0.516| 1.005 [0.793, 1.275]| 71.0 | 1568303.0 | 64255.0 | 1724.0 | 0.500| 
| 25 | Lab:MCH [Entitic mass] by Automated count 785-6[normedValue_sd_between_-0.5,0.5] |0.509| 1.745 [1.504, 2.025]| 196.0 | 1525419.0 | 107139.0 | 1599.0 | 0.522| 
| 26 | Diagnosis:Disorder of body wall sid:399986003 102453009[count>0] |-0.491| 1.657 [1.428, 1.922]| 196.0 | 1520077.0 | 112481.0 | 1599.0 | 0.520| 
| 27 | Diagnosis:Heart valve structure sid:17401000 181285005[count>2] |-0.490| 1.341 [1.050, 1.712]| 67.0 | 1586683.0 | 45875.0 | 1728.0 | 0.505| 
| 28 | demographics_RACE_Unknown |-0.479| 0.585 [0.476, 0.718]| 96.0 | 1488717.0 | 143841.0 | 1699.0 | 0.483| 
| 29 | Diagnosis:Other specified cardiac arrhythmias I49.8[count>0] |-0.467| 1.283 [0.957, 1.720]| 46.0 | 1599772.0 | 32786.0 | 1749.0 | 0.503| 
| 30 | Diagnosis:Finding of back sid:414252009 283089004[count>0] |0.463| 1.886 [1.687, 2.108]| 399.0 | 1417663.0 | 214895.0 | 1396.0 | 0.545| 
| 31 | Diagnosis:Localized swelling, mass and lump, neck R22.1[count>0] |0.455| 1.417 [0.955, 2.104]| 25.0 | 1616446.0 | 16112.0 | 1770.0 | 0.502| 
| 32 | ProcedureCPT:Emergency dept visit 99284[count>0] |0.453| 1.596 [1.198, 2.126]| 48.0 | 1604927.0 | 27631.0 | 1747.0 | 0.505| 
| 33 | Diagnosis:Arm sid:53120007 182245002[count>10] |0.446| 2.307 [1.858, 2.866]| 86.0 | 1597714.0 | 34844.0 | 1709.0 | 0.513| 
| 34 | Diagnosis:Carotid artery observation sid:401050002 401051003[count>0] |-0.446| 1.799 [1.354, 2.390]| 49.0 | 1607478.0 | 25080.0 | 1746.0 | 0.506| 
| 35 | Diagnosis:Drug therapy status (situation) sid:410684002 135794007[count>0] |0.438| 1.701 [1.408, 2.055]| 115.0 | 1569401.0 | 63157.0 | 1680.0 | 0.513| 
| 36 | Diagnosis:GI - Gastrointestinal bleed sid:74474003 276229008[count>2] |0.430| 2.689 [1.904, 3.796]| 33.0 | 1621264.0 | 11294.0 | 1762.0 | 0.506| 
| 37 | Diagnosis:Pain in right lower limb sid:287048003 12237231000119107[count>0] |-0.427| 1.090 [0.857, 1.387]| 69.0 | 1574817.0 | 57741.0 | 1726.0 | 0.502| 
| 38 | Diagnosis:Other long term (current) drug therapy Z79.899[count>0] |-0.426| 0.724 [0.544, 0.965]| 48.0 | 1572897.0 | 59661.0 | 1747.0 | 0.495| 
| 39 | Diagnosis:Neoplasm (morphologic abnormality) sid:108369006 253061008[count>0] |-0.425| 1.244 [1.113, 1.391]| 401.0 | 1326000.0 | 306558.0 | 1394.0 | 0.518| 
| 40 | Diagnosis:Cranial neuropathy sid:73013002 10277002[count>0] |-0.422| 0.247 [0.093, 0.659]| 4.0 | 1617940.0 | 14618.0 | 1791.0 | 0.497| 
| 41 | Diagnosis:Disorder of pelvic region of trunk sid:609619005 363194005[count>0] |-0.417| 1.379 [1.234, 1.542]| 398.0 | 1353048.0 | 279510.0 | 1397.0 | 0.525| 
| 42 | Diagnosis:Disorder of body system (disorder) sid:362965005 283985007[count>10] |-0.417| 1.385 [1.260, 1.522]| 723.0 | 1097851.0 | 534707.0 | 1072.0 | 0.538| 
| 43 | Lab:MCV [Entitic volume] by Automated count 787-2[normedValue_sd_between_-0.5,0.5] |0.412| 1.700 [1.464, 1.975]| 192.0 | 1525116.0 | 107442.0 | 1603.0 | 0.521| 
| 44 | Diagnosis:Disorder of upper extremity sid:118947000 239972001[count>0] |-0.396| 1.412 [1.210, 1.647]| 180.0 | 1513083.0 | 119475.0 | 1615.0 | 0.514| 
| 45 | Diagnosis:MD - Metabolic disorders sid:75934005 106000008[count>0] |-0.395| 1.528 [1.386, 1.686]| 603.0 | 1226565.0 | 405993.0 | 1192.0 | 0.544| 
| 46 | Diagnosis:Arthralgia of hip sid:49218002 299308007[count>0] |-0.393| 1.230 [0.888, 1.704]| 37.0 | 1605100.0 | 27458.0 | 1758.0 | 0.502| 
| 47 | Diagnosis:Major depressive disorder, single episode, unspecified F32.9[count>0] |-0.390| 1.747 [1.423, 2.144]| 97.0 | 1580865.0 | 51693.0 | 1698.0 | 0.511| 
| 48 | Diagnosis:Disorder of lower extremity sid:118937003 202863007[count>10] |-0.385| 1.151 [0.906, 1.462]| 70.0 | 1576946.0 | 55612.0 | 1725.0 | 0.502| 
| 49 | Diagnosis:Encounter for follow-up examination after completed treatment for conditions other than malignant neoplasm Z09[count>0] |-0.385| 0.960 [0.727, 1.268]| 51.0 | 1584293.0 | 48265.0 | 1744.0 | 0.499| 
| 50 | Diagnosis:Difficult passing motion sid:14760008 111360009[count>2] |0.384| 2.821 [2.206, 3.609]| 66.0 | 1610764.0 | 21794.0 | 1729.0 | 0.512| 
| 51 | Diagnosis:Disorder of carbohydrate metabolism (disorder) sid:20957000 237597000[count>2] |0.381| 1.710 [1.466, 1.996]| 179.0 | 1533264.0 | 99294.0 | 1616.0 | 0.519| 
| 52 | Diagnosis:Intervertebral disc degeneration sid:77547008 26538006[count>0] |0.381| 2.053 [1.664, 2.533]| 92.0 | 1590709.0 | 41849.0 | 1703.0 | 0.513| 
| 53 | Diagnosis:Larynx observation sid:271748007 249431007[count>0] |0.370| 1.493 [0.997, 2.234]| 24.0 | 1617870.0 | 14688.0 | 1771.0 | 0.502| 
| 54 | Diagnosis:Mass of head sid:432525007 429429006[count>0] |0.359| 1.775 [1.369, 2.302]| 59.0 | 1601890.0 | 30668.0 | 1736.0 | 0.507| 
| 55 | Diagnosis:Giddiness sid:404641004 162261005[count>0] |0.356| 2.429 [2.046, 2.883]| 142.0 | 1576786.0 | 55772.0 | 1653.0 | 0.522| 
| 56 | Diagnosis:ADL - activity of daily living sid:129025006 258156005[count>0] |0.352| 4.406 [3.810, 5.096]| 206.0 | 1585898.0 | 46660.0 | 1589.0 | 0.543| 
| 57 | Lab:Platelets [#/volume] in Blood by Automated count 777-3[normedValue_sd_between_-0.5,0.5] |-0.350| 0.980 [0.814, 1.180]| 120.0 | 1521363.0 | 111195.0 | 1675.0 | 0.499| 
| 58 | Diagnosis:Pain in unspecified shoulder M25.519[count>2] |0.350| 2.985 [2.320, 3.840]| 63.0 | 1612903.0 | 19655.0 | 1732.0 | 0.512| 
| 59 | Diagnosis:Structure of genitourinary system sid:21514008 278861008[count>0] |0.350| 1.420 [1.284, 1.569]| 551.0 | 1244308.0 | 388250.0 | 1244.0 | 0.535| 
