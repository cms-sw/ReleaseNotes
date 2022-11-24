---
layout: post
rel_link:  "12_6_0_pre5"
title:  "CMSSW_12_6_0_pre5"
date:   2022-11-24 07:45:33
categories: cmssw
relmajor: 12
relminor: 6
relsubminor: 0
relpre: _pre5
---

# CMSSW_12_6_0_pre5
#### Changes since CMSSW_12_6_0_pre4:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_12_6_0_pre4...CMSSW_12_6_0_pre5)



1. [40127](http://github.com/cms-sw/cmssw/pull/40127){:target="_blank"}  from **@civanch**: Protection for negative kinetic energy in Geant4 tracking `simulation` created: 2022-11-22 08:18:29 merged: 2022-11-23 09:49:53

2. [40121](http://github.com/cms-sw/cmssw/pull/40121){:target="_blank"}  from **@Sam-Harper**: cleaning the folder name of the per path histograms `hlt` created: 2022-11-21 04:44:39 merged: 2022-11-22 10:36:38

3. [40116](http://github.com/cms-sw/cmssw/pull/40116){:target="_blank"}  from **@civanch**: Check geant4 voxels structure `simulation` created: 2022-11-19 04:11:14 merged: 2022-11-23 09:54:45

4. [40114](http://github.com/cms-sw/cmssw/pull/40114){:target="_blank"}  from **@TomasKello**: Fix alignment offline validation ROOT6.27/01 issue `alca` created: 2022-11-18 19:35:56 merged: 2022-11-21 11:58:29

5. [40109](http://github.com/cms-sw/cmssw/pull/40109){:target="_blank"}  from **@francescobrivio**: Fix HI rawDataInputTag for beamhlt DQM client `dqm` created: 2022-11-18 16:42:49 merged: 2022-11-21 12:01:02

6. [40105](http://github.com/cms-sw/cmssw/pull/40105){:target="_blank"}  from **@dan131riley**: fix initialization of local variables to avoid vagrind warnings `reconstruction` created: 2022-11-17 18:17:22 merged: 2022-11-19 09:38:37

7. [40101](http://github.com/cms-sw/cmssw/pull/40101){:target="_blank"}  from **@francescobrivio**: Add MC GT for 2022 postEE leak `alca` created: 2022-11-17 16:01:55 merged: 2022-11-18 14:57:32

8. [40098](http://github.com/cms-sw/cmssw/pull/40098){:target="_blank"}  from **@civanch**: Protection in geant4 stacking action  `simulation` created: 2022-11-17 12:53:36 merged: 2022-11-18 14:58:14

9. [40093](http://github.com/cms-sw/cmssw/pull/40093){:target="_blank"}  from **@AnnikaStein**: Adapt protection against zero weights or pt for SV producer `reconstruction` created: 2022-11-16 22:09:50 merged: 2022-11-22 21:58:58

10. [40084](http://github.com/cms-sw/cmssw/pull/40084){:target="_blank"}  from **@swagata87**: Improve unprotected areas of GSF code to avoid segfault `reconstruction` created: 2022-11-16 13:03:54 merged: 2022-11-16 18:09:59

11. [40081](http://github.com/cms-sw/cmssw/pull/40081){:target="_blank"}  from **@laurenhay**: Protect against particles with zero weight and pt being given as input to njettiness `reconstruction` created: 2022-11-15 23:27:55 merged: 2022-11-16 13:16:39

12. [40069](http://github.com/cms-sw/cmssw/pull/40069){:target="_blank"}  from **@suchandradutta**: Phase2TrackerDigitizer: Activating Bias Rail Inefficiency `simulation` `upgrade` created: 2022-11-15 12:01:45 merged: 2022-11-21 13:57:16

13. [40062](http://github.com/cms-sw/cmssw/pull/40062){:target="_blank"}  from **@fwyzard**: Fix the `ThroughputService` and `FastTimerService` DQM folders `hlt` created: 2022-11-14 16:26:45 merged: 2022-11-15 22:41:30

14. [40061](http://github.com/cms-sw/cmssw/pull/40061){:target="_blank"}  from **@CMSTrackerDPG**: Fix in SiPixelQualityESProducer to support two labelled records `alca` created: 2022-11-14 15:27:19 merged: 2022-11-15 20:41:13

15. [40060](http://github.com/cms-sw/cmssw/pull/40060){:target="_blank"}  from **@elfontan**: OS requirement for Triple Muon seeds in the uGT emulator `l1` created: 2022-11-14 10:49:01 merged: 2022-11-21 13:55:25

16. [40056](http://github.com/cms-sw/cmssw/pull/40056){:target="_blank"}  from **@bsunanda**: Phase2-hgx329E Remove obsolete FastTimer code from Geometry/HCalCommonData `geometry` `upgrade` created: 2022-11-14 01:41:11 merged: 2022-11-15 10:02:58

17. [40055](http://github.com/cms-sw/cmssw/pull/40055){:target="_blank"}  from **@bsunanda**: Phase2-hgx327I Take care of some remaining obsolete python scripts in Geometry/HGCalCommonData `geometry` `upgrade` created: 2022-11-14 00:33:20 merged: 2022-11-19 09:45:08

18. [40053](http://github.com/cms-sw/cmssw/pull/40053){:target="_blank"}  from **@bsunanda**: Run3-alca235 Update some of the scripts used in calibrating HCAL channels using muons `alca` created: 2022-11-12 11:55:41 merged: 2022-11-14 11:19:06

19. [40052](http://github.com/cms-sw/cmssw/pull/40052){:target="_blank"}  from **@bsunanda**: Phase2-hgx329D Remove obsolete files FastTimeTopology and its usage from Geometry/CaloTopology and Geometry/CaloEventSetup `geometry` created: 2022-11-12 07:04:31 merged: 2022-11-12 19:32:39

20. [40050](http://github.com/cms-sw/cmssw/pull/40050){:target="_blank"}  from **@dan131riley**: Improve cpu feature discover on ppc and aarch64 `core` created: 2022-11-11 20:40:07 merged: 2022-11-17 06:01:40

21. [40049](http://github.com/cms-sw/cmssw/pull/40049){:target="_blank"}  from **@fabiocos**: MTD geometry and reconstruction: update locaPosition in RectangularMTDTopology and adapt cluster accordingly `dqm` `geometry` `reconstruction` `upgrade` created: 2022-11-11 15:17:39 merged: 2022-11-17 15:56:30

22. [40046](http://github.com/cms-sw/cmssw/pull/40046){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `12_5_X` (1/N): HLT HIon V1.0 of 2022 [`12_6_X`] `hlt` created: 2022-11-10 17:20:10 merged: 2022-11-11 14:25:52

23. [40045](http://github.com/cms-sw/cmssw/pull/40045){:target="_blank"}  from **@rgoldouz**: Run3 ele ID is added to the cleaned 126 nanoAOD electron module + DQM (Run3 EffArea is applied only to the EGamma supported variables) `reconstruction` `xpog` created: 2022-11-10 17:18:27 merged: 2022-11-18 14:59:30

24. [40039](http://github.com/cms-sw/cmssw/pull/40039){:target="_blank"}  from **@asculac**: Adding HZZ electron ID mva score to miniAOD for Run3 `reconstruction` created: 2022-11-10 13:56:04 merged: 2022-11-11 14:28:24

25. [40038](http://github.com/cms-sw/cmssw/pull/40038){:target="_blank"}  from **@agrohsje**: isrptmin2fac option for PS weights in Pythia 8.306  `generators` created: 2022-11-10 11:35:09 merged: 2022-11-10 21:38:26

26. [40037](http://github.com/cms-sw/cmssw/pull/40037){:target="_blank"}  from **@bsunanda**: Phase2-hgx327H Clean up unused obsolete python files preceding V16 of HGCAL specification from Geometry/HGCalCommonData `geometry` `upgrade` created: 2022-11-10 05:30:44 merged: 2022-11-14 05:50:46

27. [40035](http://github.com/cms-sw/cmssw/pull/40035){:target="_blank"}  from **@bsunanda**: Run3-sim136 Extend the testing of wrong cell assignments in HCAL `simulation` created: 2022-11-10 02:07:52 merged: 2022-11-11 14:29:27

28. [40033](http://github.com/cms-sw/cmssw/pull/40033){:target="_blank"}  from **@swertz**: Fix JMENano, further cleanup in Nano `xpog` created: 2022-11-09 16:01:22 merged: 2022-11-10 16:38:45

29. [40019](http://github.com/cms-sw/cmssw/pull/40019){:target="_blank"}  from **@mmusich**: fix `gcc11` compilation issues in `CompareAlignments`, post #38304 merge `alca` created: 2022-11-09 08:08:01 merged: 2022-11-10 13:39:27

30. [40018](http://github.com/cms-sw/cmssw/pull/40018){:target="_blank"}  from **@missirol**: improve logging of `addOnTests` `core` created: 2022-11-08 23:17:13 merged: 2022-11-23 09:39:03

31. [40017](http://github.com/cms-sw/cmssw/pull/40017){:target="_blank"}  from **@mmusich**: [TsosGaussianStateConversions] proposal fix for Gsf Tracking segmentation fault when no states are passing selection criteria  `reconstruction` created: 2022-11-08 14:15:45 merged: 2022-11-14 11:56:07

32. [40015](http://github.com/cms-sw/cmssw/pull/40015){:target="_blank"}  from **@francescobrivio**: Use ppEra_Run3_pp_on_PbPb_approxSiStripClusters for hi_run in visualization DQM clients `dqm` created: 2022-11-08 13:39:02 merged: 2022-11-09 14:40:19

33. [40011](http://github.com/cms-sw/cmssw/pull/40011){:target="_blank"}  from **@tvami**: Remove MVASelector tags for tracking in data GTs + re-snapshot frozen GT `alca` created: 2022-11-07 20:05:38 merged: 2022-11-11 14:31:19

34. [40010](http://github.com/cms-sw/cmssw/pull/40010){:target="_blank"}  from **@tvami**: Remove MVASelector tags for tracking in MC GTs `alca` created: 2022-11-07 19:28:04 merged: 2022-11-10 21:35:19

35. [40009](http://github.com/cms-sw/cmssw/pull/40009){:target="_blank"}  from **@mmusich**: [`DQMOffline/Alignment`] Improvements on di-muon mass bias plots `dqm` created: 2022-11-07 16:42:02 merged: 2022-11-10 21:34:31

36. [40008](http://github.com/cms-sw/cmssw/pull/40008){:target="_blank"}  from **@bsunanda**: Phase2-329C Remove all obsolete files relevant to FastTimerGeoemtry from HGCal related projects `geometry` `upgrade` created: 2022-11-07 16:12:24 merged: 2022-11-11 14:31:50

37. [40006](http://github.com/cms-sw/cmssw/pull/40006){:target="_blank"}  from **@tvami**: Move HcalCalIsolatedBunchSelector from Commissioning to ZB PD `alca` created: 2022-11-07 15:28:10 merged: 2022-11-09 14:44:20

38. [40005](http://github.com/cms-sw/cmssw/pull/40005){:target="_blank"}  from **@mmusich**: use `EvFFEDExcluder` instead of `EvFFEDSelector` for `rawPrimeDataRepacker` `operations` `pdmv` `upgrade` created: 2022-11-07 14:42:19 merged: 2022-11-17 08:10:17

39. [40004](http://github.com/cms-sw/cmssw/pull/40004){:target="_blank"}  from **@missirol**: various improvements to HLT-development tools `hlt` created: 2022-11-07 14:30:16 merged: 2022-11-18 15:01:41

40. [40003](http://github.com/cms-sw/cmssw/pull/40003){:target="_blank"}  from **@mmusich**: add a `TransientTrackingRechitBuilder` for `CPEFast` `reconstruction` created: 2022-11-07 11:45:59 merged: 2022-11-14 11:14:52

41. [40002](http://github.com/cms-sw/cmssw/pull/40002){:target="_blank"}  from **@michaelwassmer**: Rework MET correction/uncertainty tool `reconstruction` `xpog` created: 2022-11-07 10:24:57 merged: 2022-11-22 13:34:12

42. [39998](http://github.com/cms-sw/cmssw/pull/39998){:target="_blank"}  from **@francescobrivio**: Add ppEra_Run3_pp_on_PbPb_approxSiStripClusters scenario `operations` created: 2022-11-07 09:29:42 merged: 2022-11-07 14:04:31

43. [39997](http://github.com/cms-sw/cmssw/pull/39997){:target="_blank"}  from **@rseidita**: Adding log(pt) to jet DQM `dqm` created: 2022-11-07 09:28:00 merged: 2022-11-14 06:04:18

44. [39994](http://github.com/cms-sw/cmssw/pull/39994){:target="_blank"}  from **@bsunanda**: Run3-sim135 Modify the analysis code of SimHit Results `simulation` created: 2022-11-06 09:53:45 merged: 2022-11-09 14:48:05

45. [39993](http://github.com/cms-sw/cmssw/pull/39993){:target="_blank"}  from **@missirol**: add plugin to produce `FEDRawDataCollection` excluding a list of FEDs `daq` created: 2022-11-05 10:35:23 merged: 2022-11-06 19:01:00

46. [39992](http://github.com/cms-sw/cmssw/pull/39992){:target="_blank"}  from **@srimanob**: Fix D97 unit test and clean up Phase2 XMLs `geometry` `upgrade` created: 2022-11-05 01:09:53 merged: 2022-11-08 20:10:27

47. [39991](http://github.com/cms-sw/cmssw/pull/39991){:target="_blank"}  from **@Dr15Jones**: Do not call methods on EcalTrigTowerConstituentsMap nullptr `geometry` `l1` `upgrade` created: 2022-11-04 20:28:03 merged: 2022-11-10 21:33:21

48. [39990](http://github.com/cms-sw/cmssw/pull/39990){:target="_blank"}  from **@Dr15Jones**: Set member data in GEMClusterProcessor `l1` created: 2022-11-04 18:20:47 merged: 2022-11-07 11:59:21

49. [39989](http://github.com/cms-sw/cmssw/pull/39989){:target="_blank"}  from **@suchandradutta**: Implementation of  digitizer noise occupancy  `simulation` `upgrade` created: 2022-11-04 17:55:23 merged: 2022-11-10 21:32:11

50. [39988](http://github.com/cms-sw/cmssw/pull/39988){:target="_blank"}  from **@francescobrivio**: Use Era Run3_pp_on_PbPb_approxSiStripClusters in DQM clients with tracking `dqm` created: 2022-11-04 15:36:17 merged: 2022-11-08 04:51:31

51. [39986](http://github.com/cms-sw/cmssw/pull/39986){:target="_blank"}  from **@mmusich**: add FED 1022 to the list passed to `rawPrimeDataRepacker` `operations` created: 2022-11-04 13:08:07 merged: 2022-11-08 05:20:59

52. [39978](http://github.com/cms-sw/cmssw/pull/39978){:target="_blank"}  from **@Dr15Jones**: Remove WatchRuns restriction on HectorProducer `simulation` created: 2022-11-03 15:13:39 merged: 2022-11-04 06:55:28

53. [39974](http://github.com/cms-sw/cmssw/pull/39974){:target="_blank"}  from **@bsunanda**: Phase2-hcx341 Add a new Prodcut file Phase2 HCAL and modify the scenarios accordingly `geometry` `upgrade` created: 2022-11-03 08:55:39 merged: 2022-11-04 07:56:32

54. [39972](http://github.com/cms-sw/cmssw/pull/39972){:target="_blank"}  from **@bsunanda**: Phase2-hgx327G Remove and modify many more test scripts in Geometry/HGCalCommonData in view of retaining only stuffs for V16, V17 and TB `geometry` `upgrade` created: 2022-11-03 07:10:54 merged: 2022-11-07 14:09:47

55. [39968](http://github.com/cms-sw/cmssw/pull/39968){:target="_blank"}  from **@bsunanda**: Run3-hcx338 Modify the dumping for geometry visualisation of HCAL `geometry` created: 2022-11-03 05:15:41 merged: 2022-11-03 10:22:53

56. [39967](http://github.com/cms-sw/cmssw/pull/39967){:target="_blank"}  from **@bsunanda**: Run3-hcx337 Fix a bug for wrong DetID assignment in HCAL - relevenat for Runs 1,2,3,4 `geometry` `simulation` created: 2022-11-03 02:09:41 merged: 2022-11-04 06:09:43

57. [39965](http://github.com/cms-sw/cmssw/pull/39965){:target="_blank"}  from **@srimanob**: Allow to run smearing sequence separate from GEN step `operations` created: 2022-11-02 18:24:39 merged: 2022-11-08 20:23:49

58. [39963](http://github.com/cms-sw/cmssw/pull/39963){:target="_blank"}  from **@shdutta16**: Cut based photon id run iii winter22 `reconstruction` `xpog` created: 2022-11-02 16:03:07 merged: 2022-11-17 16:11:53

59. [39962](http://github.com/cms-sw/cmssw/pull/39962){:target="_blank"}  from **@sroychow**: TkDQM: Add DQM modules for monitoring VectorHits `dqm` created: 2022-11-02 15:22:33 merged: 2022-11-16 13:11:39

60. [39960](http://github.com/cms-sw/cmssw/pull/39960){:target="_blank"}  from **@Dr15Jones**: Added getByToken to edm::EventBase `core` created: 2022-11-02 13:29:07 merged: 2022-11-03 18:41:02

61. [39959](http://github.com/cms-sw/cmssw/pull/39959){:target="_blank"}  from **@mmusich**: add era-dependent switch on the AlCaRecoTriggerBit key for SiPixel ALCARECO producers `alca` created: 2022-11-02 11:46:08 merged: 2022-11-21 13:51:19

62. [39956](http://github.com/cms-sw/cmssw/pull/39956){:target="_blank"}  from **@wonpoint4**: [NanoAOD V10] - Adding correct Iso filter name (without cut values) for Run3 `xpog` created: 2022-11-02 08:57:24 merged: 2022-11-03 12:44:40

63. [39955](http://github.com/cms-sw/cmssw/pull/39955){:target="_blank"}  from **@vlimant**: Setting precision in GlobalVariablesProducer `xpog` created: 2022-11-02 08:43:41 merged: 2022-11-19 11:52:08

64. [39952](http://github.com/cms-sw/cmssw/pull/39952){:target="_blank"}  from **@nickh2000**: EMTF DQM fix to remove duplicate x-axis bin labels `dqm` created: 2022-11-01 18:08:07 merged: 2022-11-02 09:08:27

65. [39947](http://github.com/cms-sw/cmssw/pull/39947){:target="_blank"}  from **@bsunanda**: Phase2-hgx329B Remove reference to FastTimeGeometry from Fireworks - this is an obsolete reference, never used and never will be `visualization` created: 2022-11-01 04:24:37 merged: 2022-11-02 20:32:32

66. [39946](http://github.com/cms-sw/cmssw/pull/39946){:target="_blank"}  from **@bsunanda**: Phase2-329A Remove obsolete class from Validation/HGCalValidation `dqm` created: 2022-11-01 03:00:42 merged: 2022-11-02 09:10:53

67. [39945](http://github.com/cms-sw/cmssw/pull/39945){:target="_blank"}  from **@makortel**: Work around a segfault when a non-consumed module with Transfomer ability has been deleted `core` created: 2022-10-31 20:41:26 merged: 2022-11-01 17:30:18

68. [39941](http://github.com/cms-sw/cmssw/pull/39941){:target="_blank"}  from **@abhih1**: Change threshold for presample mean in ECAL DQM Pedestal Quality plot [Master] `dqm` created: 2022-10-31 17:01:37 merged: 2022-11-02 16:12:09

69. [39934](http://github.com/cms-sw/cmssw/pull/39934){:target="_blank"}  from **@francescobrivio**: Fix rerecoCommon DQM sequence `dqm` created: 2022-10-31 14:58:15 merged: 2022-11-01 13:54:08

70. [39930](http://github.com/cms-sw/cmssw/pull/39930){:target="_blank"}  from **@bsunanda**: Run3-alca234 Make a new set of PU correction factor for 2022 calibration runs `alca` created: 2022-10-31 07:17:05 merged: 2022-11-01 07:48:10

71. [39929](http://github.com/cms-sw/cmssw/pull/39929){:target="_blank"}  from **@mrcthiel**: updating triggerObjects_cff V10 `xpog` created: 2022-10-30 18:49:50 merged: 2022-11-02 13:56:31

72. [39928](http://github.com/cms-sw/cmssw/pull/39928){:target="_blank"}  from **@bsunanda**: Phase2-hgx327F Modify more scripts in Geometry/HGCalCommonData/test/python to retain minimum number of scripts useful for V16, V17 and TB setups `geometry` `upgrade` created: 2022-10-30 11:51:38 merged: 2022-11-01 17:58:37

73. [39927](http://github.com/cms-sw/cmssw/pull/39927){:target="_blank"}  from **@Prasant1993**: Photon MVA-based ID for Run3 from EGamma POG `reconstruction` `xpog` created: 2022-10-29 19:46:53 merged: 2022-11-08 20:14:04

74. [39924](http://github.com/cms-sw/cmssw/pull/39924){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `12_4_X` (10/N): HLT V1.5 of 2022 [`12_6_X`] `hlt` `pdmv` `upgrade` created: 2022-10-29 17:39:14 merged: 2022-10-31 10:05:12

75. [39923](http://github.com/cms-sw/cmssw/pull/39923){:target="_blank"}  from **@bsunanda**: Run3-gex144 Avoid compilation warnings in RecoParticleFlow/PFProducer test codes `reconstruction` created: 2022-10-29 07:32:28 merged: 2022-11-21 11:31:41

76. [39922](http://github.com/cms-sw/cmssw/pull/39922){:target="_blank"}  from **@bsunanda**: Run3-gex143 Update RecoEgamma/EgammaElectronProducers to avoid compilation warnings `reconstruction` created: 2022-10-29 07:04:11 merged: 2022-11-21 17:22:37

77. [39920](http://github.com/cms-sw/cmssw/pull/39920){:target="_blank"}  from **@bsunanda**: Run3-hcx335 Add protection to eta values for phase2 scenario in HCAL geometry `alca` `geometry` `db` created: 2022-10-29 06:05:12 merged: 2022-10-31 19:16:48

78. [39919](http://github.com/cms-sw/cmssw/pull/39919){:target="_blank"}  from **@fwyzard**: Improve the SoA accessors and optimisations `heterogeneous` created: 2022-10-28 22:11:45 merged: 2022-11-16 21:02:37

79. [39918](http://github.com/cms-sw/cmssw/pull/39918){:target="_blank"}  from **@Michael-Krohn**:  HCAL: Modifications to the HCAL trigger key generation scripts `db` created: 2022-10-28 17:38:12 merged: 2022-10-31 20:20:56

80. [39917](http://github.com/cms-sw/cmssw/pull/39917){:target="_blank"}  from **@mmusich**: add protection for AlCa step in several specialized phase-2 workflows `pdmv` `upgrade` created: 2022-10-28 17:01:16 merged: 2022-10-29 06:23:55

81. [39916](http://github.com/cms-sw/cmssw/pull/39916){:target="_blank"}  from **@bsunanda**: Phase2-hgx327E Update several scripts in Geometry/HGCalCommonData/test/python to support only v16 and V17 geometries of HGCal `geometry` `upgrade` created: 2022-10-28 16:34:38 merged: 2022-10-31 12:11:11

82. [39915](http://github.com/cms-sw/cmssw/pull/39915){:target="_blank"}  from **@Dr15Jones**: Removed unused EDAnalyzer.h from METTester `dqm` created: 2022-10-28 16:32:57 merged: 2022-10-31 20:00:19

83. [39913](http://github.com/cms-sw/cmssw/pull/39913){:target="_blank"}  from **@Dr15Jones**: Remove unused EDAnalyzer.h in Reco* packages `reconstruction` created: 2022-10-28 16:23:47 merged: 2022-10-30 17:14:34

84. [39912](http://github.com/cms-sw/cmssw/pull/39912){:target="_blank"}  from **@Dr15Jones**: Removed unused EDAnalyzer.h from L1Trigger* `l1` created: 2022-10-28 16:08:30 merged: 2022-10-31 10:00:25

85. [39910](http://github.com/cms-sw/cmssw/pull/39910){:target="_blank"}  from **@Dr15Jones**: Removed unused EDAnalyzer.h header from AnalysisJV `analysis` created: 2022-10-28 15:14:59 merged: 2022-10-30 17:03:53

86. [39909](http://github.com/cms-sw/cmssw/pull/39909){:target="_blank"}  from **@Dr15Jones**: Removed unused EDAnalyzer.h from HLTJetMETValidation.h `dqm` created: 2022-10-28 15:06:34 merged: 2022-10-30 17:11:29

87. [39908](http://github.com/cms-sw/cmssw/pull/39908){:target="_blank"}  from **@Dr15Jones**: Removed unused EDAnalyzer.h header from DQMOffline `dqm` created: 2022-10-28 14:32:24 merged: 2022-10-31 10:01:55

88. [39907](http://github.com/cms-sw/cmssw/pull/39907){:target="_blank"}  from **@Dr15Jones**: Removed unneeded include of EDAnalyzer.h from DQM `dqm` `hlt` created: 2022-10-28 14:19:05 merged: 2022-10-31 10:02:05

89. [39895](http://github.com/cms-sw/cmssw/pull/39895){:target="_blank"}  from **@perrotta**: Deal with cases in which file is a nullptr in DQMRootSource.cc `dqm` created: 2022-10-28 08:38:36 merged: 2022-11-02 09:20:04

90. [39893](http://github.com/cms-sw/cmssw/pull/39893){:target="_blank"}  from **@swertz**: Nano: fix matching between pat trigger objects and L1 objects `xpog` created: 2022-10-28 07:23:58 merged: 2022-10-28 19:03:44

91. [39892](http://github.com/cms-sw/cmssw/pull/39892){:target="_blank"}  from **@bsunanda**: Phase2-hgx327D Delete some of the obsolete files in Geometry/HGCalCommonData/test area and make some more general `geometry` `upgrade` created: 2022-10-28 06:53:53 merged: 2022-10-31 12:13:54

92. [39889](http://github.com/cms-sw/cmssw/pull/39889){:target="_blank"}  from **@Dr15Jones**: Fix deprecation warnings in DQMOffline/CalibMuon `dqm` created: 2022-10-27 22:21:45 merged: 2022-11-02 20:41:45

93. [39888](http://github.com/cms-sw/cmssw/pull/39888){:target="_blank"}  from **@Dr15Jones**: Converted remaining DQM modules to edm::one::EDAnalyzer `dqm` `hlt` `db` created: 2022-10-27 21:32:21 merged: 2022-11-02 09:17:53

94. [39887](http://github.com/cms-sw/cmssw/pull/39887){:target="_blank"}  from **@Dr15Jones**: Made MagFieldConfigDBWriter an edm::one::EDAnalyzer `alca` created: 2022-10-27 20:40:51 merged: 2022-10-31 16:41:28

95. [39886](http://github.com/cms-sw/cmssw/pull/39886){:target="_blank"}  from **@Dr15Jones**: Made DataFormats test modules thread-friendly `reconstruction` created: 2022-10-27 20:31:07 merged: 2022-10-31 19:17:29

96. [39882](http://github.com/cms-sw/cmssw/pull/39882){:target="_blank"}  from **@Dr15Jones**: Removed EventFilter/Playback `daq` created: 2022-10-27 19:23:41 merged: 2022-10-28 05:39:27

97. [39881](http://github.com/cms-sw/cmssw/pull/39881){:target="_blank"}  from **@Dr15Jones**: Made DQMRivetClient thread-friendly `generators` created: 2022-10-27 19:05:27 merged: 2022-11-07 07:54:51

98. [39880](http://github.com/cms-sw/cmssw/pull/39880){:target="_blank"}  from **@Dr15Jones**: Changed profiling analyzers to edm::one::EDAnalyzer `core` created: 2022-10-27 18:44:50 merged: 2022-10-28 05:40:44

99. [39879](http://github.com/cms-sw/cmssw/pull/39879){:target="_blank"}  from **@Dr15Jones**: Change recoBSVTagInfoValidationAnalyzer to be thread-friendly `dqm` created: 2022-10-27 18:30:29 merged: 2022-11-02 09:18:43

100. [39878](http://github.com/cms-sw/cmssw/pull/39878){:target="_blank"}  from **@Dr15Jones**: Fix remaining CMS deprecation warnings in Reco* subsystems `reconstruction` created: 2022-10-27 17:35:42 merged: 2022-10-31 19:18:02

101. [39877](http://github.com/cms-sw/cmssw/pull/39877){:target="_blank"}  from **@makortel**: Remove commented unnecessary code from DigiAccumulatorMixModFactory.h `simulation` created: 2022-10-27 16:40:31 merged: 2022-10-28 19:04:13

102. [39876](http://github.com/cms-sw/cmssw/pull/39876){:target="_blank"}  from **@bsunanda**: Run3-gex142D Replace cout with edm::LogVerbatim in Alignment/CommonAlignmentMonitor `alca` created: 2022-10-27 16:31:26 merged: 2022-10-31 12:13:48

103. [39875](http://github.com/cms-sw/cmssw/pull/39875){:target="_blank"}  from **@wddgit**: Migration from deprecated ::JetCorrector class, NoPileUpPFMEtDataProducer `reconstruction` created: 2022-10-27 16:17:58 merged: 2022-11-08 20:09:44

104. [39874](http://github.com/cms-sw/cmssw/pull/39874){:target="_blank"}  from **@Dr15Jones**: Catch case where parent index is bad in Hydjet `generators` created: 2022-10-27 14:05:47 merged: 2022-11-08 03:04:38

105. [39873](http://github.com/cms-sw/cmssw/pull/39873){:target="_blank"}  from **@swagata87**: [TsosGaussianStateConversions] Require GSF states to be positive definite [12_6_X] `reconstruction` created: 2022-10-27 13:38:46 merged: 2022-10-31 12:23:26

106. [39872](http://github.com/cms-sw/cmssw/pull/39872){:target="_blank"}  from **@smuzaffar**: Fix unit test: use LNF so that input files can be read from ibeos `alca` created: 2022-10-27 13:16:18 merged: 2022-10-28 07:16:42

107. [39871](http://github.com/cms-sw/cmssw/pull/39871){:target="_blank"}  from **@bsunanda**: Phase2-hgx327C Delete some of the obsolete files in Geometry/HGCalCommonData/test/python `geometry` `upgrade` created: 2022-10-27 09:35:28 merged: 2022-10-27 15:30:14

108. [39870](http://github.com/cms-sw/cmssw/pull/39870){:target="_blank"}  from **@cecilecaillol**: [L1T] bugfix, remove duplicate file `l1` `upgrade` created: 2022-10-27 08:04:06 merged: 2022-10-27 15:29:48

109. [39869](http://github.com/cms-sw/cmssw/pull/39869){:target="_blank"}  from **@bsunanda**: Phase2-hgx327B Add a test suit to investigate why some of the SimHits are declared invalid in Geometry/HGCalCommonData `geometry` `upgrade` created: 2022-10-27 06:47:27 merged: 2022-10-30 16:59:49

110. [39867](http://github.com/cms-sw/cmssw/pull/39867){:target="_blank"}  from **@guitargeek**: RooFit-related fixes in DiMuonMassBiasClient `dqm` created: 2022-10-26 22:50:42 merged: 2022-10-28 07:44:31

111. [39866](http://github.com/cms-sw/cmssw/pull/39866){:target="_blank"}  from **@trackreco**: [MkFit] Phase2 geometry & String configurable standard functions `reconstruction` created: 2022-10-26 22:26:57 merged: 2022-11-21 13:50:45

112. [39864](http://github.com/cms-sw/cmssw/pull/39864){:target="_blank"}  from **@wddgit**: Cleanup, RecoJets/JetAnalyzers, Motivated by JetCorrector Migration `reconstruction` created: 2022-10-26 19:22:24 merged: 2022-11-14 11:09:50

113. [39863](http://github.com/cms-sw/cmssw/pull/39863){:target="_blank"}  from **@mandrenguyen**: Raw prime wf for Run 3 data w/ dropped strips + approx. clusters `daq` `operations` `reconstruction` `pdmv` `upgrade` created: 2022-10-26 18:06:26 merged: 2022-11-01 18:31:47

114. [39861](http://github.com/cms-sw/cmssw/pull/39861){:target="_blank"}  from **@ahinzmann**: Enable Puppi photon protection for jets `reconstruction` created: 2022-10-26 15:28:47 merged: 2022-11-14 15:20:57

115. [39860](http://github.com/cms-sw/cmssw/pull/39860){:target="_blank"}  from **@quark2**: GE21 recHits in GEM onlineDQM `dqm` created: 2022-10-26 15:17:38 merged: 2022-10-28 07:49:13

116. [39859](http://github.com/cms-sw/cmssw/pull/39859){:target="_blank"}  from **@missirol**: give `OnlineLuminosityRecord` info to HLT's `LumiMonitor` plugin `dqm` `hlt` created: 2022-10-26 14:27:22 merged: 2022-11-04 07:36:59

117. [39858](http://github.com/cms-sw/cmssw/pull/39858){:target="_blank"}  from **@mmusich**: Add AlCaReco producers in phase-2 workflows `alca` `reconstruction` `pdmv` `upgrade` created: 2022-10-26 12:09:15 merged: 2022-10-28 07:55:19

118. [39857](http://github.com/cms-sw/cmssw/pull/39857){:target="_blank"}  from **@fabiocos**: MTD simulation and validation: move hit position from entry point to local position `dqm` `simulation` `upgrade` created: 2022-10-26 09:47:09 merged: 2022-11-02 10:18:28

119. [39855](http://github.com/cms-sw/cmssw/pull/39855){:target="_blank"}  from **@bsunanda**: Run3-gex142C Use tokens rather than labels in accessing collections within Alignments/MuonAlignmentAlgorithms `alca` created: 2022-10-26 07:27:28 merged: 2022-10-31 12:14:23

120. [39854](http://github.com/cms-sw/cmssw/pull/39854){:target="_blank"}  from **@leonardogiannini**: mkfit pixelLess-specific DNN training `reconstruction` created: 2022-10-26 06:49:51 merged: 2022-10-31 19:19:45

121. [39852](http://github.com/cms-sw/cmssw/pull/39852){:target="_blank"}  from **@Dr15Jones**: Add histogram full name if exception happens in DQMRootSource `dqm` created: 2022-10-25 21:48:31 merged: 2022-10-28 07:40:31

122. [39850](http://github.com/cms-sw/cmssw/pull/39850){:target="_blank"}  from **@vlimant**: simple option to rerun failed workflows from a matrix report `pdmv` `upgrade` created: 2022-10-25 20:23:55 merged: 2022-10-31 16:37:10

123. [39848](http://github.com/cms-sw/cmssw/pull/39848){:target="_blank"}  from **@wddgit**: Remove deprecated JetPartonCorrector `analysis` created: 2022-10-25 19:16:33 merged: 2022-10-27 15:48:40

124. [39841](http://github.com/cms-sw/cmssw/pull/39841){:target="_blank"}  from **@srimanob**: Add D97 Phase-2 geometry `geometry` `operations` `pdmv` `upgrade` created: 2022-10-25 13:08:50 merged: 2022-11-04 07:03:21

125. [39836](http://github.com/cms-sw/cmssw/pull/39836){:target="_blank"}  from **@cecilecaillol**: [L1T] Phase-2, track MET update for FW sync (new) `l1` `upgrade` created: 2022-10-24 18:44:16 merged: 2022-11-03 13:00:43

126. [39834](http://github.com/cms-sw/cmssw/pull/39834){:target="_blank"}  from **@missirol**: use `--hltProcess reHLT` in Run-3 Data RelVals `pdmv` `upgrade` created: 2022-10-24 08:57:19 merged: 2022-10-28 07:24:20

127. [39833](http://github.com/cms-sw/cmssw/pull/39833){:target="_blank"}  from **@bsunanda**: Run3-gex142B Use tokens rather than labels in accessing collections in Alignment/CommonAlignmentProducer `alca` created: 2022-10-24 04:03:18 merged: 2022-10-29 17:00:15

128. [39823](http://github.com/cms-sw/cmssw/pull/39823){:target="_blank"}  from **@francescobrivio**: Update Run3 offline and offline_relval GTs `alca` created: 2022-10-21 17:21:38 merged: 2022-11-10 21:30:55

129. [39818](http://github.com/cms-sw/cmssw/pull/39818){:target="_blank"}  from **@johnalison**: Update trigger filters for jets stored in Nano for Run3 menu `xpog` created: 2022-10-21 15:46:44 merged: 2022-10-31 16:42:20

130. [39810](http://github.com/cms-sw/cmssw/pull/39810){:target="_blank"}  from **@SohamBhattacharya**: Switch to TICLv4 for offline HGCAL electrons and photons `reconstruction` `upgrade` created: 2022-10-21 08:48:07 merged: 2022-10-27 15:39:38

131. [39805](http://github.com/cms-sw/cmssw/pull/39805){:target="_blank"}  from **@ravindkv**: duplicated hcalDepthTowerSumEt in GsfElectron.h `reconstruction` created: 2022-10-20 23:55:20 merged: 2022-10-27 12:10:26

132. [39801](http://github.com/cms-sw/cmssw/pull/39801){:target="_blank"}  from **@Dr15Jones**: Fix CMS deprecation warnings in  RecoEgamma subsystem `reconstruction` created: 2022-10-20 18:40:20 merged: 2022-10-31 16:42:48

133. [39796](http://github.com/cms-sw/cmssw/pull/39796){:target="_blank"}  from **@vlimant**: NANO configuration Cleanup `alca` `operations` `reconstruction` `pdmv` `upgrade` `xpog` created: 2022-10-20 14:21:56 merged: 2022-11-08 05:27:11

134. [39795](http://github.com/cms-sw/cmssw/pull/39795){:target="_blank"}  from **@indra-ehep**: Muon Tomography with the reconstructed files `dqm` created: 2022-10-20 13:21:15 merged: 2022-10-28 07:20:22

135. [39776](http://github.com/cms-sw/cmssw/pull/39776){:target="_blank"}  from **@trackreco**: Disable computation of Q probability in SiPixel template CPE for iterative tracking `reconstruction` created: 2022-10-19 14:03:07 merged: 2022-10-28 19:38:06

136. [39758](http://github.com/cms-sw/cmssw/pull/39758){:target="_blank"}  from **@tvami**: Add new HI Beamspot to the Run-3 HI MC + change vertex smearing to use the estimated HI version `alca` `pdmv` `upgrade` created: 2022-10-18 16:39:59 merged: 2022-11-01 17:37:35

137. [39736](http://github.com/cms-sw/cmssw/pull/39736){:target="_blank"}  from **@hahnjo**: Add G4HepEm to CMSSW `core` `simulation` created: 2022-10-14 15:44:40 merged: 2022-11-22 18:00:18

138. [39722](http://github.com/cms-sw/cmssw/pull/39722){:target="_blank"}  from **@AdrianoDee**: Add tracking only PU workflows `pdmv` `upgrade` created: 2022-10-13 09:59:07 merged: 2022-11-10 21:29:56

139. [39498](http://github.com/cms-sw/cmssw/pull/39498){:target="_blank"}  from **@fwyzard**: Require the AlpakaService to be enabled before running on a Device `heterogeneous` created: 2022-09-25 16:32:26 merged: 2022-10-28 19:38:37

140. [39441](http://github.com/cms-sw/cmssw/pull/39441){:target="_blank"}  from **@slowmoyang**: GE21-ME21 segment reconstruction `dqm` `operations` `reconstruction` `upgrade` created: 2022-09-19 05:06:33 merged: 2022-11-22 10:54:34

141. [39428](http://github.com/cms-sw/cmssw/pull/39428){:target="_blank"}  from **@makortel**: Evolution of the Alpaka "gpu framework" `core` `heterogeneous` created: 2022-09-16 18:46:30 merged: 2022-11-22 23:54:34

142. [39355](http://github.com/cms-sw/cmssw/pull/39355){:target="_blank"}  from **@cramonal**: Adding MVA ID to nanoAOD code `xpog` created: 2022-09-09 09:39:25 merged: 2022-11-16 13:11:21

143. [39309](http://github.com/cms-sw/cmssw/pull/39309){:target="_blank"}  from **@mrcthiel**: Adding photon and muon leg trigger filters of HLT_Mu17_Photon30_IsoCa `xpog` created: 2022-09-05 13:39:52 merged: 2022-11-02 13:55:15

144. [39087](http://github.com/cms-sw/cmssw/pull/39087){:target="_blank"}  from **@jeongeun**: Replace Geometry_cff with GeometryDB_cff in MuonAnalysis `analysis` created: 2022-08-17 08:19:02 merged: 2022-10-27 16:32:44

145. [38304](http://github.com/cms-sw/cmssw/pull/38304){:target="_blank"}  from **@cms-trackeralign**: Introduction of New-All-In-One tool for Offline Validation of TrkAlignment  `alca` created: 2022-06-09 13:32:45 merged: 2022-11-08 20:17:22

#### CMSDIST Changes between Tags REL/CMSSW_12_6_0_pre4/el8_amd64_gcc10 and REL/CMSSW_12_6_0_pre5/el8_amd64_gcc10:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_12_6_0_pre4/el8_amd64_gcc10...REL/CMSSW_12_6_0_pre5/el8_amd64_gcc10)



1. [8191](http://github.com/cms-sw/cmsdist/pull/8191){:target="_blank"}  from **@cms-sw**: Update tag for RecoTracker-MkFit to V00-10-00 created: 2022-11-22 10:08:14 merged: 2022-11-22 10:15:28

2. [8189](http://github.com/cms-sw/cmsdist/pull/8189){:target="_blank"}  from **@cms-sw**: Fix cmsmon/stern created: 2022-11-17 08:40:06 merged: 2022-11-17 10:14:33

3. [8182](http://github.com/cms-sw/cmsdist/pull/8182){:target="_blank"}  from **@cms-sw**: Update cmsmon-tools.spec created: 2022-11-16 09:57:41 merged: 2022-11-16 17:27:43

4. [8181](http://github.com/cms-sw/cmsdist/pull/8181){:target="_blank"}  from **@dan131riley**: set jemalloc hugepagesize on aarch64 to avoid huge address space allocations created: 2022-11-15 18:58:24 merged: 2022-11-17 10:25:14

5. [8176](http://github.com/cms-sw/cmsdist/pull/8176){:target="_blank"}  from **@dan131riley**: build cpu_features so that it can be linked into plugins created: 2022-11-09 19:56:36 merged: 2022-11-10 07:28:52

6. [8175](http://github.com/cms-sw/cmsdist/pull/8175){:target="_blank"}  from **@cms-sw**: Update tag for RecoEgamma-PhotonIdentification to V01-06-00 created: 2022-11-09 06:46:53 merged: 2022-11-09 06:47:43

7. [8174](http://github.com/cms-sw/cmsdist/pull/8174){:target="_blank"}  from **@cms-sw**: Update tag for Alignment-OfflineValidation to V00-03-00 created: 2022-11-08 20:35:22 merged: 2022-11-08 20:37:47

8. [8173](http://github.com/cms-sw/cmsdist/pull/8173){:target="_blank"}  from **@cms-sw**: [SCRAM] map cs/alma/rocky/rhel to el created: 2022-11-08 19:35:46 merged: 2022-11-09 06:51:57

9. [8170](http://github.com/cms-sw/cmsdist/pull/8170){:target="_blank"}  from **@cms-sw**: [BuildRules] Fix for multiple DROP_DEPS created: 2022-11-07 14:07:53 merged: 2022-11-08 07:39:44

10. [8163](http://github.com/cms-sw/cmsdist/pull/8163){:target="_blank"}  from **@cms-sw**: Revert "Rivet 3.1.7 & YODA 1.9.7" created: 2022-11-01 17:06:59 merged: 2022-11-01 22:16:18

11. [8159](http://github.com/cms-sw/cmsdist/pull/8159){:target="_blank"}  from **@belforte**: promote crab-dev to crab-prod. crab-pre to old crab-prod created: 2022-10-31 16:10:14 merged: 2022-10-31 20:15:35

12. [8158](http://github.com/cms-sw/cmsdist/pull/8158){:target="_blank"}  from **@cms-sw**: Add patch to disable builting Rivet documentation created: 2022-10-31 15:36:20 merged: 2022-11-01 11:09:40

13. [8155](http://github.com/cms-sw/cmsdist/pull/8155){:target="_blank"}  from **@aandvalenzuela**: Update dd4hep to follow latest version/commits created: 2022-10-31 09:45:13 merged: 2022-11-01 13:44:41

14. [8154](http://github.com/cms-sw/cmsdist/pull/8154){:target="_blank"}  from **@wouf**: Update hydjet.spec created: 2022-10-27 14:55:31 merged: 2022-11-08 10:16:51

15. [8153](http://github.com/cms-sw/cmsdist/pull/8153){:target="_blank"}  from **@cms-sw**: [cmssw-osenv] Check and mount for /pool created: 2022-10-27 14:54:41 merged: 2022-10-27 20:29:52

16. [8152](http://github.com/cms-sw/cmsdist/pull/8152){:target="_blank"}  from **@cms-sw**: [ROOT] Allow submodules to contain headers missing headers created: 2022-10-27 12:11:15 merged: 2022-10-27 20:47:06

17. [8109](http://github.com/cms-sw/cmsdist/pull/8109){:target="_blank"}  from **@mseidel42**: Rivet 3.1.7 & YODA 1.9.7 created: 2022-09-29 06:58:15 merged: 2022-10-27 20:34:36
