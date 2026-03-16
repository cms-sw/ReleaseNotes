---
layout: post
rel_link:  "16_1_0_pre3"
title:  "CMSSW_16_1_0_pre3"
date:   2026-03-15 23:21:21
categories: cmssw
relmajor: 16
relminor: 1
relsubminor: 0
relpre: _pre3
---

# CMSSW_16_1_0_pre3
#### Changes since CMSSW_16_1_0_pre2:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_16_1_0_pre2...CMSSW_16_1_0_pre3)



1. [50398](http://github.com/cms-sw/cmssw/pull/50398){:target="_blank"}  from **@mmusich**: update `runHLTTiming` script to be more modular `hlt` created: 2026-03-13 10:18:21 merged: 2026-03-13 16:41:38

2. [50385](http://github.com/cms-sw/cmssw/pull/50385){:target="_blank"}  from **@perrotta**: Update of the GTs in autoCond with the new 2026 L1T Menu Tag L1Menu_Collisions2026_v1_1_0_xml `alca` created: 2026-03-12 12:02:27 merged: 2026-03-13 08:04:13

3. [50384](http://github.com/cms-sw/cmssw/pull/50384){:target="_blank"}  from **@martinamalberti**: MTD digitization: update for SiPM saturation + time walk corrections for BTL `reconstruction` `simulation` created: 2026-03-11 20:31:17 merged: 2026-03-13 16:41:25

4. [50377](http://github.com/cms-sw/cmssw/pull/50377){:target="_blank"}  from **@mmusich**: Miscelleaneous adjustments to HLT Scouting DQM monitor elements `dqm` `hlt` created: 2026-03-11 12:33:32 merged: 2026-03-12 13:36:43

5. [50372](http://github.com/cms-sw/cmssw/pull/50372){:target="_blank"}  from **@tvami**: Remove unused AddDirectory in analysis packages `analysis` created: 2026-03-11 04:45:27 merged: 2026-03-11 11:53:43

6. [50371](http://github.com/cms-sw/cmssw/pull/50371){:target="_blank"}  from **@bsunanda**: Run3-gex208 Update the 2026 geometry scenario by including the latest version of the shielding component `geometry` created: 2026-03-11 02:59:57 merged: 2026-03-11 11:53:57

7. [50369](http://github.com/cms-sw/cmssw/pull/50369){:target="_blank"}  from **@makortel**: Add IntrusiveAllocProfiler `core` created: 2026-03-10 21:27:16 merged: 2026-03-13 08:04:06

8. [50366](http://github.com/cms-sw/cmssw/pull/50366){:target="_blank"}  from **@makortel**: Update `DiagStreamerFile` `core` created: 2026-03-10 18:33:21 merged: 2026-03-11 16:52:35

9. [50365](http://github.com/cms-sw/cmssw/pull/50365){:target="_blank"}  from **@Dr15Jones**: Add DTRecHit1DFwd.h file `alca` `reconstruction` created: 2026-03-10 17:52:07 merged: 2026-03-11 14:48:46

10. [50364](http://github.com/cms-sw/cmssw/pull/50364){:target="_blank"}  from **@CMS-HGCAL**: Add half ROC mask bitset per ECON-D `alca` `reconstruction` `db` created: 2026-03-10 17:20:03 merged: 2026-03-13 16:40:02

11. [50361](http://github.com/cms-sw/cmssw/pull/50361){:target="_blank"}  from **@makortel**: Fix `reco::ParticleState` read rule `reconstruction` created: 2026-03-10 16:06:23 merged: 2026-03-13 06:18:05

12. [50359](http://github.com/cms-sw/cmssw/pull/50359){:target="_blank"}  from **@slomeo**: Added New Forward Shield (NFS) for Scenario 2026 `geometry` created: 2026-03-10 14:35:56 merged: 2026-03-11 06:05:02

13. [50357](http://github.com/cms-sw/cmssw/pull/50357){:target="_blank"}  from **@bsunanda**: Phase2-hgx365V1 Add a few more debug statements for the most recent version of DDHGCalSilicon used for loading the HGCal geometry of full silicon layers `geometry` created: 2026-03-10 09:52:19 merged: 2026-03-10 16:30:39

14. [50355](http://github.com/cms-sw/cmssw/pull/50355){:target="_blank"}  from **@bsunanda**: Phase2-hgx365U Correct the HGCal TB2023 scenario definitions to work with the current definitions of HGCal software `geometry` created: 2026-03-10 02:56:35 merged: 2026-03-10 10:29:17

15. [50353](http://github.com/cms-sw/cmssw/pull/50353){:target="_blank"}  from **@trackreco**: Relaxed pT cut for built track candidates and hltGeneralTracks (Phase-2 baseline) `hlt` `reconstruction` `tracking` created: 2026-03-09 16:09:21 merged: 2026-03-12 13:38:19

16. [50348](http://github.com/cms-sw/cmssw/pull/50348){:target="_blank"}  from **@Dr15Jones**: Better handling of initializing DescriptionCloner `core` created: 2026-03-09 14:25:52 merged: 2026-03-10 16:32:44

17. [50346](http://github.com/cms-sw/cmssw/pull/50346){:target="_blank"}  from **@mmusich**: move `HLTADFilter` out of `HLTrigger` subsystem into its own package `hlt` `reconstruction` `ml` created: 2026-03-09 14:10:01 merged: 2026-03-11 11:54:19

18. [50345](http://github.com/cms-sw/cmssw/pull/50345){:target="_blank"}  from **@Dr15Jones**: Throw is ESHandle is not set `core` `hlt` created: 2026-03-09 13:58:59 merged: 2026-03-10 17:21:37

19. [50341](http://github.com/cms-sw/cmssw/pull/50341){:target="_blank"}  from **@bsunanda**: Phase2-gex207 Add a new version of Forward system for the Phase2 scenario including a new forward shielding system `geometry` created: 2026-03-08 04:23:54 merged: 2026-03-08 09:17:38

20. [50340](http://github.com/cms-sw/cmssw/pull/50340){:target="_blank"}  from **@bsunanda**: Phase2-gex206 Adding test to evaluate the new forwardshield made by Sergio `geometry` created: 2026-03-07 05:20:25 merged: 2026-03-07 09:51:02

21. [50337](http://github.com/cms-sw/cmssw/pull/50337){:target="_blank"}  from **@mbluj**: fix gen-tau decay-modes  `analysis` created: 2026-03-06 17:41:01 merged: 2026-03-07 09:50:27

22. [50335](http://github.com/cms-sw/cmssw/pull/50335){:target="_blank"}  from **@ghyls**: Add the an option to disable the `TrivialSerialisation` mechanism in MPI modules `heterogeneous` created: 2026-03-06 17:13:55 merged: 2026-03-10 10:29:00

23. [50333](http://github.com/cms-sw/cmssw/pull/50333){:target="_blank"}  from **@slomeo**: Added New Forward Shield (NFS) for Phase2 Run4 `geometry` created: 2026-03-06 17:04:09 merged: 2026-03-07 09:49:37

24. [50331](http://github.com/cms-sw/cmssw/pull/50331){:target="_blank"}  from **@mmusich**: Speed-up `SiPixelBadFEDChannelSimulationSanityChecker` `db` `trk` created: 2026-03-06 16:06:44 merged: 2026-03-07 19:04:30

25. [50330](http://github.com/cms-sw/cmssw/pull/50330){:target="_blank"}  from **@makortel**: Add missing dependencies to SimDataFormats `dqm` `l1` created: 2026-03-06 15:35:49 merged: 2026-03-10 17:19:21

26. [50323](http://github.com/cms-sw/cmssw/pull/50323){:target="_blank"}  from **@bsunanda**: Phase2-hgx365T Make testing code for neighbour finder as a tool inside the HGCal topology class `geometry` created: 2026-03-06 09:21:59 merged: 2026-03-06 13:22:40

27. [50322](http://github.com/cms-sw/cmssw/pull/50322){:target="_blank"}  from **@bsunanda**: Run3-gex205 Modify the 2026 scenario to add sensitive detector for FSC `geometry` created: 2026-03-06 04:51:39 merged: 2026-03-06 13:22:51

28. [50321](http://github.com/cms-sw/cmssw/pull/50321){:target="_blank"}  from **@slava77**: LST: skip T3 creation with all empty modules; don't run TC extension for acase with 0 TCs. `reconstruction` `tracking` created: 2026-03-06 00:36:43 merged: 2026-03-12 13:39:50

29. [50318](http://github.com/cms-sw/cmssw/pull/50318){:target="_blank"}  from **@JanGerritSchulz**: Fix CopyToDevice of TrackingRecHitsSoACollection `reconstruction` `heterogeneous` `tracking` created: 2026-03-05 17:53:43 merged: 2026-03-10 07:35:57

30. [50317](http://github.com/cms-sw/cmssw/pull/50317){:target="_blank"}  from **@stahlleiton**: Update DeDxHitCalibrator with pixel isSaturated flag `reconstruction` `tracking` created: 2026-03-05 16:47:45 merged: 2026-03-06 13:24:11

31. [50313](http://github.com/cms-sw/cmssw/pull/50313){:target="_blank"}  from **@bsunanda**: Run3-gex204 Provide Sensitive Detector class for the Forward Shower Counter `simulation` created: 2026-03-05 11:25:43 merged: 2026-03-08 09:18:48

32. [50311](http://github.com/cms-sw/cmssw/pull/50311){:target="_blank"}  from **@JHiltbrand**: Minor Tweaks for HCAL MAHI Debugger `reconstruction` `hcal` created: 2026-03-05 07:30:36 merged: 2026-03-06 13:22:07

33. [50310](http://github.com/cms-sw/cmssw/pull/50310){:target="_blank"}  from **@mmusich**: alphabetically order autoDQM.py `dqm` created: 2026-03-05 04:58:58 merged: 2026-03-05 08:11:57

34. [50309](http://github.com/cms-sw/cmssw/pull/50309){:target="_blank"}  from **@bsunanda**: Phase2-hgx365S  Add more diagnostic messages for the algorithms in Geometry/HGCalCommonData/plugins/dd4hep `geometry` created: 2026-03-05 04:18:05 merged: 2026-03-06 13:22:27

35. [50306](http://github.com/cms-sw/cmssw/pull/50306){:target="_blank"}  from **@makortel**: Speed up `SiPixelDigitizerAlgorithm::init()` `simulation` `trk` created: 2026-03-04 22:07:55 merged: 2026-03-06 13:23:23

36. [50304](http://github.com/cms-sw/cmssw/pull/50304){:target="_blank"}  from **@missirol**: L1S: replace data format `l1ScoutingRun3::FastJet` with `l1ScoutingRun3::CaloJet` `daq` `l1` created: 2026-03-04 17:09:13 merged: 2026-03-06 13:23:57

37. [50301](http://github.com/cms-sw/cmssw/pull/50301){:target="_blank"}  from **@bsunanda**: Phase2-hgx365R Add more diagnostic message for the algorithms in Geometry/HGCalCommonData/plugins `geometry` created: 2026-03-04 11:32:34 merged: 2026-03-05 07:27:49

38. [50300](http://github.com/cms-sw/cmssw/pull/50300){:target="_blank"}  from **@akritkbehera**: Move CUDA Alpaka backends under cuda-gcc-support `reconstruction` created: 2026-03-04 10:34:53 merged: 2026-03-05 07:14:52

39. [50299](http://github.com/cms-sw/cmssw/pull/50299){:target="_blank"}  from **@mmusich**: fix `GenericTriggerEventFlag` parameters for stage2 L1T in `DQMOffline/JetMET` `dqm` created: 2026-03-04 10:21:59 merged: 2026-03-05 06:53:41

40. [50298](http://github.com/cms-sw/cmssw/pull/50298){:target="_blank"}  from **@bsunanda**: Phase2-hgx365Q Try to create scenarios for the 2 HGCal TestBeam runs of 2025 `geometry` created: 2026-03-04 09:48:47 merged: 2026-03-05 07:13:55

41. [50296](http://github.com/cms-sw/cmssw/pull/50296){:target="_blank"}  from **@makortel**: Make prefetching configurable and default to disabled in RepeatingCachedRootSource `core` created: 2026-03-03 21:01:36 merged: 2026-03-07 09:49:13

42. [50295](http://github.com/cms-sw/cmssw/pull/50295){:target="_blank"}  from **@makortel**: Add class version for MtdCaloParticle and other cleanup `simulation` created: 2026-03-03 20:38:23 merged: 2026-03-05 07:14:23

43. [50294](http://github.com/cms-sw/cmssw/pull/50294){:target="_blank"}  from **@Dr15Jones**: Modernize particle guns `generators` created: 2026-03-03 19:10:30 merged: 2026-03-10 17:15:28

44. [50293](http://github.com/cms-sw/cmssw/pull/50293){:target="_blank"}  from **@mmusich**: Spring Cleaning of unused global `PSets` in Phase-2 HLT menus `hlt` created: 2026-03-03 10:43:35 merged: 2026-03-03 20:04:01

45. [50286](http://github.com/cms-sw/cmssw/pull/50286){:target="_blank"}  from **@smuzaffar**: [FWLite] Avoid dependency on TrackingTools/PatternTools `reconstruction` created: 2026-03-02 13:33:17 merged: 2026-03-03 19:46:01

46. [50285](http://github.com/cms-sw/cmssw/pull/50285){:target="_blank"}  from **@adzel-werk**: add a fillPSetDescription for JetMETDQMDCSFilter and use it in JetAnalyzer `dqm` created: 2026-03-01 11:02:28 merged: 2026-03-03 19:42:42

47. [50283](http://github.com/cms-sw/cmssw/pull/50283){:target="_blank"}  from **@leonardogiannini**: [MkFit]  MkFit final fit calibration and minor adjustments  `hlt` `reconstruction` `tracking` created: 2026-02-28 00:47:52 merged: 2026-03-13 16:38:57

48. [50278](http://github.com/cms-sw/cmssw/pull/50278){:target="_blank"}  from **@Parsifal-2045**: Update Phase 2 timing configuration `hlt` created: 2026-02-27 16:24:04 merged: 2026-03-01 17:15:36

49. [50277](http://github.com/cms-sw/cmssw/pull/50277){:target="_blank"}  from **@ljuckett**: [DQM] Phase-2: Fix module order in 2S_Ladder_layerX histograms `dqm` `trk` created: 2026-02-27 15:28:31 merged: 2026-03-03 19:47:22

50. [50276](http://github.com/cms-sw/cmssw/pull/50276){:target="_blank"}  from **@bsunanda**: Run3-gex203 Use the validation scripts to test the 2026 Geometry scenario `dqm` `geometry` `simulation` created: 2026-02-27 13:48:57 merged: 2026-03-02 14:53:17

51. [50275](http://github.com/cms-sw/cmssw/pull/50275){:target="_blank"}  from **@hjkwon260**: ML Metadata workflow initialisation `alca` `db` `ml` created: 2026-02-27 12:26:46 merged: 2026-03-11 11:55:44

52. [50274](http://github.com/cms-sw/cmssw/pull/50274){:target="_blank"}  from **@perrotta**: Update 2025 and 2026 MC Gts `alca` created: 2026-02-27 11:34:57 merged: 2026-03-06 13:20:47

53. [50270](http://github.com/cms-sw/cmssw/pull/50270){:target="_blank"}  from **@makortel**: Avoid streamer mode in RNTuple for `edm::RefCore` and `edm::RefCoreWithIndex` `core` created: 2026-02-26 21:07:24 merged: 2026-03-01 17:13:21

54. [50266](http://github.com/cms-sw/cmssw/pull/50266){:target="_blank"}  from **@fwyzard**: Make `processFromFile` behave like `cmsRun` `core` created: 2026-02-26 13:56:27 merged: 2026-02-26 21:57:06

55. [50265](http://github.com/cms-sw/cmssw/pull/50265){:target="_blank"}  from **@bsunanda**: Run3-gex202 Modify the 2026 scripts for geometry creation such that it will create only the standard 2026 geometry `db` created: 2026-02-26 12:38:18 merged: 2026-03-06 13:20:30

56. [50264](http://github.com/cms-sw/cmssw/pull/50264){:target="_blank"}  from **@stahlleiton**: Implement saturation flag in pixel cluster `reconstruction` `heterogeneous` `trk` created: 2026-02-26 12:05:24 merged: 2026-03-03 18:46:07

57. [50263](http://github.com/cms-sw/cmssw/pull/50263){:target="_blank"}  from **@bsunanda**: Run3-gex201 Try to make the geometry for 2026 scenario `geometry` `operations` created: 2026-02-26 07:59:38 merged: 2026-02-26 21:57:57

58. [50262](http://github.com/cms-sw/cmssw/pull/50262){:target="_blank"}  from **@bsunanda**: Phase2-hgx365P Modify HGCalConvert.cpp to make use of the flat file for TB Geometry `geometry` created: 2026-02-26 07:56:40 merged: 2026-03-01 17:14:51

59. [50261](http://github.com/cms-sw/cmssw/pull/50261){:target="_blank"}  from **@slava77**: LST: Improved handling of CA pixel tracks with OT extension, distinguish IT from OT hits `reconstruction` `tracking` created: 2026-02-25 21:57:03 merged: 2026-03-03 19:44:47

60. [50259](http://github.com/cms-sw/cmssw/pull/50259){:target="_blank"}  from **@missirol**: L1S: fix slow debug calls in `ScCALORawToDigi` and `ScGMTRawToDigi` `daq` created: 2026-02-25 19:11:17 merged: 2026-02-26 09:17:02

61. [50257](http://github.com/cms-sw/cmssw/pull/50257){:target="_blank"}  from **@mmusich**: HLT Scouting DQM: add HB/HE separation, energy-threshold and energy-time plots for scouting rechits `dqm` `hlt` created: 2026-02-25 15:28:07 merged: 2026-03-01 17:13:56

62. [50252](http://github.com/cms-sw/cmssw/pull/50252){:target="_blank"}  from **@konpas17**: Move HB TDC thresholds to CondDB `l1` `reconstruction` `hcal` created: 2026-02-25 12:27:22 merged: 2026-03-11 05:35:21

63. [50249](http://github.com/cms-sw/cmssw/pull/50249){:target="_blank"}  from **@makortel**: [GCC15] Fix IntrusiveAllocMonitor test `core` created: 2026-02-24 21:15:42 merged: 2026-02-25 17:39:29

64. [50247](http://github.com/cms-sw/cmssw/pull/50247){:target="_blank"}  from **@missirol**: L1S: add plugins `MaskOrbitBx<l1ScoutingRun3::{CaloTower,FastJet}>` `daq` `l1` created: 2026-02-24 19:32:12 merged: 2026-02-25 08:48:55

65. [50245](http://github.com/cms-sw/cmssw/pull/50245){:target="_blank"}  from **@mroguljic**: Customizer to turn off pixel template cpe `reconstruction` `tracking` created: 2026-02-24 17:45:40 merged: 2026-02-26 21:56:53

66. [50244](http://github.com/cms-sw/cmssw/pull/50244){:target="_blank"}  from **@mmusich**: limit phase-2 Heavy Ion relval workflow to run on 1 event `pdmv` created: 2026-02-24 17:34:04 merged: 2026-02-25 15:41:35

67. [50239](http://github.com/cms-sw/cmssw/pull/50239){:target="_blank"}  from **@smuzaffar**: Changes needed for mplhep 1.1.0 as hep.cms.lumitext is removed `alca` `dqm` `trk` created: 2026-02-24 11:33:46 merged: 2026-02-25 17:44:12

68. [50235](http://github.com/cms-sw/cmssw/pull/50235){:target="_blank"}  from **@smuzaffar**: Include cpuinfo_riscv.h on RISCV64 arch `core` created: 2026-02-23 22:10:29 merged: 2026-02-24 19:14:07

69. [50233](http://github.com/cms-sw/cmssw/pull/50233){:target="_blank"}  from **@Dr15Jones**: Allow only one ParameterSetDescription per plugin `core` `l1` `reconstruction` `trk` created: 2026-02-23 21:24:45 merged: 2026-03-01 17:13:36

70. [50231](http://github.com/cms-sw/cmssw/pull/50231){:target="_blank"}  from **@missirol**: L1S: fixes to the `ScoutingJetProducer` plugin (eta/phi values, sorting of outputs) `daq` `l1` created: 2026-02-23 19:08:33 merged: 2026-02-24 19:14:39

71. [50229](http://github.com/cms-sw/cmssw/pull/50229){:target="_blank"}  from **@valsdav**: Removed gradients computation by default for PyTorch inference `ml` created: 2026-02-23 17:59:20 merged: 2026-02-24 19:16:24

72. [50228](http://github.com/cms-sw/cmssw/pull/50228){:target="_blank"}  from **@perrotta**: Update the online GTs in autoCond with some frozen at 2026-02-23 `alca` created: 2026-02-23 15:27:36 merged: 2026-02-24 08:34:18

73. [50227](http://github.com/cms-sw/cmssw/pull/50227){:target="_blank"}  from **@smuzaffar**: Drop py3-html5lib unit test `analysis` created: 2026-02-23 15:08:53 merged: 2026-02-23 21:59:51

74. [50225](http://github.com/cms-sw/cmssw/pull/50225){:target="_blank"}  from **@bfonta**: CloseBy smearing for Phase-1. `pdmv` created: 2026-02-23 14:02:42 merged: 2026-03-03 19:43:28

75. [50224](http://github.com/cms-sw/cmssw/pull/50224){:target="_blank"}  from **@bsunanda**: Phase2-hgx365O Make V18 also using cog as the default - thus removing the error report in the  ID test `geometry` created: 2026-02-23 11:11:04 merged: 2026-02-24 08:34:30

76. [50223](http://github.com/cms-sw/cmssw/pull/50223){:target="_blank"}  from **@mmusich**: Make `JetAnalyzer` independent of the Phase0 L1Trigger legacy code `dqm` created: 2026-02-22 13:04:00 merged: 2026-02-23 21:59:03

77. [50222](http://github.com/cms-sw/cmssw/pull/50222){:target="_blank"}  from **@stahlleiton**: Fix PbPb relvals `pdmv` created: 2026-02-21 17:01:15 merged: 2026-02-25 15:42:00

78. [50216](http://github.com/cms-sw/cmssw/pull/50216){:target="_blank"}  from **@bsunanda**: Phase2-hgx365N Try to address the issue for the V18 version of HGCal geometry description `geometry` created: 2026-02-21 02:46:23 merged: 2026-02-21 09:52:32

79. [50215](http://github.com/cms-sw/cmssw/pull/50215){:target="_blank"}  from **@mmusich**: Adapt `ScoutingEGammaCollectionMonitoring` to run in online DQM `dqm` created: 2026-02-20 22:09:43 merged: 2026-02-24 08:47:24

80. [50214](http://github.com/cms-sw/cmssw/pull/50214){:target="_blank"}  from **@artlbv**: HLT topological trigger based on XGBoost for events with muons, HT and btags `hlt` `reconstruction` `ml` created: 2026-02-20 21:51:45 merged: 2026-03-05 07:12:18

81. [50207](http://github.com/cms-sw/cmssw/pull/50207){:target="_blank"}  from **@mmusich**: make `edm::Wrapper` of GsfTracking types not defined in `DataFormats` non persistable `reconstruction` `tracking` created: 2026-02-20 12:34:04 merged: 2026-02-23 22:00:23

82. [50206](http://github.com/cms-sw/cmssw/pull/50206){:target="_blank"}  from **@mmusich**: make `ngt` DQM online client unit test run over the `DQMOnlineScouting` streamer files `dqm` created: 2026-02-20 09:08:37 merged: 2026-02-21 09:53:32

83. [50204](http://github.com/cms-sw/cmssw/pull/50204){:target="_blank"}  from **@Dr15Jones**: Replace forward references with Fwd.h includes for SimDataFormats `dqm` `simulation` `tracking` created: 2026-02-19 22:34:40 merged: 2026-02-21 09:53:25

84. [50203](http://github.com/cms-sw/cmssw/pull/50203){:target="_blank"}  from **@Dr15Jones**: Replace forward declaration of DTuROSFEDData with Fwd.h include `dqm` `reconstruction` `simulation` created: 2026-02-19 22:31:39 merged: 2026-02-24 08:48:07

85. [50202](http://github.com/cms-sw/cmssw/pull/50202){:target="_blank"}  from **@Dr15Jones**: Remove unnecessary forward declaration of ClusterSummary `reconstruction` `trk` created: 2026-02-19 22:26:16 merged: 2026-02-25 17:43:50

86. [50201](http://github.com/cms-sw/cmssw/pull/50201){:target="_blank"}  from **@Dr15Jones**: Replace forward declaration with StripDigiSimLinkFwd.h include `simulation` `trk` created: 2026-02-19 21:54:43 merged: 2026-02-24 08:33:23

87. [50200](http://github.com/cms-sw/cmssw/pull/50200){:target="_blank"}  from **@dan131riley**: L1TrackJetClustering and other fixes for gcc15 crashes `l1` created: 2026-02-19 21:44:50 merged: 2026-02-20 07:53:22

88. [50199](http://github.com/cms-sw/cmssw/pull/50199){:target="_blank"}  from **@Dr15Jones**: Replace forward declaration with TrackingParticleFwd.h `dqm` `tracking` created: 2026-02-19 21:41:15 merged: 2026-02-20 09:21:40

89. [50198](http://github.com/cms-sw/cmssw/pull/50198){:target="_blank"}  from **@Dr15Jones**: Replace forward references to Fwd.h includes for EcalDigi `simulation` created: 2026-02-19 21:29:03 merged: 2026-02-23 22:00:04

90. [50197](http://github.com/cms-sw/cmssw/pull/50197){:target="_blank"}  from **@Dr15Jones**: Replace forward declarations with Fwd.h includes for EcalDetId `alca` `dqm` `reconstruction` `simulation` `db` created: 2026-02-19 21:08:08 merged: 2026-02-24 08:47:54

91. [50196](http://github.com/cms-sw/cmssw/pull/50196){:target="_blank"}  from **@Dr15Jones**: Replace forward reference with Fwd.h includes for HcalDigi `reconstruction` `simulation` created: 2026-02-19 19:53:49 merged: 2026-02-24 08:32:13

92. [50195](http://github.com/cms-sw/cmssw/pull/50195){:target="_blank"}  from **@waredjeb**: Add Reco2Sim association map to NGTScouting NanoAOD `hlt` created: 2026-02-19 18:19:27 merged: 2026-02-20 07:52:57

93. [50194](http://github.com/cms-sw/cmssw/pull/50194){:target="_blank"}  from **@fwyzard**: Use alpaka::allocBuf for blocking CPU queues `heterogeneous` created: 2026-02-19 18:05:22 merged: 2026-02-20 07:49:52

94. [50193](http://github.com/cms-sw/cmssw/pull/50193){:target="_blank"}  from **@Dr15Jones**: Replace forward references with Fwd.h in DataFormats/Scalers `daq` `l1` `reconstruction` created: 2026-02-19 17:53:08 merged: 2026-02-20 09:33:56

95. [50192](http://github.com/cms-sw/cmssw/pull/50192){:target="_blank"}  from **@Dr15Jones**: Create and use L1MuGMTReadoutCollectionFwd.h `l1` created: 2026-02-19 17:33:35 merged: 2026-02-20 07:53:09

96. [50191](http://github.com/cms-sw/cmssw/pull/50191){:target="_blank"}  from **@Dr15Jones**: Replace forward declaration with Fwd.h in EventWithHistory `analysis` `daq` `l1` `reconstruction` `trk` created: 2026-02-19 17:18:19 merged: 2026-02-25 17:43:39

97. [50190](http://github.com/cms-sw/cmssw/pull/50190){:target="_blank"}  from **@Dr15Jones**: Replace forward references with Fwd.h includes for  L1TMuon data products `l1` created: 2026-02-19 16:12:00 merged: 2026-02-20 07:54:22

98. [50189](http://github.com/cms-sw/cmssw/pull/50189){:target="_blank"}  from **@Dr15Jones**: Replace forward references with Fwd.h for L1*CaloTrigger data products `l1` created: 2026-02-19 15:40:07 merged: 2026-02-20 07:53:43

99. [50188](http://github.com/cms-sw/cmssw/pull/50188){:target="_blank"}  from **@etzovara**: JME Offline DQM: adding trigger efficiency for scouting jets `dqm` `hlt` `reconstruction` created: 2026-02-19 14:12:49 merged: 2026-03-11 11:56:14

100. [50187](http://github.com/cms-sw/cmssw/pull/50187){:target="_blank"}  from **@smuzaffar**: Drop explicit dependency on stdc++fs which is now part of stdc++ since GCC8/c++17 `alca` `core` `daq` `dqm` `generators` `l1` `reconstruction` `db` `trk` created: 2026-02-19 12:15:06 merged: 2026-02-21 09:52:21

101. [50184](http://github.com/cms-sw/cmssw/pull/50184){:target="_blank"}  from **@fwyzard**: Optimise directory checks in DirManager `daq` created: 2026-02-19 07:34:05 merged: 2026-02-20 07:52:42

102. [50181](http://github.com/cms-sw/cmssw/pull/50181){:target="_blank"}  from **@Dr15Jones**: Replace forward references with Fwd.h includes for some L1 stored classes `dqm` `hlt` `l1` created: 2026-02-18 21:18:31 merged: 2026-02-19 09:45:55

103. [50180](http://github.com/cms-sw/cmssw/pull/50180){:target="_blank"}  from **@mmusich**: `conddblib`: add an option `onlinepro` to `officialdbs` to point to `FrontierProd` servlet `db` created: 2026-02-18 21:09:15 merged: 2026-02-19 09:45:43

104. [50177](http://github.com/cms-sw/cmssw/pull/50177){:target="_blank"}  from **@Dr15Jones**: Replace class forward with Fwd.h includes for L1Global* `hlt` `l1` created: 2026-02-18 18:00:38 merged: 2026-02-19 09:43:55

105. [50176](http://github.com/cms-sw/cmssw/pull/50176){:target="_blank"}  from **@sakura-ngt**: Introducing Dilepton and 0 HLT Scouting DQM  + fixes to the `ScoutingCollectionMonitor` and `ScoutingRechitMonitoring` labels `dqm` `hlt` created: 2026-02-18 17:22:58 merged: 2026-02-20 07:52:28

106. [50175](http://github.com/cms-sw/cmssw/pull/50175){:target="_blank"}  from **@gartung**: Configuration/PyReleaseValidation: Add 18634.21 to relval_2017.py which is loaded by default `pdmv` created: 2026-02-18 16:58:29 merged: 2026-02-25 17:43:00

107. [50171](http://github.com/cms-sw/cmssw/pull/50171){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `16_0_X` (3/N) [`16_1_X`] `hlt` created: 2026-02-18 13:57:07 merged: 2026-02-18 18:19:59

108. [50170](http://github.com/cms-sw/cmssw/pull/50170){:target="_blank"}  from **@smuzaffar**: Fix use-after-free in L1TrackJet cluster merge loop `l1` created: 2026-02-18 13:32:15 merged: 2026-02-20 07:50:46

109. [50169](http://github.com/cms-sw/cmssw/pull/50169){:target="_blank"}  from **@smuzaffar**: Fix UB exposed by GCC 15 (use-after-free) `dqm` `hlt` `l1` created: 2026-02-18 10:03:50 merged: 2026-02-20 09:13:06

110. [50167](http://github.com/cms-sw/cmssw/pull/50167){:target="_blank"}  from **@stahlleiton**: Update HLTPixelThrustFilter to consider saturated pixels `analysis` `hlt` created: 2026-02-17 20:03:59 merged: 2026-03-07 09:49:52

111. [50166](http://github.com/cms-sw/cmssw/pull/50166){:target="_blank"}  from **@Dr15Jones**: Use CreateBareEntry in RNTupleOutputModule `core` created: 2026-02-17 18:50:04 merged: 2026-02-19 09:44:21

112. [50163](http://github.com/cms-sw/cmssw/pull/50163){:target="_blank"}  from **@mmusich**: [NGT] Miscellaneous improvements to `DQM/SiPixelHeterogeneous` towards Phase-2  `dqm` `trk` created: 2026-02-17 17:24:56 merged: 2026-02-19 09:43:43

113. [50161](http://github.com/cms-sw/cmssw/pull/50161){:target="_blank"}  from **@Dr15Jones**: Use Fwd.h files for classes which are stored [part 1] `alca` `analysis` `dqm` `fastsim` `geometry` `hlt` `l1` `reconstruction` `visualization` `simulation` `pdmv` `db` `xpog` `tracking` `trk` created: 2026-02-17 15:09:22 merged: 2026-02-20 07:50:35

114. [50157](http://github.com/cms-sw/cmssw/pull/50157){:target="_blank"}  from **@SegmentLinking**: Memory Improvements for LST `reconstruction` `tracking` created: 2026-02-17 00:32:00 merged: 2026-02-18 18:19:21

115. [50155](http://github.com/cms-sw/cmssw/pull/50155){:target="_blank"}  from **@ljuckett**: Phase-2 CRACK DQM: Crack overview and edit crack ranges `dqm` `trk` created: 2026-02-16 17:27:08 merged: 2026-02-24 19:11:59

116. [50151](http://github.com/cms-sw/cmssw/pull/50151){:target="_blank"}  from **@bsunanda**: Phase2-hgx365L Update the xml files related to HGCal for ConsData to make the layer types conformal to ones used in HGCal Types `geometry` created: 2026-02-16 13:57:22 merged: 2026-02-18 09:29:50

117. [50150](http://github.com/cms-sw/cmssw/pull/50150){:target="_blank"}  from **@esiam**: fix stack buffer overflow problem in ZGammaplusJetsPostProcessor `dqm` created: 2026-02-16 10:24:31 merged: 2026-02-18 09:30:55

118. [50149](http://github.com/cms-sw/cmssw/pull/50149){:target="_blank"}  from **@Dr15Jones**: Added HepMCProductFwd.h file `dqm` `generators` `simulation` `trk` created: 2026-02-15 15:06:38 merged: 2026-02-18 09:34:53

119. [50148](http://github.com/cms-sw/cmssw/pull/50148){:target="_blank"}  from **@Dr15Jones**: Added forward declaration files for more data products `dqm` `hlt` `l1` `reconstruction` created: 2026-02-15 14:26:06 merged: 2026-02-18 09:34:26

120. [50147](http://github.com/cms-sw/cmssw/pull/50147){:target="_blank"}  from **@perrotta**: Revert SiPixelQuality conditions in autoCond to the old ones, as requested by TSG `alca` created: 2026-02-15 08:18:39 merged: 2026-02-15 21:42:39

121. [50141](http://github.com/cms-sw/cmssw/pull/50141){:target="_blank"}  from **@Dr15Jones**: Apply suggested performance improvements to RNTuple output `core` created: 2026-02-13 22:27:08 merged: 2026-02-18 09:35:19

122. [50140](http://github.com/cms-sw/cmssw/pull/50140){:target="_blank"}  from **@Dr15Jones**: Added omit ability to DescriptionCloner `core` `l1` `reconstruction` created: 2026-02-13 19:00:34 merged: 2026-02-21 09:52:53

123. [50139](http://github.com/cms-sw/cmssw/pull/50139){:target="_blank"}  from **@gartung**: Update edmModuleAllocMonitorAnalyze.py to handle additional transitions `core` created: 2026-02-13 17:37:41 merged: 2026-02-18 09:31:28

124. [50136](http://github.com/cms-sw/cmssw/pull/50136){:target="_blank"}  from **@jfernan2**: [DQM][DT] Remove DT DQM Module using TensorFlow for ML occupancy plot `dqm` created: 2026-02-13 15:24:33 merged: 2026-02-18 09:33:51

125. [50135](http://github.com/cms-sw/cmssw/pull/50135){:target="_blank"}  from **@slava77**: trackingNtuple fix: use seed charge from the original seed state `dqm` `tracking` created: 2026-02-13 15:23:23 merged: 2026-02-18 09:30:42

126. [50131](http://github.com/cms-sw/cmssw/pull/50131){:target="_blank"}  from **@Electricks94**: SoA backend cleanup `reconstruction` `simulation` `heterogeneous` `tracking` `trk` `ml` created: 2026-02-13 12:43:14 merged: 2026-03-11 14:50:42

127. [50129](http://github.com/cms-sw/cmssw/pull/50129){:target="_blank"}  from **@Dr15Jones**: Apply DescriptionCloner to modules generating multiple cfi `geometry` `reconstruction` `tracking` `trk` created: 2026-02-12 21:30:37 merged: 2026-02-18 18:15:19

128. [50127](http://github.com/cms-sw/cmssw/pull/50127){:target="_blank"}  from **@bfonta**: DQM Monitor Element: improve Kind debug message `dqm` created: 2026-02-12 16:03:25 merged: 2026-02-18 09:30:20

129. [50125](http://github.com/cms-sw/cmssw/pull/50125){:target="_blank"}  from **@Dr15Jones**: Have ProducerWithPSetDesc only use cloner `core` created: 2026-02-12 14:42:39 merged: 2026-02-13 07:34:34

130. [50117](http://github.com/cms-sw/cmssw/pull/50117){:target="_blank"}  from **@bfonta**: [Bugfix] Typo in HGCAL_noises. `simulation` created: 2026-02-11 12:17:47 merged: 2026-02-12 07:47:46

131. [50116](http://github.com/cms-sw/cmssw/pull/50116){:target="_blank"}  from **@kandrosov**: Updated CSC LCT data format `l1` `simulation` created: 2026-02-11 12:08:55 merged: 2026-02-13 07:35:05

132. [50111](http://github.com/cms-sw/cmssw/pull/50111){:target="_blank"}  from **@AdrianoDee**: Re-enable `*.999` in PR tests `pdmv` created: 2026-02-11 10:11:09 merged: 2026-02-12 07:48:13

133. [50109](http://github.com/cms-sw/cmssw/pull/50109){:target="_blank"}  from **@mpresill**: Adding 2026 pp and HI scenarios `operations` created: 2026-02-11 09:22:09 merged: 2026-02-12 17:54:24

134. [50108](http://github.com/cms-sw/cmssw/pull/50108){:target="_blank"}  from **@fwyzard**: Drop legacy CUDA utilities `core` `heterogeneous` created: 2026-02-10 23:29:56 merged: 2026-02-12 07:46:57

135. [50107](http://github.com/cms-sw/cmssw/pull/50107){:target="_blank"}  from **@cms-ngt-hlt**: fix faulty default of `sigmaZ` in `VertexAssociatorByPositionAndTracksProducer`, use fake cut only for HLT `dqm` `simulation` `tracking` `trk` created: 2026-02-10 22:22:16 merged: 2026-02-12 15:59:56

136. [50106](http://github.com/cms-sw/cmssw/pull/50106){:target="_blank"}  from **@perrotta**: Update autoCond with first 2026 MC GT and L1T menu `alca` created: 2026-02-10 21:32:12 merged: 2026-02-12 07:47:23

137. [50105](http://github.com/cms-sw/cmssw/pull/50105){:target="_blank"}  from **@Dr15Jones**: Created L1CandidateFwd.h and changed related forward declarations `l1` created: 2026-02-10 20:16:47 merged: 2026-02-13 07:36:50

138. [50104](http://github.com/cms-sw/cmssw/pull/50104){:target="_blank"}  from **@Dr15Jones**: Fix ODR violation in L1Trigger/L1TCalorimeter `l1` created: 2026-02-10 19:07:19 merged: 2026-02-12 07:47:03

139. [50103](http://github.com/cms-sw/cmssw/pull/50103){:target="_blank"}  from **@makortel**: Add PhaseAllocMonitor `core` created: 2026-02-10 17:11:43 merged: 2026-02-13 07:35:24

140. [50102](http://github.com/cms-sw/cmssw/pull/50102){:target="_blank"}  from **@missirol**: NanoAOD: remove duplicates of `nanoMetadata` in `cff` fragments `xpog` `hcal` created: 2026-02-10 16:19:44 merged: 2026-02-16 08:21:59

141. [50096](http://github.com/cms-sw/cmssw/pull/50096){:target="_blank"}  from **@makortel**: Use `TApplication` in `edmRNTupleTemp{FileUtil,ProvDump,Storage}` `core` created: 2026-02-09 22:42:48 merged: 2026-02-11 09:26:28

142. [50095](http://github.com/cms-sw/cmssw/pull/50095){:target="_blank"}  from **@smuzaffar**: [DQM-GENERATORS] [LLVM21] Apply code-checks and formats `dqm` `generators` created: 2026-02-09 21:34:31 merged: 2026-02-23 21:59:29

143. [50094](http://github.com/cms-sw/cmssw/pull/50094){:target="_blank"}  from **@smuzaffar**: [ALCA-DB] [LLVM21] Apply code-checks and formats `alca` `db` `trk` created: 2026-02-09 21:34:20 merged: 2026-02-11 09:27:31

144. [50093](http://github.com/cms-sw/cmssw/pull/50093){:target="_blank"}  from **@smuzaffar**: [DB-L1] [LLVM21] Apply code-checks and formats `l1` `db` created: 2026-02-09 21:34:04 merged: 2026-02-12 07:47:58

145. [50092](http://github.com/cms-sw/cmssw/pull/50092){:target="_blank"}  from **@smuzaffar**: [RECONSTRUCTION] [LLVM21] Apply code-checks and formats `reconstruction` `tracking` `trk` created: 2026-02-09 21:33:52 merged: 2026-02-22 21:07:08

146. [50091](http://github.com/cms-sw/cmssw/pull/50091){:target="_blank"}  from **@smuzaffar**: [DQM] [LLVM21] Apply code-checks and formats `dqm` `tracking` `trk` created: 2026-02-09 21:33:32 merged: 2026-02-11 09:26:05

147. [50090](http://github.com/cms-sw/cmssw/pull/50090){:target="_blank"}  from **@smuzaffar**: [ALCA-DB-L1] [LLVM21] Apply code-checks and formats `alca` `l1` `db` created: 2026-02-09 21:33:26 merged: 2026-02-12 07:49:42

148. [50089](http://github.com/cms-sw/cmssw/pull/50089){:target="_blank"}  from **@smuzaffar**: [DAQ] [LLVM21] Apply code-checks and formats `daq` created: 2026-02-09 21:33:10 merged: 2026-02-10 06:21:05

149. [50088](http://github.com/cms-sw/cmssw/pull/50088){:target="_blank"}  from **@smuzaffar**: [CORE] [LLVM21] Apply code-checks and formats `core` created: 2026-02-09 21:33:02 merged: 2026-02-11 09:27:15

150. [50087](http://github.com/cms-sw/cmssw/pull/50087){:target="_blank"}  from **@smuzaffar**: [L1] [LLVM21] Apply code-checks and formats `l1` created: 2026-02-09 21:32:38 merged: 2026-02-12 07:46:44

151. [50086](http://github.com/cms-sw/cmssw/pull/50086){:target="_blank"}  from **@smuzaffar**: [SIMULATION] [LLVM21] Apply code-checks and formats `simulation` `trk` created: 2026-02-09 21:32:30 merged: 2026-02-12 07:49:18

152. [50085](http://github.com/cms-sw/cmssw/pull/50085){:target="_blank"}  from **@smuzaffar**: [ANALYSIS] [LLVM21] Apply code-checks and formats `analysis` created: 2026-02-09 21:32:06 merged: 2026-02-10 06:21:57

153. [50084](http://github.com/cms-sw/cmssw/pull/50084){:target="_blank"}  from **@smuzaffar**: [RECONSTRUCTION-XPOG] [LLVM21] Apply code-checks and formats `reconstruction` `xpog` created: 2026-02-09 21:31:57 merged: 2026-02-24 08:49:34

154. [50083](http://github.com/cms-sw/cmssw/pull/50083){:target="_blank"}  from **@smuzaffar**: [VISUALIZATION] [LLVM21] Apply code-checks and formats `visualization` created: 2026-02-09 21:31:35 merged: 2026-02-10 08:39:23

155. [50082](http://github.com/cms-sw/cmssw/pull/50082){:target="_blank"}  from **@smuzaffar**: [FASTSIM] [LLVM21] Apply code-checks and formats `fastsim` `tracking` created: 2026-02-09 21:31:25 merged: 2026-02-12 07:48:29

156. [50081](http://github.com/cms-sw/cmssw/pull/50081){:target="_blank"}  from **@smuzaffar**: [HLT] [LLVM21] Apply code-checks and formats `hlt` created: 2026-02-09 21:30:55 merged: 2026-02-11 09:25:27

157. [50080](http://github.com/cms-sw/cmssw/pull/50080){:target="_blank"}  from **@smuzaffar**: [GENERATORS] [LLVM21] Apply code-checks and formats `generators` created: 2026-02-09 21:30:46 merged: 2026-02-23 21:59:15

158. [50079](http://github.com/cms-sw/cmssw/pull/50079){:target="_blank"}  from **@smuzaffar**: [XPOG] [LLVM21] Apply code-checks and formats `xpog` created: 2026-02-09 21:30:23 merged: 2026-02-20 09:35:11

159. [50078](http://github.com/cms-sw/cmssw/pull/50078){:target="_blank"}  from **@smuzaffar**: [HETEROGENEOUS-ML] [LLVM21] Apply code-checks and formats `heterogeneous` `ml` created: 2026-02-09 21:30:12 merged: 2026-02-11 09:27:55

160. [50077](http://github.com/cms-sw/cmssw/pull/50077){:target="_blank"}  from **@smuzaffar**: [GEOMETRY] [LLVM21] Apply code-checks and formats `geometry` created: 2026-02-09 21:29:48 merged: 2026-02-11 09:25:57

161. [50076](http://github.com/cms-sw/cmssw/pull/50076){:target="_blank"}  from **@smuzaffar**: [HETEROGENEOUS] [LLVM21] Apply code-checks and formats `heterogeneous` created: 2026-02-09 21:29:33 merged: 2026-02-11 09:25:47

162. [50073](http://github.com/cms-sw/cmssw/pull/50073){:target="_blank"}  from **@raoatifshad**: [GCC15] (simulation) Initialize EcalTBEventHeader to fix GCC15 warning `analysis` created: 2026-02-09 09:19:32 merged: 2026-02-09 18:05:39

163. [50071](http://github.com/cms-sw/cmssw/pull/50071){:target="_blank"}  from **@Dr15Jones**: Use std::variant in OptimalHelixPlaneCrossing `reconstruction` `tracking` created: 2026-02-08 17:20:10 merged: 2026-02-12 07:48:57

164. [50069](http://github.com/cms-sw/cmssw/pull/50069){:target="_blank"}  from **@Dr15Jones**: Added edm::BaseVector `core` created: 2026-02-08 14:53:06 merged: 2026-02-10 06:20:02

165. [50066](http://github.com/cms-sw/cmssw/pull/50066){:target="_blank"}  from **@Dr15Jones**: Added DescriptionCloner to configuration description system `core` created: 2026-02-06 21:29:33 merged: 2026-02-12 07:49:51

166. [50059](http://github.com/cms-sw/cmssw/pull/50059){:target="_blank"}  from **@goblirsc**: Millepede: check the pede exit code `alca` `trk` created: 2026-02-06 16:14:53 merged: 2026-02-11 09:24:52

167. [50058](http://github.com/cms-sw/cmssw/pull/50058){:target="_blank"}  from **@raoatifshad**: [GCC15] (Reconstruction) Fix warnings in METFilters, LSTCore, and MkF `reconstruction` `tracking` created: 2026-02-06 16:04:06 merged: 2026-02-26 21:57:41

168. [50057](http://github.com/cms-sw/cmssw/pull/50057){:target="_blank"}  from **@missirol**: NanoAOD: add `saveTriggerResults` parameter to `NanoAOD*OutputModule` `xpog` created: 2026-02-06 15:01:15 merged: 2026-02-09 21:37:58

169. [50056](http://github.com/cms-sw/cmssw/pull/50056){:target="_blank"}  from **@missirol**: enable ROOT's batch mode in `test-btvNano-check` unit test `xpog` created: 2026-02-06 14:53:17 merged: 2026-02-09 21:38:18

170. [50053](http://github.com/cms-sw/cmssw/pull/50053){:target="_blank"}  from **@tihsu99**: [Scouting DQM] Filter-by-filter monitoring for Scouting-EGM DQM `dqm` created: 2026-02-06 10:44:36 merged: 2026-02-12 07:45:38

171. [50046](http://github.com/cms-sw/cmssw/pull/50046){:target="_blank"}  from **@smuzaffar**: Cleanup CUDACore dependency from PFClusterProducer/plugin `reconstruction` created: 2026-02-05 15:44:29 merged: 2026-02-11 09:24:30

172. [50040](http://github.com/cms-sw/cmssw/pull/50040){:target="_blank"}  from **@SegmentLinking**: Switch to the new tracking baseline (single iteration, CA-extended Patatrack + LST, mkFit) as Phase 2 HLT default `dqm` `hlt` `operations` `pdmv` `tracking` `trk` created: 2026-02-05 09:28:24 merged: 2026-03-03 19:41:29

173. [50035](http://github.com/cms-sw/cmssw/pull/50035){:target="_blank"}  from **@missirol**: NanoAOD: add `savePUDensityVars` parameter to `NPUTablesProducer` `xpog` created: 2026-02-04 17:27:37 merged: 2026-02-09 21:38:53

174. [50031](http://github.com/cms-sw/cmssw/pull/50031){:target="_blank"}  from **@cms-ngt-hlt**: Adjust TICL track linking to work with (extended) pixel tracks `reconstruction` `hgcal` created: 2026-02-04 13:19:30 merged: 2026-02-24 08:48:46

175. [50018](http://github.com/cms-sw/cmssw/pull/50018){:target="_blank"}  from **@Dr15Jones**: Use Fwd.h files instead of forward declaring stored l1t:: objects `l1` created: 2026-02-03 15:25:17 merged: 2026-02-11 09:24:17

176. [50013](http://github.com/cms-sw/cmssw/pull/50013){:target="_blank"}  from **@fabiocos**: MTD geometry and simulation: geometry scenarios and workflows to simulate BTL 2025 test beam `geometry` `simulation` created: 2026-02-03 13:49:05 merged: 2026-02-13 09:43:30

177. [50011](http://github.com/cms-sw/cmssw/pull/50011){:target="_blank"}  from **@esiam**: JME updates for Jet monitoring for DQMOffline (CMSSW_16_1) `dqm` created: 2026-02-03 11:36:41 merged: 2026-02-13 07:35:39

178. [49987](http://github.com/cms-sw/cmssw/pull/49987){:target="_blank"}  from **@alaperto**: C-RACK Phase2 DQM `dqm` `trk` created: 2026-01-30 10:11:31 merged: 2026-02-13 07:34:50

179. [49984](http://github.com/cms-sw/cmssw/pull/49984){:target="_blank"}  from **@SegmentLinking**: Updates to the offline CPU vs. GPU workflows for LST `dqm` `operations` `reconstruction` `pdmv` `tracking` created: 2026-01-29 22:11:18 merged: 2026-02-09 21:40:12

180. [49975](http://github.com/cms-sw/cmssw/pull/49975){:target="_blank"}  from **@JanGerritSchulz**: Fix function input type in the OneToManyAssoc of the alpaka interface `reconstruction` `heterogeneous` `tracking` created: 2026-01-29 16:04:00 merged: 2026-02-21 09:54:09

181. [49951](http://github.com/cms-sw/cmssw/pull/49951){:target="_blank"}  from **@stahlleiton**: Add NANO PbPb UPC relvals `pdmv` created: 2026-01-28 02:34:36 merged: 2026-02-12 07:45:33

182. [49905](http://github.com/cms-sw/cmssw/pull/49905){:target="_blank"}  from **@cms-AlCaDB**: Base classes for refactor of CondTools/Hcal PopConAnalyzers and PopConSourceHandlers `db` `hcal` created: 2026-01-23 08:42:37 merged: 2026-03-05 07:26:23

183. [49901](http://github.com/cms-sw/cmssw/pull/49901){:target="_blank"}  from **@omiguelc**: Implemented HTo2XTo4LGunProducer `generators` created: 2026-01-22 20:58:47 merged: 2026-03-01 17:15:56

184. [49857](http://github.com/cms-sw/cmssw/pull/49857){:target="_blank"}  from **@trackreco**: Fix: remove dependencies of trackingNutple sequence for phase-2 HLT `dqm` `pdmv` `tracking` created: 2026-01-16 18:15:40 merged: 2026-02-24 08:28:38

185. [49699](http://github.com/cms-sw/cmssw/pull/49699){:target="_blank"}  from **@acmbulla**: NanoAOD: handle Sherpa PS weights consistently `xpog` created: 2025-12-22 17:31:21 merged: 2026-02-16 08:20:29

186. [49565](http://github.com/cms-sw/cmssw/pull/49565){:target="_blank"}  from **@cms-L1TK**: Delete obsolete TTTrack::stubPtConsistency function `dqm` `l1` `trk` created: 2025-12-06 19:48:33 merged: 2026-02-25 08:49:27

187. [49550](http://github.com/cms-sw/cmssw/pull/49550){:target="_blank"}  from **@cms-L1TK**: Fix memory leaks in L1 tracking found with Valgrind `l1` created: 2025-12-04 16:59:45 merged: 2026-03-01 17:16:27

188. [48383](http://github.com/cms-sw/cmssw/pull/48383){:target="_blank"}  from **@manuel-gonzalez-henandez**: Pythia8 ResonanceDecayFilter Fix `generators` created: 2025-06-23 08:21:45 merged: 2026-03-11 11:53:04

189. [48248](http://github.com/cms-sw/cmssw/pull/48248){:target="_blank"}  from **@alexstrel**: Alpaka Multi-depth particle flow clusterizer    `reconstruction` `heterogeneous` created: 2025-06-04 16:26:42 merged: 2026-03-01 17:15:22

190. [48093](http://github.com/cms-sw/cmssw/pull/48093){:target="_blank"}  from **@l1scout**: Calo towers L1 scouting data format update `core` `daq` `l1` created: 2025-05-15 16:31:11 merged: 2026-02-13 07:36:31

191. [47020](http://github.com/cms-sw/cmssw/pull/47020){:target="_blank"}  from **@linacre**: [L1T] Peak Finding Algorithm for Vertex Reconstruction (Phase 2) `l1` created: 2024-12-20 18:15:46 merged: 2026-02-26 07:19:05

#### CMSDIST Changes between Tags REL/CMSSW_16_1_0_pre2/el8_amd64_gcc13 and REL/CMSSW_16_1_0_pre3/el8_amd64_gcc13:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_16_1_0_pre2/el8_amd64_gcc13...REL/CMSSW_16_1_0_pre3/el8_amd64_gcc13)



1. [10419](http://github.com/cms-sw/cmsdist/pull/10419){:target="_blank"}  from **@cms-sw**: cms-common: cmsset_default fixes for bash created: 2026-03-15 06:04:10 merged: 2026-03-15 11:38:54

2. [10418](http://github.com/cms-sw/cmsdist/pull/10418){:target="_blank"}  from **@fwyzard**: Update OpenMPI to v5.0.10 created: 2026-03-14 23:30:39 merged: 2026-03-15 11:39:26

3. [10416](http://github.com/cms-sw/cmsdist/pull/10416){:target="_blank"}  from **@fwyzard**: Add missing dependency on compression libraries created: 2026-03-14 22:14:36 merged: 2026-03-15 11:38:38

4. [10415](http://github.com/cms-sw/cmsdist/pull/10415){:target="_blank"}  from **@cms-sw**: py3-grpcio: set parallel build jobs created: 2026-03-13 04:46:36 merged: 2026-03-13 08:52:00

5. [10414](http://github.com/cms-sw/cmsdist/pull/10414){:target="_blank"}  from **@cms-sw**: remove build-system env which is now set via cmsBuild created: 2026-03-12 10:31:57 merged: 2026-03-12 19:29:55

6. [10412](http://github.com/cms-sw/cmsdist/pull/10412){:target="_blank"}  from **@cms-sw**: Set build time env so that edmPluginRefresh can find gpu-backend specfic libs created: 2026-03-11 22:18:02 merged: 2026-03-12 05:06:01

7. [10411](http://github.com/cms-sw/cmsdist/pull/10411){:target="_blank"}  from **@cms-sw**: added support to build herwig7 and thepeg in debug mode created: 2026-03-11 20:47:17 merged: 2026-03-12 05:06:46

8. [10409](http://github.com/cms-sw/cmsdist/pull/10409){:target="_blank"}  from **@cms-sw**: set env for various build system so that each package respect the build jobs count created: 2026-03-11 10:30:45 merged: 2026-03-12 05:12:50

9. [10408](http://github.com/cms-sw/cmsdist/pull/10408){:target="_blank"}  from **@cms-sw**: Added support for gpu backend specific packages created: 2026-03-10 10:54:30 merged: 2026-03-10 11:32:00

10. [10407](http://github.com/cms-sw/cmsdist/pull/10407){:target="_blank"}  from **@cms-sw**: Update build rules tag V09-09-00 which supports env selection based on available nvidia/amd gpu created: 2026-03-10 09:16:24 merged: 2026-03-10 10:18:20

11. [10406](http://github.com/cms-sw/cmsdist/pull/10406){:target="_blank"}  from **@cms-sw**: llvm: create clang cfg files before the build so that llvm tests can use it too created: 2026-03-09 16:36:02 merged: 2026-03-10 08:54:29

12. [10404](http://github.com/cms-sw/cmsdist/pull/10404){:target="_blank"}  from **@cms-sw**: Fix for IWYU so that it can find the correct clang header created: 2026-03-09 09:41:09 merged: 2026-03-09 14:48:56

13. [10399](http://github.com/cms-sw/cmsdist/pull/10399){:target="_blank"}  from **@quinnanm**: Update AXOL1TL to v6.0.4 created: 2026-03-07 04:42:37 merged: 2026-03-07 11:24:16

14. [10398](http://github.com/cms-sw/cmsdist/pull/10398){:target="_blank"}  from **@cms-sw**: Install prmon for non-riscv64/ppc64le created: 2026-03-07 04:12:21 merged: 2026-03-07 04:12:29

15. [10396](http://github.com/cms-sw/cmsdist/pull/10396){:target="_blank"}  from **@cms-sw**: Update tag for L1Trigger-TrackFindingTracklet to V00-06-00 created: 2026-03-06 15:57:16 merged: 2026-03-06 15:57:18

16. [10394](http://github.com/cms-sw/cmsdist/pull/10394){:target="_blank"}  from **@cms-sw**: sherpa: disable building sherpa examples and manual created: 2026-03-06 13:55:05 merged: 2026-03-07 04:13:18

17. [10393](http://github.com/cms-sw/cmsdist/pull/10393){:target="_blank"}  from **@cms-sw**: Update tag for DQM-Integration to V00-16-00 created: 2026-03-05 06:53:50 merged: 2026-03-05 06:53:52

18. [10392](http://github.com/cms-sw/cmsdist/pull/10392){:target="_blank"}  from **@shimashimarin**: [Sherpa] Update Sherpa to 2.2.16 and compile with HepMC3 created: 2026-03-03 15:50:04 merged: 2026-03-05 09:33:00

19. [10389](http://github.com/cms-sw/cmsdist/pull/10389){:target="_blank"}  from **@cms-sw**: Remove JetFlavourInfo.h from fwlite build set created: 2026-03-02 13:39:20 merged: 2026-03-02 13:49:35

20. [10386](http://github.com/cms-sw/cmsdist/pull/10386){:target="_blank"}  from **@fwyzard**: Enble HIP/ROCm build for Traccc in Acts created: 2026-03-01 06:08:21 merged: 2026-03-04 10:58:38

21. [10384](http://github.com/cms-sw/cmsdist/pull/10384){:target="_blank"}  from **@cms-sw**: fix prmon-env.csh to avoid nasted back-ticks created: 2026-02-26 18:21:35 merged: 2026-02-26 22:47:35

22. [10379](http://github.com/cms-sw/cmsdist/pull/10379){:target="_blank"}  from **@cms-sw**: [prmon]Build and deploy prmon along with cmssw-tools created: 2026-02-26 10:59:24 merged: 2026-02-26 12:00:45

23. [10377](http://github.com/cms-sw/cmsdist/pull/10377){:target="_blank"}  from @akritkbehera: Refer to tool name using **@TOOL_FILENAME**@ created: 2026-02-25 16:43:43 merged: 2026-02-25 21:16:13

24. [10372](http://github.com/cms-sw/cmsdist/pull/10372){:target="_blank"}  from **@cms-sw**: Update tag for HLTrigger-HLTfilters to V00-02-00 created: 2026-02-24 14:03:16 merged: 2026-02-24 14:03:18

25. [10371](http://github.com/cms-sw/cmsdist/pull/10371){:target="_blank"}  from **@akritkbehera**: Update clhep.spec to version 2.4.7.2 created: 2026-02-24 12:13:52 merged: 2026-02-25 15:50:51

26. [10359](http://github.com/cms-sw/cmsdist/pull/10359){:target="_blank"}  from **@fwyzard**: Include Google Benchmark and Test in the CMSSW distribution created: 2026-02-19 15:23:26 merged: 2026-02-21 20:38:02

27. [10357](http://github.com/cms-sw/cmsdist/pull/10357){:target="_blank"}  from **@cms-sw**: Drop stdcxx-fs toolfile: It is part of stdc++ since c++17 created: 2026-02-18 22:14:14 merged: 2026-02-21 20:33:02

28. [10354](http://github.com/cms-sw/cmsdist/pull/10354){:target="_blank"}  from **@cms-sw**: Update SCRAMV1 version from V3_00_85 to V3_00_86 created: 2026-02-18 18:11:09 merged: 2026-02-18 19:47:45

29. [10352](http://github.com/cms-sw/cmsdist/pull/10352){:target="_blank"}  from **@cms-sw**: Drop DQM-DTMonitorClient from cmssw dependency created: 2026-02-17 08:42:32 merged: 2026-02-18 12:21:10

30. [10349](http://github.com/cms-sw/cmsdist/pull/10349){:target="_blank"}  from **@quinnanm**: Update AXOL1TL to v6.0.3 created: 2026-02-16 15:42:39 merged: 2026-02-16 20:56:57

31. [10346](http://github.com/cms-sw/cmsdist/pull/10346){:target="_blank"}  from **@cms-sw**: use dumpfullversion so that for system gcc we also get Major.Minor.Patch created: 2026-02-14 11:17:50 merged: 2026-02-16 11:42:39

32. [10345](http://github.com/cms-sw/cmsdist/pull/10345){:target="_blank"}  from **@cms-sw**: [gcc-tool] Change GCC version command to dump full version created: 2026-02-14 10:46:46 merged: 2026-02-14 11:49:17

33. [10343](http://github.com/cms-sw/cmsdist/pull/10343){:target="_blank"}  from **@BenjaminRS**: Updating UTM to 0.14.1 with patch fixes created: 2026-02-13 16:34:16 merged: 2026-02-14 10:26:16

34. [10335](http://github.com/cms-sw/cmsdist/pull/10335){:target="_blank"}  from **@akritkbehera**: Set env variable LIT_OPTS in llvm.spec created: 2026-02-10 15:51:30 merged: 2026-02-10 21:06:47

35. [10334](http://github.com/cms-sw/cmsdist/pull/10334){:target="_blank"}  from **@cms-sw**: Update tag for L1Trigger-TrackFindingTracklet to V00-05-00 created: 2026-02-10 14:56:24 merged: 2026-02-10 14:56:27

36. [10332](http://github.com/cms-sw/cmsdist/pull/10332){:target="_blank"}  from **@akritkbehera**: Updated root to tip of branch v6-36-00-patches created: 2026-02-09 11:16:27 merged: 2026-02-09 21:11:08
