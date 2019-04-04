| index | variable | beta coef | unadjusted OR | TP | TN | FP | FN | AUC Single | 
| --- | --- | --- | --- | --- | --- | --- | --- | --- | 
| 0 | demographics_age[between_1_and_10] |-1.212| 0.131 [0.107, 0.161]| 93.0 | 1485852.0 | 46235.0 | 22785.0 | 0.487| 
| 1 | demographics_age[between_10_and_20] |-0.742| 0.320 [0.285, 0.359]| 297.0 | 1471570.0 | 60517.0 | 22581.0 | 0.487| 
| 2 | Diagnosis:Neoplasm of central nervous system (disorder) sid:126951006 126962006[count>0] |0.446| 3.825 [3.445, 4.247]| 377.0 | 1525405.0 | 6682.0 | 22501.0 | 0.506| 
| 3 | demographics_RACE_White |0.382| 1.684 [1.634, 1.735]| 17164.0 | 550281.0 | 981806.0 | 5714.0 | 0.555| 
| 4 | Diagnosis:Encounter for general adult medical examination without abnormal findings Z00.00[count>0] |0.236| 1.636 [1.583, 1.691]| 4480.0 | 1333559.0 | 198528.0 | 18398.0 | 0.533| 
| 5 | Diagnosis:Epithelial neoplasm of skin sid:254649008 254650008[count>0] |0.222| 6.236 [5.853, 6.645]| 1089.0 | 1519906.0 | 12181.0 | 21789.0 | 0.520| 
| 6 | Diagnosis:Neoplasm of skin (disorder) sid:126488004 254649008[count>0] |0.221| 4.740 [4.524, 4.966]| 2060.0 | 1500758.0 | 31329.0 | 20818.0 | 0.535| 
| 7 | Diagnosis:Benign neoplasm of soft tissue sid:92069005 255195007[count>0] |0.194| 4.556 [4.333, 4.789]| 1763.0 | 1504512.0 | 27575.0 | 21115.0 | 0.530| 
| 8 | demographics_age[between_70_and_80] |0.163| 1.429 [1.380, 1.480]| 3802.0 | 1344589.0 | 187498.0 | 19076.0 | 0.522| 
| 9 | demographics_age[between_20_and_30] |-0.161| 0.764 [0.724, 0.807]| 1382.0 | 1413210.0 | 118877.0 | 21496.0 | 0.491| 
| 10 | Diagnosis:Screening - procedure intent sid:360156006 169673001[count>2] |0.155| 1.697 [1.632, 1.765]| 2961.0 | 1408695.0 | 123392.0 | 19917.0 | 0.524| 
| 11 | Diagnosis:Malignant neoplasm sid:363346000 255056009[count>0] |0.154| 2.131 [2.069, 2.195]| 6132.0 | 1307395.0 | 224692.0 | 16746.0 | 0.561| 
| 12 | Diagnosis:Ocular structure sid:371398005 181142009[count>0] |0.145| 2.033 [1.932, 2.140]| 1637.0 | 1476137.0 | 55950.0 | 21241.0 | 0.518| 
| 13 | Diagnosis:Genital lesion sid:724386005 5327000[count>0] |-0.144| 1.403 [1.335, 1.475]| 1700.0 | 1449172.0 | 82915.0 | 21178.0 | 0.510| 
| 14 | Diagnosis:Patient encounter status (finding) sid:305058001 185324002[count>0] |0.138| 1.591 [1.549, 1.633]| 9922.0 | 1034221.0 | 497866.0 | 12956.0 | 0.554| 
| 15 | Diagnosis:Mental disorder (disorder) sid:74732009 192616009[count>2] |-0.138| 1.202 [1.138, 1.269]| 1410.0 | 1452713.0 | 79374.0 | 21468.0 | 0.505| 
| 16 | Diagnosis:Disorder of integument (disorder) sid:128598002 38164009[count>0] |0.136| 2.425 [2.351, 2.503]| 5221.0 | 1365604.0 | 166483.0 | 17657.0 | 0.560| 
| 17 | Diagnosis:Procedure on trunk (procedure) sid:118694006 180292008[count>2] |0.134| 1.481 [1.418, 1.546]| 2350.0 | 1422136.0 | 109951.0 | 20528.0 | 0.515| 
| 18 | Diagnosis:Body mass index above normal parameters sid:48499001 162863004[count>0] |-0.133| 1.015 [0.931, 1.107]| 530.0 | 1497103.0 | 34984.0 | 22348.0 | 0.500| 
| 19 | ProcedureCPT:Other diagnostic procedures (interview, evaluation, consultation) ccs group 227 0074T[count>0] |0.123| 1.553 [1.502, 1.605]| 4426.0 | 1327100.0 | 204987.0 | 18452.0 | 0.530| 
| 20 | ProcedureCPT:Other procedures to assist delivery [137.]ccs group13.5 73.4[count>2] |-0.119| 1.123 [1.079, 1.168]| 20055.0 | 209092.0 | 1322995.0 | 2823.0 | 0.507| 
| 21 | Diagnosis:Structure of central nervous system sid:21483005 278199004[count>0] |-0.117| 1.169 [1.118, 1.222]| 2207.0 | 1403852.0 | 128235.0 | 20671.0 | 0.506| 
| 22 | Diagnosis:Structure of eye proper sid:81745001 244486005[count>0] |0.110| 2.060 [1.951, 2.175]| 1424.0 | 1484256.0 | 47831.0 | 21454.0 | 0.516| 
| 23 | Diagnosis:Mammography (procedure) sid:71651007 241055006[count>0] |-0.109| 0.771 [0.743, 0.801]| 3220.0 | 1263727.0 | 268360.0 | 19658.0 | 0.483| 
| 24 | Diagnosis:Mass (morphologic abnormality) sid:4147007 103605005[count>0] |0.108| 2.130 [2.072, 2.189]| 7900.0 | 1227973.0 | 304114.0 | 14978.0 | 0.573| 
| 25 | Diagnosis:Mass (morphologic abnormality) sid:4147007 103605005[count>2] |0.103| 2.439 [2.366, 2.515]| 5529.0 | 1355051.0 | 177036.0 | 17349.0 | 0.563| 
| 26 | demographics_ETHNICITY_Not of Spanish/Hispanic Origin |0.103| 1.552 [1.510, 1.595]| 8047.0 | 1135153.0 | 396934.0 | 14831.0 | 0.546| 
| 27 | Diagnosis:Operative procedure sid:387713003 103708000[count>2] |-0.102| 1.241 [1.177, 1.309]| 1487.0 | 1450845.0 | 81242.0 | 21391.0 | 0.506| 
| 28 | Diagnosis:Malignant neoplasm of primary, secondary, or uncertain origin sid:367651003 14799000[count>2] |0.101| 2.527 [2.422, 2.635]| 2513.0 | 1460746.0 | 71341.0 | 20365.0 | 0.532| 
| 29 | Diagnosis:Structure of head and/or neck sid:774007 281232002[count>0] |0.101| 1.564 [1.523, 1.606]| 9838.0 | 1033542.0 | 498545.0 | 13040.0 | 0.552| 
| 30 | demographics_age[between_80_and_90] |0.100| 1.430 [1.358, 1.505]| 1604.0 | 1455335.0 | 76752.0 | 21274.0 | 0.510| 
| 31 | Diagnosis:Finding of abdominal segment of trunk (finding) sid:609627001 116306000[count>0] |0.098| 1.613 [1.571, 1.656]| 10176.0 | 1023716.0 | 508371.0 | 12702.0 | 0.556| 
| 32 | Diagnosis:Procedure on thorax (procedure) sid:118695007 238327005[count>0] |-0.097| 0.813 [0.784, 0.842]| 3607.0 | 1245313.0 | 286774.0 | 19271.0 | 0.485| 
| 33 | Diagnosis:Disease of epidermal appendages sid:238714008 238753004[count>0] |0.095| 2.210 [2.093, 2.334]| 1417.0 | 1487649.0 | 44438.0 | 21461.0 | 0.516| 
| 34 | Diagnosis:Disorder of thoracic segment of trunk (disorder) sid:609622007 118946009[count>0] |-0.094| 1.329 [1.292, 1.368]| 6670.0 | 1169935.0 | 362152.0 | 16208.0 | 0.528| 
| 35 | ProcedureCPT:Tte w/doppler complete 93306[count>0] |0.094| 1.994 [1.869, 2.126]| 993.0 | 1497993.0 | 34094.0 | 21885.0 | 0.511| 
| 36 | Diagnosis:Imaging of thorax sid:413815006 415232002[count>0] |-0.093| 0.761 [0.732, 0.790]| 3044.0 | 1274866.0 | 257221.0 | 19834.0 | 0.483| 
| 37 | Diagnosis:Skin AND/OR mucosa finding sid:415531008 367394000[count>0] |0.089| 2.237 [2.173, 2.303]| 6422.0 | 1304523.0 | 227564.0 | 16456.0 | 0.566| 
| 38 | Diagnosis:Rheumatic pain sid:279069000 279062009[count>2] |0.086| 1.617 [1.550, 1.686]| 2465.0 | 1425597.0 | 106490.0 | 20413.0 | 0.519| 
| 39 | Diagnosis:Enlargement sid:442021009 56246009[count>0] |0.085| 1.566 [1.492, 1.644]| 1821.0 | 1451906.0 | 80181.0 | 21057.0 | 0.514| 
| 40 | Diagnosis:Mass of head sid:432525007 429429006[count>0] |0.083| 3.029 [2.825, 3.248]| 854.0 | 1512723.0 | 19364.0 | 22024.0 | 0.512| 
| 41 | Diagnosis:Structure of genitourinary system sid:21514008 278861008[count>2] |0.082| 1.818 [1.761, 1.876]| 4999.0 | 1327837.0 | 204250.0 | 17879.0 | 0.543| 
| 42 | demographics_GENDER_Female |-0.081| 0.839 [0.816, 0.861]| 14007.0 | 531422.0 | 1000665.0 | 8871.0 | 0.480| 
| 43 | demographics_RACE_Unknown |-0.081| 0.527 [0.497, 0.560]| 1151.0 | 1392244.0 | 139843.0 | 21727.0 | 0.480| 
| 44 | ProcedureCPT:Other diagnostic radiology and related techniques ccs group 226 0028T[count>0] |0.081| 1.499 [1.445, 1.554]| 3467.0 | 1368923.0 | 163164.0 | 19411.0 | 0.523| 
| 45 | Diagnosis:Clinical evaluation sid:386053000 103705002[count>2] |0.080| 1.651 [1.609, 1.695]| 10180.0 | 1031390.0 | 500697.0 | 12698.0 | 0.559| 
| 46 | Diagnosis:Disorder of spinal region sid:410730009 73671007[count>2] |0.078| 1.699 [1.619, 1.783]| 1852.0 | 1456578.0 | 75509.0 | 21026.0 | 0.516| 
| 47 | Diagnosis:Overweight (finding) sid:238131007 275947003[count>0] |-0.078| 1.135 [1.077, 1.197]| 1496.0 | 1443157.0 | 88930.0 | 21382.0 | 0.504| 
| 48 | Diagnosis:Clinical imaging sid:363679005 169283005[count>2] |0.077| 1.442 [1.378, 1.510]| 2042.0 | 1434601.0 | 97486.0 | 20836.0 | 0.513| 
| 49 | demographics_RACE_Other Race |0.077| 0.864 [0.824, 0.905]| 1946.0 | 1383201.0 | 148886.0 | 20932.0 | 0.494| 
| 50 | Diagnosis:Structure of genitourinary system sid:21514008 278861008[count>0] |0.076| 1.604 [1.560, 1.650]| 7351.0 | 1182954.0 | 349133.0 | 15527.0 | 0.547| 
| 51 | Diagnosis:Soft tissue disorder sid:19660004 238981002[count>0] |0.076| 1.935 [1.885, 1.986]| 11212.0 | 1023682.0 | 508405.0 | 11666.0 | 0.579| 
| 52 | Diagnosis:Neoplasm and/or hamartoma sid:399981008 55342001[count>0] |0.076| 2.471 [2.400, 2.544]| 6373.0 | 1325021.0 | 207066.0 | 16505.0 | 0.572| 
| 53 | Diagnosis:Malignant neoplasm, primary sid:86049000 10069009[count>0] |0.074| 2.706 [2.547, 2.874]| 1151.0 | 1502664.0 | 29423.0 | 21727.0 | 0.516| 
| 54 | Diagnosis:Hearing observations sid:118230007 247284004[count>0] |0.071| 1.711 [1.601, 1.829]| 920.0 | 1495472.0 | 36615.0 | 21958.0 | 0.508| 
| 55 | demographics_age[between_30_and_40] |-0.071| 0.900 [0.862, 0.941]| 2234.0 | 1367713.0 | 164374.0 | 20644.0 | 0.495| 
| 56 | Diagnosis:Neoplasm (morphologic abnormality) sid:108369006 253061008[count>0] |0.070| 2.427 [2.360, 2.497]| 7154.0 | 1290259.0 | 241828.0 | 15724.0 | 0.577| 
| 57 | Diagnosis:Benign neoplasm of intra-abdominal organs (disorder) sid:92153000 91958007[count>0] |-0.069| 1.572 [1.488, 1.661]| 1378.0 | 1472061.0 | 60026.0 | 21500.0 | 0.511| 
| 58 | Diagnosis:Procedure on body system (procedure) sid:118664000 284366008[count>0] |-0.069| 0.885 [0.858, 0.912]| 5287.0 | 1143536.0 | 388551.0 | 17591.0 | 0.489| 
| 59 | Diagnosis:Anatomical or acquired body structure sid:442083009 91723000[count>0] |-0.069| 1.425 [1.330, 1.527]| 22036.0 | 79111.0 | 1452976.0 | 842.0 | 0.507| 
