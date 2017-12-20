---
layout: post
rel_link:  "8_1_0"
title:  "CMSSW_8_1_0"
date:   2016-12-01 20:27:00
categories: cmssw
relmajor: 8
relminor: 1
relsubminor: 0
---

# CMSSW_8_1_0
#### Changes since CMSSW_8_1_0_pre16:

[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_8_1_0_pre16...CMSSW_8_1_0)



1. [16831](http://github.com/cms-sw/cmssw/pull/16831){:target="_blank"}  from **@cms-AlCaDB**: [81X] update RECO & SIM phase-1 geometry  `alca`  created: 2016-12-01 11:01:53 merged: 2016-12-01 20:26:14

2. [16805](http://github.com/cms-sw/cmssw/pull/16805){:target="_blank"}  from **@cms-sw**: Revert "interface compatible with evtgen 1.6" `comparison`  `generators`  created: 2016-11-29 17:33:17 merged: 2016-11-29 17:33:23

3. [16789](http://github.com/cms-sw/cmssw/pull/16789){:target="_blank"}  from **@shervin86**: bug fix in clone constructor of GsfElectron. New method to get regres `reconstruction`  created: 2016-11-29 09:16:02 merged: 2016-12-01 08:07:48

4. [16781](http://github.com/cms-sw/cmssw/pull/16781){:target="_blank"}  from **@kpedro88**: Remove obsolete customize from D6 workflows [81X] `pdmv`  created: 2016-11-28 16:02:05 merged: 2016-11-28 18:35:49

5. [16774](http://github.com/cms-sw/cmssw/pull/16774){:target="_blank"}  from **@hengne**: complete the list of wfs in upgrade framework `pdmv`  created: 2016-11-28 14:04:20 merged: 2016-12-01 08:07:56

6. [16773](http://github.com/cms-sw/cmssw/pull/16773){:target="_blank"}  from **@kencall**: Hcal validation new histograms `dqm`  created: 2016-11-28 14:03:52 merged: 2016-12-01 14:30:24

7. [16771](http://github.com/cms-sw/cmssw/pull/16771){:target="_blank"}  from **@rovere**: Revert TOB6 and full TEC material to pre8 `geometry`  created: 2016-11-27 17:06:14 merged: 2016-12-01 11:09:54

8. [16762](http://github.com/cms-sw/cmssw/pull/16762){:target="_blank"}  from **@VinInn**: protect DAClusterizerInZ_vect.cc from a too small value backport  #16761 `reconstruction`  created: 2016-11-25 14:33:58 merged: 2016-11-26 18:06:52

9. [16757](http://github.com/cms-sw/cmssw/pull/16757){:target="_blank"}  from **@ianna**: Bugfix: 2019 Geometry Scenario  `geometry`  `visualization`  created: 2016-11-25 11:17:43 merged: 2016-11-27 07:26:04

10. [16744](http://github.com/cms-sw/cmssw/pull/16744){:target="_blank"}  from **@bsunanda**: bsunanda:Phase2-ft12 Clean up FastTimeTopology code `geometry`  created: 2016-11-23 20:14:04 merged: 2016-11-24 08:22:42

11. [16741](http://github.com/cms-sw/cmssw/pull/16741){:target="_blank"}  from **@ferencek**: Extended maximum allowed span for Phase2 Inner Tracker pixel clusters (81X) `reconstruction`  created: 2016-11-23 14:28:18 merged: 2016-11-27 07:20:31

12. [16740](http://github.com/cms-sw/cmssw/pull/16740){:target="_blank"}  from **@makortel**: Switch phase1 tracking to generic pixel CPE (81X) `reconstruction`  created: 2016-11-23 14:25:18 merged: 2016-11-25 08:27:32

13. [16735](http://github.com/cms-sw/cmssw/pull/16735){:target="_blank"}  from **@Dr15Jones**: Fixed precedence order problem with FormulaEvaluator `analysis`  `reconstruction`  created: 2016-11-22 23:26:22 merged: 2016-11-24 08:22:34

14. [16731](http://github.com/cms-sw/cmssw/pull/16731){:target="_blank"}  from **@deguio**: fix calib map and typo `dqm`  created: 2016-11-22 17:20:47 merged: 2016-12-01 08:08:43

15. [16726](http://github.com/cms-sw/cmssw/pull/16726){:target="_blank"}  from **@FHead**: HIN High-pT trigger DQM for 81X (CMSHLT-1129, CMSHLT-1135, CMSHLT-1137) `dqm`  created: 2016-11-22 16:43:45 merged: 2016-11-27 07:25:24

16. [16722](http://github.com/cms-sw/cmssw/pull/16722){:target="_blank"}  from **@idebruyn**: Split cluster charge & S/N MEs for thin and thick sensors (81X) `dqm`  created: 2016-11-22 09:55:57 merged: 2016-11-27 07:21:06

17. [16720](http://github.com/cms-sw/cmssw/pull/16720){:target="_blank"}  from **@diguida**: [CMSSW_8_1_X] Add a new python configuration for EcalADCToGeV B transition O2O, and new modules and configuration for EcalIntercalibConstants and EcalPedestals B transition O2O `db`  created: 2016-11-22 07:57:03 merged: 2016-12-01 08:08:51

18. [16700](http://github.com/cms-sw/cmssw/pull/16700){:target="_blank"}  from **@diguida**: Add HLT_PAZeroBias and HLT_PAL1AlwaysTrue trigger bits to the input event selection for PixelLumi online DQM client forVdM scan.  `dqm`  created: 2016-11-21 08:06:00 merged: 2016-11-25 08:28:11

19. [16697](http://github.com/cms-sw/cmssw/pull/16697){:target="_blank"}  from **@kpedro88**: Fix Phase2 memory corruption (81X) `analysis`  `reconstruction`  created: 2016-11-20 03:52:04 merged: 2016-11-26 18:09:07

20. [16694](http://github.com/cms-sw/cmssw/pull/16694){:target="_blank"}  from **@cms-sw**: Revert "bsunanda:Phase2-hgx67 Correct reconstruction geometry for EE and FH with full coverage" `comparison`  `dqm`  `geometry`  `reconstruction`  created: 2016-11-19 08:08:48 merged: 2016-11-19 08:08:55

21. [16685](http://github.com/cms-sw/cmssw/pull/16685){:target="_blank"}  from **@cms-AlCaDB**: [81X] Re-add eventSetupPathKey to ALCARECOLumiPixels `alca`  created: 2016-11-18 14:19:16 merged: 2016-11-23 08:36:37

22. [16672](http://github.com/cms-sw/cmssw/pull/16672){:target="_blank"}  from **@cms-AlCaDB**: [81X] update phase-I Simulation geometry `alca`  created: 2016-11-17 11:47:02 merged: 2016-11-18 16:17:27

23. [16670](http://github.com/cms-sw/cmssw/pull/16670){:target="_blank"}  from **@calabria**:  Reduced muon validation for PhaseII Upgrade high PU scenarios (81X) `dqm`  `hlt`  `reconstruction`  `simulation`  created: 2016-11-17 11:27:31 merged: 2016-12-01 08:09:09

24. [16666](http://github.com/cms-sw/cmssw/pull/16666){:target="_blank"}  from **@kpedro88**: Improvements for upgrade matrix (81X) `generators`  `pdmv`  created: 2016-11-16 19:24:16 merged: 2016-11-27 07:21:53

25. [16661](http://github.com/cms-sw/cmssw/pull/16661){:target="_blank"}  from **@makortel**: Fix MultiTrackValidator MVA monitoring (81X) `dqm`  `reconstruction`  created: 2016-11-16 16:29:26 merged: 2016-11-24 08:23:47

26. [16657](http://github.com/cms-sw/cmssw/pull/16657){:target="_blank"}  from **@cms-AlCaDB**: [81X] update dataRun2 GT with conditions for Sept2016 re-reco `alca`  created: 2016-11-16 12:03:56 merged: 2016-11-16 19:46:24

27. [16590](http://github.com/cms-sw/cmssw/pull/16590){:target="_blank"}  from **@bsunanda**: bsunanda:Phase2-ft11 Update README file in Configuration/Geometry and add required files for FastTime Reco Geometry `geometry`  created: 2016-11-16 04:51:29 merged: 2016-11-16 10:27:40

28. [16589](http://github.com/cms-sw/cmssw/pull/16589){:target="_blank"}  from **@mtosi**: fix some DQM sequences for phase1 scenario `dqm`  `reconstruction`  `simulation`  created: 2016-11-15 17:13:38 merged: 2016-11-27 07:32:07

29. [16585](http://github.com/cms-sw/cmssw/pull/16585){:target="_blank"}  from **@civanch**: Added PhysList for study of HGCAL TB `simulation`  created: 2016-11-15 16:56:48 merged: 2016-11-23 19:59:16

30. [16583](http://github.com/cms-sw/cmssw/pull/16583){:target="_blank"}  from **@mzarucki**:  Updated L1TStage2uGT DQM histogram titles `dqm`  created: 2016-11-15 16:34:23 merged: 2016-11-16 08:49:23

31. [16582](http://github.com/cms-sw/cmssw/pull/16582){:target="_blank"}  from **@cms-sw**: fix RecoMET/METProducers/test/runtests.sh to stop the test if cmsDriver command fails `reconstruction`  created: 2016-11-15 13:32:46 merged: 2016-11-16 07:35:27

32. [16580](http://github.com/cms-sw/cmssw/pull/16580){:target="_blank"}  from **@sushilchauhan**: added dark photon model to SimG4Core custom physics `simulation`  created: 2016-11-15 12:19:49 merged: 2016-11-22 16:43:09

33. [16579](http://github.com/cms-sw/cmssw/pull/16579){:target="_blank"}  from **@kpedro88**: increase number of high pT jets for flat QCD `generators`  created: 2016-11-14 20:23:34 merged: 2016-11-15 14:18:12

34. [16578](http://github.com/cms-sw/cmssw/pull/16578){:target="_blank"}  from **@kpedro88**: remove a bunch of unneeded Pythia6 configs `core`  `dqm`  `generators`  `hlt`  created: 2016-11-14 20:18:27 merged: 2016-11-15 17:07:10

35. [16576](http://github.com/cms-sw/cmssw/pull/16576){:target="_blank"}  from **@mtosi**: re-enable HLT DQM, Validation and Harvesting sequences `dqm`  created: 2016-11-14 15:32:22 merged: 2016-11-15 14:18:05

36. [16574](http://github.com/cms-sw/cmssw/pull/16574){:target="_blank"}  from **@kfjack**: Move HighMET skim from JetHT PD to MET PD in skim matrix and relval `pdmv`  created: 2016-11-14 14:20:20 merged: 2016-11-14 18:52:51

37. [16573](http://github.com/cms-sw/cmssw/pull/16573){:target="_blank"}  from **@OlivierBondu**: Moving RecoLocalTracker from Legacy to Thread-Friendly `reconstruction`  created: 2016-11-14 14:09:07 merged: 2016-11-18 16:17:49

38. [16571](http://github.com/cms-sw/cmssw/pull/16571){:target="_blank"}  from **@ianna**: Replace Subtraction Solid with Union Solid `geometry`  created: 2016-11-14 11:30:29 merged: 2016-11-15 17:07:36

39. [16570](http://github.com/cms-sw/cmssw/pull/16570){:target="_blank"}  from **@makortel**: Fix some exceptions of cms.Modifier `core`  created: 2016-11-14 10:48:07 merged: 2016-11-15 08:17:48

40. [16569](http://github.com/cms-sw/cmssw/pull/16569){:target="_blank"}  from **@mariadalfonso**: HBHE M2-parameters: chi2, energy, pedSigma in M2 `hlt`  `reconstruction`  created: 2016-11-14 09:00:57 merged: 2016-11-22 16:43:26

41. [16567](http://github.com/cms-sw/cmssw/pull/16567){:target="_blank"}  from **@bsunanda**: bsunanda:Phase2-ft10 Modify the FastTimeDetId according to Lindsey's suggestion `simulation`  created: 2016-11-13 22:25:07 merged: 2016-11-14 16:37:43

42. [16565](http://github.com/cms-sw/cmssw/pull/16565){:target="_blank"}  from **@Dr15Jones**: Added # streams and threads to Timing JobReport `core`  created: 2016-11-13 17:19:49 merged: 2016-11-14 08:25:53

43. [16563](http://github.com/cms-sw/cmssw/pull/16563){:target="_blank"}  from **@JanFSchulte**: add customization function to switch the pixelTracks for the iterativ `hlt`  created: 2016-11-11 18:20:54 merged: 2016-12-01 08:11:14

44. [16562](http://github.com/cms-sw/cmssw/pull/16562){:target="_blank"}  from **@bsunanda**: bsunanda:Phase2-ft09 Add Reco geometry for Fast Timing `geometry`  created: 2016-11-11 15:44:35 merged: 2016-11-16 09:23:34

45. [16561](http://github.com/cms-sw/cmssw/pull/16561){:target="_blank"}  from **@slava77**: add bunchSpacingProducer in localreco\* (fw port of #16560) `operations`  created: 2016-11-11 14:12:49 merged: 2016-11-11 17:54:26

46. [16559](http://github.com/cms-sw/cmssw/pull/16559){:target="_blank"}  from **@makortel**: Monitor track selection MVAs in MultiTrackValidator `dqm`  created: 2016-11-11 13:33:56 merged: 2016-11-15 17:20:00

47. [16558](http://github.com/cms-sw/cmssw/pull/16558){:target="_blank"}  from **@cms-sw**: Revert "Do not sort the das results if CMSSDT_DAS_CLIENT_NO_SORT env is set" `comparison`  `pdmv`  created: 2016-11-11 13:29:11 merged: 2016-11-11 13:29:22

48. [16555](http://github.com/cms-sw/cmssw/pull/16555){:target="_blank"}  from **@bsunanda**: bsunanda:Phase2-hgx68 Update validation code `dqm`  created: 2016-11-10 22:54:02 merged: 2016-11-15 17:18:27

49. [16554](http://github.com/cms-sw/cmssw/pull/16554){:target="_blank"}  from **@kencall**: Hcal digi validation `dqm`  created: 2016-11-10 21:32:06 merged: 2016-11-16 20:21:23

50. [16551](http://github.com/cms-sw/cmssw/pull/16551){:target="_blank"}  from **@afiqaize**: make code pick up HI and PA EGM paths as well 81X `dqm`  created: 2016-11-10 18:06:06 merged: 2016-11-11 15:09:36

51. [16548](http://github.com/cms-sw/cmssw/pull/16548){:target="_blank"}  from **@ggovi**: fixes for the conddb copy functions `db`  created: 2016-11-10 15:24:37 merged: 2016-11-14 16:38:51

52. [16547](http://github.com/cms-sw/cmssw/pull/16547){:target="_blank"}  from **@ghugo83**: Merged pixelRecoMaterial.xml and trackerRecoMaterial.xml into one file `geometry`  `simulation`  created: 2016-11-10 15:05:39 merged: 2016-11-10 19:57:56

53. [16544](http://github.com/cms-sw/cmssw/pull/16544){:target="_blank"}  from **@cms-AlCaDB**: [81X] Update HCal TP parameters and fixes in 2017 wf `alca`  created: 2016-11-10 12:43:42 merged: 2016-11-10 20:21:38

54. [16543](http://github.com/cms-sw/cmssw/pull/16543){:target="_blank"}  from **@Dr15Jones**: Close the socket after it is used in StatisticsSenderService `core`  created: 2016-11-10 10:50:02 merged: 2016-11-10 19:58:04

55. [16540](http://github.com/cms-sw/cmssw/pull/16540){:target="_blank"}  from **@jlagram**: Strip hit eff lumi `alca`  created: 2016-11-10 09:15:19 merged: 2016-11-10 19:59:27

56. [16539](http://github.com/cms-sw/cmssw/pull/16539){:target="_blank"}  from **@smuzaffar**: fix compilation error for gcc600: sdt::accumulate need numeric header `alca`  created: 2016-11-10 07:32:01 merged: 2016-11-10 09:19:42

57. [16535](http://github.com/cms-sw/cmssw/pull/16535){:target="_blank"}  from **@kpedro88**: Update 14 TeV relval workflows to Pythia8 `generators`  `pdmv`  created: 2016-11-09 17:46:49 merged: 2016-11-11 15:09:27

58. [16534](http://github.com/cms-sw/cmssw/pull/16534){:target="_blank"}  from **@cms-tsg-storm**:  Update of HLT menu (81X)  `alca`  `hlt`  created: 2016-11-09 17:40:43 merged: 2016-11-27 07:24:23

59. [16531](http://github.com/cms-sw/cmssw/pull/16531){:target="_blank"}  from **@bsunanda**: bsunanda:Phase2-gem20 Update the current proposal for GE21 as a Dev version `geometry`  created: 2016-11-09 14:17:37 merged: 2016-11-11 08:11:51

60. [16529](http://github.com/cms-sw/cmssw/pull/16529){:target="_blank"}  from **@idebruyn**: Added SiStrip Report maps for each error flag separately `dqm`  created: 2016-11-09 09:50:59 merged: 2016-11-16 08:41:58

61. [16528](http://github.com/cms-sw/cmssw/pull/16528){:target="_blank"}  from **@fioriNTU**: Adding files and modifications to count Zero Occupancy ROCs offline `dqm`  created: 2016-11-09 08:41:37 merged: 2016-11-16 08:40:29

62. [16526](http://github.com/cms-sw/cmssw/pull/16526){:target="_blank"}  from **@kpedro88**: Update SiPM parameters and fix a few bugs in hardcode conditions `alca`  `simulation`  created: 2016-11-08 22:25:48 merged: 2016-11-16 19:48:35

63. [16524](http://github.com/cms-sw/cmssw/pull/16524){:target="_blank"}  from **@bsunanda**: bsunanda:Phase2-hgx67 Correct reconstruction geometry for EE and FH with full coverage `dqm`  `geometry`  `reconstruction`  created: 2016-11-08 20:07:00 merged: 2016-11-17 18:03:36

64. [16523](http://github.com/cms-sw/cmssw/pull/16523){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-TB18 Correct the geometry for the second CERN 8 module TB Run `geometry`  created: 2016-11-08 20:01:44 merged: 2016-11-09 11:28:07

65. [16519](http://github.com/cms-sw/cmssw/pull/16519){:target="_blank"}  from **@schneiml**: Pixel Geometry Fixes `geometry`  created: 2016-11-08 14:50:49 merged: 2016-11-11 15:09:11

66. [16515](http://github.com/cms-sw/cmssw/pull/16515){:target="_blank"}  from **@deguio**: update to support sual fed readout `comparison`  `dqm`  created: 2016-11-08 14:00:04 merged: 2016-11-08 19:49:27

67. [16512](http://github.com/cms-sw/cmssw/pull/16512){:target="_blank"}  from **@thomreis**: Fix ProductNotFound error for RPC inputs to EMTF emulator in DQM workflow `dqm`  created: 2016-11-08 13:34:02 merged: 2016-11-14 16:43:11

68. [16508](http://github.com/cms-sw/cmssw/pull/16508){:target="_blank"}  from **@hengne**: update matrixInjector to adapt to wm parameter changes `pdmv`  created: 2016-11-08 12:27:43 merged: 2016-11-10 15:11:16

69. [16505](http://github.com/cms-sw/cmssw/pull/16505){:target="_blank"}  from **@mandrenguyen**: Switched to pp event content (81X) `pdmv`  created: 2016-11-08 07:06:47 merged: 2016-11-08 11:21:22

70. [16501](http://github.com/cms-sw/cmssw/pull/16501){:target="_blank"}  from **@lgray**: Factorize fast timing layer geometry dependent things from RECO algorithms. `geometry`  `operations`  `pdmv`  `simulation`  created: 2016-11-08 02:07:16 merged: 2016-11-11 09:46:03

71. [16499](http://github.com/cms-sw/cmssw/pull/16499){:target="_blank"}  from **@kpedro88**: Hcal dump calibrations `alca`  `db`  `reconstruction`  created: 2016-11-07 22:25:27 merged: 2016-11-12 16:11:06

72. [16498](http://github.com/cms-sw/cmssw/pull/16498){:target="_blank"}  from **@pmandrik**: Pythia8 shower weights and labels saving `generators`  created: 2016-11-07 21:19:49 merged: 2016-11-17 08:38:07

73. [16495](http://github.com/cms-sw/cmssw/pull/16495){:target="_blank"}  from **@VinInn**: Add profiles for chi2 `dqm`  created: 2016-11-07 17:26:01 merged: 2016-11-08 15:09:15

74. [16492](http://github.com/cms-sw/cmssw/pull/16492){:target="_blank"}  from **@makortel**: Remove inheritance in L1MuonPixelTrackFitter and L1MuonRegionProducer `reconstruction`  created: 2016-11-07 16:50:17 merged: 2016-11-10 19:59:42

75. [16491](http://github.com/cms-sw/cmssw/pull/16491){:target="_blank"}  from **@felicepantaleo**: Pixel Phase I - CA - improving fake rejection at high pt `reconstruction`  created: 2016-11-07 15:42:13 merged: 2016-11-23 08:35:54

76. [16488](http://github.com/cms-sw/cmssw/pull/16488){:target="_blank"}  from **@felicepantaleo**: DQM timing propagation `dqm`  created: 2016-11-07 13:33:09 merged: 2016-11-15 18:21:50

77. [16486](http://github.com/cms-sw/cmssw/pull/16486){:target="_blank"}  from **@davidlange6**: trivial unit test for both histogrammar and matplotlib `analysis`  created: 2016-11-07 12:31:49 merged: 2016-11-17 19:26:13

78. [16483](http://github.com/cms-sw/cmssw/pull/16483){:target="_blank"}  from **@archiron**: Renorm provenance histos 81 x v1 `dqm`  created: 2016-11-07 11:32:37 merged: 2016-11-09 09:21:07

79. [16480](http://github.com/cms-sw/cmssw/pull/16480){:target="_blank"}  from **@mohsinwaseem**: Repeated Bins in single muon trigger histos fixed `dqm`  created: 2016-11-06 22:35:44 merged: 2016-11-09 09:06:25

80. [16479](http://github.com/cms-sw/cmssw/pull/16479){:target="_blank"}  from **@mandrenguyen**: Fix to pA skim names (81X) `pdmv`  created: 2016-11-06 16:58:20 merged: 2016-11-07 09:46:24

81. [16476](http://github.com/cms-sw/cmssw/pull/16476){:target="_blank"}  from **@deguio**: Zdc task 81x `dqm`  created: 2016-11-05 17:47:22 merged: 2016-11-09 08:44:25

82. [16474](http://github.com/cms-sw/cmssw/pull/16474){:target="_blank"}  from **@calabria**: Fix to the Muon validation parameters `dqm`  created: 2016-11-05 16:35:13 merged: 2016-11-08 19:49:57

83. [16472](http://github.com/cms-sw/cmssw/pull/16472){:target="_blank"}  from **@mazarkin**: `qFix for reading  and dumping HcalTPParameters`alca`  created: 2016-11-04 15:49:27 merged: 2016-11-05 08:12:11

84. [16470](http://github.com/cms-sw/cmssw/pull/16470){:target="_blank"}  from **@ebrondol**: Fix phase2 pixel in GeometrySearch `reconstruction`  created: 2016-11-04 13:15:39 merged: 2016-11-22 16:49:28

85. [16468](http://github.com/cms-sw/cmssw/pull/16468){:target="_blank"}  from **@emiglior**: Pixel clusterizer configurable gain cmssw 81 x `reconstruction`  created: 2016-11-04 12:45:58 merged: 2016-11-05 08:20:22

86. [16466](http://github.com/cms-sw/cmssw/pull/16466){:target="_blank"}  from **@mandrenguyen**: Updated names of pA skims `pdmv`  created: 2016-11-04 12:10:59 merged: 2016-11-05 08:19:13

87. [16465](http://github.com/cms-sw/cmssw/pull/16465){:target="_blank"}  from **@smuzaffar**: Do not sort the das results if CMSSDT_DAS_CLIENT_NO_SORT env is set `pdmv`  created: 2016-11-04 11:19:49 merged: 2016-11-04 20:02:23

88. [16464](http://github.com/cms-sw/cmssw/pull/16464){:target="_blank"}  from **@matz-e**: HCAL 2017 HF TP dual-anode readout fixes. `comparison`  `l1`  created: 2016-11-04 10:29:07 merged: 2016-11-16 10:43:35

89. [16461](http://github.com/cms-sw/cmssw/pull/16461){:target="_blank"}  from **@kpedro88**: remove HcalUpgradeDataFrame and related classes/algos `alca`  `dqm`  `reconstruction`  `simulation`  created: 2016-11-04 03:37:10 merged: 2016-11-11 08:12:51

90. [16460](http://github.com/cms-sw/cmssw/pull/16460){:target="_blank"}  from **@makortel**: Fix 2017 design workflow for '-i all' `pdmv`  created: 2016-11-03 22:23:05 merged: 2016-11-05 16:54:30

91. [16453](http://github.com/cms-sw/cmssw/pull/16453){:target="_blank"}  from **@capalmer85**: PU distributions for train BXs in high PU fill 5412 `operations`  `simulation`  created: 2016-11-03 17:34:14 merged: 2016-11-15 17:26:25

92. [16449](http://github.com/cms-sw/cmssw/pull/16449){:target="_blank"}  from **@mmusich**: [81X] Primary Vertex Validation: enable choice of y-axis range from all-in-one tool `alca`  created: 2016-11-03 16:13:46 merged: 2016-11-04 08:41:18

93. [16446](http://github.com/cms-sw/cmssw/pull/16446){:target="_blank"}  from **@smdogra**: pACentrality DQM in 81X `dqm`  created: 2016-11-03 14:26:54 merged: 2016-11-08 19:46:16

94. [16445](http://github.com/cms-sw/cmssw/pull/16445){:target="_blank"}  from **@ghugo83**: Fixed supports composites in Flat and Tilted OT in 81X (negligeable effect on MB though) `geometry`  created: 2016-11-03 13:58:29 merged: 2016-11-08 15:10:25

95. [16443](http://github.com/cms-sw/cmssw/pull/16443){:target="_blank"}  from **@alberto-sanchez**: adding muon with trigger within the Onia2MuMu package -81x `analysis`  created: 2016-11-03 12:44:21 merged: 2016-11-09 08:41:40

96. [16436](http://github.com/cms-sw/cmssw/pull/16436){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-alca71 Correct the o/p for AlCaReco stream `alca`  created: 2016-11-02 16:40:14 merged: 2016-11-11 08:14:41

97. [16435](http://github.com/cms-sw/cmssw/pull/16435){:target="_blank"}  from **@cms-met**: JER MET uncertainties and METSignifiance re-estimation `analysis`  `reconstruction`  created: 2016-11-02 16:28:52 merged: 2016-11-17 08:43:16

98. [16431](http://github.com/cms-sw/cmssw/pull/16431){:target="_blank"}  from **@FHead**: HIN High-pT trigger DQM for 81X (CMSHLT-1110) `dqm`  created: 2016-11-02 15:39:57 merged: 2016-11-05 16:53:08

99. [16428](http://github.com/cms-sw/cmssw/pull/16428){:target="_blank"}  from **@varuns23**: PR for HLT online DQM monitoring code for Proton-Lead run in 81X (upd `dqm`  `hlt`  created: 2016-11-02 14:34:40 merged: 2016-11-05 16:52:35

100. [16425](http://github.com/cms-sw/cmssw/pull/16425){:target="_blank"}  from **@echapon**: Allow a boost on particles in MCParticlePairFilter `generators`  created: 2016-11-02 13:28:42 merged: 2016-11-17 19:47:16

101. [16418](http://github.com/cms-sw/cmssw/pull/16418){:target="_blank"}  from **@swayand**: Fixing code of tau embedding (TauAnalysis/MCEmbeddingTools) for run2 needs part2 `simulation`  created: 2016-11-01 23:48:15 merged: 2016-11-08 15:10:38

102. [16415](http://github.com/cms-sw/cmssw/pull/16415){:target="_blank"}  from **@illuzate**: HLTrigger for UPC Analysis for 81X Fix Final `dqm`  created: 2016-11-01 16:15:16 merged: 2016-11-04 08:41:58

103. [16407](http://github.com/cms-sw/cmssw/pull/16407){:target="_blank"}  from **@boudoul**: Extending the Phase2 2023D4 Workflow to Reco (up to Harvesting)  steps  `pdmv`  `reconstruction`  created: 2016-11-01 13:52:25 merged: 2016-11-08 08:40:30

104. [16393](http://github.com/cms-sw/cmssw/pull/16393){:target="_blank"}  from **@ferencek**: Reclustering of SiPixelClusters `reconstruction`  created: 2016-10-31 01:27:25 merged: 2016-11-27 07:22:36

105. [16392](http://github.com/cms-sw/cmssw/pull/16392){:target="_blank"}  from **@lowette**: Introduction of Lorentz Angle correction in Phase 2 CPE `reconstruction`  created: 2016-10-30 23:27:15 merged: 2016-11-17 07:06:13

106. [16389](http://github.com/cms-sw/cmssw/pull/16389){:target="_blank"}  from **@suchandradutta**: updated Digitizer framework adding (a) option to allow independent El `simulation`  created: 2016-10-29 19:43:18 merged: 2016-11-11 15:06:56

107. [16379](http://github.com/cms-sw/cmssw/pull/16379){:target="_blank"}  from **@mommsen**: Additional FED IDs for new pixel detector `daq`  created: 2016-10-28 08:47:05 merged: 2016-11-16 19:49:45

108. [16366](http://github.com/cms-sw/cmssw/pull/16366){:target="_blank"}  from **@wulsin**: Ensure GEANT simulation of exotic long-lived particles that decay outside beampipe `generators`  `simulation`  created: 2016-10-26 23:23:05 merged: 2016-11-11 15:06:33

109. [16354](http://github.com/cms-sw/cmssw/pull/16354){:target="_blank"}  from **@dildick**: ME0 re-digitizer module `core`  `simulation`  created: 2016-10-25 16:45:02 merged: 2016-11-16 07:38:27

110. [16351](http://github.com/cms-sw/cmssw/pull/16351){:target="_blank"}  from @mtosi: add customization function for highPU **@HLT** `hlt`  created: 2016-10-25 15:43:15 merged: 2016-11-22 17:03:29

111. [16343](http://github.com/cms-sw/cmssw/pull/16343){:target="_blank"}  from **@cms-AlCaDB**: [81X] Add Phase-I Cosmics `alca`  `dqm`  `pdmv`  `reconstruction`  `simulation`  created: 2016-10-25 13:12:16 merged: 2016-11-22 17:01:02

112. [16288](http://github.com/cms-sw/cmssw/pull/16288){:target="_blank"}  from **@goni**: [HIN Dilepton] pPb Run DQMOffline for 81X `dqm`  `reconstruction`  created: 2016-10-20 19:11:56 merged: 2016-11-08 16:56:59

113. [16286](http://github.com/cms-sw/cmssw/pull/16286){:target="_blank"}  from **@kencall**: Update to Hcal Validation `dqm`  created: 2016-10-20 17:28:42 merged: 2016-11-08 15:14:31

114. [16273](http://github.com/cms-sw/cmssw/pull/16273){:target="_blank"}  from **@dildick**: ME0 pseudo digitizer: Fix the BX mixing window + enable bkg scaling with lumi `simulation`  created: 2016-10-19 21:30:46 merged: 2016-11-27 07:23:40

115. [16184](http://github.com/cms-sw/cmssw/pull/16184){:target="_blank"}  from **@pieterdavid**: CalibTracker/SiStripESProducers edm::Service to ESProducer migration `alca`  `analysis`  `dqm`  created: 2016-10-12 08:40:40 merged: 2016-11-08 15:23:29

116. [16131](http://github.com/cms-sw/cmssw/pull/16131){:target="_blank"}  from **@cms-met**: 81x MET XY correction cond DB `analysis`  `db`  `reconstruction`  created: 2016-10-07 04:51:43 merged: 2016-11-05 16:53:33

117. [16010](http://github.com/cms-sw/cmssw/pull/16010){:target="_blank"}  from **@CTPPS**: CTPPS: detector id update `alca`  `db`  `dqm`  `geometry`  `reconstruction`  `simulation`  created: 2016-09-28 11:29:03 merged: 2016-11-15 08:20:59

118. [15876](http://github.com/cms-sw/cmssw/pull/15876){:target="_blank"}  from **@alberto-sanchez**: single particle filter, add needed features `generators`  created: 2016-09-16 13:08:01 merged: 2016-11-28 07:51:48

119. [15821](http://github.com/cms-sw/cmssw/pull/15821){:target="_blank"}  from **@gouskos**: add pixel roc occupancy dqm plots `dqm`  created: 2016-09-12 20:23:12 merged: 2016-11-11 19:09:25

120. [15461](http://github.com/cms-sw/cmssw/pull/15461){:target="_blank"}  from **@alberto-sanchez**: interface compatible with evtgen 1.6 `generators`  created: 2016-08-13 13:22:32 merged: 2016-11-28 07:55:56

121. [15049](http://github.com/cms-sw/cmssw/pull/15049){:target="_blank"}  from **@forthommel**: Set the input tag for the PileupSummaryInfo collection retrieval `analysis`  created: 2016-06-29 10:08:43 merged: 2016-11-14 18:52:39

122. [14924](http://github.com/cms-sw/cmssw/pull/14924){:target="_blank"}  from **@depasse**: PreShower tools for DBv2 `db`  created: 2016-06-20 10:31:01 merged: 2016-11-28 07:56:20

#### CMSDIST Changes between Tags REL/CMSSW_8_1_0_pre16/slc6_amd64_gcc530 and REL/CMSSW_8_1_0/slc6_amd64_gcc530:

[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_8_1_0_pre16/slc6_amd64_gcc530...REL/CMSSW_8_1_0/slc6_amd64_gcc530)



1. [2695](http://github.com/cms-sw/cmsdist/pull/2695){:target="_blank"}  from **@iahmad-khan**: updates RecoEgamma-ElectronIdentification to use new tag created: 2016-11-29 21:16:46 merged: 2016-12-01 08:22:58

2. [2671](http://github.com/cms-sw/cmsdist/pull/2671){:target="_blank"}  from **@smuzaffar**: apply readline6.3 fedoraproject patches created: 2016-11-23 07:18:24 merged: 2016-11-23 07:18:29

3. [2669](http://github.com/cms-sw/cmsdist/pull/2669){:target="_blank"}  from **@smuzaffar**: cleanup cms internal variables cms_cxx and cms_cxxflags created: 2016-11-22 12:24:25 merged: 2016-11-22 12:25:02

4. [2654](http://github.com/cms-sw/cmsdist/pull/2654){:target="_blank"}  from **@iahmad-khan**: updates openloops to 1.3.1 created: 2016-11-15 18:09:59 merged: 2016-11-16 07:33:02

5. [2647](http://github.com/cms-sw/cmsdist/pull/2647){:target="_blank"}  from **@cms-sw**: update frontier client to remove the unused patch created: 2016-11-10 22:00:22 merged: 2016-11-10 22:00:26

6. [2646](http://github.com/cms-sw/cmsdist/pull/2646){:target="_blank"}  from **@cms-sw**: update icc to version 2017.0.098 created: 2016-11-10 21:53:50 merged: 2016-11-10 21:53:54

7. [2644](http://github.com/cms-sw/cmsdist/pull/2644){:target="_blank"}  from **@smuzaffar**: updated frontier client to 2.8.20 created: 2016-11-09 23:46:10 merged: 2016-11-10 21:54:42

8. [2556](http://github.com/cms-sw/cmsdist/pull/2556){:target="_blank"}  from **@xjanssen**: Rivet 2.5.2 and Yoda 1.6.5 created: 2016-10-05 09:55:25 merged: 2016-11-22 09:35:17
