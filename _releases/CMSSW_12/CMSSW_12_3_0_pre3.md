---
layout: post
rel_link:  "12_3_0_pre3"
title:  "CMSSW_12_3_0_pre3"
date:   2022-01-18 13:07:17
categories: cmssw
relmajor: 12
relminor: 3
relsubminor: 0
relpre: _pre3
---

# CMSSW_12_3_0_pre3
#### Changes since CMSSW_12_3_0_pre2:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_12_3_0_pre2...CMSSW_12_3_0_pre3)



1. [36722](http://github.com/cms-sw/cmssw/pull/36722){:target="_blank"}  from **@Sam-Harper**: bug fix for hltIntegration tests when using a setup menu : 12_3_X `hlt` created: 2022-01-17 14:00:08 merged: 2022-01-18 00:35:11

2. [36720](http://github.com/cms-sw/cmssw/pull/36720){:target="_blank"}  from **@bsunanda**: Run3-alca215 Provide possibility of using ECAL RecHit thresholds used by particle flow group in Hcal Calibration code `alca` `operations` created: 2022-01-17 02:00:25 merged: 2022-01-18 06:33:45

3. [36717](http://github.com/cms-sw/cmssw/pull/36717){:target="_blank"}  from **@civanch**: Updated Exceptions for SIM step `simulation` created: 2022-01-16 13:08:41 merged: 2022-01-17 09:41:24

4. [36714](http://github.com/cms-sw/cmssw/pull/36714){:target="_blank"}  from **@AdrianoDee**: Fix to 39434.502/501 `reconstruction` created: 2022-01-14 19:14:20 merged: 2022-01-17 12:54:21

5. [36710](http://github.com/cms-sw/cmssw/pull/36710){:target="_blank"}  from **@malbouis**: Include PF HLT Calibration and new EGM Regression in mcRun3 and mcRun4 GTs `alca` created: 2022-01-14 16:06:06 merged: 2022-01-17 03:20:31

6. [36704](http://github.com/cms-sw/cmssw/pull/36704){:target="_blank"}  from **@NiharSaha**: Drop type specs for RecoMuon `dqm` created: 2022-01-14 09:54:53 merged: 2022-01-17 18:45:37

7. [36701](http://github.com/cms-sw/cmssw/pull/36701){:target="_blank"}  from **@smuzaffar**: use std::isnan to avoid cs8 + boost1.78.0 build errors `db` created: 2022-01-13 21:18:20 merged: 2022-01-14 10:17:18

8. [36696](http://github.com/cms-sw/cmssw/pull/36696){:target="_blank"}  from **@perrotta**: Fix TEST_DIR in a CalibPPS/TimingCalibration unit test `alca` created: 2022-01-12 14:38:47 merged: 2022-01-13 11:03:32

9. [36695](http://github.com/cms-sw/cmssw/pull/36695){:target="_blank"}  from **@mmusich**: get rid of CMSDEPRECATED_X warnings from `EventFilter/Si*RawToDigi` `reconstruction` created: 2022-01-12 11:56:04 merged: 2022-01-13 13:58:00

10. [36691](http://github.com/cms-sw/cmssw/pull/36691){:target="_blank"}  from **@NiharSaha**: Drop type specs for L1Trigger `dqm` `l1` created: 2022-01-11 21:34:31 merged: 2022-01-17 09:32:42

11. [36690](http://github.com/cms-sw/cmssw/pull/36690){:target="_blank"}  from **@Dr15Jones**: Added a unique ID to ComponentDescription `core` created: 2022-01-11 21:33:06 merged: 2022-01-12 15:06:52

12. [36689](http://github.com/cms-sw/cmssw/pull/36689){:target="_blank"}  from **@Dr15Jones**: Move Reco code to use oneapi/tbb headers `reconstruction` `upgrade` created: 2022-01-11 19:50:22 merged: 2022-01-12 15:07:33

13. [36688](http://github.com/cms-sw/cmssw/pull/36688){:target="_blank"}  from **@Dr15Jones**: Moved Mixing code to use oneapi/tbb headers `simulation` created: 2022-01-11 19:46:55 merged: 2022-01-12 08:41:41

14. [36687](http://github.com/cms-sw/cmssw/pull/36687){:target="_blank"}  from **@Dr15Jones**: Move HeterogeneousCore code to use oneapi/tbb headers `heterogeneous` created: 2022-01-11 19:44:52 merged: 2022-01-12 00:42:12

15. [36686](http://github.com/cms-sw/cmssw/pull/36686){:target="_blank"}  from **@Dr15Jones**: Move common code to use oneapi/tbb headers `reconstruction` created: 2022-01-11 19:42:13 merged: 2022-01-12 15:08:04

16. [36685](http://github.com/cms-sw/cmssw/pull/36685){:target="_blank"}  from **@Dr15Jones**: Move conditions code to use oneapi/tbb headers `alca` `db` created: 2022-01-11 19:39:25 merged: 2022-01-17 03:17:53

17. [36684](http://github.com/cms-sw/cmssw/pull/36684){:target="_blank"}  from **@Dr15Jones**: Move L1 code to use oneapi/tbb headers `l1` `upgrade` created: 2022-01-11 19:36:38 merged: 2022-01-13 10:11:51

18. [36683](http://github.com/cms-sw/cmssw/pull/36683){:target="_blank"}  from **@Dr15Jones**: Move HLTrigger to use oneapi/tbb headers `hlt` created: 2022-01-11 19:32:00 merged: 2022-01-12 08:41:56

19. [36682](http://github.com/cms-sw/cmssw/pull/36682){:target="_blank"}  from **@Dr15Jones**: Move EventFilter to use oneapi/tbb headers `daq` `reconstruction` created: 2022-01-11 19:28:08 merged: 2022-01-12 15:08:42

20. [36681](http://github.com/cms-sw/cmssw/pull/36681){:target="_blank"}  from **@Dr15Jones**: Move GeneratorInterface to use oneapi/tbb headers `generators` created: 2022-01-11 19:24:10 merged: 2022-01-12 08:44:01

21. [36680](http://github.com/cms-sw/cmssw/pull/36680){:target="_blank"}  from **@bsunanda**: Run3-gex112 Correction to some of the Forward detector SD's for the dd4hep scenarios `simulation` created: 2022-01-11 19:06:30 merged: 2022-01-12 20:39:41

22. [36678](http://github.com/cms-sw/cmssw/pull/36678){:target="_blank"}  from **@Dr15Jones**: Move PhysicsTools to use oneapi/tbb headers `analysis` `reconstruction` `xpog` created: 2022-01-11 18:45:24 merged: 2022-01-12 09:28:10

23. [36677](http://github.com/cms-sw/cmssw/pull/36677){:target="_blank"}  from **@Dr15Jones**: Removed unnecessary headers in SimG4Core/Application `simulation` created: 2022-01-11 18:42:38 merged: 2022-01-12 08:43:26

24. [36676](http://github.com/cms-sw/cmssw/pull/36676){:target="_blank"}  from **@Dr15Jones**: Moved DetectorDescription/Core to use oneapi/tbb headers `geometry` created: 2022-01-11 18:37:26 merged: 2022-01-14 00:35:04

25. [36675](http://github.com/cms-sw/cmssw/pull/36675){:target="_blank"}  from **@Dr15Jones**: Move DQM to use oneapi/tbb headers `dqm` created: 2022-01-11 18:33:03 merged: 2022-01-12 20:26:41

26. [36674](http://github.com/cms-sw/cmssw/pull/36674){:target="_blank"}  from **@NiharSaha**: Drop type specs for Muon and RecoB `dqm` created: 2022-01-11 17:30:33 merged: 2022-01-12 17:18:21

27. [36672](http://github.com/cms-sw/cmssw/pull/36672){:target="_blank"}  from **@NiharSaha**: Drop type specs for GEM `dqm` created: 2022-01-11 15:53:27 merged: 2022-01-11 20:37:42

28. [36671](http://github.com/cms-sw/cmssw/pull/36671){:target="_blank"}  from **@bsunanda**: Run3-alca213X Modify many of the loops as Range based loops in Calibration/HcalCalibAlgos `alca` created: 2022-01-11 15:52:28 merged: 2022-01-15 16:41:22

29. [36668](http://github.com/cms-sw/cmssw/pull/36668){:target="_blank"}  from **@mmusich**: fix axis label titles in `Phase2ITValidateRecHitBase` `dqm` created: 2022-01-11 13:25:58 merged: 2022-01-11 18:30:45

30. [36666](http://github.com/cms-sw/cmssw/pull/36666){:target="_blank"}  from **@sarafiorendi**: Add HLT filter to select online pf taus based on their impact parameter `hlt` created: 2022-01-10 18:29:20 merged: 2022-01-18 00:39:12

31. [36664](http://github.com/cms-sw/cmssw/pull/36664){:target="_blank"}  from **@bsunanda**: Run3-gex111X Small fix for muon numbering to be used for Run3 MC with demo chambers `geometry` created: 2022-01-10 15:48:27 merged: 2022-01-11 06:50:17

32. [36663](http://github.com/cms-sw/cmssw/pull/36663){:target="_blank"}  from **@bsunanda**: Run3-gex110X Take care of Carl's comment for PR #36648 `geometry` created: 2022-01-10 14:29:50 merged: 2022-01-11 06:48:23

33. [36659](http://github.com/cms-sw/cmssw/pull/36659){:target="_blank"}  from **@civanch**: Fixed INCLXX physics configurations `simulation` created: 2022-01-10 10:07:00 merged: 2022-01-11 09:03:57

34. [36658](http://github.com/cms-sw/cmssw/pull/36658){:target="_blank"}  from **@missirol**: fixes for recent updates to `CkfTrackCandidateMaker` `reconstruction` created: 2022-01-09 23:42:33 merged: 2022-01-11 12:44:44

35. [36657](http://github.com/cms-sw/cmssw/pull/36657){:target="_blank"}  from **@missirol**: technical fix for value of L1T's `caloParams.jetPUSUsePhiRing` `l1` created: 2022-01-09 10:16:42 merged: 2022-01-10 13:36:25

36. [36656](http://github.com/cms-sw/cmssw/pull/36656){:target="_blank"}  from **@jfernan2**: [DQM] Fixing currdir for Validation/RecoVertex/src/BeamSpotHistogramMaker.cc `dqm` created: 2022-01-09 10:01:44 merged: 2022-01-09 18:01:39

37. [36653](http://github.com/cms-sw/cmssw/pull/36653){:target="_blank"}  from **@bsunanda**: Run3-gex111  Modify xml's to enable the dd4hep version to work in Geometry/ForwardCommonData and Geometry/MuonCommonData `geometry` created: 2022-01-08 22:40:20 merged: 2022-01-09 17:53:39

38. [36652](http://github.com/cms-sw/cmssw/pull/36652){:target="_blank"}  from **@bsunanda**: Run3-sim102 Make runtime variables to allow/disallow creation of SimHits for demonstration chambers `simulation` created: 2022-01-08 22:14:22 merged: 2022-01-12 09:29:53

39. [36651](http://github.com/cms-sw/cmssw/pull/36651){:target="_blank"}  from **@NiharSaha**: Drop type specs for JetMET `dqm` created: 2022-01-08 20:36:56 merged: 2022-01-09 22:37:55

40. [36648](http://github.com/cms-sw/cmssw/pull/36648){:target="_blank"}  from **@bsunanda**: Run3-gex110 Recover BHM placements in the dd4hep scenario `geometry` created: 2022-01-07 18:09:34 merged: 2022-01-08 14:56:30

41. [36645](http://github.com/cms-sw/cmssw/pull/36645){:target="_blank"}  from **@apsallid**: [HGCAL] Updates due to V16 geometry `dqm` `geometry` `simulation` created: 2022-01-07 11:31:58 merged: 2022-01-11 20:32:06

42. [36643](http://github.com/cms-sw/cmssw/pull/36643){:target="_blank"}  from **@cecilecaillol**: L1T run-3: Store EMTF displacement info in L1TNtuples TFTree `l1` created: 2022-01-07 09:19:00 merged: 2022-01-14 10:29:20

43. [36642](http://github.com/cms-sw/cmssw/pull/36642){:target="_blank"}  from **@cecilecaillol**: L1T run-3: updated L1T boosted jets `l1` created: 2022-01-07 08:48:09 merged: 2022-01-14 17:32:12

44. [36641](http://github.com/cms-sw/cmssw/pull/36641){:target="_blank"}  from **@bsunanda**: Run3-alca214 Test automatic setting ECAL RecHit thresholds as defined by PFlow group `alca` created: 2022-01-06 22:53:05 merged: 2022-01-15 20:35:31

45. [36638](http://github.com/cms-sw/cmssw/pull/36638){:target="_blank"}  from **@Dr15Jones**: Use thread safe module types in PhysicsTools/JetMCAlgos `analysis` created: 2022-01-05 20:49:01 merged: 2022-01-09 18:54:55

46. [36637](http://github.com/cms-sw/cmssw/pull/36637){:target="_blank"}  from **@Dr15Jones**: initialize members of TableOutputBranches `xpog` created: 2022-01-05 19:53:46 merged: 2022-01-06 18:15:54

47. [36636](http://github.com/cms-sw/cmssw/pull/36636){:target="_blank"}  from **@Dr15Jones**: Use proper long long type when validating Parameter `core` created: 2022-01-05 18:50:41 merged: 2022-01-06 18:13:29

48. [36635](http://github.com/cms-sw/cmssw/pull/36635){:target="_blank"}  from **@NiharSaha**: Drop type specs for Alignment and EGamma `dqm` created: 2022-01-05 16:51:36 merged: 2022-01-09 18:24:24

49. [36634](http://github.com/cms-sw/cmssw/pull/36634){:target="_blank"}  from **@bsunanda**: Run3-gex109F Try to avoid compilation warnings in some Validation codes in RecoPixelVertexing, RecoVertex, TrackerDigis `dqm` created: 2022-01-05 16:38:03 merged: 2022-01-06 18:24:07

50. [36633](http://github.com/cms-sw/cmssw/pull/36633){:target="_blank"}  from **@Dr15Jones**: EventSetupInitTrait can now have state `analysis` `reconstruction` created: 2022-01-05 16:31:46 merged: 2022-01-12 00:41:23

51. [36629](http://github.com/cms-sw/cmssw/pull/36629){:target="_blank"}  from **@bsunanda**: Run3-alca212C Make edm::Service<TFileService> as a local variable in the methods used in the classes of Calibration/HcalCalibAlgos `alca` created: 2022-01-04 14:46:44 merged: 2022-01-07 10:01:30

52. [36628](http://github.com/cms-sw/cmssw/pull/36628){:target="_blank"}  from **@seungjin-yang**: Migrate to EventSetup with ESGetToken in GEMCSCSegmentProducer `reconstruction` `upgrade` created: 2022-01-04 13:33:41 merged: 2022-01-12 18:34:06

53. [36627](http://github.com/cms-sw/cmssw/pull/36627){:target="_blank"}  from **@seungjin-yang**: Move GEM offline DQM files from DQMOffline/Muon to DQM/GEM `dqm` created: 2022-01-04 13:08:20 merged: 2022-01-08 14:21:40

54. [36626](http://github.com/cms-sw/cmssw/pull/36626){:target="_blank"}  from **@jeongeun**: Migrate module config in DPGAnalysis to use default cfipy `dqm` `reconstruction` created: 2022-01-04 11:52:08 merged: 2022-01-05 17:52:13

55. [36625](http://github.com/cms-sw/cmssw/pull/36625){:target="_blank"}  from **@missirol**: removed dummy `python/` dirs in `HLTrigger/` `hlt` created: 2022-01-03 19:22:23 merged: 2022-01-06 18:05:53

56. [36624](http://github.com/cms-sw/cmssw/pull/36624){:target="_blank"}  from **@bsunanda**: Run3-gex109E Avoid compilation warnings in some Validation classes in EventGenerator, Mixing and MtdValidation `dqm` `generators` created: 2022-01-03 19:17:32 merged: 2022-01-11 02:44:38

57. [36623](http://github.com/cms-sw/cmssw/pull/36623){:target="_blank"}  from **@bsunanda**: Phase2-hgx297E Update the test configuration in Geometry/HGCalGeometry `geometry` `upgrade` created: 2022-01-03 16:39:27 merged: 2022-01-04 13:05:24

58. [36622](http://github.com/cms-sw/cmssw/pull/36622){:target="_blank"}  from **@bsunanda**: Run3-alca212B Remove compilation warnings in the clases of EcalAlCaRecoProducers|EcalCalibAlgos within Calibration `alca` created: 2022-01-01 20:51:32 merged: 2022-01-04 02:16:54

59. [36621](http://github.com/cms-sw/cmssw/pull/36621){:target="_blank"}  from **@bsunanda**: Run3-alca213 Complete the validation of the new AlCaReco for HcalIsoTrackFilter `alca` created: 2022-01-01 20:01:17 merged: 2022-01-10 01:26:59

60. [36620](http://github.com/cms-sw/cmssw/pull/36620){:target="_blank"}  from **@Dr15Jones**: Fix CMS deprecated warnings in  L1Trigger/GlobalCaloTrigger `l1` created: 2021-12-31 20:21:01 merged: 2022-01-05 08:47:39

61. [36619](http://github.com/cms-sw/cmssw/pull/36619){:target="_blank"}  from **@Dr15Jones**: Converted modules to thread efficient types in  HLTrigger/special `hlt` created: 2021-12-31 16:38:52 merged: 2022-01-04 01:25:20

62. [36618](http://github.com/cms-sw/cmssw/pull/36618){:target="_blank"}  from **@perrotta**: Initialize variables, and a few other trivial adjustments in RecoRomanPot/RecoFP420 `reconstruction` created: 2021-12-31 14:45:20 merged: 2022-01-04 13:03:22

63. [36617](http://github.com/cms-sw/cmssw/pull/36617){:target="_blank"}  from **@bsunanda**: Run3-gex109D Try to remove compilation warnings in Validation/GlobalXXXX `dqm` created: 2021-12-29 21:48:54 merged: 2021-12-31 02:14:46

64. [36616](http://github.com/cms-sw/cmssw/pull/36616){:target="_blank"}  from **@bsunanda**: Run3-alca212 Remove compilation warnings in Calibration/HcalCalibAlgos and Calibration/HcalIsolatedTrackReco `alca` created: 2021-12-29 21:45:50 merged: 2021-12-30 18:15:40

65. [36615](http://github.com/cms-sw/cmssw/pull/36615){:target="_blank"}  from **@Dr15Jones**: Fix CMS deprecated warnings in DQM/SiStripMonitorHardware `dqm` created: 2021-12-29 20:35:23 merged: 2021-12-31 02:11:31

66. [36614](http://github.com/cms-sw/cmssw/pull/36614){:target="_blank"}  from **@Dr15Jones**: Removed unnecessary includes in DQM/DTMonitorClient `dqm` created: 2021-12-29 16:54:02 merged: 2021-12-31 02:15:46

67. [36613](http://github.com/cms-sw/cmssw/pull/36613){:target="_blank"}  from **@Dr15Jones**: Removed unnecessary includes in DQM/L1TMonitor `dqm` created: 2021-12-29 15:33:02 merged: 2021-12-31 02:12:11

68. [36611](http://github.com/cms-sw/cmssw/pull/36611){:target="_blank"}  from **@makortel**: Use std::invoke_result_t instead of std::result_of in pixelTopology.h `geometry` created: 2021-12-29 15:20:31 merged: 2021-12-31 02:13:22

69. [36610](http://github.com/cms-sw/cmssw/pull/36610){:target="_blank"}  from **@cms-sw**: Revert "Add CorrThreeBodyByTwoBodyCondition." `l1` created: 2021-12-28 19:19:04 merged: 2021-12-29 08:22:29

70. [36609](http://github.com/cms-sw/cmssw/pull/36609){:target="_blank"}  from **@bsunanda**: Run3-Sim101G Avoid compilation warnings in some of the codes of Validation/RecoEgamma `dqm` created: 2021-12-28 19:05:25 merged: 2021-12-31 02:17:01

71. [36608](http://github.com/cms-sw/cmssw/pull/36608){:target="_blank"}  from **@bsunanda**: Run3-Sim101F Avoid compilation warnings in some of the codes of Validation/RecoTau `dqm` created: 2021-12-28 17:29:22 merged: 2022-01-07 19:05:45

72. [36607](http://github.com/cms-sw/cmssw/pull/36607){:target="_blank"}  from **@AdrianoDee**: Fixing Phase-II Patatrack Failures `reconstruction` `heterogeneous` created: 2021-12-28 16:29:51 merged: 2022-01-10 14:57:13

73. [36603](http://github.com/cms-sw/cmssw/pull/36603){:target="_blank"}  from **@davidlange6**: Add missing includes uncovered by checking boost 1.78 `alca` `core` created: 2021-12-28 08:26:08 merged: 2021-12-30 00:29:51

74. [36602](http://github.com/cms-sw/cmssw/pull/36602){:target="_blank"}  from **@bsunanda**: Run3-Sim101E Remove warnings in a few classes of SimTracker/SiPixelDigitizer `simulation` created: 2021-12-27 22:24:13 merged: 2022-01-02 17:32:06

75. [36601](http://github.com/cms-sw/cmssw/pull/36601){:target="_blank"}  from **@bsunanda**: Run3-Sim101D Remove the compilation warnings in SimMuon/MCTruth `simulation` created: 2021-12-27 21:55:22 merged: 2022-01-02 17:32:20

76. [36600](http://github.com/cms-sw/cmssw/pull/36600){:target="_blank"}  from **@bsunanda**: Run3-Sim101C Avoid compilation warnings in SimMuon/GEMDigitizer and SimMuon/RPCDigitizer `simulation` `upgrade` created: 2021-12-27 19:46:13 merged: 2022-01-07 19:04:08

77. [36599](http://github.com/cms-sw/cmssw/pull/36599){:target="_blank"}  from **@bsunanda**: Run3-sim101B Remove some compilation warnings in SimGeneral/TrackingAnalysis `simulation` created: 2021-12-27 17:23:17 merged: 2022-01-02 17:35:15

78. [36598](http://github.com/cms-sw/cmssw/pull/36598){:target="_blank"}  from **@bsunanda**: Run3-sim101A Remove some compilation warnings in classes from SimCalorimetry and SimGeneral `l1` `simulation` `upgrade` created: 2021-12-27 17:20:24 merged: 2022-01-07 19:04:21

79. [36595](http://github.com/cms-sw/cmssw/pull/36595){:target="_blank"}  from **@bsunanda**: Run3-gex109C Avoid compilation warnings in some of the Validation classes `dqm` `geometry` created: 2021-12-26 18:07:27 merged: 2021-12-27 13:49:32

80. [36594](http://github.com/cms-sw/cmssw/pull/36594){:target="_blank"}  from **@bsunanda**: Run3-gex109B Avoid compilation warnings in some Validation code `dqm` `l1` created: 2021-12-26 14:36:47 merged: 2022-01-05 18:06:19

81. [36593](http://github.com/cms-sw/cmssw/pull/36593){:target="_blank"}  from **@bsunanda**: Run3-gex109A Avoid some compilation warnings in Validation codes `dqm` created: 2021-12-26 14:33:19 merged: 2021-12-27 15:51:59

82. [36592](http://github.com/cms-sw/cmssw/pull/36592){:target="_blank"}  from **@swagata87**: Small fix in ECAL recHit collection names in PFECALSuperClusterProducer `reconstruction` created: 2021-12-26 13:01:46 merged: 2021-12-28 21:02:28

83. [36591](http://github.com/cms-sw/cmssw/pull/36591){:target="_blank"}  from **@bsunanda**: Run3-gem66 Update the validation code in Validation/MuonGEMDigis with better protection `dqm` created: 2021-12-24 17:26:25 merged: 2021-12-26 09:26:32

84. [36589](http://github.com/cms-sw/cmssw/pull/36589){:target="_blank"}  from **@civanch**: PPS transport update `simulation` created: 2021-12-24 15:24:21 merged: 2022-01-04 17:06:44

85. [36588](http://github.com/cms-sw/cmssw/pull/36588){:target="_blank"}  from **@NiharSaha**: Drop type specs for L1TMonitor and L1TMonitorClient `dqm` created: 2021-12-24 15:15:47 merged: 2022-01-04 13:12:15

86. [36587](http://github.com/cms-sw/cmssw/pull/36587){:target="_blank"}  from **@JanFSchulte**: Bugfix for DNN-based outside-in track seed generator for Muon HLT `reconstruction` created: 2021-12-24 13:49:46 merged: 2021-12-28 21:06:25

87. [36586](http://github.com/cms-sw/cmssw/pull/36586){:target="_blank"}  from **@Dr15Jones**: Remove CMS deprecated warnings from RecoRomanPot/RecoFP420 `reconstruction` created: 2021-12-23 21:54:24 merged: 2021-12-30 16:56:30

88. [36584](http://github.com/cms-sw/cmssw/pull/36584){:target="_blank"}  from **@Dr15Jones**: Removed CMS deprecated warnings from RecoTracker/TrackProducer `reconstruction` created: 2021-12-23 20:08:24 merged: 2021-12-26 01:39:31

89. [36583](http://github.com/cms-sw/cmssw/pull/36583){:target="_blank"}  from **@Dr15Jones**: Removed CMS deprecated warnings from RecoTracker/NuclearSeedGenerator `reconstruction` created: 2021-12-23 17:58:47 merged: 2021-12-29 00:36:33

90. [36582](http://github.com/cms-sw/cmssw/pull/36582){:target="_blank"}  from **@Dr15Jones**: Fixed CMS Deprecated warnings in RecoTracker/DebugTools `reconstruction` created: 2021-12-23 15:24:14 merged: 2022-01-13 16:30:51

91. [36579](http://github.com/cms-sw/cmssw/pull/36579){:target="_blank"}  from **@mmusich**: Removed CMS deprecated warnings from `RecoLocalTracker` `reconstruction` `upgrade` created: 2021-12-22 21:21:05 merged: 2022-01-17 09:27:13

92. [36578](http://github.com/cms-sw/cmssw/pull/36578){:target="_blank"}  from **@bsunanda**: Phase2-gex106 Remove BSC from Phase2 scenario and will be used in any new scenarios from now on `geometry` `upgrade` created: 2021-12-22 21:00:05 merged: 2022-01-08 14:59:30

93. [36577](http://github.com/cms-sw/cmssw/pull/36577){:target="_blank"}  from **@Dr15Jones**: Removed CMS deprecated warnings from  RecoEGamma/Examples `reconstruction` created: 2021-12-22 19:58:06 merged: 2021-12-26 01:38:16

94. [36576](http://github.com/cms-sw/cmssw/pull/36576){:target="_blank"}  from **@Dr15Jones**: Remove CMS deprecation warnings from RecoBTag/PerformanceDB `reconstruction` created: 2021-12-22 18:32:23 merged: 2021-12-26 01:40:21

95. [36575](http://github.com/cms-sw/cmssw/pull/36575){:target="_blank"}  from **@bsunanda**: Phase2-hgx297D Remove unused includes in Validation/HGCalValidation `dqm` created: 2021-12-22 16:42:11 merged: 2021-12-23 08:57:41

96. [36573](http://github.com/cms-sw/cmssw/pull/36573){:target="_blank"}  from **@bsunanda**: Run3-gex105D Make use of ESGetToken in DetectorDescription/OfflineDBLoader `geometry` created: 2021-12-22 14:12:07 merged: 2021-12-24 17:29:23

97. [36572](http://github.com/cms-sw/cmssw/pull/36572){:target="_blank"}  from **@bsunanda**: Run3-gex105C Use ESGetToken in Geometry/CMSCommonData `geometry` `upgrade` created: 2021-12-22 14:07:06 merged: 2021-12-23 08:56:37

98. [36570](http://github.com/cms-sw/cmssw/pull/36570){:target="_blank"}  from **@makortel**: Add processGUID() singleton, and use it in InputSource, StatisticsSenderService, and CondorStatusService `core` created: 2021-12-21 23:08:03 merged: 2021-12-23 08:55:52

99. [36569](http://github.com/cms-sw/cmssw/pull/36569){:target="_blank"}  from **@bsunanda**: Run3-gex105B Use ESGetToken in SimTracker/TrackerMaterialAnalysis `simulation` created: 2021-12-21 21:26:33 merged: 2021-12-22 10:40:07

100. [36568](http://github.com/cms-sw/cmssw/pull/36568){:target="_blank"}  from **@Dr15Jones**: Migrate to new oneapi naming `core` created: 2021-12-21 21:08:47 merged: 2021-12-23 15:25:22

101. [36566](http://github.com/cms-sw/cmssw/pull/36566){:target="_blank"}  from **@bsunanda**: Run3-gex105A Make use of ESGetToken in GeometryReaders/XMLIdealGeometryESSource `geometry` created: 2021-12-21 19:56:37 merged: 2021-12-22 10:37:52

102. [36565](http://github.com/cms-sw/cmssw/pull/36565){:target="_blank"}  from **@mmusich**: Further optimization of the SiPixel LA PCL workflow `alca` created: 2021-12-21 17:34:23 merged: 2022-01-04 16:34:23

103. [36564](http://github.com/cms-sw/cmssw/pull/36564){:target="_blank"}  from **@bsunanda**: Run3-gex104 Modify xml files for plt, bcmf to be included for run3 scenario and test how removal of  bsc detector from the scenario can be made effective `geometry` created: 2021-12-21 16:18:06 merged: 2021-12-22 12:59:06

104. [36563](http://github.com/cms-sw/cmssw/pull/36563){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `12_3_X` `hlt` created: 2021-12-21 15:51:01 merged: 2021-12-23 14:16:18

105. [36562](http://github.com/cms-sw/cmssw/pull/36562){:target="_blank"}  from **@Dr15Jones**: Removed unused member BaseHolder::fillRefIfMyTypeMatches `core` created: 2021-12-21 15:18:25 merged: 2021-12-22 00:27:38

106. [36560](http://github.com/cms-sw/cmssw/pull/36560){:target="_blank"}  from **@slehti**: HLTTauDQM: ignoring modules starting with '-' (modules inside cms.ign `dqm` created: 2021-12-21 12:03:40 merged: 2021-12-24 07:38:37

107. [36559](http://github.com/cms-sw/cmssw/pull/36559){:target="_blank"}  from **@errai-**: Correcting a JEC indexing bug for the pat::Jet class in association to scaleEnergy function calls `reconstruction` created: 2021-12-21 04:43:41 merged: 2022-01-08 07:34:59

108. [36556](http://github.com/cms-sw/cmssw/pull/36556){:target="_blank"}  from **@ggovi**: CondDBESSources: reworked refresh for updated lumi-based conditions `alca` `db` created: 2021-12-20 21:10:18 merged: 2022-01-15 07:16:36

109. [36555](http://github.com/cms-sw/cmssw/pull/36555){:target="_blank"}  from **@bsunanda**: Run3-gex103 Use of ESGetToken in Validation/Geometry and updating the cfg's `dqm` `geometry` created: 2021-12-20 16:49:49 merged: 2021-12-22 00:29:19

110. [36553](http://github.com/cms-sw/cmssw/pull/36553){:target="_blank"}  from **@zuoxunwu**: Expand L1T Shower data vs emulator comparison DQM `dqm` `l1` created: 2021-12-20 10:47:33 merged: 2022-01-17 13:52:14

111. [36551](http://github.com/cms-sw/cmssw/pull/36551){:target="_blank"}  from **@bsunanda**: Run3-gem66 Update the production cut files for run3 muon system `geometry` created: 2021-12-19 19:39:18 merged: 2021-12-23 00:49:38

112. [36550](http://github.com/cms-sw/cmssw/pull/36550){:target="_blank"}  from **@davidlange6**: add missing include in RefHolder_.h needed for gcc10/modules  `core` created: 2021-12-19 16:20:36 merged: 2021-12-20 14:50:12

113. [36549](http://github.com/cms-sw/cmssw/pull/36549){:target="_blank"}  from **@cvuosalo**: [DD4hep] Follow-up to #36496 -- Update versions of materials files in unit tests `geometry` `reconstruction` created: 2021-12-18 20:45:35 merged: 2021-12-20 14:48:27

114. [36548](http://github.com/cms-sw/cmssw/pull/36548){:target="_blank"}  from **@cvuosalo**: [DD4hep] Resolve static analyzer warning by protecting against divide by 0 `geometry` created: 2021-12-17 23:15:45 merged: 2021-12-21 00:39:18

115. [36543](http://github.com/cms-sw/cmssw/pull/36543){:target="_blank"}  from **@NiharSaha**: Drop type specs in HLTEvF, MuonMonitor and Physics `dqm` `hlt` created: 2021-12-17 18:49:05 merged: 2021-12-20 00:50:41

116. [36541](http://github.com/cms-sw/cmssw/pull/36541){:target="_blank"}  from **@malbouis**: include MuonDQM AlCaRecoTriggerBits in mcRun3 and mcRun4 GTs `alca` created: 2021-12-17 17:15:21 merged: 2021-12-18 01:44:32

117. [36540](http://github.com/cms-sw/cmssw/pull/36540){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `12_3_X` + migration to `12_3_0_pre2` template `hlt` created: 2021-12-17 16:24:00 merged: 2021-12-18 09:10:27

118. [36539](http://github.com/cms-sw/cmssw/pull/36539){:target="_blank"}  from **@Dr15Jones**: Customize concurrency for ESSource DataProxies `analysis` `core` created: 2021-12-17 16:00:56 merged: 2021-12-21 21:23:41

119. [36538](http://github.com/cms-sw/cmssw/pull/36538){:target="_blank"}  from **@mmusich**: Several updates to SiPixel LA PCL workflow `alca` created: 2021-12-17 14:16:45 merged: 2021-12-21 10:23:52

120. [36537](http://github.com/cms-sw/cmssw/pull/36537){:target="_blank"}  from **@ChrisMisan**: Calibration record for diamond-hptdc nonlinearities compensation `alca` `db` created: 2021-12-17 14:01:48 merged: 2021-12-21 10:32:33

121. [36536](http://github.com/cms-sw/cmssw/pull/36536){:target="_blank"}  from **@missirol**: make `customizeHLTforPatatrack` even more robust `hlt` created: 2021-12-17 13:57:04 merged: 2021-12-20 17:02:27

122. [36535](http://github.com/cms-sw/cmssw/pull/36535){:target="_blank"}  from **@mmusich**: `CondFormats`: fix warning message about "skipping this put" `alca` `db` created: 2021-12-17 13:34:05 merged: 2021-12-17 17:12:38

123. [36534](http://github.com/cms-sw/cmssw/pull/36534){:target="_blank"}  from **@perrotta**: Fix for DTMapGenerator and cleanup for DTTTrigCorrectionFirst (in CalibMuon/DTCalibration) `alca` created: 2021-12-17 10:27:29 merged: 2021-12-17 16:07:01

124. [36533](http://github.com/cms-sw/cmssw/pull/36533){:target="_blank"}  from **@smuzaffar**: Run testBuildersReaders unit test in its own directory `db` created: 2021-12-17 09:28:23 merged: 2021-12-17 16:10:29

125. [36532](http://github.com/cms-sw/cmssw/pull/36532){:target="_blank"}  from **@mmusich**: clean-up remaining commented instances of `createNewIOV` in the codebase `alca` `db` created: 2021-12-17 09:23:15 merged: 2021-12-17 16:12:25

126. [36531](http://github.com/cms-sw/cmssw/pull/36531){:target="_blank"}  from **@bsunanda**: Phase2-hgx297C Safer syntax fr modifying configuration parameters in some of the cfi's in Geometry/HGCalCommonData `geometry` `upgrade` created: 2021-12-17 00:51:10 merged: 2021-12-18 09:06:00

127. [36530](http://github.com/cms-sw/cmssw/pull/36530){:target="_blank"}  from **@makortel**: Remove MallocOpts as obsolete `core` created: 2021-12-16 21:28:50 merged: 2021-12-20 07:58:36

128. [36529](http://github.com/cms-sw/cmssw/pull/36529){:target="_blank"}  from **@AdrianoDee**: Fixing Patatrak pixelTracking only wfs `reconstruction` created: 2021-12-16 17:43:12 merged: 2022-01-08 14:26:50

129. [36528](http://github.com/cms-sw/cmssw/pull/36528){:target="_blank"}  from **@Michael-Krohn**: HCAL: Remove 4th depth from trigger primitive sum over depths, for |ieta| = 16 `alca` `l1` created: 2021-12-16 17:42:59 merged: 2021-12-17 16:14:46

130. [36525](http://github.com/cms-sw/cmssw/pull/36525){:target="_blank"}  from **@fabiocos**: MTD reconstruction: Implementation of MTDTrayBarrelLayer::groupedCompatibleDets() `reconstruction` `upgrade` created: 2021-12-16 16:45:23 merged: 2021-12-19 01:33:45

131. [36524](http://github.com/cms-sw/cmssw/pull/36524){:target="_blank"}  from **@perrotta**: Safer syntax for modifying the configuration parameters in g4SimHits_cfi.py `simulation` created: 2021-12-16 15:22:46 merged: 2021-12-17 21:41:19

132. [36523](http://github.com/cms-sw/cmssw/pull/36523){:target="_blank"}  from **@bsunanda**: Run3-gex102D Correct cfg's in view of change in the Era definition `simulation` created: 2021-12-16 14:56:26 merged: 2021-12-20 00:57:37

133. [36520](http://github.com/cms-sw/cmssw/pull/36520){:target="_blank"}  from **@tlampen**: First version of Payload Inspector plots for DropBoxMetadata `alca` `db` created: 2021-12-16 14:16:15 merged: 2021-12-21 00:47:15

134. [36517](http://github.com/cms-sw/cmssw/pull/36517){:target="_blank"}  from **@iarspider**: Drop tests for py3-climate and py3-theanets `analysis` created: 2021-12-16 12:47:29 merged: 2021-12-17 16:44:30

135. [36516](http://github.com/cms-sw/cmssw/pull/36516){:target="_blank"}  from **@mmusich**: get rid of CMSDEPRECATED_X warnings in `SLHCUpgradeSimulations/Geometry` `geometry` `upgrade` created: 2021-12-16 10:30:49 merged: 2021-12-21 10:09:43

136. [36513](http://github.com/cms-sw/cmssw/pull/36513){:target="_blank"}  from **@makortel**: Fix EventSetupIncorrectConsumes test `core` created: 2021-12-16 03:18:42 merged: 2021-12-17 02:27:22

137. [36512](http://github.com/cms-sw/cmssw/pull/36512){:target="_blank"}  from **@bsunanda**: Run3-gex102C Get rid of compilation warning in Validation/HGCalValidation and use ESGetToken in Validation/CSCRecHits `dqm` created: 2021-12-16 01:10:51 merged: 2021-12-17 02:34:33

138. [36511](http://github.com/cms-sw/cmssw/pull/36511){:target="_blank"}  from **@NiharSaha**: Drop type specs in RecoTau and RecoVertex `dqm` created: 2021-12-15 20:46:13 merged: 2021-12-26 13:02:10

139. [36510](http://github.com/cms-sw/cmssw/pull/36510){:target="_blank"}  from **@NiharSaha**: Drop type specs in RecoHI, RecoJets and RecoMET `dqm` created: 2021-12-15 19:21:20 merged: 2021-12-31 13:16:04

140. [36508](http://github.com/cms-sw/cmssw/pull/36508){:target="_blank"}  from **@mmusich**: `CondTools/SiStrip` unit tests: introduce gain rescaler tool in unit tests `db` created: 2021-12-15 18:44:49 merged: 2022-01-12 18:08:33

141. [36507](http://github.com/cms-sw/cmssw/pull/36507){:target="_blank"}  from **@Dr15Jones**: Removed use of tbb::task_arena in EventSetup `core` `geometry` `reconstruction` `upgrade` created: 2021-12-15 16:26:56 merged: 2021-12-21 08:36:02

142. [36502](http://github.com/cms-sw/cmssw/pull/36502){:target="_blank"}  from **@imranyusuff**: HGCalWaferValidation: refinements and D86 geometry validation fix `dqm` created: 2021-12-15 03:46:59 merged: 2021-12-17 17:07:28

143. [36501](http://github.com/cms-sw/cmssw/pull/36501){:target="_blank"}  from **@makortel**: Extend cutParser exception message temporarily to help debugging `reconstruction` created: 2021-12-15 00:47:30 merged: 2021-12-17 16:05:08

144. [36499](http://github.com/cms-sw/cmssw/pull/36499){:target="_blank"}  from **@dpilipov**: Inv mass over dr 12 3 x `l1` created: 2021-12-14 19:09:27 merged: 2021-12-17 02:33:23

145. [36496](http://github.com/cms-sw/cmssw/pull/36496){:target="_blank"}  from **@cvuosalo**: [DD4hep] Prohibit use of undefined materials `geometry` `upgrade` created: 2021-12-14 16:50:12 merged: 2021-12-17 16:50:06

146. [36490](http://github.com/cms-sw/cmssw/pull/36490){:target="_blank"}  from **@ggovi**: DBOutputService: Removed deprecated methods `alca` `dqm` `db` created: 2021-12-14 14:55:32 merged: 2021-12-17 09:28:31

147. [36486](http://github.com/cms-sw/cmssw/pull/36486){:target="_blank"}  from **@bsunanda**: Run3-gem65 Add the demonstration chamber of RPC for the Run3 scenario `geometry` created: 2021-12-14 14:14:29 merged: 2021-12-18 01:40:35

148. [36485](http://github.com/cms-sw/cmssw/pull/36485){:target="_blank"}  from **@mmusich**: modernize `MuonAnalysis/MomentumScaleCalibration` `analysis` created: 2021-12-14 11:45:58 merged: 2021-12-19 06:42:44

149. [36484](http://github.com/cms-sw/cmssw/pull/36484){:target="_blank"}  from **@indra-ehep**: Adding HGCAL simhit validation histograms `dqm` created: 2021-12-14 10:30:34 merged: 2021-12-18 09:21:34

150. [36478](http://github.com/cms-sw/cmssw/pull/36478){:target="_blank"}  from **@makortel**: Add early delete customisation for mkFit temporary data products `operations` `reconstruction` created: 2021-12-13 19:59:51 merged: 2022-01-05 00:46:56

151. [36471](http://github.com/cms-sw/cmssw/pull/36471){:target="_blank"}  from **@mbluj**: Small cleanups in RecoTauTag/RecoTau `reconstruction` created: 2021-12-13 15:39:07 merged: 2021-12-20 17:49:03

152. [36469](http://github.com/cms-sw/cmssw/pull/36469){:target="_blank"}  from **@Pruthvi-ch**: Adding provision for HGCal geometry v17 development `geometry` `upgrade` created: 2021-12-13 15:00:07 merged: 2021-12-20 00:54:42

153. [36459](http://github.com/cms-sw/cmssw/pull/36459){:target="_blank"}  from **@missirol**: add `fillDescriptions` to `CkfTrackCandidateMaker` (and its dependencies) `hlt` `reconstruction` created: 2021-12-11 09:28:25 merged: 2022-01-08 15:20:23

154. [36457](http://github.com/cms-sw/cmssw/pull/36457){:target="_blank"}  from **@adewit**: Phase 2 tracker: add T28 and T29 (geometries with bricked pixels for IT sensor design studies) `geometry` `operations` `pdmv` `upgrade` created: 2021-12-10 20:35:09 merged: 2021-12-21 18:04:53

155. [36446](http://github.com/cms-sw/cmssw/pull/36446){:target="_blank"}  from **@CMS-ECAL-Trigger-Group**: ECAL TPG Parameter Builder changes for double weights mechanism `alca` `l1` `db` created: 2021-12-10 09:34:01 merged: 2022-01-14 16:49:48

156. [36408](http://github.com/cms-sw/cmssw/pull/36408){:target="_blank"}  from **@tvami**: Removal of hardcoded testing L1T tag and move it to GT `alca` `l1` created: 2021-12-08 02:44:09 merged: 2021-12-21 13:02:15

157. [36383](http://github.com/cms-sw/cmssw/pull/36383){:target="_blank"}  from **@tvami**: es get() migration of L1CondDBPayloadWriter and L1CondDBPayloadWriterExt `l1` `db` created: 2021-12-07 00:35:37 merged: 2021-12-17 16:35:24

158. [36372](http://github.com/cms-sw/cmssw/pull/36372){:target="_blank"}  from **@bsunanda**: Run3-hcx328 Replace cout with LogVerbatim and update the cfg's in Geometry/HcalCommonData `geometry` created: 2021-12-06 13:41:26 merged: 2021-12-17 02:36:20

159. [36325](http://github.com/cms-sw/cmssw/pull/36325){:target="_blank"}  from **@kakwok**: Update HLT filter for MuonRechitClusters `hlt` created: 2021-12-01 18:34:42 merged: 2021-12-20 14:54:39

160. [36323](http://github.com/cms-sw/cmssw/pull/36323){:target="_blank"}  from **@vpicco**: Include FSR for electrons (in addition to muons) `analysis` `xpog` created: 2021-12-01 16:41:51 merged: 2022-01-11 18:42:31

161. [36320](http://github.com/cms-sw/cmssw/pull/36320){:target="_blank"}  from **@slava77**: replace ttbar classic PU for 2017 with 2021 variant (10224->11834) in the short matrix `pdmv` `upgrade` created: 2021-12-01 14:41:16 merged: 2021-12-17 16:16:25

162. [36276](http://github.com/cms-sw/cmssw/pull/36276){:target="_blank"}  from **@llunerti**: Adding modules for tag-and-probe efficiency computation in DQMOffline `dqm` created: 2021-11-29 12:01:36 merged: 2022-01-15 16:30:56

163. [36259](http://github.com/cms-sw/cmssw/pull/36259){:target="_blank"}  from **@hftsoi**: Calo-L1 unpacker modified to read 5BX payload format `l1` created: 2021-11-26 15:37:50 merged: 2021-12-17 11:24:53

164. [36235](http://github.com/cms-sw/cmssw/pull/36235){:target="_blank"}  from **@AdrianoDee**: Phase II Patatrack Pixel Local Reco `reconstruction` `alca` `dqm` `geometry` `pdmv` `db` `upgrade` `heterogeneous` created: 2021-11-24 14:39:02 merged: 2021-12-22 15:42:09

165. [36172](http://github.com/cms-sw/cmssw/pull/36172){:target="_blank"}  from **@rovere**: HGCAL Pattern Recognition using FastJet `operations` `reconstruction` `pdmv` `upgrade` created: 2021-11-18 17:34:03 merged: 2022-01-11 11:24:45

166. [36153](http://github.com/cms-sw/cmssw/pull/36153){:target="_blank"}  from **@davidlange6**: (Partial) Cleaning of unused CommonTools/CandAlgos classes `reconstruction` created: 2021-11-17 10:17:16 merged: 2021-12-17 02:46:00

167. [35481](http://github.com/cms-sw/cmssw/pull/35481){:target="_blank"}  from **@cms-sw**: For async calls always store XrdCl::FileSystem with the response-handler. `core` created: 2021-09-30 07:00:20 merged: 2022-01-11 01:02:30

168. [34991](http://github.com/cms-sw/cmssw/pull/34991){:target="_blank"}  from **@mrodozov**: Backport XrootD 5.3.1 PR to master from DEVEL `core` created: 2021-08-24 09:13:37 merged: 2022-01-11 01:03:17

#### CMSDIST Changes between Tags REL/CMSSW_12_3_0_pre2/slc7_amd64_gcc10 and REL/CMSSW_12_3_0_pre3/slc7_amd64_gcc10:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_12_3_0_pre2/slc7_amd64_gcc10...REL/CMSSW_12_3_0_pre3/slc7_amd64_gcc10)



1. [7549](http://github.com/cms-sw/cmsdist/pull/7549){:target="_blank"}  from **@cms-sw**: [py-make] use tagged source URL created: 2022-01-17 12:49:39 merged: 2022-01-18 07:24:32

2. [7546](http://github.com/cms-sw/cmsdist/pull/7546){:target="_blank"}  from **@cms-sw**: Updated cmsos to support rhel OS created: 2022-01-14 08:32:30 merged: 2022-01-14 14:48:32

3. [7545](http://github.com/cms-sw/cmsdist/pull/7545){:target="_blank"}  from **@cms-sw**: Update py-pillow to version 9.0.0 created: 2022-01-14 08:30:14 merged: 2022-01-14 13:55:28

4. [7543](http://github.com/cms-sw/cmsdist/pull/7543){:target="_blank"}  from **@cms-sw**: Update UTM to version 0.10.0 created: 2022-01-12 15:21:39 merged: 2022-01-13 06:41:05

5. [7539](http://github.com/cms-sw/cmsdist/pull/7539){:target="_blank"}  from **@cms-sw**: fronteir client: patch for function arg/return types in frontier_client created: 2022-01-11 23:28:20 merged: 2022-01-12 06:24:32

6. [7537](http://github.com/cms-sw/cmsdist/pull/7537){:target="_blank"}  from **@cms-sw**:  Fix check for requirements (#7534), add missing dependencies created: 2022-01-11 08:45:21 merged: 2022-01-14 20:57:51

7. [7536](http://github.com/cms-sw/cmsdist/pull/7536){:target="_blank"}  from **@belforte**: test latest crab client (no asourl/db) created: 2022-01-10 15:56:19 merged: 2022-01-10 22:26:34

8. [7535](http://github.com/cms-sw/cmsdist/pull/7535){:target="_blank"}  from **@cms-sw**: Update lxml to verion 4.6.5 created: 2022-01-09 22:02:47 merged: 2022-01-10 09:45:57

9. [7522](http://github.com/cms-sw/cmsdist/pull/7522){:target="_blank"}  from **@vkuznet**: New dasgoclient version created: 2021-12-17 14:12:46 merged: 2021-12-18 00:25:29

10. [7518](http://github.com/cms-sw/cmsdist/pull/7518){:target="_blank"}  from **@cms-sw**: Drop py-theanets and py-climate created: 2021-12-16 12:54:20 merged: 2022-01-10 22:11:23

11. [7516](http://github.com/cms-sw/cmsdist/pull/7516){:target="_blank"}  from **@cms-sw**: Drop -fsanitize=pointer-compare from ASAN IB created: 2021-12-16 06:22:56 merged: 2021-12-27 16:49:43

12. [7515](http://github.com/cms-sw/cmsdist/pull/7515){:target="_blank"}  from **@cms-sw**: Update Correctionlib to version 2.1.0 created: 2021-12-16 05:40:26 merged: 2022-01-11 08:01:49

13. [7514](http://github.com/cms-sw/cmsdist/pull/7514){:target="_blank"}  from **@cms-sw**: [DD4hep] Update to v01-19 created: 2021-12-16 05:36:31 merged: 2021-12-17 08:29:57

14. [7233](http://github.com/cms-sw/cmsdist/pull/7233){:target="_blank"}  from **@mrodozov**: XrootD - backport 531 from devel to master created: 2021-08-24 09:13:40 merged: 2022-01-11 01:02:44
