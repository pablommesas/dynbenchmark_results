# cellrouter
![Overview](cellrouter.png)

## ERROR STATUS EXECUTION_ERROR

### ERROR CLUSTER EXECUTION_ERROR -- 1
![Cluster plot](error_class_plots/cellrouter_execution_error_1.png)

 * Number of instances: 1
 * Dataset ids: scaling_0649

Last 10 lines of scaling_0649:
```
File: /home/rcannood/Workspace/dynverse/dynbenchmark//derived/05-scaling/suite/cellrouter/Cat1/r2gridengine/20181008_142039_cellrouter_Cat1_JlIuC23pBP/log/log.649.e.txt
In addition: Warning message:
In babelwhale::get_label(container_id, "version") : [31m(B[m[31m(B[m
mktemp: failed to create directory via template ‘/data/tmp//.singularity-inspect.XXXXXXXX’: No space left on device
ERROR: Failed to create temporary directory
ABORT: Aborting with RETVAL=255
Execution halted
```

## ERROR STATUS METHOD_ERROR

### ERROR CLUSTER METHOD_ERROR -- 1
![Cluster plot](error_class_plots/cellrouter_method_error_1.png)

 * Number of instances: 55
 * Dataset ids: scaling_0001, scaling_0002, scaling_0003, scaling_0004, scaling_0007, scaling_0009, scaling_0011, scaling_0013, scaling_0015, scaling_0027, scaling_0030, scaling_0048, scaling_0050, scaling_0070, scaling_0075, scaling_0105, scaling_0215, scaling_0255, scaling_0330, scaling_0680, scaling_0697, scaling_0837, scaling_0855, scaling_0899, scaling_0994, scaling_1008, scaling_1022, scaling_1036, scaling_1050, scaling_1069, scaling_1107, scaling_1126, scaling_1145, scaling_1181, scaling_1197, scaling_1213, scaling_1229, scaling_1245, scaling_1296, scaling_1338, scaling_1359, scaling_1452, scaling_1464, scaling_1476, scaling_1488, scaling_1500, scaling_1549, scaling_1568, scaling_1587, scaling_1606, scaling_1625, scaling_1647, scaling_1691, scaling_1713, scaling_1735

Last 10 lines of scaling_0001:
```
[1] "Initializing CellRouter object"
Loading required package: Matrix
Attaching package: ‘Matrix’
The following object is masked from ‘package:reshape’:
    expand
Warning in irlba(A = t(object@scale.data[genes.use, ]), nv = num.pcs) :
  You're computing too large a percentage of total singular values, use a standard svd instead.
Error in pca$cell.embeddings[, 1:num.pcs] : subscript out of bounds
Calls: tryCatch -> tryCatchList -> tryCatchOne -> <Anonymous>
Execution halted
```

### ERROR CLUSTER METHOD_ERROR -- 2
![Cluster plot](error_class_plots/cellrouter_method_error_2.png)

 * Number of instances: 219
 * Dataset ids: scaling_0006, scaling_0008, scaling_0010, scaling_0012, scaling_0016, scaling_0019, scaling_0022, scaling_0025, scaling_0031, scaling_0033, scaling_0035, scaling_0037, scaling_0039, scaling_0041, scaling_0043, scaling_0045, scaling_0047, scaling_0051, scaling_0052, scaling_0056, scaling_0057, scaling_0061, scaling_0062, scaling_0066, scaling_0067, scaling_0072, scaling_0076, scaling_0077, scaling_0082, scaling_0083, scaling_0088, scaling_0089, scaling_0094, scaling_0095, scaling_0101, scaling_0106, scaling_0107, scaling_0113, scaling_0114, scaling_0120, scaling_0121, scaling_0127, scaling_0128, scaling_0135, scaling_0151, scaling_0152, scaling_0157, scaling_0158, scaling_0163, scaling_0164, scaling_0169, scaling_0170, scaling_0176, scaling_0181, scaling_0188, scaling_0195, scaling_0202, scaling_0216, scaling_0218, scaling_0220, scaling_0222, scaling_0224, scaling_0226, scaling_0227, scaling_0232, scaling_0233, scaling_0238, scaling_0239, scaling_0244, scaling_0245, scaling_0251, scaling_0276, scaling_0277, scaling_0287, scaling_0288, scaling_0298, scaling_0299, scaling_0309, scaling_0310, scaling_0321, scaling_0341, scaling_0342, scaling_0351, scaling_0352, scaling_0361, scaling_0362, scaling_0371, scaling_0372, scaling_0382, scaling_0391, scaling_0392, scaling_0404, scaling_0405, scaling_0417, scaling_0418, scaling_0430, scaling_0431, scaling_0444, scaling_0456, scaling_0466, scaling_0476, scaling_0486, scaling_0506, scaling_0510, scaling_0514, scaling_0518, scaling_0522, scaling_0526, scaling_0532, scaling_0538, scaling_0544, scaling_0550, scaling_0556, scaling_0565, scaling_0574, scaling_0583, scaling_0601, scaling_0602, scaling_0617, scaling_0618, scaling_0633, scaling_0634, scaling_0650, scaling_0666, scaling_0681, scaling_0682, scaling_0698, scaling_0699, scaling_0715, scaling_0716, scaling_0732, scaling_0733, scaling_0750, scaling_0766, scaling_0767, scaling_0784, scaling_0785, scaling_0802, scaling_0803, scaling_0820, scaling_0821, scaling_0839, scaling_0856, scaling_0867, scaling_0878, scaling_0889, scaling_0911, scaling_0919, scaling_0927, scaling_0935, scaling_0943, scaling_0951, scaling_0957, scaling_0963, scaling_0969, scaling_0975, scaling_0981, scaling_0995, scaling_1009, scaling_1023, scaling_1051, scaling_1070, scaling_1089, scaling_1108, scaling_1146, scaling_1148, scaling_1150, scaling_1152, scaling_1154, scaling_1166, scaling_1167, scaling_1182, scaling_1183, scaling_1198, scaling_1199, scaling_1214, scaling_1215, scaling_1231, scaling_1276, scaling_1277, scaling_1297, scaling_1298, scaling_1318, scaling_1319, scaling_1339, scaling_1340, scaling_1361, scaling_1441, scaling_1442, scaling_1453, scaling_1454, scaling_1465, scaling_1466, scaling_1477, scaling_1478, scaling_1490, scaling_1531, scaling_1532, scaling_1550, scaling_1551, scaling_1569, scaling_1570, scaling_1588, scaling_1589, scaling_1608, scaling_1626, scaling_1648, scaling_1670, scaling_1692, scaling_1736, scaling_1740, scaling_1744, scaling_1748, scaling_1752, scaling_1766, scaling_1781, scaling_1796, scaling_1811, scaling_1826

