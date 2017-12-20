---
layout: post
rel_link:  "8_1_0_pre1"
title:  "CMSSW_8_1_0_pre1"
date:   2016-03-10 11:26:18
categories: cmssw
relmajor: 8
relminor: 1
relsubminor: 0
relpre: _pre1
---

# CMSSW_8_1_0_pre1
#### Changes since CMSSW_8_0_2:

[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_8_0_2...CMSSW_8_1_0_pre1)



1. [13667](http://github.com/cms-sw/cmssw/pull/13667){:target="_blank"}  from **@mdhildreth**: Add automatic turn-off of tracker digiSimLink production in standard production mode `simulation`  created: 2016-03-09 16:07:55 merged: 2016-03-10 09:41:50

2. [13662](http://github.com/cms-sw/cmssw/pull/13662){:target="_blank"}  from **@deguio**: add protection for T0 configuration query `dqm`  created: 2016-03-09 13:32:49 merged: 2016-03-09 17:01:47

3. [13658](http://github.com/cms-sw/cmssw/pull/13658){:target="_blank"}  from **@davidlt**: Do not use constexpr with std::log in C++14 for ICC `reconstruction`  created: 2016-03-09 10:28:21 merged: 2016-03-10 09:42:12

4. [13651](http://github.com/cms-sw/cmssw/pull/13651){:target="_blank"}  from **@davidlt**: Regenerate DQMServices/Core/src/ROOTFilePB.proto `comparison`  `dqm`  created: 2016-03-08 18:51:11 merged: 2016-03-08 18:58:19

5. [13645](http://github.com/cms-sw/cmssw/pull/13645){:target="_blank"}  from **@cms-tsg-storm**: Cummulative 80X PRs for 81X: (#13558 #13572 #13588 #13596 #13602 #13607 #13621) `alca`  `hlt`  `l1`  `reconstruction`  created: 2016-03-08 16:26:28 merged: 2016-03-10 09:56:01

6. [13643](http://github.com/cms-sw/cmssw/pull/13643){:target="_blank"}  from **@ghellwig**: Declare 'seedOnlyFromAbove_' as 'int'. `alca`  created: 2016-03-08 16:23:59 merged: 2016-03-09 13:08:04

7. [13642](http://github.com/cms-sw/cmssw/pull/13642){:target="_blank"}  from **@ahinzmann**: Add PU id working points to MiniAOD 8_1_X `analysis`  `reconstruction`  created: 2016-03-08 14:18:01 merged: 2016-03-09 16:28:12

8. [13638](http://github.com/cms-sw/cmssw/pull/13638){:target="_blank"}  from **@cms-sw**: Revert "Fix a minor error in DQM/L1TMonitor BuildFile" `comparison`  `dqm`  created: 2016-03-08 09:49:56 merged: 2016-03-08 09:50:01

9. [13634](http://github.com/cms-sw/cmssw/pull/13634){:target="_blank"}  from **@davidlt**: Misc cleanup for GCC 6 (missing header, integer overflow, wrong address usage, ..) `analysis`  `reconstruction`  created: 2016-03-08 08:56:38 merged: 2016-03-09 13:11:22

10. [13632](http://github.com/cms-sw/cmssw/pull/13632){:target="_blank"}  from **@davidlt**: Clean up ElectroWeakAnalysis (GCC 6) `analysis`  created: 2016-03-07 18:13:18 merged: 2016-03-07 19:20:05

11. [13631](http://github.com/cms-sw/cmssw/pull/13631){:target="_blank"}  from **@davidlt**: Clean up for GCC 6 (<cmath> header, std::, __afs cache files) `l1`  created: 2016-03-07 17:42:29 merged: 2016-03-08 08:55:29

12. [13630](http://github.com/cms-sw/cmssw/pull/13630){:target="_blank"}  from **@swang373**: EMTF DQM Module for CMSSW_8_1_X `dqm`  `l1`  created: 2016-03-07 17:09:04 merged: 2016-03-09 13:13:14

13. [13627](http://github.com/cms-sw/cmssw/pull/13627){:target="_blank"}  from **@mbandrews**: Fix binning in ZS filter SRTask plots `dqm`  created: 2016-03-07 15:54:16 merged: 2016-03-08 08:35:41

14. [13619](http://github.com/cms-sw/cmssw/pull/13619){:target="_blank"}  from **@dmitrijus**: Fix a minor error in DQM/L1TMonitor BuildFile `dqm`  created: 2016-03-07 09:19:51 merged: 2016-03-07 19:19:36

15. [13617](http://github.com/cms-sw/cmssw/pull/13617){:target="_blank"}  from **@dmitrijus**: Fix a small bug in an online DQM input source `dqm`  created: 2016-03-07 08:22:01 merged: 2016-03-07 19:19:20

16. [13616](http://github.com/cms-sw/cmssw/pull/13616){:target="_blank"}  from **@davidlt**: Use std::abs for enum (tauImpactParameter::PDGInfo::PDGMCNumbering) `reconstruction`  created: 2016-03-07 06:36:22 merged: 2016-03-07 10:13:23

17. [13615](http://github.com/cms-sw/cmssw/pull/13615){:target="_blank"}  from **@davidlt**: Add missing <vector> header `generators`  created: 2016-03-06 22:42:32 merged: 2016-03-07 09:10:46

18. [13614](http://github.com/cms-sw/cmssw/pull/13614){:target="_blank"}  from **@davidlt**: Add missing <cmath> header and remove <string.h> header `core`  created: 2016-03-06 22:35:32 merged: 2016-03-07 09:11:01

19. [13613](http://github.com/cms-sw/cmssw/pull/13613){:target="_blank"}  from **@davidlt**: Add missing <cassert> header `simulation`  created: 2016-03-06 22:27:51 merged: 2016-03-07 09:11:22

20. [13611](http://github.com/cms-sw/cmssw/pull/13611){:target="_blank"}  from **@davidlt**: Add missing <numeric> include for std::accumulate `reconstruction`  created: 2016-03-06 21:57:15 merged: 2016-03-08 08:55:54

21. [13610](http://github.com/cms-sw/cmssw/pull/13610){:target="_blank"}  from **@davidlt**: Add missing headers (GCC 6.0.0) `hlt`  created: 2016-03-06 21:44:53 merged: 2016-03-07 09:10:29

22. [13601](http://github.com/cms-sw/cmssw/pull/13601){:target="_blank"}  from **@makortel**: Remove 2017 fake conditions `geometry`  `simulation`  created: 2016-03-04 15:48:15 merged: 2016-03-07 09:12:38

23. [13600](http://github.com/cms-sw/cmssw/pull/13600){:target="_blank"}  from **@wmtan**: Enforce consumes interface in output modules `core`  `daq`  `dqm`  `reconstruction`  `simulation`  created: 2016-03-04 15:47:27 merged: 2016-03-10 10:09:09

24. [13594](http://github.com/cms-sw/cmssw/pull/13594){:target="_blank"}  from **@VinInn**: Gsf cleanup and debug `reconstruction`  created: 2016-03-04 11:07:54 merged: 2016-03-08 08:36:27

25. [13591](http://github.com/cms-sw/cmssw/pull/13591){:target="_blank"}  from **@makortel**: Enable castor digis for 2017 `operations`  created: 2016-03-04 09:58:43 merged: 2016-03-06 21:32:52

26. [13585](http://github.com/cms-sw/cmssw/pull/13585){:target="_blank"}  from **@tmrhombus**: cleaning static analyzer warnings `reconstruction`  created: 2016-03-03 16:56:44 merged: 2016-03-06 08:35:13

27. [13583](http://github.com/cms-sw/cmssw/pull/13583){:target="_blank"}  from **@ianna**: Remove Extra Plane in Pixel Service Cylinder Polycone `geometry`  created: 2016-03-03 13:49:24 merged: 2016-03-06 08:35:30

28. [13579](http://github.com/cms-sw/cmssw/pull/13579){:target="_blank"}  from **@makortel**: Fix track validation for heavy ions `dqm`  created: 2016-03-03 11:21:41 merged: 2016-03-08 16:50:39

29. [13571](http://github.com/cms-sw/cmssw/pull/13571){:target="_blank"}  from **@degano**: [SimCalorimetry/EcalElectronicsEmulation] Solve warning found by gcc 5.3.0. `simulation`  created: 2016-03-03 10:50:30 merged: 2016-03-10 09:57:38

30. [13570](http://github.com/cms-sw/cmssw/pull/13570){:target="_blank"}  from **@makortel**: Fix QuickTrackAssociatorByHits for empty TrackingParticleRefVector `simulation`  created: 2016-03-03 10:32:36 merged: 2016-03-03 13:22:41

31. [13567](http://github.com/cms-sw/cmssw/pull/13567){:target="_blank"}  from **@lihux25**: Fix "withTopo" issue `alca`  created: 2016-03-03 09:51:11 merged: 2016-03-08 18:13:29

32. [13564](http://github.com/cms-sw/cmssw/pull/13564){:target="_blank"}  from **@lveldere**: Fastsim: Muon HLT: refactor seeding configuration `fastsim`  `hlt`  created: 2016-03-03 08:24:37 merged: 2016-03-06 21:32:28

33. [13560](http://github.com/cms-sw/cmssw/pull/13560){:target="_blank"}  from **@rrabadan**: StoN in module highest values `dqm`  created: 2016-03-02 20:05:33 merged: 2016-03-08 08:53:41

34. [13559](http://github.com/cms-sw/cmssw/pull/13559){:target="_blank"}  from **@civanch**: Hcal tb2006 update `simulation`  created: 2016-03-02 18:46:23 merged: 2016-03-03 12:39:46

35. [13557](http://github.com/cms-sw/cmssw/pull/13557){:target="_blank"}  from **@bsunanda**: bsunada:Run2-hcx73 Correct hcal customization code `simulation`  created: 2016-03-02 16:42:23 merged: 2016-03-03 10:13:01

36. [13555](http://github.com/cms-sw/cmssw/pull/13555){:target="_blank"}  from **@ggovi**: popcon2dropbox tool moved to condition uploader `db`  created: 2016-03-02 15:29:02 merged: 2016-03-03 12:35:30

37. [13554](http://github.com/cms-sw/cmssw/pull/13554){:target="_blank"}  from **@davidlange6**: Printout reduction (81x) `dqm`  `l1`  created: 2016-03-02 11:30:32 merged: 2016-03-03 10:16:27

38. [13552](http://github.com/cms-sw/cmssw/pull/13552){:target="_blank"}  from **@ianna**: DD Regression Test for All Scenarios `geometry`  created: 2016-03-02 11:00:20 merged: 2016-03-02 16:20:47

39. [13551](http://github.com/cms-sw/cmssw/pull/13551){:target="_blank"}  from **@makortel**: Update tracking MC validation scripts `dqm`  created: 2016-03-02 10:42:38 merged: 2016-03-08 08:37:27

40. [13550](http://github.com/cms-sw/cmssw/pull/13550){:target="_blank"}  from **@lveldere**: Fastsim: muon hlt cleanup `fastsim`  created: 2016-03-02 09:46:47 merged: 2016-03-02 16:20:27

41. [13544](http://github.com/cms-sw/cmssw/pull/13544){:target="_blank"}  from **@vkhristenko**: HCAL DQM small fixed `dqm`  created: 2016-03-01 18:34:25 merged: 2016-03-08 08:38:06

42. [13539](http://github.com/cms-sw/cmssw/pull/13539){:target="_blank"}  from **@jfernan2**: Fixes to DT*Trigger classes to make them compatible with the DT PoA `dqm`  created: 2016-03-01 16:42:40 merged: 2016-03-08 08:39:41

43. [13530](http://github.com/cms-sw/cmssw/pull/13530){:target="_blank"}  from **@bendavid**: Changes needed for SUSY parameter scans `analysis`  `generators`  `reconstruction`  created: 2016-03-01 00:37:39 merged: 2016-03-10 09:56:40

44. [13529](http://github.com/cms-sw/cmssw/pull/13529){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-hcx72 Modify the code/xml files to define BH `geometry`  created: 2016-02-29 22:30:01 merged: 2016-03-01 11:23:29

45. [13527](http://github.com/cms-sw/cmssw/pull/13527){:target="_blank"}  from **@smrenna**: Modifications to guns to allow finite decay length for mothers `generators`  created: 2016-02-29 17:38:33 merged: 2016-03-02 16:20:16

46. [13526](http://github.com/cms-sw/cmssw/pull/13526){:target="_blank"}  from **@Dr15Jones**: PSet.clone now works like module clone `core`  created: 2016-02-29 16:45:30 merged: 2016-03-01 11:23:43

47. [13525](http://github.com/cms-sw/cmssw/pull/13525){:target="_blank"}  from **@ianna**: Enable Partial Sim/Reco Geometry Dump `visualization`  created: 2016-02-29 16:44:49 merged: 2016-03-01 11:48:11

48. [13524](http://github.com/cms-sw/cmssw/pull/13524){:target="_blank"}  from **@hengne**: relval matrix updates, PR#13516 port to 81x `alca`  `pdmv`  created: 2016-02-29 16:39:09 merged: 2016-03-07 09:12:12

49. [13522](http://github.com/cms-sw/cmssw/pull/13522){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-hcx71 Try to sort out some geometry issue of HGCal `geometry`  created: 2016-02-29 15:55:27 merged: 2016-03-01 11:48:34

50. [13521](http://github.com/cms-sw/cmssw/pull/13521){:target="_blank"}  from **@Dr15Jones**: Improve exception message for missing produces call `core`  created: 2016-02-29 15:45:20 merged: 2016-03-01 11:51:11

51. [13519](http://github.com/cms-sw/cmssw/pull/13519){:target="_blank"}  from **@lveldere**: FastSim: run btag DQM `fastsim`  created: 2016-02-29 15:18:52 merged: 2016-03-03 08:35:44

52. [13518](http://github.com/cms-sw/cmssw/pull/13518){:target="_blank"}  from **@lveldere**: FastSim: never run DQM in endPath for FastSim `operations`  created: 2016-02-29 14:25:10 merged: 2016-03-01 17:32:17

53. [13517](http://github.com/cms-sw/cmssw/pull/13517){:target="_blank"}  from **@makortel**: Fix trackingOnly DQM `dqm`  created: 2016-02-29 11:07:22 merged: 2016-03-08 08:39:06

54. [13515](http://github.com/cms-sw/cmssw/pull/13515){:target="_blank"}  from **@davidlt**: Fix all [-Wheader-guard] warnings `alca`  `analysis`  `core`  `db`  `dqm`  `fastsim`  `generators`  `geometry`  `hlt`  `l1`  `reconstruction`  `simulation`  `visualization`  created: 2016-02-28 08:42:56 merged: 2016-02-29 15:09:48

55. [13511](http://github.com/cms-sw/cmssw/pull/13511){:target="_blank"}  from **@kpedro88**: add QIE10 product to DataMixingModule (one-line fix) `comparison`  `simulation`  created: 2016-02-27 19:24:11 merged: 2016-02-28 08:16:09

56. [13509](http://github.com/cms-sw/cmssw/pull/13509){:target="_blank"}  from **@Martin-Grunewald**: Add protection against 0-element uGtAlgoBlocks in HLTL1TSeed module `hlt`  created: 2016-02-27 06:23:40 merged: 2016-02-29 17:49:54

57. [13506](http://github.com/cms-sw/cmssw/pull/13506){:target="_blank"}  from **@slava77**: add missing initialization in CaloCluster `reconstruction`  created: 2016-02-26 21:31:06 merged: 2016-03-01 11:49:23

58. [13503](http://github.com/cms-sw/cmssw/pull/13503){:target="_blank"}  from **@makortel**: Print deprecation warning if anybody uses phase1TkCustoms without phase1Pixel era `simulation`  created: 2016-02-26 17:53:16 merged: 2016-03-02 21:26:08

59. [13502](http://github.com/cms-sw/cmssw/pull/13502){:target="_blank"}  from **@tanmaymudholkar**: New chi-squared plots `dqm`  created: 2016-02-26 17:45:29 merged: 2016-03-08 08:38:49

60. [13501](http://github.com/cms-sw/cmssw/pull/13501){:target="_blank"}  from **@lveldere**: FastSim: fix layer definition of hltPixelPairSeeds `fastsim`  created: 2016-02-26 17:36:51 merged: 2016-02-27 18:05:41

61. [13500](http://github.com/cms-sw/cmssw/pull/13500){:target="_blank"}  from **@mbandrews**: Add channel status + laser threshold `dqm`  created: 2016-02-26 17:12:42 merged: 2016-03-08 18:18:15

62. [13494](http://github.com/cms-sw/cmssw/pull/13494){:target="_blank"}  from **@mmusich**: Fixing 81X relval alcareco in express test `pdmv`  created: 2016-02-26 14:57:18 merged: 2016-03-02 21:56:17

63. [13493](http://github.com/cms-sw/cmssw/pull/13493){:target="_blank"}  from **@lveldere**: FastSim: disable btag DQM cause it depends on product not available in FastSim `fastsim`  created: 2016-02-26 13:19:22 merged: 2016-02-26 16:06:02

64. [13491](http://github.com/cms-sw/cmssw/pull/13491){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-hcx69 Create scenario to run with new HCAL TP `geometry`  created: 2016-02-26 11:38:15 merged: 2016-03-06 08:36:19

65. [13486](http://github.com/cms-sw/cmssw/pull/13486){:target="_blank"}  from **@fioriNTU**: correct raw data collection to be used `alca`  created: 2016-02-26 10:40:21 merged: 2016-02-27 18:26:24

66. [13485](http://github.com/cms-sw/cmssw/pull/13485){:target="_blank"}  from **@schneiml**: Add cuts to SiStripMonitorTrack (8_1_X version) `dqm`  created: 2016-02-26 09:31:30 merged: 2016-03-03 10:19:16

67. [13483](http://github.com/cms-sw/cmssw/pull/13483){:target="_blank"}  from **@alberto-sanchez**: Adding tracks from V0, and fixing bug in photon conversion producer `analysis`  created: 2016-02-25 19:55:04 merged: 2016-03-06 21:34:57

68. [13482](http://github.com/cms-sw/cmssw/pull/13482){:target="_blank"}  from **@lveldere**: FastSim : Tracking: fix bad import `fastsim`  created: 2016-02-25 18:52:44 merged: 2016-02-26 06:16:31

69. [13481](http://github.com/cms-sw/cmssw/pull/13481){:target="_blank"}  from **@Dr15Jones**: Principal::getForOutput now always retrieves the product `comparison`  `core`  created: 2016-02-25 16:17:32 merged: 2016-02-29 16:56:14

70. [13478](http://github.com/cms-sw/cmssw/pull/13478){:target="_blank"}  from **@pietverwilligen**: Me0 digitizer constand phi smearing 800 `simulation`  created: 2016-02-25 12:35:53 merged: 2016-02-27 07:27:18

71. [13477](http://github.com/cms-sw/cmssw/pull/13477){:target="_blank"}  from **@makortel**: Migrate 2017 tracking to eras `dqm`  `reconstruction`  `simulation`  created: 2016-02-25 10:41:17 merged: 2016-03-08 18:16:26

72. [13475](http://github.com/cms-sw/cmssw/pull/13475){:target="_blank"}  from **@schneiml**: Improve print_trace in DQMStore `dqm`  created: 2016-02-25 10:20:24 merged: 2016-03-08 18:15:48

73. [13472](http://github.com/cms-sw/cmssw/pull/13472){:target="_blank"}  from **@jbrands**: including the 76X pileup Jet Id training  `reconstruction`  created: 2016-02-25 09:05:21 merged: 2016-03-06 08:37:24

74. [13470](http://github.com/cms-sw/cmssw/pull/13470){:target="_blank"}  from **@kirschen**: remove unused L1 includes and members of the class `hlt`  created: 2016-02-25 08:30:55 merged: 2016-02-27 18:06:25

75. [13468](http://github.com/cms-sw/cmssw/pull/13468){:target="_blank"}  from **@kirschen**: add HLTJetL1TMatchProducer as simplified stage2L1-version with corres `hlt`  created: 2016-02-24 21:53:30 merged: 2016-02-27 18:07:15

76. [13467](http://github.com/cms-sw/cmssw/pull/13467){:target="_blank"}  from **@Dr15Jones**: Testing OutputModules only get products they consume `core`  created: 2016-02-24 20:40:49 merged: 2016-02-26 08:08:19

77. [13466](http://github.com/cms-sw/cmssw/pull/13466){:target="_blank"}  from **@mmusich**: Updated Photon regressions, added e/gamma regressions for online, updated JECs with L2L3 residuals and other fixes `alca`  created: 2016-02-24 20:32:49 merged: 2016-02-29 15:26:46

78. [13465](http://github.com/cms-sw/cmssw/pull/13465){:target="_blank"}  from **@wmtan**: Better way to disable rootlogon `core`  created: 2016-02-24 17:51:35 merged: 2016-02-26 08:08:32

79. [13464](http://github.com/cms-sw/cmssw/pull/13464){:target="_blank"}  from **@lveldere**: FastSim bug fix 8_1_X: fastSim era for Validation sequence, define DQM sequence for FastSim => *run physicsDQM8 `fastsim`  `operations`  `pdmv`  created: 2016-02-24 17:33:56 merged: 2016-02-25 09:19:35

80. [13462](http://github.com/cms-sw/cmssw/pull/13462){:target="_blank"}  from **@Vlandr57**: FastSim: New correction coefficients for HF 81X `fastsim`  created: 2016-02-24 17:20:28 merged: 2016-02-26 08:09:00

81. [13459](http://github.com/cms-sw/cmssw/pull/13459){:target="_blank"}  from **@lveldere**: FastSim: apply fastsim customs on L1Reco via fastsim era `fastsim`  `l1`  `operations`  created: 2016-02-24 16:19:59 merged: 2016-03-03 10:14:48

82. [13458](http://github.com/cms-sw/cmssw/pull/13458){:target="_blank"}  from **@lveldere**: Fastsim tracking remove obs files `fastsim`  created: 2016-02-24 15:54:12 merged: 2016-02-27 07:26:41

83. [13456](http://github.com/cms-sw/cmssw/pull/13456){:target="_blank"}  from **@lveldere**: FastSim: fix L1 muons `fastsim`  created: 2016-02-24 15:36:57 merged: 2016-02-26 08:09:14

84. [13451](http://github.com/cms-sw/cmssw/pull/13451){:target="_blank"}  from **@kirschen**: change selector to stream for multithreading `analysis`  `reconstruction`  created: 2016-02-24 12:47:18 merged: 2016-02-25 09:18:47

85. [13448](http://github.com/cms-sw/cmssw/pull/13448){:target="_blank"}  from **@VinInn**: Small performance improvement in Tracking `reconstruction`  `simulation`  created: 2016-02-24 06:29:52 merged: 2016-03-02 11:15:33

86. [13446](http://github.com/cms-sw/cmssw/pull/13446){:target="_blank"}  from **@aysent**: Fix AssociationMap in TrackRefitter (81X) `reconstruction`  created: 2016-02-24 05:14:24 merged: 2016-02-26 08:09:53

87. [13444](http://github.com/cms-sw/cmssw/pull/13444){:target="_blank"}  from **@wmtan**: Support ESProducrs returning std::unique_ptr. `comparison`  `core`  created: 2016-02-23 22:29:35 merged: 2016-02-27 18:08:11

88. [13442](http://github.com/cms-sw/cmssw/pull/13442){:target="_blank"}  from **@wmtan**: Use correct python version `alca`  `core`  `db`  `dqm`  `hlt`  `reconstruction`  created: 2016-02-23 19:52:07 merged: 2016-02-26 08:11:37

89. [13440](http://github.com/cms-sw/cmssw/pull/13440){:target="_blank"}  from **@civanch**: Fixed static anal warnings in SIM `simulation`  created: 2016-02-23 17:18:47 merged: 2016-02-29 15:47:08

90. [13439](http://github.com/cms-sw/cmssw/pull/13439){:target="_blank"}  from **@dmitrijus**: Further improve memory tracking (for DQM PR tests) `dqm`  created: 2016-02-23 14:08:24 merged: 2016-03-02 11:08:49

91. [13437](http://github.com/cms-sw/cmssw/pull/13437){:target="_blank"}  from **@lveldere**: Fastsim trackrefactor `fastsim`  created: 2016-02-23 12:31:33 merged: 2016-02-24 09:52:14

92. [13434](http://github.com/cms-sw/cmssw/pull/13434){:target="_blank"}  from **@friccita**: debugged MaterialBudgetAction and runP_*_cfg.py `dqm`  `geometry`  created: 2016-02-23 00:53:52 merged: 2016-03-06 08:37:48

93. [13432](http://github.com/cms-sw/cmssw/pull/13432){:target="_blank"}  from **@wmtan**: Fix incorrect exception message `core`  created: 2016-02-22 20:28:50 merged: 2016-02-24 09:36:18

94. [13430](http://github.com/cms-sw/cmssw/pull/13430){:target="_blank"}  from **@wmtan**: Use consumes info to populate lookup tables `core`  created: 2016-02-22 17:07:41 merged: 2016-02-24 09:36:37

95. [13429](http://github.com/cms-sw/cmssw/pull/13429){:target="_blank"}  from **@kencall**: Adds option to EcalDeadCellTriggerPrimitiveFilter to consider kTPSaturated flag `analysis`  `reconstruction`  created: 2016-02-22 16:02:35 merged: 2016-02-27 18:10:19

96. [13428](http://github.com/cms-sw/cmssw/pull/13428){:target="_blank"}  from **@ericvaandering**: Fix regressions of python 2 modernization features `core`  `docs`  `dqm`  `l1`  created: 2016-02-22 15:58:33 merged: 2016-02-26 08:10:42

97. [13427](http://github.com/cms-sw/cmssw/pull/13427){:target="_blank"}  from **@Dr15Jones**: Clean EndPaths as well when going unscheduled `core`  created: 2016-02-22 14:07:28 merged: 2016-02-24 09:37:57

98. [13426](http://github.com/cms-sw/cmssw/pull/13426){:target="_blank"}  from **@slehti**: HLTTauRefProducer: bugfix `dqm`  created: 2016-02-22 13:14:57 merged: 2016-03-02 11:41:39

99. [13424](http://github.com/cms-sw/cmssw/pull/13424){:target="_blank"}  from **@makortel**: Make TrackExtra::setSeedRef() to take RefToBase<TrajectorySeed> via const reference `reconstruction`  created: 2016-02-22 11:21:09 merged: 2016-02-25 09:18:22

100. [13423](http://github.com/cms-sw/cmssw/pull/13423){:target="_blank"}  from **@makortel**: Remove remaining PixelCPEGeneric customizations for phase1 `simulation`  created: 2016-02-22 10:48:12 merged: 2016-02-24 18:30:35

101. [13419](http://github.com/cms-sw/cmssw/pull/13419){:target="_blank"}  from **@IHEP-CMS**: Adding 1D Flightdistance tagging variables from cmssw 8_0_0_pre6 `comparison`  `reconstruction`  created: 2016-02-22 00:12:14 merged: 2016-02-27 18:22:21

102. [13410](http://github.com/cms-sw/cmssw/pull/13410){:target="_blank"}  from **@bsunanda**: bsunanda:Phase2-hgx01 Remove a few bugs in HGC code and add example for TB `geometry`  created: 2016-02-19 16:28:19 merged: 2016-02-21 15:46:51

103. [13408](http://github.com/cms-sw/cmssw/pull/13408){:target="_blank"}  from **@VinInn**: fix non const static and obsolete avx code `reconstruction`  created: 2016-02-19 14:00:51 merged: 2016-02-21 15:46:06

104. [13400](http://github.com/cms-sw/cmssw/pull/13400){:target="_blank"}  from **@cmsdqm**: migrate to consumes `dqm`  `l1`  `pdmv`  created: 2016-02-18 20:36:03 merged: 2016-02-24 09:37:42

105. [13386](http://github.com/cms-sw/cmssw/pull/13386){:target="_blank"}  from **@VinInn**: Code cleanup, debug improvements, bug fixes in Tracking code `alca`  `db`  `reconstruction`  created: 2016-02-18 10:18:16 merged: 2016-02-27 07:26:26

106. [13385](http://github.com/cms-sw/cmssw/pull/13385){:target="_blank"}  from **@heppye**: add DQM Validation plots for MSSM Hbb Trigger Paths `dqm`  created: 2016-02-18 10:18:02 merged: 2016-02-23 10:00:06

107. [13383](http://github.com/cms-sw/cmssw/pull/13383){:target="_blank"}  from **@makortel**: Add eras to select tracking configuration for 2017 detector `operations`  created: 2016-02-18 10:13:45 merged: 2016-02-23 10:00:44

108. [13372](http://github.com/cms-sw/cmssw/pull/13372){:target="_blank"}  from **@cms-met**: MET PAT tool update + update of MET significance `analysis`  `reconstruction`  created: 2016-02-18 10:06:23 merged: 2016-03-10 09:56:26

109. [13370](http://github.com/cms-sw/cmssw/pull/13370){:target="_blank"}  from **@diguida**: Further cleanup of Condition access in AlCaDB, online DQM, Geometry, HLT, Simulation, and standard configuration `alca`  `db`  `dqm`  `geometry`  `hlt`  `operations`  `simulation`  created: 2016-02-18 10:05:50 merged: 2016-03-10 10:05:26

110. [13368](http://github.com/cms-sw/cmssw/pull/13368){:target="_blank"}  from **@suchandradutta**: Porting Phase2Tracker Digitizer from 62X_SLHC release. Updated also T `geometry`  `simulation`  created: 2016-02-18 10:05:17 merged: 2016-03-03 09:45:01

111. [13365](http://github.com/cms-sw/cmssw/pull/13365){:target="_blank"}  from **@lveldere**: FastSim : HLT SUSYBSM validation : remove dependence on non-existing collection 'conversions' `dqm`  created: 2016-02-18 10:04:29 merged: 2016-02-23 10:04:46

112. [13362](http://github.com/cms-sw/cmssw/pull/13362){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-alca34 Update Pythia Isolated Track Filter `generators`  `reconstruction`  created: 2016-02-18 10:03:40 merged: 2016-02-19 10:35:09

113. [13360](http://github.com/cms-sw/cmssw/pull/13360){:target="_blank"}  from **@gpasztor**: HLTElectronMuonInvMassFilter update `comparison`  `hlt`  created: 2016-02-18 10:03:08 merged: 2016-02-19 10:32:07

114. [13358](http://github.com/cms-sw/cmssw/pull/13358){:target="_blank"}  from **@mbandrews**: ECALbyLumi+Timing `dqm`  created: 2016-02-18 10:02:36 merged: 2016-03-08 18:24:24

115. [13357](http://github.com/cms-sw/cmssw/pull/13357){:target="_blank"}  from **@dkotlins**: Phase1 customs `db`  `geometry`  `simulation`  created: 2016-02-18 10:02:20 merged: 2016-03-02 16:35:45

116. [13350](http://github.com/cms-sw/cmssw/pull/13350){:target="_blank"}  from **@makortel**: Fix NavigationSchoolAnalyzer for "ByGeom" `comparison`  `reconstruction`  created: 2016-02-18 10:00:27 merged: 2016-02-19 10:33:03

117. [13348](http://github.com/cms-sw/cmssw/pull/13348){:target="_blank"}  from **@makortel**: Add GsfTracks to tracking validation `dqm`  `reconstruction`  `simulation`  created: 2016-02-18 09:59:55 merged: 2016-03-02 11:07:11

118. [13346](http://github.com/cms-sw/cmssw/pull/13346){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-hcx68 Add xml files for BH (HGCal) `geometry`  created: 2016-02-18 09:59:22 merged: 2016-02-21 15:47:47

119. [13344](http://github.com/cms-sw/cmssw/pull/13344){:target="_blank"}  from **@kpedro88**: SIM/DIGI/RECO changes for HF QIE10 (part B) `alca`  `operations`  `reconstruction`  `simulation`  created: 2016-02-18 09:58:50 merged: 2016-02-26 16:06:42

120. [13341](http://github.com/cms-sw/cmssw/pull/13341){:target="_blank"}  from **@cms-l1t-offline**: L1t hlt wseeds presc mask 80x `comparison`  `hlt`  created: 2016-02-18 09:58:01 merged: 2016-02-19 10:34:03

#### CMSDIST Changes between Tags REL/CMSSW_8_0_2/slc6_amd64_gcc530 and REL/CMSSW_8_1_0_pre1/slc6_amd64_gcc530:

[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_8_0_2/slc6_amd64_gcc530...REL/CMSSW_8_1_0_pre1/slc6_amd64_gcc530)



1. [2187](http://github.com/cms-sw/cmsdist/pull/2187){:target="_blank"}  from **@smuzaffar**: updated root from 81x next branch created: 2016-03-09 21:38:22 merged: 2016-03-09 21:38:30

2. [2180](http://github.com/cms-sw/cmsdist/pull/2180){:target="_blank"}  from **@degano**: Advance data for Fireworks/Geometry. created: 2016-03-04 15:06:28 merged: 2016-03-07 09:04:23

3. [2176](http://github.com/cms-sw/cmsdist/pull/2176){:target="_blank"}  from **@degano**: Advance data for L1Trigger/L1TGlobal. created: 2016-03-03 13:29:01 merged: 2016-03-04 08:48:28

4. [2174](http://github.com/cms-sw/cmsdist/pull/2174){:target="_blank"}  from **@degano**: Update frontier client to 2.8.18. created: 2016-03-03 08:55:12 merged: 2016-03-04 08:47:44

5. [2171](http://github.com/cms-sw/cmsdist/pull/2171){:target="_blank"}  from **@degano**: Update python to 2.7.11 created: 2016-03-01 13:50:44 merged: 2016-03-02 09:40:24

6. [2170](http://github.com/cms-sw/cmsdist/pull/2170){:target="_blank"}  from **@degano**: Add external generator Starlight. created: 2016-03-01 13:45:43 merged: 2016-03-02 08:55:16

7. [2169](http://github.com/cms-sw/cmsdist/pull/2169){:target="_blank"}  from **@degano**: Upgrade Froniter client to 2.8.16 and pacparser to 1.3.5. created: 2016-03-01 13:36:47 merged: 2016-03-02 08:55:32

8. [2168](http://github.com/cms-sw/cmsdist/pull/2168){:target="_blank"}  from **@degano**: Update xrootd to 4.2.3. created: 2016-03-01 13:30:49 merged: 2016-03-07 10:38:33

9. [2166](http://github.com/cms-sw/cmsdist/pull/2166){:target="_blank"}  from **@degano**: Advance data for RecoJets/JetProducers. created: 2016-02-25 09:04:34 merged: 2016-02-26 14:41:10

10. [2159](http://github.com/cms-sw/cmsdist/pull/2159){:target="_blank"}  from **@TaiSakuma**: update pandas version to 0.17.1 for 8_1_X created: 2016-02-24 14:31:27 merged: 2016-02-29 09:03:24

11. [2158](http://github.com/cms-sw/cmsdist/pull/2158){:target="_blank"}  from **@degano**: Advance data for FastSimulation/TrackingRecHitProducer. created: 2016-02-24 10:43:15 merged: 2016-02-24 13:08:52

12. [2152](http://github.com/cms-sw/cmsdist/pull/2152){:target="_blank"}  from **@davidlt**: cmsos.file: add a proper shebang created: 2016-02-20 11:58:47 merged: 2016-03-01 12:01:19
