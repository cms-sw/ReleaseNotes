---
layout: post
rel_link:  "13_0_0_pre2"
title:  "CMSSW_13_0_0_pre2"
date:   2022-12-14 22:29:15
categories: cmssw
relmajor: 13
relminor: 0
relsubminor: 0
relpre: _pre2
---

# CMSSW_13_0_0_pre2
#### Changes since CMSSW_13_0_0_pre1:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_13_0_0_pre1...CMSSW_13_0_0_pre2)



1. [40310](http://github.com/cms-sw/cmssw/pull/40310){:target="_blank"}  from **@gartung**: Utilities/StaticAnalysers: Fix assert in ConstCast and ConstCastAway checkers. `core` created: 2022-12-13 21:59:46 merged: 2022-12-14 15:40:06

2. [40306](http://github.com/cms-sw/cmssw/pull/40306){:target="_blank"}  from **@makortel**: [UBSAN] Add missing dependence to Calibration/HcalCalibAlgos/test/BuildFile.xml `alca` created: 2022-12-13 14:49:12 merged: 2022-12-14 06:30:52

3. [40303](http://github.com/cms-sw/cmssw/pull/40303){:target="_blank"}  from **@Dr15Jones**: Avoid short-circuiting ESWatchers in  ElectronSeedGenerator `reconstruction` created: 2022-12-12 21:16:39 merged: 2022-12-13 09:21:32

4. [40302](http://github.com/cms-sw/cmssw/pull/40302){:target="_blank"}  from **@Dr15Jones**: Avoid short-circuiting ESWatchers in SiStripCorrelateBadStripAndNoise `dqm` created: 2022-12-12 21:05:56 merged: 2022-12-13 09:21:38

5. [40301](http://github.com/cms-sw/cmssw/pull/40301){:target="_blank"}  from **@wddgit**: Migrate HI_DiJetSkim_cff.py to use reco::JetCorrector `analysis` created: 2022-12-12 21:03:36 merged: 2022-12-13 06:20:43

6. [40300](http://github.com/cms-sw/cmssw/pull/40300){:target="_blank"}  from **@Dr15Jones**: Avoid short-circuiting ESWatchers in PFCandidateRecalibrator `reconstruction` created: 2022-12-12 20:52:39 merged: 2022-12-13 09:22:02

7. [40298](http://github.com/cms-sw/cmssw/pull/40298){:target="_blank"}  from **@gartung**: Utilities/StaticAnalyzer: Add null_ptr guard to ConstCast and ConstCastAway Checkers. `core` created: 2022-12-12 18:50:19 merged: 2022-12-13 14:22:02

8. [40297](http://github.com/cms-sw/cmssw/pull/40297){:target="_blank"}  from **@Dr15Jones**: Avoid short-circuiting ESWatchers in FastSimProducer `fastsim` created: 2022-12-12 18:43:52 merged: 2022-12-13 08:46:01

9. [40296](http://github.com/cms-sw/cmssw/pull/40296){:target="_blank"}  from **@Dr15Jones**: Protect TFile in HFShowerLibrary from thread-local context `simulation` created: 2022-12-12 18:06:06 merged: 2022-12-13 08:39:22

10. [40293](http://github.com/cms-sw/cmssw/pull/40293){:target="_blank"}  from **@elusian**: Fix `PostDQMOffline*` sequences in cmsDriver.py `dqm` `operations` created: 2022-12-12 16:21:25 merged: 2022-12-13 16:47:01

11. [40289](http://github.com/cms-sw/cmssw/pull/40289){:target="_blank"}  from **@srimanob**: Enable Phase-2 HLT wf which runs together with DIGI+L1 `pdmv` `upgrade` created: 2022-12-12 13:58:13 merged: 2022-12-13 21:34:34

12. [40288](http://github.com/cms-sw/cmssw/pull/40288){:target="_blank"}  from **@missirol**: add unit test for `TriggerEvent*` analyzers `hlt` created: 2022-12-12 12:51:04 merged: 2022-12-13 10:23:58

13. [40284](http://github.com/cms-sw/cmssw/pull/40284){:target="_blank"}  from **@riga**: Move TF session in DeepMETProducer to global cache `reconstruction` created: 2022-12-10 18:06:03 merged: 2022-12-13 09:59:20

14. [40282](http://github.com/cms-sw/cmssw/pull/40282){:target="_blank"}  from **@riga**: Remove obsolete tf session const_cast's in RecoHGCal `reconstruction` `upgrade` created: 2022-12-10 18:05:48 merged: 2022-12-12 09:44:48

15. [40278](http://github.com/cms-sw/cmssw/pull/40278){:target="_blank"}  from **@Dr15Jones**: Allow caching of HFShowerLibrary `simulation` created: 2022-12-09 18:52:39 merged: 2022-12-12 09:18:47

16. [40276](http://github.com/cms-sw/cmssw/pull/40276){:target="_blank"}  from **@Dr15Jones**: Initialize variables for SiStripMonitorDigi::SubDetMEs `dqm` created: 2022-12-09 16:45:40 merged: 2022-12-13 21:37:34

17. [40275](http://github.com/cms-sw/cmssw/pull/40275){:target="_blank"}  from **@Dr15Jones**: Set nullptr for L1TParticleFlow classes `l1` `upgrade` created: 2022-12-09 16:09:36 merged: 2022-12-12 12:21:55

18. [40274](http://github.com/cms-sw/cmssw/pull/40274){:target="_blank"}  from **@epalencia**: Update VertexWord.h sumPt to 12b format, 10b int. `l1` created: 2022-12-09 15:40:20 merged: 2022-12-12 12:26:06

19. [40273](http://github.com/cms-sw/cmssw/pull/40273){:target="_blank"}  from **@Dr15Jones**: Check for null histogram in PlotAlignmentValidation `alca` created: 2022-12-09 14:53:34 merged: 2022-12-12 09:28:52

20. [40267](http://github.com/cms-sw/cmssw/pull/40267){:target="_blank"}  from **@CMS-LUMI-POG**: New Run3 pileup scenarios for max PU studies `operations` `simulation` created: 2022-12-09 11:16:03 merged: 2022-12-13 08:47:24

21. [40266](http://github.com/cms-sw/cmssw/pull/40266){:target="_blank"}  from **@LukaLambrecht**: modify nanoDQMIO configuration `dqm` created: 2022-12-09 11:08:30 merged: 2022-12-13 17:38:14

22. [40265](http://github.com/cms-sw/cmssw/pull/40265){:target="_blank"}  from **@malbouis**: Add all PDs from 2022 in AlCaReco Matrix `alca` created: 2022-12-08 20:10:48 merged: 2022-12-09 14:34:58

23. [40264](http://github.com/cms-sw/cmssw/pull/40264){:target="_blank"}  from **@mmusich**: template `DQM/SiPixelPhase1Heterogenous` class to be able to handle the Phase-2 SoA objects `dqm` `hlt` created: 2022-12-08 20:09:03 merged: 2022-12-13 21:51:26

24. [40263](http://github.com/cms-sw/cmssw/pull/40263){:target="_blank"}  from **@dan131riley**: Turn off Tauolapp output redirection `generators` created: 2022-12-08 18:33:25 merged: 2022-12-13 08:09:40

25. [40255](http://github.com/cms-sw/cmssw/pull/40255){:target="_blank"}  from **@mmusich**: `SiStripHitEfficiencyHarvester`: Hit efficiency summary saved in dqm files `alca` created: 2022-12-07 10:35:22 merged: 2022-12-08 15:54:30

26. [40254](http://github.com/cms-sw/cmssw/pull/40254){:target="_blank"}  from **@jieunyoo**: add filter for intermediate resonance particles `generators` created: 2022-12-06 22:47:34 merged: 2022-12-13 08:13:55

27. [40253](http://github.com/cms-sw/cmssw/pull/40253){:target="_blank"}  from **@Dr15Jones**: Remove last use of tbb::task::suspend `core` created: 2022-12-06 21:46:32 merged: 2022-12-08 15:52:15

28. [40252](http://github.com/cms-sw/cmssw/pull/40252){:target="_blank"}  from **@civanch**: Updated Geant4 user actions `simulation` created: 2022-12-06 18:58:10 merged: 2022-12-07 13:22:35

29. [40249](http://github.com/cms-sw/cmssw/pull/40249){:target="_blank"}  from **@p-masterson**: Replace old cms_test_conditions schema with cms_cond_general_w; use C `db` created: 2022-12-06 16:30:33 merged: 2022-12-08 15:50:46

30. [40246](http://github.com/cms-sw/cmssw/pull/40246){:target="_blank"}  from **@bsunanda**: Phase2-hgx333A Modify the test code to spot the issue for V17 Geometry of HGCal `geometry` `upgrade` created: 2022-12-06 13:12:05 merged: 2022-12-07 13:23:16

31. [40245](http://github.com/cms-sw/cmssw/pull/40245){:target="_blank"}  from **@guitargeek**: Move all PCLConfigPlugins sources to `plugins` `db` created: 2022-12-06 10:56:32 merged: 2022-12-08 15:50:00

32. [40244](http://github.com/cms-sw/cmssw/pull/40244){:target="_blank"}  from **@AdrianoDee**: Adding Running PU ProdLike Wfs `operations` `pdmv` `upgrade` created: 2022-12-06 09:47:28 merged: 2022-12-12 18:23:50

33. [40243](http://github.com/cms-sw/cmssw/pull/40243){:target="_blank"}  from **@cms-tsg-storm**: Fix 2022v15 frozen HLT menu for PixelCPEFast changes `hlt` created: 2022-12-06 09:04:11 merged: 2022-12-06 15:51:00

34. [40242](http://github.com/cms-sw/cmssw/pull/40242){:target="_blank"}  from **@smuzaffar**: [SIMULATION] [LLVM 14] bitwise-instead-of-logical warnings fixed `simulation` created: 2022-12-06 07:02:20 merged: 2022-12-08 15:49:07

35. [40235](http://github.com/cms-sw/cmssw/pull/40235){:target="_blank"}  from **@vlimant**: short name also in the final report `pdmv` `upgrade` created: 2022-12-04 13:13:46 merged: 2022-12-06 14:36:41

36. [40232](http://github.com/cms-sw/cmssw/pull/40232){:target="_blank"}  from **@nurfikri89**: [JMENanoAOD] Setup DQM and increase precision of PileUp ID & QGL input variables `dqm` `xpog` created: 2022-12-03 15:30:07 merged: 2022-12-06 14:14:32

37. [40230](http://github.com/cms-sw/cmssw/pull/40230){:target="_blank"}  from **@Prasant1993**: Electron MVA-based ID for Run3 from EGamma POG `reconstruction` `xpog` created: 2022-12-03 00:41:21 merged: 2022-12-08 15:48:20

38. [40228](http://github.com/cms-sw/cmssw/pull/40228){:target="_blank"}  from **@Michael-Krohn**: HCAL: Modifications to the LUT validation script `db` created: 2022-12-02 17:03:37 merged: 2022-12-03 08:12:28

39. [40227](http://github.com/cms-sw/cmssw/pull/40227){:target="_blank"}  from **@bsunanda**: Run-sim137 Correct the code in the analysis code of Simulation `simulation` created: 2022-12-02 16:52:15 merged: 2022-12-05 20:46:00

40. [40225](http://github.com/cms-sw/cmssw/pull/40225){:target="_blank"}  from **@archiron**: FakeHistos  V1 : plugins part `dqm` created: 2022-12-02 14:55:16 merged: 2022-12-08 15:47:30

41. [40223](http://github.com/cms-sw/cmssw/pull/40223){:target="_blank"}  from **@missirol**: update of `hltDumpStream` for Run-3 HLT menus `hlt` created: 2022-12-02 11:45:59 merged: 2022-12-09 14:36:42

42. [40222](http://github.com/cms-sw/cmssw/pull/40222){:target="_blank"}  from **@mmusich**: minor improvements to `Alignment/OfflineValidation` `alca` created: 2022-12-02 11:43:16 merged: 2022-12-04 04:42:13

43. [40220](http://github.com/cms-sw/cmssw/pull/40220){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `12_6_X` (1/N) [`13_0_X`] `hlt` created: 2022-12-02 09:06:19 merged: 2022-12-02 14:26:31

44. [40216](http://github.com/cms-sw/cmssw/pull/40216){:target="_blank"}  from **@saumyaphor4252**: Update SiPixel bad components in Run 3 MC GTs `alca` created: 2022-12-01 20:43:35 merged: 2022-12-02 21:55:56

45. [40215](http://github.com/cms-sw/cmssw/pull/40215){:target="_blank"}  from **@AdrianoDee**: Avoid CPE Fast ES Producers Renaming `reconstruction` created: 2022-12-01 16:41:20 merged: 2022-12-05 20:44:15

46. [40211](http://github.com/cms-sw/cmssw/pull/40211){:target="_blank"}  from **@vlimant**: update input dataset and fix step `pdmv` `upgrade` created: 2022-12-01 10:07:54 merged: 2022-12-02 12:08:56

47. [40210](http://github.com/cms-sw/cmssw/pull/40210){:target="_blank"}  from **@smuzaffar**: [LTO] Add default initialization to fix LTO build warnings `reconstruction` created: 2022-12-01 09:46:02 merged: 2022-12-07 14:30:25

48. [40209](http://github.com/cms-sw/cmssw/pull/40209){:target="_blank"}  from **@swertz**: Nano: restore Run2/3 consistency between electron/photon IDs; remove scale+smearing correction for Run3 `operations` `xpog` created: 2022-12-01 09:34:32 merged: 2022-12-03 08:47:56

49. [40208](http://github.com/cms-sw/cmssw/pull/40208){:target="_blank"}  from **@bsunanda**: Phase2-hgx333 Bug fix for invalid DetID declaration for SimHits n V16/V17 geometry versions of HGCal `geometry` `upgrade` created: 2022-12-01 07:17:58 merged: 2022-12-06 14:35:58

50. [40207](http://github.com/cms-sw/cmssw/pull/40207){:target="_blank"}  from **@mmusich**: provide a record for `cond::BasicPayload` `alca` `db` created: 2022-11-30 18:22:10 merged: 2022-12-01 20:18:28

51. [40206](http://github.com/cms-sw/cmssw/pull/40206){:target="_blank"}  from **@AdrianoDee**: Fix for TTRHBuilders with PixelCPEFast `reconstruction` created: 2022-11-30 18:21:23 merged: 2022-12-01 09:08:25

52. [40204](http://github.com/cms-sw/cmssw/pull/40204){:target="_blank"}  from **@gartung**: Utilities/StaticAnalyzers: Check for CMS_THREAD_SAFETY or CMS_SA_ALLOW attributes on statments using const_cast and skip warnings. `core` created: 2022-11-30 16:47:01 merged: 2022-11-30 22:33:17

53. [40203](http://github.com/cms-sw/cmssw/pull/40203){:target="_blank"}  from **@smuzaffar**: [CORE] [LLVM14] Apply code checks `core` created: 2022-11-30 15:12:00 merged: 2022-11-30 23:00:25

54. [40202](http://github.com/cms-sw/cmssw/pull/40202){:target="_blank"}  from **@smuzaffar**: [HLT] [LLVM14] Apply code checks `hlt` created: 2022-11-30 15:11:39 merged: 2022-11-30 22:29:37

55. [40201](http://github.com/cms-sw/cmssw/pull/40201){:target="_blank"}  from **@smuzaffar**: [XPOG] [LLVM14] Apply code checks `xpog` created: 2022-11-30 15:08:01 merged: 2022-12-01 08:02:42

56. [40200](http://github.com/cms-sw/cmssw/pull/40200){:target="_blank"}  from **@smuzaffar**: [ALCA-DB] [LLVM14] Apply code checks `alca` `db` created: 2022-11-30 15:07:43 merged: 2022-11-30 22:31:13

57. [40199](http://github.com/cms-sw/cmssw/pull/40199){:target="_blank"}  from **@smuzaffar**: [VISUALIZATION] [LLVM14] Apply code checks `visualization` created: 2022-11-30 15:07:10 merged: 2022-12-01 20:15:12

58. [40198](http://github.com/cms-sw/cmssw/pull/40198){:target="_blank"}  from **@smuzaffar**: [GEOMETRY] [LLVM14] Apply code checks `geometry` created: 2022-11-30 15:06:30 merged: 2022-12-01 08:01:16

59. [40197](http://github.com/cms-sw/cmssw/pull/40197){:target="_blank"}  from **@smuzaffar**: [RECONSTRUCTION-UPGRADE] [LLVM14] Apply code checks `reconstruction` `upgrade` created: 2022-11-30 15:06:08 merged: 2022-12-03 19:56:35

60. [40196](http://github.com/cms-sw/cmssw/pull/40196){:target="_blank"}  from **@smuzaffar**: [L1] [LLVM14] Apply code checks `l1` created: 2022-11-30 15:05:50 merged: 2022-12-02 11:53:45

61. [40195](http://github.com/cms-sw/cmssw/pull/40195){:target="_blank"}  from **@smuzaffar**: [DB] [LLVM14] Apply code checks `db` created: 2022-11-30 15:04:41 merged: 2022-12-01 20:23:44

62. [40194](http://github.com/cms-sw/cmssw/pull/40194){:target="_blank"}  from **@smuzaffar**: [ANALYSIS] [LLVM14] Apply code checks `analysis` created: 2022-11-30 15:03:55 merged: 2022-12-01 07:57:31

63. [40193](http://github.com/cms-sw/cmssw/pull/40193){:target="_blank"}  from **@smuzaffar**: [ALCA] [LLVM14] Apply code checks `alca` created: 2022-11-30 15:03:30 merged: 2022-12-02 08:26:03

64. [40192](http://github.com/cms-sw/cmssw/pull/40192){:target="_blank"}  from **@smuzaffar**: [RECONSTRUCTION-XPOG] [LLVM14] Apply code checks `reconstruction` `xpog` created: 2022-11-30 15:02:36 merged: 2022-12-11 20:17:42

65. [40191](http://github.com/cms-sw/cmssw/pull/40191){:target="_blank"}  from **@smuzaffar**: [GENERATORS] [LLVM14] Apply code checks `generators` created: 2022-11-30 15:02:14 merged: 2022-12-11 20:14:51

66. [40190](http://github.com/cms-sw/cmssw/pull/40190){:target="_blank"}  from **@smuzaffar**: [ALCA-L1] [LLVM14] Apply code checks `alca` `l1` created: 2022-11-30 15:01:30 merged: 2022-12-02 11:52:11

67. [40189](http://github.com/cms-sw/cmssw/pull/40189){:target="_blank"}  from **@smuzaffar**: [RECONSTRUCTION] [LLVM14] Apply code checks `reconstruction` created: 2022-11-30 15:01:12 merged: 2022-12-03 20:01:51

68. [40188](http://github.com/cms-sw/cmssw/pull/40188){:target="_blank"}  from **@smuzaffar**: [GEOMETRY-UPGRADE] [LLVM14] Apply code checks `geometry` `upgrade` created: 2022-11-30 14:59:50 merged: 2022-12-05 20:41:52

69. [40187](http://github.com/cms-sw/cmssw/pull/40187){:target="_blank"}  from **@smuzaffar**: [DQM-L1] [LLVM14] Apply code checks `dqm` `l1` created: 2022-11-30 14:59:02 merged: 2022-12-02 11:50:07

70. [40186](http://github.com/cms-sw/cmssw/pull/40186){:target="_blank"}  from **@smuzaffar**: [DQM] [LLVM14] Apply code checks `dqm` created: 2022-11-30 14:58:35 merged: 2022-12-02 11:49:46

71. [40185](http://github.com/cms-sw/cmssw/pull/40185){:target="_blank"}  from **@smuzaffar**: [SIMULATION] [LLVM14] Apply code checks `simulation` created: 2022-11-30 14:56:20 merged: 2022-12-01 08:01:43

72. [40181](http://github.com/cms-sw/cmssw/pull/40181){:target="_blank"}  from **@guitargeek**: Clean unused dependencies from BuildFiles `analysis` `alca` `dqm` `hlt` `l1` `reconstruction` `db` `upgrade` `xpog` created: 2022-11-29 17:41:54 merged: 2022-12-03 08:51:36

73. [40180](http://github.com/cms-sw/cmssw/pull/40180){:target="_blank"}  from **@civanch**: Safe Geant4 stacking action `simulation` created: 2022-11-29 17:26:11 merged: 2022-12-01 20:15:57

74. [40179](http://github.com/cms-sw/cmssw/pull/40179){:target="_blank"}  from **@makortel**: Make two function-static variables const `core` created: 2022-11-29 16:57:40 merged: 2022-12-02 15:57:08

75. [40175](http://github.com/cms-sw/cmssw/pull/40175){:target="_blank"}  from **@mandrenguyen**: Remove deprecated `NoPileUpPFMEtDataProducer` `reconstruction` created: 2022-11-29 14:43:41 merged: 2022-11-30 08:12:46

76. [40172](http://github.com/cms-sw/cmssw/pull/40172){:target="_blank"}  from **@abdoulline**: Adding "hcal2" DQM to "rerecoCommon" in autoDQM.py `dqm` created: 2022-11-29 11:11:45 merged: 2022-12-02 12:05:01

77. [40170](http://github.com/cms-sw/cmssw/pull/40170){:target="_blank"}  from **@mmusich**: Fix warning message about `PixelCPEFast` in `TkTransientTrackingRecHitBuilderESProducer` `alca` `reconstruction` created: 2022-11-29 11:06:56 merged: 2022-11-30 08:18:28

78. [40169](http://github.com/cms-sw/cmssw/pull/40169){:target="_blank"}  from **@swertz**: NanoDQM: remove consumesMany, plot bits in bitsets `xpog` created: 2022-11-29 10:58:34 merged: 2022-12-01 20:16:33

79. [40168](http://github.com/cms-sw/cmssw/pull/40168){:target="_blank"}  from **@bsunanda**: Phase2-hgx332 Add debug tools to investigate shortcomings of V16/V17 geometries of HGCal `dqm` `geometry` `simulation` `upgrade` created: 2022-11-29 07:38:20 merged: 2022-12-03 08:26:03

80. [40166](http://github.com/cms-sw/cmssw/pull/40166){:target="_blank"}  from **@makortel**: Add missing dependence on DataFormats/MuonReco to RecoLocalMuon/GEMCSCSegment/test/BuildFile.xml `reconstruction` `upgrade` created: 2022-11-28 18:56:28 merged: 2022-12-01 11:35:14

81. [40165](http://github.com/cms-sw/cmssw/pull/40165){:target="_blank"}  from **@Michael-Krohn**: HCAL: Remove the MIP fine grain bit logic from the HCAL endcap `alca` `l1` created: 2022-11-28 15:44:34 merged: 2022-12-02 12:03:35

82. [40162](http://github.com/cms-sw/cmssw/pull/40162){:target="_blank"}  from **@swertz**: Nano: fix and additions to collection matching, remove cross-cleaning `reconstruction` `xpog` created: 2022-11-27 19:11:54 merged: 2022-12-06 14:30:00

83. [40161](http://github.com/cms-sw/cmssw/pull/40161){:target="_blank"}  from **@riga**: Accept const session in TF interface. `reconstruction` created: 2022-11-27 16:48:26 merged: 2022-12-07 01:06:29

84. [40160](http://github.com/cms-sw/cmssw/pull/40160){:target="_blank"}  from **@bsunanda**: Phase2-hgx331 Transfer HGCal TB related stuff to Geometry/HGCalTestBeam and modify these accordingly `geometry` `simulation` `upgrade` created: 2022-11-27 12:21:13 merged: 2022-12-05 20:38:07

85. [40158](http://github.com/cms-sw/cmssw/pull/40158){:target="_blank"}  from **@missirol**: change default of `resetPSCountersEachLumiSec` to `false` in L1T emulator `l1` created: 2022-11-25 12:48:16 merged: 2022-11-30 22:27:57

86. [40153](http://github.com/cms-sw/cmssw/pull/40153){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `12_5_X` (2/N) [`13_0_X`] `hlt` created: 2022-11-25 10:53:26 merged: 2022-11-27 21:15:38

87. [40151](http://github.com/cms-sw/cmssw/pull/40151){:target="_blank"}  from **@sunilUIET**: addition of WFs with post EE conditions `pdmv` `upgrade` created: 2022-11-24 18:12:14 merged: 2022-11-28 09:15:55

88. [40147](http://github.com/cms-sw/cmssw/pull/40147){:target="_blank"}  from **@cms-tsg-storm**: Use LFN for EDM files of HLT-Validation and HLT-addon tests `hlt` created: 2022-11-24 17:47:46 merged: 2022-11-25 13:50:54

89. [40146](http://github.com/cms-sw/cmssw/pull/40146){:target="_blank"}  from **@fabiocos**: MTD reconstruction: fix local cluster position and uncertainty determination `reconstruction` `upgrade` created: 2022-11-24 16:15:50 merged: 2022-11-28 09:34:16

90. [40145](http://github.com/cms-sw/cmssw/pull/40145){:target="_blank"}  from **@vlimant**: streamline the configuration of TriggerObjectTableProducer `xpog` created: 2022-11-24 15:40:03 merged: 2022-11-29 20:59:38

91. [40144](http://github.com/cms-sw/cmssw/pull/40144){:target="_blank"}  from **@bsunanda**: Phase2-gex146 Remove all references to FastTimerDetID which are no longer used in CMSSW `reconstruction` `simulation` `upgrade` created: 2022-11-24 11:42:04 merged: 2022-11-30 12:35:37

92. [40143](http://github.com/cms-sw/cmssw/pull/40143){:target="_blank"}  from **@fabiocos**: MTD validation: update monitoring of reconstructed clusters `dqm` created: 2022-11-24 10:02:52 merged: 2022-11-28 09:18:22

93. [40139](http://github.com/cms-sw/cmssw/pull/40139){:target="_blank"}  from **@wddgit**: JetCorrector migration in DiJetAnalyzer, GammaJetAnalysis `alca` created: 2022-11-23 22:58:04 merged: 2022-12-02 21:58:41

94. [40136](http://github.com/cms-sw/cmssw/pull/40136){:target="_blank"}  from **@makortel**: Make duplicate branch check work properly with SwitchProducer that has EDAlias case `core` created: 2022-11-23 02:24:42 merged: 2022-11-29 06:11:30

95. [40135](http://github.com/cms-sw/cmssw/pull/40135){:target="_blank"}  from **@CMSTrackerDPG**: Remove deprecated `exists` API in favor of `fillDescriptions` in `SiPixelQualityESProducer` `alca` created: 2022-11-22 23:19:22 merged: 2022-11-28 09:25:00

96. [40133](http://github.com/cms-sw/cmssw/pull/40133){:target="_blank"}  from **@Dr15Jones**: Revived being able to run modules inside a mixing module `core` `simulation` created: 2022-11-22 16:29:16 merged: 2022-12-05 20:37:12

97. [40125](http://github.com/cms-sw/cmssw/pull/40125){:target="_blank"}  from **@vjmastra**: Update and cleaning of BPH trigger DQM/RelVal code and plots `dqm` created: 2022-11-21 17:43:45 merged: 2022-11-28 14:51:45

98. [40122](http://github.com/cms-sw/cmssw/pull/40122){:target="_blank"}  from **@bsunanda**: Phase2-hgx330 Transfer most of the HGCal TB related geometry file to the new branch Geometry/HGCalTBCommonData `geometry` created: 2022-11-21 09:00:33 merged: 2022-11-25 13:59:29

99. [40117](http://github.com/cms-sw/cmssw/pull/40117){:target="_blank"}  from **@lwang046**: HcalDQM: Add protection to collection non-exist case for GPUTask `dqm` created: 2022-11-19 13:06:49 merged: 2022-12-02 12:16:37

100. [40113](http://github.com/cms-sw/cmssw/pull/40113){:target="_blank"}  from **@sroychow**: SiStrip use LFN for unit test input `alca` created: 2022-11-18 17:26:46 merged: 2022-11-28 09:20:50

101. [40107](http://github.com/cms-sw/cmssw/pull/40107){:target="_blank"}  from **@dinyar**: Remove left over uGMT ZS configuration `dqm` created: 2022-11-18 16:19:05 merged: 2022-11-28 17:06:24

102. [40106](http://github.com/cms-sw/cmssw/pull/40106){:target="_blank"}  from **@vlimant**: short names for matrix workflows `pdmv` `upgrade` created: 2022-11-17 22:37:56 merged: 2022-12-03 08:34:59

103. [40104](http://github.com/cms-sw/cmssw/pull/40104){:target="_blank"}  from **@wddgit**: Allow SwitchProducer cases to declare different transient products `core` created: 2022-11-17 17:43:48 merged: 2022-11-25 13:52:15

104. [40100](http://github.com/cms-sw/cmssw/pull/40100){:target="_blank"}  from **@yuanchao**: Add Run 3 muon process using proper DNN b-tagger `alca` `reconstruction` `xpog` created: 2022-11-17 14:58:57 merged: 2022-12-07 13:26:55

105. [40099](http://github.com/cms-sw/cmssw/pull/40099){:target="_blank"}  from **@smorovic**: (DAQ) File based protocol update `daq` `dqm` `hlt` created: 2022-11-17 13:18:54 merged: 2022-11-25 13:57:17

106. [40072](http://github.com/cms-sw/cmssw/pull/40072){:target="_blank"}  from **@abhih1**: Add TTID integrity error plots for ECAL DQM [Master] `dqm` created: 2022-11-15 15:25:12 merged: 2022-11-28 17:04:37

107. [40058](http://github.com/cms-sw/cmssw/pull/40058){:target="_blank"}  from **@yuanchao**: Replacing jet b-tagger with 'pfDeepCSVJetTags:probb' for Run 3. `alca` `dqm` created: 2022-11-14 10:28:45 merged: 2022-11-28 17:04:00

108. [40057](http://github.com/cms-sw/cmssw/pull/40057){:target="_blank"}  from **@guitargeek**: Use `fp_traits_non_native` directly in eos-portable-archive `db` created: 2022-11-14 09:07:19 merged: 2022-11-28 20:27:45

109. [40051](http://github.com/cms-sw/cmssw/pull/40051){:target="_blank"}  from **@bsunanda**: Run3-gex145 Change getByLabel to use tokens in Alignment/OfflineValidation `alca` created: 2022-11-12 06:35:21 merged: 2022-12-06 14:34:42

110. [40043](http://github.com/cms-sw/cmssw/pull/40043){:target="_blank"}  from **@yuanchao**: Add Run 3 patjet process with supported b-taggers `alca` `reconstruction` `xpog` created: 2022-11-10 14:49:45 merged: 2022-12-09 14:38:59

111. [39995](http://github.com/cms-sw/cmssw/pull/39995){:target="_blank"}  from **@GPUOfflinePV-CMS**: New Vertex Clustering in Blocks and Weighted Mean Estimator `operations` `reconstruction` `pdmv` `upgrade` created: 2022-11-07 08:19:09 merged: 2022-11-28 20:03:28

112. [39985](http://github.com/cms-sw/cmssw/pull/39985){:target="_blank"}  from **@quark2**: Updates on GE21 online/offlineDQM plots with division on modules `dqm` `reconstruction` `simulation` `upgrade` created: 2022-11-04 11:43:27 merged: 2022-11-26 06:03:59

113. [39953](http://github.com/cms-sw/cmssw/pull/39953){:target="_blank"}  from **@wddgit**: Remove deprecated JetCorrector and related files `analysis` `dqm` `reconstruction` `xpog` created: 2022-11-01 19:00:30 merged: 2022-12-12 09:51:14

114. [39847](http://github.com/cms-sw/cmssw/pull/39847){:target="_blank"}  from **@wddgit**: JetCorrector migration in DQM/Physics `dqm` created: 2022-10-25 17:01:33 merged: 2022-12-02 05:30:12

115. [39808](http://github.com/cms-sw/cmssw/pull/39808){:target="_blank"}  from **@yuanchao**: Mask old b-taggers and keep only DNN taggers with Era modifier for run3. `alca` `reconstruction` created: 2022-10-21 08:19:14 merged: 2022-12-09 14:40:25

116. [39167](http://github.com/cms-sw/cmssw/pull/39167){:target="_blank"}  from **@jeongeun**: Replace Geometry_cff with GeometryDB_cff in DPGAnalysis `pdmv` created: 2022-08-24 08:22:08 merged: 2022-11-30 09:29:59

117. [38761](http://github.com/cms-sw/cmssw/pull/38761){:target="_blank"}  from **@AdrianoDee**: Tracker Traits and Enabling Phase2 for Inner Tracker Reconstruction on GPU `dqm` `geometry` `hlt` `reconstruction` `heterogeneous` created: 2022-07-15 18:30:17 merged: 2022-11-30 16:55:03

#### CMSDIST Changes between Tags REL/CMSSW_13_0_0_pre1/el8_amd64_gcc11 and REL/CMSSW_13_0_0_pre2/el8_amd64_gcc11:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_13_0_0_pre1/el8_amd64_gcc11...REL/CMSSW_13_0_0_pre2/el8_amd64_gcc11)



1. [8222](http://github.com/cms-sw/cmsdist/pull/8222){:target="_blank"}  from **@cms-sw**: Update tag for RecoEgamma-ElectronIdentification to V01-12-00 created: 2022-12-09 06:37:37 merged: 2022-12-09 06:38:14

2. [8215](http://github.com/cms-sw/cmsdist/pull/8215){:target="_blank"}  from **@gartung**: Update igprof to handle unrecognosed prologue for movq instruction with XMM registers created: 2022-12-04 14:28:21 merged: 2022-12-05 08:25:53

3. [8200](http://github.com/cms-sw/cmsdist/pull/8200){:target="_blank"}  from **@cms-sw**: Update dasgoclient to use revXX as version suffix, fix for finding correct exec created: 2022-11-25 13:13:55 merged: 2022-11-26 10:45:33

4. [8199](http://github.com/cms-sw/cmsdist/pull/8199){:target="_blank"}  from **@cms-sw**: Update tag for L1Trigger-TrackFindingTracklet to V00-03-00 created: 2022-11-25 12:42:01 merged: 2022-11-25 12:47:03

5. [8198](http://github.com/cms-sw/cmsdist/pull/8198){:target="_blank"}  from **@mseidel42**: Rivet 3.1.7 & YODA 1.9.7, disentagle from Sherpa created: 2022-11-24 13:29:01 merged: 2022-11-27 21:18:41

6. [8187](http://github.com/cms-sw/cmsdist/pull/8187){:target="_blank"}  from **@cms-sw**: SCRAM V2 disto via latest cmssw releases created: 2022-11-16 17:34:13 merged: 2022-11-25 12:19:48

7. [8084](http://github.com/cms-sw/cmsdist/pull/8084){:target="_blank"}  from **@cms-sw**: [Boost] Update boost 1.80.0 created: 2022-09-13 15:18:07 merged: 2022-11-27 21:16:30