Last 10 lines of scaling_0006:
```
    union
[1] "Initializing CellRouter object"
Loading required package: Matrix
Attaching package: ‘Matrix’
The following object is masked from ‘package:reshape’:
    expand
Error in irlba(A = t(object@scale.data[genes.use, ]), nv = num.pcs) : 
  max(nu, nv) must be strictly less than min(nrow(A), ncol(A))
Calls: computePCA -> computePCA -> irlba
Execution halted
```

### ERROR CLUSTER METHOD_ERROR -- 3
![Cluster plot](error_class_plots/cellrouter_method_error_3.png)

 * Number of instances: 3
 * Dataset ids: scaling_0017, scaling_0020, scaling_0023

Last 10 lines of scaling_0017:
```
[1] "building k-nearest neighbors graph"
[1] "updating CellRouter object"
Warning message:
In write.graph.gml(graph, file, ...) :
  At foreign.c:2616 :A boolean graph attribute was converted to numeric
Error in `[.data.frame`(b[[i]][[j]], , "merge") : 
  undefined columns selected
Calls: findPaths -> findPaths -> as.vector -> [ -> [.data.frame
In addition: There were 15 warnings (use warnings() to see them)
Execution halted
```

### ERROR CLUSTER METHOD_ERROR -- 4
![Cluster plot](error_class_plots/cellrouter_method_error_4.png)

 * Number of instances: 72
 * Dataset ids: scaling_0018, scaling_0021, scaling_0024, scaling_0042, scaling_0044, scaling_0046, scaling_0055, scaling_0060, scaling_0065, scaling_0081, scaling_0087, scaling_0093, scaling_0099, scaling_0112, scaling_0119, scaling_0126, scaling_0133, scaling_0140, scaling_0156, scaling_0162, scaling_0168, scaling_0174, scaling_0180, scaling_0187, scaling_0194, scaling_0201, scaling_0208, scaling_0231, scaling_0237, scaling_0243, scaling_0249, scaling_0286, scaling_0297, scaling_0308, scaling_0319, scaling_0350, scaling_0360, scaling_0370, scaling_0380, scaling_0390, scaling_0403, scaling_0416, scaling_0429, scaling_0442, scaling_0455, scaling_0465, scaling_0475, scaling_0485, scaling_0495, scaling_0505, scaling_0564, scaling_0573, scaling_0582, scaling_0591, scaling_0632, scaling_0648, scaling_0664, scaling_0714, scaling_0731, scaling_0748, scaling_0765, scaling_0783, scaling_0801, scaling_0819, scaling_0866, scaling_0877, scaling_0888, scaling_0910, scaling_1088, scaling_1317, scaling_1380, scaling_1669

Last 10 lines of scaling_0018:
```
Attaching package: ‘Matrix’
The following object is masked from ‘package:reshape’:
    expand
Warning in irlba(A = t(object@scale.data[genes.use, ]), nv = num.pcs) :
  You're computing too large a percentage of total singular values, use a standard svd instead.
Warning in irlba(A = t(object@scale.data[genes.use, ]), nv = num.pcs) :
  did not converge--results might be invalid!; try increasing work or maxit
Error in pca$cell.embeddings[, 1:num.pcs] : subscript out of bounds
Calls: tryCatch -> tryCatchList -> tryCatchOne -> <Anonymous>
Execution halted
```

### ERROR CLUSTER METHOD_ERROR -- 5
![Cluster plot](error_class_plots/cellrouter_method_error_5.png)

 * Number of instances: 27
 * Dataset ids: scaling_0026, scaling_0029, scaling_0038, scaling_0040, scaling_0068, scaling_0069, scaling_0073, scaling_0074, scaling_0080, scaling_0092, scaling_0097, scaling_0098, scaling_0102, scaling_0103, scaling_0104, scaling_0131, scaling_0136, scaling_0137, scaling_0138, scaling_0149, scaling_0177, scaling_0178, scaling_0211, scaling_0212, scaling_0252, scaling_0324, scaling_0384

Last 10 lines of scaling_0026:
```
TSNE: Perplexity is too large. Reducing perplexity by 25%: 22.5 -> 16.875
TSNE: Perplexity is too large. Reducing perplexity by 25%: 16.875 -> 12.65625
TSNE: Perplexity is too large. Reducing perplexity by 25%: 12.65625 -> 9.492188
TSNE: Perplexity is too large. Reducing perplexity by 25%: 9.492188 -> 7.119141
TSNE: Perplexity is too large. Reducing perplexity by 25%: 7.119141 -> 5.339355
TSNE: Perplexity is too large. Reducing perplexity by 25%: 5.339355 -> 4.004517
Error in Rtsne.default(pca$cell.embeddings[, 1:num.pcs], perplexity = perplexity,  : 
  Remove duplicates before running TSNE.
Calls: tryCatch -> tryCatchList -> tryCatchOne -> <Anonymous>
Execution halted
```

### ERROR CLUSTER METHOD_ERROR -- 6
![Cluster plot](error_class_plots/cellrouter_method_error_6.png)

 * Number of instances: 204
 * Dataset ids: scaling_0032, scaling_0034, scaling_0036, scaling_0053, scaling_0054, scaling_0058, scaling_0063, scaling_0078, scaling_0084, scaling_0090, scaling_0096, scaling_0108, scaling_0115, scaling_0122, scaling_0129, scaling_0130, scaling_0141, scaling_0143, scaling_0145, scaling_0147, scaling_0153, scaling_0165, scaling_0171, scaling_0182, scaling_0183, scaling_0189, scaling_0196, scaling_0197, scaling_0203, scaling_0204, scaling_0210, scaling_0256, scaling_0257, scaling_0260, scaling_0264, scaling_0265, scaling_0268, scaling_0269, scaling_0272, scaling_0273, scaling_0278, scaling_0279, scaling_0289, scaling_0300, scaling_0301, scaling_0311, scaling_0312, scaling_0322, scaling_0323, scaling_0331, scaling_0333, scaling_0335, scaling_0337, scaling_0339, scaling_0343, scaling_0363, scaling_0373, scaling_0383, scaling_0393, scaling_0394, scaling_0406, scaling_0419, scaling_0420, scaling_0432, scaling_0433, scaling_0445, scaling_0446, scaling_0457, scaling_0458, scaling_0467, scaling_0477, scaling_0478, scaling_0487, scaling_0488, scaling_0497, scaling_0498, scaling_0557, scaling_0558, scaling_0566, scaling_0575, scaling_0576, scaling_0584, scaling_0585, scaling_0593, scaling_0594, scaling_0603, scaling_0619, scaling_0635, scaling_0636, scaling_0651, scaling_0652, scaling_0667, scaling_0668, scaling_0683, scaling_0684, scaling_0700, scaling_0717, scaling_0718, scaling_0734, scaling_0735, scaling_0751, scaling_0752, scaling_0768, scaling_0769, scaling_0786, scaling_0804, scaling_0805, scaling_0822, scaling_0823, scaling_0840, scaling_0841, scaling_0857, scaling_0858, scaling_0868, scaling_0879, scaling_0880, scaling_0890, scaling_0891, scaling_0901, scaling_0902, scaling_0982, scaling_0983, scaling_0996, scaling_1010, scaling_1011, scaling_1024, scaling_1025, scaling_1038, scaling_1039, scaling_1052, scaling_1053, scaling_1071, scaling_1090, scaling_1091, scaling_1109, scaling_1110, scaling_1128, scaling_1129, scaling_1156, scaling_1160, scaling_1162, scaling_1164, scaling_1246, scaling_1250, scaling_1254, scaling_1258, scaling_1262, scaling_1278, scaling_1279, scaling_1299, scaling_1320, scaling_1321, scaling_1341, scaling_1342, scaling_1362, scaling_1363, scaling_1381, scaling_1382, scaling_1393, scaling_1405, scaling_1406, scaling_1417, scaling_1418, scaling_1429, scaling_1430, scaling_1533, scaling_1534, scaling_1552, scaling_1571, scaling_1572, scaling_1590, scaling_1591, scaling_1609, scaling_1610, scaling_1627, scaling_1628, scaling_1649, scaling_1671, scaling_1672, scaling_1693, scaling_1715, scaling_1716, scaling_1841, scaling_1842, scaling_1849, scaling_1857, scaling_1858, scaling_1865, scaling_1866, scaling_1873, scaling_1874, scaling_1891, scaling_1892, scaling_1913, scaling_1935, scaling_1936, scaling_1957, scaling_1958, scaling_1979, scaling_1980, scaling_2001, scaling_2017, scaling_2025, scaling_2033

Last 10 lines of scaling_0032:
```
The following objects are masked from ‘package:stats’:
    as.dist, dist
The following object is masked from ‘package:base’:
    as.matrix
[1] "building k-nearest neighbors graph"
[1] "discoverying subpopulation structure"
Error in rgb(xt[1], xt[2], xt[3], maxColorValue = 255) : 
  color intensity NA, not in 0:255
Calls: findClusters ... graphClustering -> cRampClust -> apply -> FUN -> rgb
Execution halted
```

### ERROR CLUSTER METHOD_ERROR -- 7
![Cluster plot](error_class_plots/cellrouter_method_error_7.png)

 * Number of instances: 383
 * Dataset ids: scaling_0059, scaling_0064, scaling_0085, scaling_0086, scaling_0109, scaling_0110, scaling_0116, scaling_0117, scaling_0118, scaling_0123, scaling_0124, scaling_0142, scaling_0144, scaling_0146, scaling_0154, scaling_0159, scaling_0160, scaling_0161, scaling_0166, scaling_0172, scaling_0184, scaling_0185, scaling_0186, scaling_0191, scaling_0192, scaling_0193, scaling_0198, scaling_0199, scaling_0200, scaling_0205, scaling_0219, scaling_0229, scaling_0234, scaling_0236, scaling_0240, scaling_0246, scaling_0259, scaling_0261, scaling_0262, scaling_0263, scaling_0280, scaling_0281, scaling_0282, scaling_0283, scaling_0284, scaling_0290, scaling_0291, scaling_0292, scaling_0293, scaling_0294, scaling_0295, scaling_0296, scaling_0302, scaling_0303, scaling_0305, scaling_0306, scaling_0313, scaling_0314, scaling_0315, scaling_0332, scaling_0334, scaling_0336, scaling_0344, scaling_0345, scaling_0346, scaling_0347, scaling_0348, scaling_0353, scaling_0354, scaling_0355, scaling_0356, scaling_0357, scaling_0358, scaling_0359, scaling_0364, scaling_0365, scaling_0366, scaling_0367, scaling_0368, scaling_0374, scaling_0375, scaling_0376, scaling_0395, scaling_0398, scaling_0399, scaling_0400, scaling_0401, scaling_0407, scaling_0408, scaling_0409, scaling_0410, scaling_0411, scaling_0412, scaling_0415, scaling_0421, scaling_0422, scaling_0423, scaling_0424, scaling_0425, scaling_0426, scaling_0427, scaling_0434, scaling_0435, scaling_0436, scaling_0437, scaling_0459, scaling_0460, scaling_0461, scaling_0462, scaling_0463, scaling_0464, scaling_0468, scaling_0469, scaling_0470, scaling_0471, scaling_0472, scaling_0473, scaling_0474, scaling_0479, scaling_0480, scaling_0481, scaling_0483, scaling_0484, scaling_0489, scaling_0490, scaling_0491, scaling_0500, scaling_0507, scaling_0511, scaling_0512, scaling_0513, scaling_0516, scaling_0519, scaling_0523, scaling_0527, scaling_0528, scaling_0533, scaling_0535, scaling_0536, scaling_0539, scaling_0540, scaling_0541, scaling_0547, scaling_0551, scaling_0552, scaling_0559, scaling_0560, scaling_0561, scaling_0562, scaling_0567, scaling_0568, scaling_0570, scaling_0577, scaling_0578, scaling_0579, scaling_0580, scaling_0581, scaling_0586, scaling_0587, scaling_0588, scaling_0595, scaling_0605, scaling_0606, scaling_0608, scaling_0609, scaling_0610, scaling_0611, scaling_0612, scaling_0620, scaling_0621, scaling_0622, scaling_0623, scaling_0626, scaling_0627, scaling_0628, scaling_0638, scaling_0639, scaling_0641, scaling_0642, scaling_0643, scaling_0644, scaling_0645, scaling_0654, scaling_0656, scaling_0657, scaling_0658, scaling_0669, scaling_0672, scaling_0673, scaling_0688, scaling_0703, scaling_0724, scaling_0791, scaling_0808, scaling_0863, scaling_0872, scaling_0881, scaling_0920, scaling_0928, scaling_0964, scaling_0984, scaling_1013, scaling_1043, scaling_1058, scaling_1060, scaling_1072, scaling_1073, scaling_1094, scaling_1099, scaling_1158, scaling_1168, scaling_1172, scaling_1173, scaling_1184, scaling_1185, scaling_1188, scaling_1190, scaling_1202, scaling_1205, scaling_1207, scaling_1216, scaling_1218, scaling_1219, scaling_1220, scaling_1232, scaling_1233, scaling_1234, scaling_1236, scaling_1238, scaling_1247, scaling_1256, scaling_1259, scaling_1268, scaling_1270, scaling_1272, scaling_1274, scaling_1281, scaling_1283, scaling_1300, scaling_1301, scaling_1302, scaling_1305, scaling_1322, scaling_1323, scaling_1324, scaling_1325, scaling_1329, scaling_1343, scaling_1344, scaling_1345, scaling_1364, scaling_1366, scaling_1367, scaling_1368, scaling_1369, scaling_1370, scaling_1373, scaling_1383, scaling_1384, scaling_1394, scaling_1395, scaling_1397, scaling_1398, scaling_1407, scaling_1408, scaling_1409, scaling_1420, scaling_1421, scaling_1422, scaling_1431, scaling_1435, scaling_1443, scaling_1444, scaling_1455, scaling_1456, scaling_1458, scaling_1467, scaling_1468, scaling_1470, scaling_1479, scaling_1480, scaling_1482, scaling_1491, scaling_1492, scaling_1493, scaling_1494, scaling_1495, scaling_1501, scaling_1503, scaling_1507, scaling_1513, scaling_1515, scaling_1519, scaling_1520, scaling_1521, scaling_1526, scaling_1535, scaling_1536, scaling_1537, scaling_1553, scaling_1558, scaling_1574, scaling_1575, scaling_1592, scaling_1593, scaling_1594, scaling_1629, scaling_1633, scaling_1635, scaling_1652, scaling_1675, scaling_1680, scaling_1694, scaling_1697, scaling_1698, scaling_1699, scaling_1718, scaling_1720, scaling_1721, scaling_1722, scaling_1741, scaling_1762, scaling_1764, scaling_1767, scaling_1768, scaling_1769, scaling_1772, scaling_1782, scaling_1783, scaling_1787, scaling_1797, scaling_1798, scaling_1799, scaling_1801, scaling_1812, scaling_1814, scaling_1815, scaling_1851, scaling_1859, scaling_1860, scaling_1875, scaling_1885, scaling_1887, scaling_1893, scaling_1894, scaling_1914, scaling_1916, scaling_1917, scaling_1937, scaling_1938, scaling_1939, scaling_1960, scaling_1962, scaling_1963, scaling_1981, scaling_1982, scaling_1983, scaling_1987, scaling_1988, scaling_2009, scaling_2018, scaling_2027, scaling_2041, scaling_2042, scaling_2043, scaling_2045, scaling_2047, scaling_2056, scaling_2057, scaling_2061, scaling_2071, scaling_2072, scaling_2073, scaling_2074, scaling_2086, scaling_2087, scaling_2088, scaling_2089, scaling_2146, scaling_2166, scaling_2194, scaling_2195, scaling_2197

Last 10 lines of scaling_0059:
```
path size before: 23
path size after: 23
Subnet size: 22
merging: Cells_FlowNetwork_all_paths_subnet_exportGML.R
[1] "parsing trajectory information"
[1] 3
Error in igraph::induced.subgraph(graph = g, vids = unlist(igraph::neighborhood(graph = g,  : 
  Not a graph object
Calls: processTrajectories ... processTrajectories -> pathsinfo -> pathsinfo -> <Anonymous>
Execution halted
```

### ERROR CLUSTER METHOD_ERROR -- 8
![Cluster plot](error_class_plots/cellrouter_method_error_8.png)

 * Number of instances: 57
 * Dataset ids: scaling_0111, scaling_0125, scaling_0132, scaling_0155, scaling_0167, scaling_0173, scaling_0217, scaling_0221, scaling_0223, scaling_0230, scaling_0242, scaling_0248, scaling_0254, scaling_0285, scaling_0307, scaling_0318, scaling_0329, scaling_0349, scaling_0369, scaling_0379, scaling_0389, scaling_0402, scaling_0428, scaling_0441, scaling_0454, scaling_0509, scaling_0517, scaling_0521, scaling_0525, scaling_0531, scaling_0543, scaling_0549, scaling_0555, scaling_0615, scaling_0647, scaling_0663, scaling_0679, scaling_0696, scaling_0730, scaling_0747, scaling_0764, scaling_0782, scaling_0818, scaling_0836, scaling_0854, scaling_0918, scaling_0934, scaling_0942, scaling_0950, scaling_0956, scaling_0974, scaling_0980, scaling_1147, scaling_1153, scaling_1228, scaling_1358, scaling_1548

Last 10 lines of scaling_0111:
```
The following object is masked from ‘package:reshape’:
    expand
Warning in irlba(A = t(object@scale.data[genes.use, ]), nv = num.pcs) :
  You're computing too large a percentage of total singular values, use a standard svd instead.
Warning in irlba(A = t(object@scale.data[genes.use, ]), nv = num.pcs) :
  did not converge--results might be invalid!; try increasing work or maxit
Error in Rtsne.default(pca$cell.embeddings[, 1:num.pcs], perplexity = perplexity,  : 
  Remove duplicates before running TSNE.
Calls: tryCatch -> tryCatchList -> tryCatchOne -> <Anonymous>
Execution halted
```

### ERROR CLUSTER METHOD_ERROR -- 9
![Cluster plot](error_class_plots/cellrouter_method_error_9.png)

 * Number of instances: 127
 * Dataset ids: scaling_0139, scaling_0148, scaling_0150, scaling_0179, scaling_0206, scaling_0207, scaling_0213, scaling_0214, scaling_0225, scaling_0270, scaling_0271, scaling_0274, scaling_0275, scaling_0316, scaling_0317, scaling_0327, scaling_0328, scaling_0338, scaling_0340, scaling_0378, scaling_0388, scaling_0439, scaling_0440, scaling_0452, scaling_0453, scaling_0493, scaling_0494, scaling_0503, scaling_0504, scaling_0589, scaling_0590, scaling_0598, scaling_0599, scaling_0661, scaling_0662, scaling_0677, scaling_0678, scaling_0745, scaling_0746, scaling_0762, scaling_0763, scaling_0781, scaling_0817, scaling_0834, scaling_0835, scaling_0852, scaling_0853, scaling_0865, scaling_0887, scaling_0897, scaling_0898, scaling_0908, scaling_0909, scaling_0968, scaling_1034, scaling_1035, scaling_1048, scaling_1049, scaling_1124, scaling_1125, scaling_1143, scaling_1144, scaling_1151, scaling_1155, scaling_1163, scaling_1165, scaling_1180, scaling_1212, scaling_1244, scaling_1261, scaling_1265, scaling_1294, scaling_1295, scaling_1336, scaling_1337, scaling_1356, scaling_1357, scaling_1377, scaling_1378, scaling_1379, scaling_1392, scaling_1416, scaling_1427, scaling_1428, scaling_1439, scaling_1440, scaling_1451, scaling_1475, scaling_1487, scaling_1499, scaling_1547, scaling_1585, scaling_1586, scaling_1603, scaling_1604, scaling_1605, scaling_1622, scaling_1623, scaling_1624, scaling_1646, scaling_1690, scaling_1711, scaling_1712, scaling_1733, scaling_1734, scaling_1739, scaling_1747, scaling_1751, scaling_1755, scaling_1780, scaling_1810, scaling_1825, scaling_1840, scaling_1848, scaling_1864, scaling_1871, scaling_1872, scaling_1879, scaling_1880, scaling_1912, scaling_1956, scaling_1977, scaling_1978, scaling_1999, scaling_2000, scaling_2032, scaling_2040

Last 10 lines of scaling_0139:
```
Loading required package: Matrix
Attaching package: ‘Matrix’
The following object is masked from ‘package:reshape’:
    expand
Warning in irlba(A = t(object@scale.data[genes.use, ]), nv = num.pcs) :
  You're computing too large a percentage of total singular values, use a standard svd instead.
Error in Rtsne.default(pca$cell.embeddings[, 1:num.pcs], perplexity = perplexity,  : 
  Remove duplicates before running TSNE.
Calls: tryCatch -> tryCatchList -> tryCatchOne -> <Anonymous>
Execution halted
```

### ERROR CLUSTER METHOD_ERROR -- 10
![Cluster plot](error_class_plots/cellrouter_method_error_10.png)

 * Number of instances: 115
 * Dataset ids: scaling_0253, scaling_0325, scaling_0326, scaling_0377, scaling_0385, scaling_0386, scaling_0387, scaling_0438, scaling_0448, scaling_0449, scaling_0450, scaling_0451, scaling_0492, scaling_0501, scaling_0502, scaling_0548, scaling_0553, scaling_0554, scaling_0596, scaling_0597, scaling_0660, scaling_0674, scaling_0675, scaling_0676, scaling_0743, scaling_0744, scaling_0758, scaling_0759, scaling_0760, scaling_0761, scaling_0832, scaling_0833, scaling_0848, scaling_0849, scaling_0850, scaling_0851, scaling_0896, scaling_0907, scaling_0941, scaling_0947, scaling_0948, scaling_0949, scaling_0973, scaling_0979, scaling_1033, scaling_1045, scaling_1046, scaling_1047, scaling_1122, scaling_1123, scaling_1139, scaling_1140, scaling_1141, scaling_1142, scaling_1226, scaling_1227, scaling_1241, scaling_1242, scaling_1243, scaling_1264, scaling_1273, scaling_1275, scaling_1355, scaling_1374, scaling_1375, scaling_1376, scaling_1426, scaling_1437, scaling_1438, scaling_1486, scaling_1496, scaling_1497, scaling_1498, scaling_1524, scaling_1529, scaling_1530, scaling_1602, scaling_1619, scaling_1620, scaling_1621, scaling_1709, scaling_1710, scaling_1729, scaling_1730, scaling_1731, scaling_1732, scaling_1754, scaling_1765, scaling_1823, scaling_1824, scaling_1837, scaling_1838, scaling_1839, scaling_1878, scaling_1975, scaling_1976, scaling_1994, scaling_1995, scaling_1996, scaling_1997, scaling_1998, scaling_2039, scaling_2099, scaling_2100, scaling_2112, scaling_2113, scaling_2114, scaling_2115, scaling_2139, scaling_2145, scaling_2209, scaling_2222, scaling_2223, scaling_2224, scaling_2225

Last 10 lines of scaling_0253:
```
    union
[1] "Initializing CellRouter object"
Loading required package: Matrix
Attaching package: ‘Matrix’
The following object is masked from ‘package:reshape’:
    expand
Error in Rtsne.default(pca$cell.embeddings[, 1:num.pcs], perplexity = perplexity,  : 
  Remove duplicates before running TSNE.
Calls: tryCatch -> tryCatchList -> tryCatchOne -> <Anonymous>
Execution halted
```

### ERROR CLUSTER METHOD_ERROR -- 11
![Cluster plot](error_class_plots/cellrouter_method_error_11.png)

 * Number of instances: 3
 * Dataset ids: scaling_0447, scaling_0499, scaling_1556

Last 10 lines of scaling_0447:
```
[1] "building k-nearest neighbors graph"
[1] "updating CellRouter object"
Warning message:
In write.graph.gml(graph, file, ...) :
  At foreign.c:2616 :A boolean graph attribute was converted to numeric
[1] "parsing trajectory information"
Error in complete.cases(paths) : 
  no input has determined the number of cases
Calls: processTrajectories -> processTrajectories -> complete.cases
Execution halted
```

### ERROR CLUSTER METHOD_ERROR -- 12
![Cluster plot](error_class_plots/cellrouter_method_error_12.png)

 * Number of instances: 1
 * Dataset ids: scaling_0614

Last 10 lines of scaling_0614:
```
  At foreign.c:2616 :A boolean graph attribute was converted to numeric
[1] "building k-nearest neighbors graph"
[1] "updating CellRouter object"
Error in write.graph.gml(graph, file, ...) : 
  At foreign.c:2702 : Write failed, File operation error
Calls: buildKNN -> buildKNN -> write.graph -> write.graph.gml
In addition: Warning message:
In write.graph.gml(graph, file, ...) :
  At foreign.c:2616 :A boolean graph attribute was converted to numeric
Execution halted
```

### ERROR CLUSTER METHOD_ERROR -- 13
![Cluster plot](error_class_plots/cellrouter_method_error_13.png)

 * Number of instances: 4
 * Dataset ids: scaling_1000, scaling_1251, scaling_1303, scaling_1457

Last 10 lines of scaling_1000:
```
[1] "parsing trajectory information"
Cells_FlowNetwork_all_paths_subnet.gml 
Cells_FlowNetwork_all_paths_subnet.gml 
Cells_FlowNetwork_all_paths_subnet.gml 
Cells_FlowNetwork_all_paths_subnet.gml 
Cells_FlowNetwork_all_paths_subnet.gml 
Error in `$<-.data.frame`(`*tmp*`, "ID", value = c("path_1", "path_0")) : 
  replacement has 2 rows, data has 0
Calls: processTrajectories -> processTrajectories -> $<- -> $<-.data.frame
Execution halted
```

### ERROR CLUSTER METHOD_ERROR -- 14
![Cluster plot](error_class_plots/cellrouter_method_error_14.png)

 * Number of instances: 22
 * Dataset ids: scaling_1149, scaling_1249, scaling_1253, scaling_1257, scaling_1293, scaling_1314, scaling_1335, scaling_1450, scaling_1462, scaling_1474, scaling_1545, scaling_1564, scaling_1583, scaling_1738, scaling_1742, scaling_1746, scaling_1846, scaling_1854, scaling_1862, scaling_2051, scaling_2081, scaling_2111

Last 10 lines of scaling_1149:
```
    as.matrix
The following objects are masked from ‘package:stats’:
    as.dist, dist
The following object is masked from ‘package:base’:
    as.matrix
[1] "building k-nearest neighbors graph"
Error in do.call(".Call", c(list(method), list(x), list(y), pairwise,  : 
  negative length vectors are not allowed
Calls: findClusters ... as.matrix -> <Anonymous> -> dist -> do.call -> .Call
Execution halted
```

## ERROR STATUS TIME_LIMIT

### ERROR CLUSTER TIME_LIMIT -- 1
![Cluster plot](error_class_plots/cellrouter_time_limit_1.png)

 * Number of instances: 141
 * Dataset ids: scaling_1196, scaling_1315, scaling_1316, scaling_1391, scaling_1403, scaling_1404, scaling_1415, scaling_1463, scaling_1506, scaling_1512, scaling_1518, scaling_1543, scaling_1546, scaling_1565, scaling_1566, scaling_1567, scaling_1584, scaling_1640, scaling_1643, scaling_1644, scaling_1645, scaling_1662, scaling_1665, scaling_1666, scaling_1667, scaling_1668, scaling_1684, scaling_1687, scaling_1688, scaling_1689, scaling_1706, scaling_1728, scaling_1743, scaling_1750, scaling_1775, scaling_1777, scaling_1778, scaling_1779, scaling_1790, scaling_1792, scaling_1793, scaling_1794, scaling_1795, scaling_1805, scaling_1807, scaling_1808, scaling_1809, scaling_1820, scaling_1822, scaling_1835, scaling_1847, scaling_1855, scaling_1856, scaling_1863, scaling_1870, scaling_1904, scaling_1906, scaling_1907, scaling_1908, scaling_1909, scaling_1910, scaling_1911, scaling_1926, scaling_1928, scaling_1929, scaling_1930, scaling_1931, scaling_1932, scaling_1933, scaling_1934, scaling_1948, scaling_1950, scaling_1951, scaling_1952, scaling_1953, scaling_1954, scaling_1955, scaling_1970, scaling_1972, scaling_1973, scaling_1974, scaling_1991, scaling_1992, scaling_2007, scaling_2008, scaling_2015, scaling_2016, scaling_2023, scaling_2024, scaling_2031, scaling_2052, scaling_2053, scaling_2054, scaling_2055, scaling_2066, scaling_2067, scaling_2068, scaling_2069, scaling_2070, scaling_2082, scaling_2083, scaling_2084, scaling_2085, scaling_2096, scaling_2097, scaling_2098, scaling_2120, scaling_2121, scaling_2126, scaling_2127, scaling_2132, scaling_2133, scaling_2138, scaling_2144, scaling_2157, scaling_2158, scaling_2159, scaling_2160, scaling_2161, scaling_2173, scaling_2174, scaling_2175, scaling_2176, scaling_2177, scaling_2189, scaling_2190, scaling_2191, scaling_2192, scaling_2193, scaling_2205, scaling_2206, scaling_2207, scaling_2208, scaling_2221, scaling_2240, scaling_2241, scaling_2242, scaling_2243, scaling_2244, scaling_2245, scaling_2246

Last 10 lines of scaling_1196:
```
File: /home/rcannood/Workspace/dynverse/dynbenchmark//derived/05-scaling/suite/cellrouter/Cat3/r2gridengine/20181010_161020_cellrouter_Cat3_vWTC8gMKBP/log/log.51.e.txt
```

## ERROR STATUS MEMORY_LIMIT

### ERROR CLUSTER MEMORY_LIMIT -- 1
![Cluster plot](error_class_plots/cellrouter_memory_limit_1.png)

 * Number of instances: 6
 * Dataset ids: scaling_0600, scaling_0604, scaling_0616, scaling_0637, scaling_0646, scaling_0653

Last 10 lines of scaling_0600:
```
error writing to connection
```

### ERROR CLUSTER MEMORY_LIMIT -- 2
![Cluster plot](error_class_plots/cellrouter_memory_limit_2.png)

 * Number of instances: 27
 * Dataset ids: scaling_0800, scaling_0876, scaling_0992, scaling_1006, scaling_1020, scaling_1066, scaling_1085, scaling_1104, scaling_1178, scaling_1194, scaling_1210, scaling_1291, scaling_1312, scaling_1333, scaling_1354, scaling_1448, scaling_1460, scaling_1472, scaling_1484, scaling_1562, scaling_1581, scaling_1600, scaling_2049, scaling_2064, scaling_2079, scaling_2094, scaling_2109

Last 10 lines of scaling_0800:
```
[1] "discoverying subpopulation structure"
[1] "updating CellRouter object"
Warning message:
In write.graph.gml(graph, file, ...) :
  At foreign.c:2616 :A boolean graph attribute was converted to numeric
[1] "building k-nearest neighbors graph"
Error in similarity.jaccard(h, vids = V(h), loops = FALSE) : 
  At vector.pmt:442 : cannot reserve space for vector, Out of memory
Calls: buildKNN -> buildKNN -> similarity.jaccard
Execution halted
```

### ERROR CLUSTER MEMORY_LIMIT -- 3
![Cluster plot](error_class_plots/cellrouter_memory_limit_3.png)

 * Number of instances: 87
 * Dataset ids: scaling_0926, scaling_0962, scaling_0993, scaling_1007, scaling_1021, scaling_1067, scaling_1068, scaling_1086, scaling_1087, scaling_1105, scaling_1106, scaling_1157, scaling_1159, scaling_1161, scaling_1179, scaling_1195, scaling_1211, scaling_1267, scaling_1269, scaling_1271, scaling_1292, scaling_1313, scaling_1334, scaling_1390, scaling_1402, scaling_1414, scaling_1449, scaling_1461, scaling_1473, scaling_1485, scaling_1505, scaling_1511, scaling_1517, scaling_1523, scaling_1544, scaling_1563, scaling_1582, scaling_1601, scaling_1641, scaling_1642, scaling_1663, scaling_1664, scaling_1685, scaling_1686, scaling_1707, scaling_1708, scaling_1757, scaling_1759, scaling_1761, scaling_1763, scaling_1776, scaling_1791, scaling_1806, scaling_1821, scaling_1836, scaling_1882, scaling_1884, scaling_1886, scaling_1888, scaling_1890, scaling_1905, scaling_1927, scaling_1949, scaling_1971, scaling_1993, scaling_2006, scaling_2014, scaling_2022, scaling_2030, scaling_2038, scaling_2050, scaling_2065, scaling_2080, scaling_2095, scaling_2110, scaling_2119, scaling_2125, scaling_2131, scaling_2137, scaling_2143, scaling_2156, scaling_2172, scaling_2188, scaling_2204, scaling_2220, scaling_2238, scaling_2239

Last 10 lines of scaling_0926:
```
Attaching package: ‘proxy’
The following object is masked from ‘package:Matrix’:
    as.matrix
The following objects are masked from ‘package:stats’:
    as.dist, dist
The following object is masked from ‘package:base’:
    as.matrix
[1] "building k-nearest neighbors graph"
Error: cannot allocate vector of size 2.4 Gb
Execution halted
```

### ERROR CLUSTER MEMORY_LIMIT -- 4
![Cluster plot](error_class_plots/cellrouter_memory_limit_4.png)

 * Number of instances: 6
 * Dataset ids: scaling_2155, scaling_2171, scaling_2187, scaling_2203, scaling_2219, scaling_2237

Last 10 lines of scaling_2155:
```
    as.matrix
The following objects are masked from ‘package:stats’:
    as.dist, dist
The following object is masked from ‘package:base’:
    as.matrix
[1] "building k-nearest neighbors graph"
Error in similarity.jaccard(h, vids = V(h), loops = FALSE) : 
  At vector.pmt:442 : cannot reserve space for vector, Out of memory
Calls: findClusters ... graphClustering -> graphClustering -> similarity.jaccard
Execution halted
```


