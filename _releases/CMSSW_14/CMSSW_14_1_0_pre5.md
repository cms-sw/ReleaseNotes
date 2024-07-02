---
layout: post
rel_link:  "14_1_0_pre5"
title:  "CMSSW_14_1_0_pre5"
date:   2024-07-01 11:55:27
categories: cmssw
relmajor: 14
relminor: 1
relsubminor: 0
relpre: _pre5
---

# CMSSW_14_1_0_pre5
#### Changes since CMSSW_14_1_0_pre4:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_14_1_0_pre4...CMSSW_14_1_0_pre5)



1. [45311](http://github.com/cms-sw/cmssw/pull/45311){:target="_blank"}  from **@fwyzard**: Protect ECAL time reconstruction for events without EB `reconstruction` `ecal` created: 2024-06-26 12:41:26 merged: 2024-06-27 00:06:32

2. [45310](http://github.com/cms-sw/cmssw/pull/45310){:target="_blank"}  from **@fabiocos**: MTD geometry: fix RecoMTD/DetLayers unit test  `reconstruction` `upgrade` `mtd` created: 2024-06-26 11:47:35 merged: 2024-06-27 18:04:02

3. [45308](http://github.com/cms-sw/cmssw/pull/45308){:target="_blank"}  from **@cms-sw**: Revert "Add Unpacker for L1T Calo Layer 1 to unpack CICADA" `l1` created: 2024-06-26 07:40:31 merged: 2024-06-26 09:17:19

4. [45298](http://github.com/cms-sw/cmssw/pull/45298){:target="_blank"}  from **@smuzaffar**: Fix lost Dict Def: Add HcalRecHitSoA for HcalRecHit package `core` created: 2024-06-25 09:26:38 merged: 2024-06-27 17:57:52

5. [45296](http://github.com/cms-sw/cmssw/pull/45296){:target="_blank"}  from **@mandrenguyen**: Protect against null  `VertexRef` in `deep_helpers.cc` `reconstruction` `btv` created: 2024-06-25 02:29:33 merged: 2024-06-25 15:36:44

6. [45288](http://github.com/cms-sw/cmssw/pull/45288){:target="_blank"}  from **@stahlleiton**: Fix issue in TauMCEmbedding related to missing Pixel Cluster Shape `reconstruction` `simulation` `tracking` created: 2024-06-24 09:04:22 merged: 2024-06-26 20:13:14

7. [45287](http://github.com/cms-sw/cmssw/pull/45287){:target="_blank"}  from **@mmusich**: `TestDQMOfflineConfigurationGotAll`: increase the number of  considered DQM sequences `dqm` created: 2024-06-24 08:33:23 merged: 2024-06-25 15:36:49

8. [45286](http://github.com/cms-sw/cmssw/pull/45286){:target="_blank"}  from @mmusich: Protect `DQMEventInfo` when there is no `PoolDBESSource**@GlobalTag**` `PSet` in the process history `dqm` created: 2024-06-24 08:15:12 merged: 2024-06-25 15:37:48

9. [45279](http://github.com/cms-sw/cmssw/pull/45279){:target="_blank"}  from **@fabiocos**: Use of MTD time in reconstruction: fixes and update `reconstruction` `upgrade` `tracking` `mtd` created: 2024-06-20 15:13:56 merged: 2024-06-25 15:38:04

10. [45275](http://github.com/cms-sw/cmssw/pull/45275){:target="_blank"}  from **@mmusich**: Improve `DetectorStateFilter` to check DCS state of selected combinations of Tracker partitions `dqm` `trk` created: 2024-06-20 09:57:39 merged: 2024-06-27 20:08:04

11. [45274](http://github.com/cms-sw/cmssw/pull/45274){:target="_blank"}  from **@perrotta**: Move phase2_realistic to the T33 tracker geometry in autoCond `alca` created: 2024-06-20 09:36:24 merged: 2024-06-21 01:02:10

12. [45270](http://github.com/cms-sw/cmssw/pull/45270){:target="_blank"}  from **@nurfikri89**: [PileUpJetId] Set jet phi for JEC `reconstruction` created: 2024-06-19 20:37:19 merged: 2024-06-21 12:35:43

13. [45269](http://github.com/cms-sw/cmssw/pull/45269){:target="_blank"}  from **@rovere**: Include other in the re-scaled pie measurements `hlt` created: 2024-06-19 14:20:06 merged: 2024-06-21 01:00:35

14. [45268](http://github.com/cms-sw/cmssw/pull/45268){:target="_blank"}  from **@mmusich**: Improve plugins in `Alignment/HIPAlignmentAlgorithm` and add unit tests `alca` `trk` created: 2024-06-19 11:27:23 merged: 2024-06-24 11:34:26

15. [45266](http://github.com/cms-sw/cmssw/pull/45266){:target="_blank"}  from **@kyungminparkdrums**: Add extended version of SCraw energy plots `dqm` `ecal` created: 2024-06-19 09:34:19 merged: 2024-06-21 12:33:28

16. [45263](http://github.com/cms-sw/cmssw/pull/45263){:target="_blank"}  from **@jsamudio**: Change CaloRecHitProducer to produce new HCAL RecHit SoA `reconstruction` `heterogeneous` `hcal` `pf` created: 2024-06-18 17:27:44 merged: 2024-06-20 22:24:32

17. [45262](http://github.com/cms-sw/cmssw/pull/45262){:target="_blank"}  from **@Mmiglio**: Unpacker and DataFormat for L1 Trigger Scouting BMTF source `daq` created: 2024-06-18 15:41:05 merged: 2024-06-21 12:31:43

18. [45255](http://github.com/cms-sw/cmssw/pull/45255){:target="_blank"}  from **@mmusich**: `DQMEventInfo`: add the possibility to register the `GlobalTag` name in a `MonitorElement` `dqm` created: 2024-06-18 13:24:09 merged: 2024-06-21 00:56:24

19. [45253](http://github.com/cms-sw/cmssw/pull/45253){:target="_blank"}  from **@smorovic**: (DAQ) fix double conting of meta event (14_1_X) `daq` created: 2024-06-18 11:04:41 merged: 2024-06-18 15:08:54

20. [45251](http://github.com/cms-sw/cmssw/pull/45251){:target="_blank"}  from **@iarspider**: Remove unused constants from EcalChannelStatus_PayloadInspector.cc `db` created: 2024-06-18 08:43:45 merged: 2024-06-21 00:52:35

21. [45250](http://github.com/cms-sw/cmssw/pull/45250){:target="_blank"}  from **@iarspider**: Remove unused lambda captures in test_catch2_WaitingThreadPool.cc `core` created: 2024-06-18 08:42:00 merged: 2024-06-21 00:51:09

22. [45249](http://github.com/cms-sw/cmssw/pull/45249){:target="_blank"}  from **@iarspider**: moduleAlloc_setupFile.h: ThreadAllocInfo is struct not class `core` created: 2024-06-18 08:38:01 merged: 2024-06-21 00:45:29

23. [45248](http://github.com/cms-sw/cmssw/pull/45248){:target="_blank"}  from **@jonamotta**: Calo Layer-2 EG conditions for 2024 post-TS `l1` created: 2024-06-18 06:05:55 merged: 2024-06-21 12:24:57

24. [45247](http://github.com/cms-sw/cmssw/pull/45247){:target="_blank"}  from **@Dr15Jones**: Fixed artificial new files in StreamerInputModule `core` created: 2024-06-18 00:35:06 merged: 2024-06-18 15:09:13

25. [45244](http://github.com/cms-sw/cmssw/pull/45244){:target="_blank"}  from **@fabiocos**: Tracking MC truth: fixes and updates to TrackingTruthDumper `simulation` `tracking` created: 2024-06-17 15:41:16 merged: 2024-06-21 00:49:48

26. [45243](http://github.com/cms-sw/cmssw/pull/45243){:target="_blank"}  from **@namapane**: Add protection for pathologic cases in MuonBeamspotConstraintValueMapProducer `reconstruction` created: 2024-06-17 14:05:51 merged: 2024-06-29 12:17:54

27. [45238](http://github.com/cms-sw/cmssw/pull/45238){:target="_blank"}  from **@fwyzard**: Introduce kInvalidDenseId for ECAL and HCAL `reconstruction` `pf` created: 2024-06-17 09:03:22 merged: 2024-06-17 16:47:01

28. [45236](http://github.com/cms-sw/cmssw/pull/45236){:target="_blank"}  from **@missirol**: fix configuration of ZDC inputs in `L1REPACK:uGT` `operations` created: 2024-06-16 21:42:45 merged: 2024-06-27 01:19:02

29. [45234](http://github.com/cms-sw/cmssw/pull/45234){:target="_blank"}  from **@bsunanda**: Run3-alca247C Modify CalibFitPlots to provide multiple depth plots to individual plots with single depths `alca` created: 2024-06-16 08:46:28 merged: 2024-06-17 16:47:13

30. [45232](http://github.com/cms-sw/cmssw/pull/45232){:target="_blank"}  from **@mmusich**: introduce const variant of `XGBooster::predict `and use it in `PhotonXGBoostEstimator` `reconstruction` `ml` created: 2024-06-15 20:02:34 merged: 2024-06-17 12:29:57

31. [45231](http://github.com/cms-sw/cmssw/pull/45231){:target="_blank"}  from **@mmusich**: Fix broken `DQM/Integration` unit tests after streamers layout update `dqm` created: 2024-06-15 16:00:36 merged: 2024-06-21 12:09:05

32. [45229](http://github.com/cms-sw/cmssw/pull/45229){:target="_blank"}  from **@bsunanda**: Phase2-gex178 Update the cfi's for HFNose in testing some beyond Phase2 scenarios `geometry` created: 2024-06-15 05:45:04 merged: 2024-06-17 16:47:34

33. [45228](http://github.com/cms-sw/cmssw/pull/45228){:target="_blank"}  from **@bsunanda**: Phase2-hgx356Y Update the Analyzer code for 2023 HGCal Test Beam codes utilizing 8 inch wafers `geometry` `simulation` `upgrade` created: 2024-06-15 05:09:30 merged: 2024-06-21 00:20:05

34. [45225](http://github.com/cms-sw/cmssw/pull/45225){:target="_blank"}  from **@CMSTrackingPOG**: double precision in `StandaloneTrackMonitor` and `TrackTypeMonitor` plots to avoid numerical overflow with high number of bin counts `dqm` `tracking` created: 2024-06-14 08:21:11 merged: 2024-06-21 00:18:05

35. [45222](http://github.com/cms-sw/cmssw/pull/45222){:target="_blank"}  from **@smuzaffar**: Remove unused variable, fixes cuda warnings `reconstruction` created: 2024-06-14 06:48:19 merged: 2024-06-17 16:47:43

36. [45221](http://github.com/cms-sw/cmssw/pull/45221){:target="_blank"}  from **@dan131riley**: workaround for -O3/UBSAN compiler error in GeneratorInterface/SherpaInterface `generators` created: 2024-06-13 20:54:19 merged: 2024-06-21 00:15:04

37. [45220](http://github.com/cms-sw/cmssw/pull/45220){:target="_blank"}  from **@perrotta**: Move online (frozen) GTs to 141X and add the dedxCalibration record for HI `alca` created: 2024-06-13 20:20:51 merged: 2024-06-17 16:47:53

38. [45219](http://github.com/cms-sw/cmssw/pull/45219){:target="_blank"}  from **@dan131riley**: workaround for -O3 compilation issues in Geometry/HGCalCommonData `geometry` `upgrade` created: 2024-06-13 17:55:46 merged: 2024-06-24 11:33:26

39. [45218](http://github.com/cms-sw/cmssw/pull/45218){:target="_blank"}  from **@fwyzard**: Add a serialisation test `heterogeneous` created: 2024-06-13 16:38:20 merged: 2024-06-17 16:48:02

40. [45217](http://github.com/cms-sw/cmssw/pull/45217){:target="_blank"}  from **@mmusich**: either remove or make a bunch of configuration fragments compile `analysis` `dqm` `geometry` `l1` `reconstruction` `simulation` `trk` created: 2024-06-13 13:18:53 merged: 2024-06-21 00:13:36

41. [45215](http://github.com/cms-sw/cmssw/pull/45215){:target="_blank"}  from **@waredjeb**: TICLv5 - Fix TracksterLinkingbySkeletons Logic `reconstruction` `upgrade` created: 2024-06-13 11:54:07 merged: 2024-06-17 16:48:21

42. [45214](http://github.com/cms-sw/cmssw/pull/45214){:target="_blank"}  from **@smuzaffar**: workflow runner: use previous step output as next step input `pdmv` `upgrade` created: 2024-06-13 08:41:14 merged: 2024-07-01 11:50:48

43. [45213](http://github.com/cms-sw/cmssw/pull/45213){:target="_blank"}  from **@CMSTrackingPOG**: Introduce `reco::Track::recHitsOk()` and use it to remove try/catch pattern in `SingleLongTrackProducer`  `reconstruction` `tracking` created: 2024-06-13 07:21:09 merged: 2024-06-17 12:28:52

44. [45212](http://github.com/cms-sw/cmssw/pull/45212){:target="_blank"}  from **@stahlleiton**: [PF] Add fillDescription to RecoParticleFlow producers `reconstruction` `pf` created: 2024-06-13 06:54:05 merged: 2024-06-21 00:12:06

45. [45211](http://github.com/cms-sw/cmssw/pull/45211){:target="_blank"}  from **@fabiocos**: MTD geometry: fix BTL numbering scheme for scenario v3, input by Geant4, move unit tests to D110 scenario `geometry` `reconstruction` `simulation` `upgrade` created: 2024-06-12 21:57:43 merged: 2024-06-17 17:03:49

46. [45209](http://github.com/cms-sw/cmssw/pull/45209){:target="_blank"}  from **@fwyzard**: Initialise the `EcalElectronicsMappingHost` with null detids `reconstruction` `ecal` created: 2024-06-12 21:05:39 merged: 2024-06-13 15:04:31

47. [45208](http://github.com/cms-sw/cmssw/pull/45208){:target="_blank"}  from **@smuzaffar**: Move commons.h to DataFormats/HGCalReco to break cyclic dep `dqm` `reconstruction` `upgrade` created: 2024-06-12 20:06:12 merged: 2024-06-20 22:50:05

48. [45206](http://github.com/cms-sw/cmssw/pull/45206){:target="_blank"}  from **@borzari**: Including more general DQM compare modules for pixel tracks objects `dqm` `hlt` `reconstruction` `heterogeneous` `tracking` `trk` created: 2024-06-12 14:28:17 merged: 2024-06-27 01:23:05

49. [45205](http://github.com/cms-sw/cmssw/pull/45205){:target="_blank"}  from **@iarspider**: StreamSchedule.h: remove unused variable `core` created: 2024-06-12 11:49:50 merged: 2024-06-12 16:01:39

50. [45202](http://github.com/cms-sw/cmssw/pull/45202){:target="_blank"}  from **@rseidita**: Adding various MEs to per-LS scope `dqm` created: 2024-06-12 08:01:23 merged: 2024-06-20 22:46:57

51. [45201](http://github.com/cms-sw/cmssw/pull/45201){:target="_blank"}  from **@smuzaffar**: Explicitly build with O2 to avoid build errors `geometry` `upgrade` created: 2024-06-11 22:31:58 merged: 2024-06-13 15:04:46

52. [45199](http://github.com/cms-sw/cmssw/pull/45199){:target="_blank"}  from **@kakwok**: HcalRecHit SoA dataFormat `reconstruction` `heterogeneous` `hcal` created: 2024-06-11 20:39:38 merged: 2024-06-20 22:20:53

53. [45197](http://github.com/cms-sw/cmssw/pull/45197){:target="_blank"}  from **@abolshov**: add GEM pad numbers check before doing coordinate conversion to avoid `l1` created: 2024-06-11 17:10:32 merged: 2024-06-25 15:38:34

54. [45196](http://github.com/cms-sw/cmssw/pull/45196){:target="_blank"}  from **@richardkasongo2003**: Added local web server for Tracer log viewer `core` created: 2024-06-11 16:42:52 merged: 2024-06-13 15:05:07

55. [45193](http://github.com/cms-sw/cmssw/pull/45193){:target="_blank"}  from **@iarspider**: Replace enums with static constexpr int in EcalChannelStatus_PayloadInspector.cc `db` created: 2024-06-11 13:37:48 merged: 2024-06-12 11:55:24

56. [45191](http://github.com/cms-sw/cmssw/pull/45191){:target="_blank"}  from **@Ksavva1021**: Removed unused PFRecoTauProducer_cfi `reconstruction` created: 2024-06-11 11:57:26 merged: 2024-06-12 11:54:29

57. [45184](http://github.com/cms-sw/cmssw/pull/45184){:target="_blank"}  from **@stahlleiton**: [PF] Fix RecoParticleFlow.PFProducer.pfGsfElectronCiCSelector_cfi `reconstruction` `pf` created: 2024-06-10 22:24:35 merged: 2024-06-12 01:25:54

58. [45180](http://github.com/cms-sw/cmssw/pull/45180){:target="_blank"}  from **@dinyar**: Set uGMT version used for 2024 in the packers `l1` created: 2024-06-10 10:17:21 merged: 2024-06-20 22:45:22

59. [45175](http://github.com/cms-sw/cmssw/pull/45175){:target="_blank"}  from **@srimanob**: Update default Phase-2 geometry to D110 and restructure relvals_2026 `pdmv` `upgrade` created: 2024-06-08 04:03:54 merged: 2024-06-25 15:39:04

60. [45173](http://github.com/cms-sw/cmssw/pull/45173){:target="_blank"}  from **@CMSTrackingPOG**: Miscellaneous fixes for TRK POG Data/MC validation tool `dqm` `tracking` created: 2024-06-08 03:23:30 merged: 2024-06-13 15:07:51

61. [45172](http://github.com/cms-sw/cmssw/pull/45172){:target="_blank"}  from **@Dr15Jones**: do not throw in PerigeeConversions::ftsToPerigeeParameters `analysis` `reconstruction` `tracking` created: 2024-06-07 15:35:19 merged: 2024-06-12 01:26:07

62. [45171](http://github.com/cms-sw/cmssw/pull/45171){:target="_blank"}  from **@iarspider**: Update DDHGCalPassive.cc `geometry` `upgrade` created: 2024-06-07 13:16:11 merged: 2024-06-12 01:26:25

63. [45169](http://github.com/cms-sw/cmssw/pull/45169){:target="_blank"}  from **@iarspider**: [ALCA] Remove Wall flag from Alignment/OfflineValidation/bin/BuildFile.xml `alca` `trk` created: 2024-06-07 09:52:27 merged: 2024-06-12 01:26:49

64. [45168](http://github.com/cms-sw/cmssw/pull/45168){:target="_blank"}  from **@iarspider**: [Core] Remove unused lambda captures in test_catch2_WaitingThreadPool.cc and StreamSchedule.h `core` created: 2024-06-07 09:45:31 merged: 2024-06-12 01:27:04

65. [45167](http://github.com/cms-sw/cmssw/pull/45167){:target="_blank"}  from **@nurfikri89**: [JMENano] Add customize functions to recompute Puppi weights and PuppiMET, add new autoNano option `pdmv` `upgrade` `xpog` created: 2024-06-07 09:44:10 merged: 2024-06-21 12:23:08

66. [45166](http://github.com/cms-sw/cmssw/pull/45166){:target="_blank"}  from **@fwyzard**: Update `edm::bit_cast` `core` created: 2024-06-07 09:18:57 merged: 2024-06-12 11:52:31

67. [45163](http://github.com/cms-sw/cmssw/pull/45163){:target="_blank"}  from **@bsunanda**: Phase2-356X Fix bugs in the simulation of 2023 HGCal TB setups to provide multiple hits `geometry` `simulation` created: 2024-06-07 07:11:33 merged: 2024-06-12 01:28:25

68. [45160](http://github.com/cms-sw/cmssw/pull/45160){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `14_0_X` (8/N) [`14_1_X`]  `hlt` created: 2024-06-06 20:03:40 merged: 2024-06-11 04:30:40

69. [45159](http://github.com/cms-sw/cmssw/pull/45159){:target="_blank"}  from **@wddgit**: Change assert to exception, related to FEDRawDataCollection `core` created: 2024-06-06 19:12:16 merged: 2024-06-12 01:28:40

70. [45156](http://github.com/cms-sw/cmssw/pull/45156){:target="_blank"}  from **@mteroerd**: New APE measurement workflow `alca` `trk` created: 2024-06-06 15:35:18 merged: 2024-06-12 01:29:33

71. [45155](http://github.com/cms-sw/cmssw/pull/45155){:target="_blank"}  from **@thomreis**: ECAL - Roll back to ECAL ratio timing for Run 3 `operations` `reconstruction` `ecal` created: 2024-06-06 15:30:37 merged: 2024-06-07 12:11:06

72. [45152](http://github.com/cms-sw/cmssw/pull/45152){:target="_blank"}  from **@iarspider**: Fix maybe-uninitialized warning in SeedingTrackFeatures `reconstruction` created: 2024-06-06 08:29:06 merged: 2024-06-12 11:36:44

73. [45151](http://github.com/cms-sw/cmssw/pull/45151){:target="_blank"}  from **@vince502**: Include HIon type traits for Alpaka pixel tracking `reconstruction` `heterogeneous` `tracking` `trk` created: 2024-06-06 03:42:34 merged: 2024-06-25 15:39:25

74. [45150](http://github.com/cms-sw/cmssw/pull/45150){:target="_blank"}  from **@Dr15Jones**: Fix thread local use in AllocMonitor `core` created: 2024-06-05 21:38:39 merged: 2024-06-12 01:30:51

75. [45147](http://github.com/cms-sw/cmssw/pull/45147){:target="_blank"}  from **@mmusich**: `L2TauTagNNProducerAlpaka`: do not call TF inference with empty grid `hlt` `tau` created: 2024-06-05 19:58:32 merged: 2024-06-06 13:22:18

76. [45144](http://github.com/cms-sw/cmssw/pull/45144){:target="_blank"}  from **@CTPPS**: Run the T2 test with ROOT Raw instead of streamer files `reconstruction` created: 2024-06-05 14:18:33 merged: 2024-06-07 12:39:57

77. [45141](http://github.com/cms-sw/cmssw/pull/45141){:target="_blank"}  from **@makortel**: Add context for exceptions being thrown via RootOutputFile::finishEndFile() `core` created: 2024-06-05 13:47:20 merged: 2024-06-06 13:22:33

78. [45140](http://github.com/cms-sw/cmssw/pull/45140){:target="_blank"}  from **@fwyzard**: Use the mergeResourcesJson.py script bundled with CMSSW `hlt` created: 2024-06-05 13:17:15 merged: 2024-06-06 13:22:48

79. [45139](http://github.com/cms-sw/cmssw/pull/45139){:target="_blank"}  from **@valsdav**: Skip evaluation of TensorFlow model if inputs are empty `ml` created: 2024-06-05 12:35:07 merged: 2024-06-06 13:25:44

80. [45133](http://github.com/cms-sw/cmssw/pull/45133){:target="_blank"}  from **@iarspider**: Fix deprecated enum arithmetics in CaloGeometry `geometry` created: 2024-06-04 13:22:31 merged: 2024-06-06 13:30:49

81. [45132](http://github.com/cms-sw/cmssw/pull/45132){:target="_blank"}  from **@eyigitba**: Modifications to L1REPACK:FullSimTP to prevent crashes and make it more compatible with other REPACK options `operations` created: 2024-06-04 13:22:10 merged: 2024-06-11 01:30:52

82. [45131](http://github.com/cms-sw/cmssw/pull/45131){:target="_blank"}  from **@iarspider**: Fix deprecated bitwise operations between different enum types in WTableWidget `visualization` created: 2024-06-04 12:58:57 merged: 2024-06-05 20:15:09

83. [45130](http://github.com/cms-sw/cmssw/pull/45130){:target="_blank"}  from **@iarspider**: Fix maybe-uninitialized warning in BaseCrystal `fastsim` created: 2024-06-04 12:15:22 merged: 2024-06-06 13:31:04

84. [45129](http://github.com/cms-sw/cmssw/pull/45129){:target="_blank"}  from **@iarspider**: Fix deprecated enum arithmetics in ElectronConversionRejectionValidator and PhotonValidator `dqm` created: 2024-06-04 08:47:27 merged: 2024-06-20 22:42:42

85. [45125](http://github.com/cms-sw/cmssw/pull/45125){:target="_blank"}  from **@missirol**: remove leftover printout in `GlobalEvFOutputModule` `daq` created: 2024-06-03 21:20:26 merged: 2024-06-05 20:07:49

86. [45114](http://github.com/cms-sw/cmssw/pull/45114){:target="_blank"}  from **@sroychow**: remove SiOuterTracker dqm and validation packages `dqm` `simulation` `trk` created: 2024-05-31 09:33:10 merged: 2024-06-13 15:08:02

87. [45113](http://github.com/cms-sw/cmssw/pull/45113){:target="_blank"}  from **@bsunanda**: Run3-alca247B Add new options for getting correction factors - to be used to understand the impact on JetMET corrections `alca` created: 2024-05-31 08:46:43 merged: 2024-06-06 13:26:38

88. [45112](http://github.com/cms-sw/cmssw/pull/45112){:target="_blank"}  from **@Dr15Jones**: Removed _cfi.py which were duplicate of auto-generated ones `core` `geometry` `l1` created: 2024-05-30 19:39:08 merged: 2024-06-11 15:16:47

89. [45110](http://github.com/cms-sw/cmssw/pull/45110){:target="_blank"}  from **@Dr15Jones**: Added missing header in StreamerInputModule.h `core` created: 2024-05-30 16:12:48 merged: 2024-05-31 16:09:13

90. [45109](http://github.com/cms-sw/cmssw/pull/45109){:target="_blank"}  from **@slava77**: remove unused mkFitHitConverter_cfi.py `reconstruction` `tracking` created: 2024-05-30 16:10:40 merged: 2024-05-31 16:07:14

91. [45108](http://github.com/cms-sw/cmssw/pull/45108){:target="_blank"}  from **@Dr15Jones**: Added value method to additional python Parameter types `core` created: 2024-05-30 15:51:53 merged: 2024-05-31 16:07:44

92. [45105](http://github.com/cms-sw/cmssw/pull/45105){:target="_blank"}  from **@eyigitba**: EMTF emulator support for 2024 primitive converison LUTs `l1` created: 2024-05-30 14:52:19 merged: 2024-06-05 20:05:19

93. [45104](http://github.com/cms-sw/cmssw/pull/45104){:target="_blank"}  from **@francescobrivio**: [CPP20] Remove volatile from CondCore/Utilities `db` created: 2024-05-30 14:07:16 merged: 2024-06-12 11:37:44

94. [45097](http://github.com/cms-sw/cmssw/pull/45097){:target="_blank"}  from **@smorovic**: (DAQ) fix lock contention in source `daq` created: 2024-05-30 11:15:46 merged: 2024-05-31 16:08:22

95. [45096](http://github.com/cms-sw/cmssw/pull/45096){:target="_blank"}  from **@iarspider**: Remove unused constants in CondCore/EcalPlugins/plugins/Ecal*_PayloadInspector.cc `db` created: 2024-05-30 09:53:26 merged: 2024-06-03 14:20:28

96. [45095](http://github.com/cms-sw/cmssw/pull/45095){:target="_blank"}  from **@bsunanda**: Phase2-hgx357 Add a new version of HGCalCellOffest to provide a more correct results for the cell areas `geometry` `simulation` `upgrade` created: 2024-05-30 06:35:48 merged: 2024-06-05 20:01:25

97. [45094](http://github.com/cms-sw/cmssw/pull/45094){:target="_blank"}  from **@Dr15Jones**: Removed duplicate cfi file in L1Trigger/L1CaloTrigger `l1` `upgrade` created: 2024-05-29 20:06:46 merged: 2024-06-03 14:20:38

98. [45093](http://github.com/cms-sw/cmssw/pull/45093){:target="_blank"}  from **@iarspider**: Remove unused variable in VertexTimeAlgorithmLegacy4D.cc `reconstruction` `tracking` created: 2024-05-29 10:04:19 merged: 2024-05-30 14:31:04

99. [45092](http://github.com/cms-sw/cmssw/pull/45092){:target="_blank"}  from **@cms-AlCaDB**: Add possibility to read triggerbits for Secondary Datasets from the GT `alca` `hlt` `pdmv` created: 2024-05-29 09:55:32 merged: 2024-06-10 23:21:25

100. [45091](http://github.com/cms-sw/cmssw/pull/45091){:target="_blank"}  from **@VinInn**: [CPP20] remove depracated use of volatile as for #45072 `reconstruction` created: 2024-05-29 09:51:50 merged: 2024-05-30 14:31:19

101. [45088](http://github.com/cms-sw/cmssw/pull/45088){:target="_blank"}  from **@iarspider**: Fix maybe-uninitialized warnings in Zmumumerge.cc `alca` `trk` created: 2024-05-29 07:47:44 merged: 2024-06-12 01:31:23

102. [45086](http://github.com/cms-sw/cmssw/pull/45086){:target="_blank"}  from **@nabrandman**: Adds muon shower triggers for MC data `l1` created: 2024-05-29 00:38:28 merged: 2024-06-13 15:08:21

103. [45085](http://github.com/cms-sw/cmssw/pull/45085){:target="_blank"}  from **@mmusich**: move `pat::XGBooster` out of `PhysicsTools/PatAlgos` into its own package and use it for `PhotonXGBoostEstimator` `reconstruction` `xpog` `ml` created: 2024-05-28 22:53:29 merged: 2024-06-05 19:51:54

104. [45080](http://github.com/cms-sw/cmssw/pull/45080){:target="_blank"}  from **@makortel**: Revert "Workaround to produce exactly same data products in Serial and CUDA backends in Alpaka modules possibly used at HLT" `alca` `reconstruction` `heterogeneous` `tracking` `trk` created: 2024-05-28 15:25:37 merged: 2024-05-29 15:37:30

105. [45079](http://github.com/cms-sw/cmssw/pull/45079){:target="_blank"}  from **@waredjeb**: Add ParticleFlow Client for Online DQM -  GPUvsCPU comparison `dqm` `pf` created: 2024-05-28 15:16:47 merged: 2024-06-12 11:48:41

106. [45078](http://github.com/cms-sw/cmssw/pull/45078){:target="_blank"}  from **@iarspider**: [CPP20][Visualization] Remove deprecated implicit capture of this in FWTEveViewer `visualization` created: 2024-05-28 14:23:20 merged: 2024-06-03 14:21:41

107. [45077](http://github.com/cms-sw/cmssw/pull/45077){:target="_blank"}  from **@yeonsu108**: Update btag from DeepCSV to ParticleNet for BTV DQM `dqm` created: 2024-05-28 14:19:51 merged: 2024-06-12 01:31:56

108. [45076](http://github.com/cms-sw/cmssw/pull/45076){:target="_blank"}  from **@iarspider**: [CPP20][Visualisation] Fix deprecated enum bitwise operation in FWCandidateHGCalLegoProxyBuilder `visualization` created: 2024-05-28 14:00:19 merged: 2024-06-03 14:21:53

109. [45074](http://github.com/cms-sw/cmssw/pull/45074){:target="_blank"}  from **@martinamalberti**: [MTD] Update MTD hit pattern + add outermost hits position in the TrackExtenderWithMTD `dqm` `reconstruction` `simulation` `upgrade` `tracking` created: 2024-05-28 13:24:26 merged: 2024-06-12 01:32:11

110. [45073](http://github.com/cms-sw/cmssw/pull/45073){:target="_blank"}  from **@iarspider**: [CPP20] Replace enum with static constexpr int in L1TriggerRates `daq` `l1` `reconstruction` created: 2024-05-28 13:04:39 merged: 2024-05-29 15:42:48

111. [45071](http://github.com/cms-sw/cmssw/pull/45071){:target="_blank"}  from **@iarspider**: [CPP20][DQM] Fix deprecated enum arithmetics in TkAlCaRecoMonitor and SiPixelPhase1RawDataErrorComparator `dqm` `trk` created: 2024-05-28 12:38:50 merged: 2024-06-06 13:26:48

112. [45070](http://github.com/cms-sw/cmssw/pull/45070){:target="_blank"}  from **@iarspider**: [CPP20][DQM] Replace enum with static constexpr int in DQWorkerClient; replace ecaldqm::Constants enum with  static constexpr ints `dqm` created: 2024-05-28 11:50:56 merged: 2024-06-06 13:27:21

113. [45069](http://github.com/cms-sw/cmssw/pull/45069){:target="_blank"}  from **@iarspider**: Fix deprecated arithmetics between different enum types in AlignPCLThresholdsHG `alca` `db` created: 2024-05-28 10:04:03 merged: 2024-05-29 15:42:34

114. [45068](http://github.com/cms-sw/cmssw/pull/45068){:target="_blank"}  from **@iarspider**: [CPP20][DB] Replace some enums with constexpr ints in Ecal*_PayloadInspector.cc `db` created: 2024-05-28 09:33:58 merged: 2024-05-29 15:42:21

115. [45067](http://github.com/cms-sw/cmssw/pull/45067){:target="_blank"}  from **@iarspider**: Remove extraneous parentheses in CMTRawAnalyzer.cc `dqm` created: 2024-05-28 09:04:04 merged: 2024-06-20 22:40:35

116. [45066](http://github.com/cms-sw/cmssw/pull/45066){:target="_blank"}  from **@Pruthvi-ch**: Correction to cell shapes for partial wafers in v18 version of HGCal  `geometry` `simulation` `upgrade` created: 2024-05-28 07:20:07 merged: 2024-06-03 14:22:14

117. [45063](http://github.com/cms-sw/cmssw/pull/45063){:target="_blank"}  from **@mmusich**: `MuonHLTSeedMVAClassifier`: update to use MVA-related parameters according to `isL1` value `hlt` `reconstruction` created: 2024-05-27 20:40:28 merged: 2024-05-30 14:37:29

118. [45060](http://github.com/cms-sw/cmssw/pull/45060){:target="_blank"}  from **@iarspider**: Use std::abs instead of abs in PixelPhase2TopologyBuilder.cc `geometry` `trk` created: 2024-05-27 15:18:21 merged: 2024-05-29 15:42:11

119. [45059](http://github.com/cms-sw/cmssw/pull/45059){:target="_blank"}  from **@iarspider**: Fix compilation warning in Batching.cc `ml` created: 2024-05-27 14:52:22 merged: 2024-05-29 15:42:03

120. [45058](http://github.com/cms-sw/cmssw/pull/45058){:target="_blank"}  from **@iarspider**: Use std::abs instead of integer abs in HLTMCtruth.cc `hlt` created: 2024-05-27 14:45:24 merged: 2024-05-29 15:41:56

121. [45056](http://github.com/cms-sw/cmssw/pull/45056){:target="_blank"}  from **@mmusich**: Updates to `TkAlV0sAnalyzer` and `V0Monitor` `alca` `dqm` `tracking` `trk` created: 2024-05-27 13:44:05 merged: 2024-06-05 19:53:39

122. [45053](http://github.com/cms-sw/cmssw/pull/45053){:target="_blank"}  from **@24LopezR**: Protection for invalid TSOS in MuonTrajectoryUpdator `reconstruction` `muon` created: 2024-05-27 11:18:06 merged: 2024-05-29 15:41:44

123. [45052](http://github.com/cms-sw/cmssw/pull/45052){:target="_blank"}  from **@iarspider**: Fix compilation warning in DDHGCalPassive.cc `geometry` `upgrade` created: 2024-05-27 08:56:35 merged: 2024-05-31 16:08:27

124. [45049](http://github.com/cms-sw/cmssw/pull/45049){:target="_blank"}  from **@mandrenguyen**: Protect against invalid trajectory state on surface in STA muon reco `reconstruction` created: 2024-05-26 13:50:30 merged: 2024-05-26 23:54:22

125. [45047](http://github.com/cms-sw/cmssw/pull/45047){:target="_blank"}  from **@missirol**: guard against invalid output products from `HLTL1TSeed` `hlt` created: 2024-05-26 10:18:08 merged: 2024-05-26 23:53:04

126. [45046](http://github.com/cms-sw/cmssw/pull/45046){:target="_blank"}  from **@bsunanda**: Run3-alca247A Bug fix to the code Calibration/HcalCalibAlgos/plugins/HcalIsoTrkAnalyzer.cc for initialiting uncorrection of RecHit energies `alca` created: 2024-05-26 05:46:38 merged: 2024-05-28 14:34:27

127. [45045](http://github.com/cms-sw/cmssw/pull/45045){:target="_blank"}  from **@bsunanda**: Run3-alca247YX Add examples for the IsoTrack calibration in Calibration/HcalCalibAlgos/macros/jobs (restore the material from #45010) `alca` created: 2024-05-26 04:12:21 merged: 2024-05-28 14:44:19

128. [45044](http://github.com/cms-sw/cmssw/pull/45044){:target="_blank"}  from **@bsunanda**: Run3-alca247Z Add a new defintion of truncated DetID and a new scaling script for HCAL IsoTrack  calibration `alca` created: 2024-05-25 10:15:16 merged: 2024-05-28 14:43:37

129. [45042](http://github.com/cms-sw/cmssw/pull/45042){:target="_blank"}  from **@mmusich**: `PhotonXGBoostEstimator` : set `XGBoost` to use one thread to avoid spawning hundreds of OpenMP threads `reconstruction` `egamma` created: 2024-05-24 20:52:49 merged: 2024-05-26 23:51:40

130. [45041](http://github.com/cms-sw/cmssw/pull/45041){:target="_blank"}  from **@agrubercms**: L1 filters using P2GT for tau paths `hlt` created: 2024-05-24 16:37:46 merged: 2024-06-12 01:32:36

131. [45038](http://github.com/cms-sw/cmssw/pull/45038){:target="_blank"}  from **@iarspider**: Fix undeclared identifiers in RectangularPixelPhase2Topology `geometry` `trk` created: 2024-05-24 09:49:30 merged: 2024-05-28 14:42:52

132. [45037](http://github.com/cms-sw/cmssw/pull/45037){:target="_blank"}  from **@aloeliger**: Add Unpacker for L1T Calo Layer 1 to unpack CICADA `l1` created: 2024-05-24 09:45:09 merged: 2024-06-25 15:40:29

133. [45036](http://github.com/cms-sw/cmssw/pull/45036){:target="_blank"}  from **@bsunanda**: Phase2-hgx356 Fix the bugs in HGCal TB simulation for 2023 scenarios `geometry` `simulation` `upgrade` created: 2024-05-24 08:24:13 merged: 2024-05-28 14:33:22

134. [45034](http://github.com/cms-sw/cmssw/pull/45034){:target="_blank"}  from **@cms-sw**: clang-tidy: Remove deprecated AnalyzeTemporaryDtors option `core` created: 2024-05-23 21:36:09 merged: 2024-05-28 14:41:36

135. [45033](http://github.com/cms-sw/cmssw/pull/45033){:target="_blank"}  from **@abdoulline**: HcalZDCDetId fix for Run3 `simulation` `hcal` created: 2024-05-23 20:32:09 merged: 2024-05-28 12:54:13

136. [45032](http://github.com/cms-sw/cmssw/pull/45032){:target="_blank"}  from **@kbunkow**: possibility of configuring the OMTF emulator directly from XMLs `l1` `upgrade` created: 2024-05-23 18:10:24 merged: 2024-06-12 11:43:40

137. [45030](http://github.com/cms-sw/cmssw/pull/45030){:target="_blank"}  from **@mbluj**: Set 3 instead of 4 OMTF track sub-address as expected by uGMT `l1` created: 2024-05-23 16:16:42 merged: 2024-05-28 12:52:58

138. [45029](http://github.com/cms-sw/cmssw/pull/45029){:target="_blank"}  from **@jhgoh**: RPCDigis validaiton module update `dqm` created: 2024-05-23 16:01:51 merged: 2024-06-12 01:33:44

139. [45026](http://github.com/cms-sw/cmssw/pull/45026){:target="_blank"}  from **@alaperto**: Disabled ROCs for Online DQM Pixel Summary `dqm` `trk` created: 2024-05-23 15:13:33 merged: 2024-05-26 23:57:04

140. [45025](http://github.com/cms-sw/cmssw/pull/45025){:target="_blank"}  from **@Dr15Jones**: Added ModuleAllocMonitor Service `core` created: 2024-05-23 14:31:46 merged: 2024-06-12 01:34:17

141. [45024](http://github.com/cms-sw/cmssw/pull/45024){:target="_blank"}  from **@stahlleiton**: Add new dEdx calibration condition format `alca` `db` created: 2024-05-23 14:20:17 merged: 2024-05-28 14:40:53

142. [45023](http://github.com/cms-sw/cmssw/pull/45023){:target="_blank"}  from **@VinInn**: Introduce a Long-track bonus in CkfTrackBuilder `hlt` `reconstruction` `tracking` created: 2024-05-23 13:21:55 merged: 2024-06-06 13:28:54

143. [45021](http://github.com/cms-sw/cmssw/pull/45021){:target="_blank"}  from **@namapane**: Revive MF map and XML geometry visualization `reconstruction` `visualization` created: 2024-05-23 08:03:02 merged: 2024-05-29 15:41:12

144. [45020](http://github.com/cms-sw/cmssw/pull/45020){:target="_blank"}  from **@smuzaffar**: AMPTInterface: Fix used uninitialized warnings `generators` created: 2024-05-23 07:36:50 merged: 2024-06-05 19:57:48

145. [45017](http://github.com/cms-sw/cmssw/pull/45017){:target="_blank"}  from **@wddgit**: Improve behavior after exception in begin/end run transitions `core` `simulation` created: 2024-05-22 17:47:41 merged: 2024-06-03 14:22:48

146. [45016](http://github.com/cms-sw/cmssw/pull/45016){:target="_blank"}  from **@stahlleiton**: Add new dEdx calibration and estimator `reconstruction` `pdmv` `upgrade` `tracking` created: 2024-05-22 14:19:56 merged: 2024-06-21 12:19:43

147. [45012](http://github.com/cms-sw/cmssw/pull/45012){:target="_blank"}  from **@smdogra**: Clean offline DQM of Photon "smin" triggers and adding CSCCluster50_Photon20Unseeded `dqm` created: 2024-05-22 02:39:23 merged: 2024-06-05 19:57:04

148. [45011](http://github.com/cms-sw/cmssw/pull/45011){:target="_blank"}  from **@cgsavard**: Bin L1 track quality MVA variable `l1` `upgrade` created: 2024-05-21 17:41:31 merged: 2024-06-03 14:24:14

149. [45005](http://github.com/cms-sw/cmssw/pull/45005){:target="_blank"}  from **@AdrianoDee**: Introducing `SimOnGen` and `GenOnly` wfs for 2024 and 2026D110 `pdmv` `upgrade` created: 2024-05-21 10:18:46 merged: 2024-06-12 01:34:46

150. [44992](http://github.com/cms-sw/cmssw/pull/44992){:target="_blank"}  from **@lowette**: Integration of sexaquark simulation code (for EXO-24-003) `simulation` created: 2024-05-17 00:45:55 merged: 2024-06-03 14:26:00

151. [44991](http://github.com/cms-sw/cmssw/pull/44991){:target="_blank"}  from **@smorovic**: (DAQ) remove dummy MicroStateService `daq` `dqm` `hlt` created: 2024-05-16 21:37:23 merged: 2024-05-29 15:40:53

152. [44988](http://github.com/cms-sw/cmssw/pull/44988){:target="_blank"}  from **@fwyzard**: Enable SoA range checking by default `heterogeneous` created: 2024-05-16 15:32:29 merged: 2024-06-05 19:56:14

153. [44984](http://github.com/cms-sw/cmssw/pull/44984){:target="_blank"}  from **@mbluj**: [DBG] Fix undefined ref errors in L1TMuonOverlapPhase2 `l1` `upgrade` created: 2024-05-16 11:50:47 merged: 2024-05-28 14:36:02

154. [44977](http://github.com/cms-sw/cmssw/pull/44977){:target="_blank"}  from **@AdrianoDee**: Fix RelMon Piecharts using `Chart.js` `dqm` created: 2024-05-15 12:59:34 merged: 2024-06-12 01:35:19

155. [44965](http://github.com/cms-sw/cmssw/pull/44965){:target="_blank"}  from **@AdrianoDee**: Add D110 Default Input Dataset `pdmv` `upgrade` created: 2024-05-13 15:32:47 merged: 2024-06-03 14:26:14

156. [44963](http://github.com/cms-sw/cmssw/pull/44963){:target="_blank"}  from **@gpetruc**: [L1T Phase-2] Correlator Layer 1 pattern file producer updates for multi-board tests `l1` `upgrade` created: 2024-05-13 10:29:23 merged: 2024-06-03 14:27:12

157. [44901](http://github.com/cms-sw/cmssw/pull/44901){:target="_blank"}  from **@makortel**: Introduce edm::Async service, and use it in CUDA and Alpaka modules `core` `heterogeneous` created: 2024-05-03 16:30:08 merged: 2024-06-06 13:29:11

158. [44892](http://github.com/cms-sw/cmssw/pull/44892){:target="_blank"}  from **@Dr15Jones**: Handle event meta data changes in streamer files `alca` `core` `daq` `dqm` created: 2024-05-02 16:32:24 merged: 2024-05-29 22:07:26

159. [44785](http://github.com/cms-sw/cmssw/pull/44785){:target="_blank"}  from **@felicepantaleo**: first release of TICLv5 `core` `dqm` `hlt` `operations` `reconstruction` `visualization` `simulation` `pdmv` `upgrade` created: 2024-04-19 15:06:43 merged: 2024-06-12 11:35:35

160. [44669](http://github.com/cms-sw/cmssw/pull/44669){:target="_blank"}  from **@AdrianoDee**: Tunable `PUMax`  in `PrimaryVertexMonitor` and Finer d_xy DQM Tracking Plots `dqm` `tracking` created: 2024-04-09 11:23:50 merged: 2024-06-13 15:08:35

161. [44560](http://github.com/cms-sw/cmssw/pull/44560){:target="_blank"}  from **@brusale**: CaloParticles in the barrel for Phase2 and generalization of the LC associators `dqm` `reconstruction` `simulation` `upgrade` `hgcal` created: 2024-03-27 16:58:25 merged: 2024-05-29 13:08:34

162. [44222](http://github.com/cms-sw/cmssw/pull/44222){:target="_blank"}  from **@aloeliger**: CICADA-uGT emulator additions `hlt` `l1` created: 2024-02-27 15:33:27 merged: 2024-06-27 18:12:50

163. [44219](http://github.com/cms-sw/cmssw/pull/44219){:target="_blank"}  from **@ericcano**: Removes duplicate/unneeded entries in serialization XML of test objects. `heterogeneous` created: 2024-02-27 12:28:47 merged: 2024-06-21 12:37:36

164. [43761](http://github.com/cms-sw/cmssw/pull/43761){:target="_blank"}  from **@mmusich**: add `Era_Run3_2024`, `Era_Run3_2025`, Tier0 reco scenario for 2024, and change default era in `PyReleaseValidation` `operations` `pdmv` `upgrade` created: 2024-01-20 14:02:38 merged: 2024-06-12 01:36:18

#### CMSDIST Changes between Tags REL/CMSSW_14_1_0_pre4/el8_amd64_gcc12 and REL/CMSSW_14_1_0_pre5/el8_amd64_gcc12:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_14_1_0_pre4/el8_amd64_gcc12...REL/CMSSW_14_1_0_pre5/el8_amd64_gcc12)



1. [9275](http://github.com/cms-sw/cmsdist/pull/9275){:target="_blank"}  from **@cms-sw**: Buildrules: Use sort instead of python3 to calculcate the dependency order created: 2024-06-28 11:01:01 merged: 2024-06-28 20:25:16

2. [9274](http://github.com/cms-sw/cmsdist/pull/9274){:target="_blank"}  from **@cms-sw**: Update tag for Geometry-TestReference to V00-14-00 created: 2024-06-27 18:02:13 merged: 2024-06-27 18:02:15

3. [9273](http://github.com/cms-sw/cmsdist/pull/9273){:target="_blank"}  from **@cms-sw**: cmssw-osenv: Fix for calling cmsset_default and user login scripts created: 2024-06-27 13:17:50 merged: 2024-06-27 20:24:47

4. [9271](http://github.com/cms-sw/cmsdist/pull/9271){:target="_blank"}  from **@thesps**: Update AXOL1TL to v4.0.0 created: 2024-06-27 10:39:58 merged: 2024-06-27 20:33:13

5. [9268](http://github.com/cms-sw/cmsdist/pull/9268){:target="_blank"}  from **@belforte**: bump crabprod version to current (tested) crab-dev created: 2024-06-26 16:56:08 merged: 2024-06-27 20:25:14

6. [9267](http://github.com/cms-sw/cmsdist/pull/9267){:target="_blank"}  from **@cms-sw**: added as needed IBs overrides created: 2024-06-26 14:49:22 merged: 2024-06-26 15:08:56

7. [9263](http://github.com/cms-sw/cmsdist/pull/9263){:target="_blank"}  from **@cms-sw**: [BuildRules] Added support to link default lib to the alpaka backends created: 2024-06-24 10:27:53 merged: 2024-06-24 19:59:08

8. [9262](http://github.com/cms-sw/cmsdist/pull/9262){:target="_blank"}  from **@cms-sw**: Get crab command complete fucntion from crab-bash-completion.sh created: 2024-06-24 10:11:32 merged: 2024-06-24 10:24:55

9. [9261](http://github.com/cms-sw/cmsdist/pull/9261){:target="_blank"}  from **@belforte**: bump crab client version in  crab-dev created: 2024-06-21 20:04:42 merged: 2024-06-24 10:09:29

10. [9260](http://github.com/cms-sw/cmsdist/pull/9260){:target="_blank"}  from **@cms-sw**: Update tag for DataFormats-L1Scouting to V00-03-00 created: 2024-06-21 12:30:03 merged: 2024-06-21 12:30:05

11. [9259](http://github.com/cms-sw/cmsdist/pull/9259){:target="_blank"}  from **@cms-sw**: Update tag for DQM-Integration to V00-07-00 created: 2024-06-21 12:07:19 merged: 2024-06-21 12:07:20

12. [9258](http://github.com/cms-sw/cmsdist/pull/9258){:target="_blank"}  from **@cms-sw**: No need to distribute tensorflow-sources created: 2024-06-20 16:10:38 merged: 2024-06-20 20:31:38

13. [9256](http://github.com/cms-sw/cmsdist/pull/9256){:target="_blank"}  from **@cms-sw**: Supress CUDA warning about "module" keyword created: 2024-06-20 09:56:34 merged: 2024-06-20 20:33:39

14. [9255](http://github.com/cms-sw/cmsdist/pull/9255){:target="_blank"}  from **@cms-sw**: Update DD4Hep to v01-29-00 created: 2024-06-20 08:43:01 merged: 2024-06-20 20:33:53

15. [9253](http://github.com/cms-sw/cmsdist/pull/9253){:target="_blank"}  from **@DickyChant**: Update professor2 to 2.4.2 and fixing Python3 env created: 2024-06-19 12:25:27 merged: 2024-06-20 20:30:54

16. [9252](http://github.com/cms-sw/cmsdist/pull/9252){:target="_blank"}  from **@cms-sw**: cuda-flags: suppress volatile destination type warning created: 2024-06-18 13:54:25 merged: 2024-06-18 20:53:31

17. [9250](http://github.com/cms-sw/cmsdist/pull/9250){:target="_blank"}  from **@cms-sw**: Update urllib3 to fix 2 dependabot issues created: 2024-06-18 08:51:29 merged: 2024-06-18 20:40:31

18. [9248](http://github.com/cms-sw/cmsdist/pull/9248){:target="_blank"}  from **@cms-sw**: Update tag for Geometry-TestReference to V00-13-00 created: 2024-06-17 17:03:55 merged: 2024-06-17 17:03:57

19. [9244](http://github.com/cms-sw/cmsdist/pull/9244){:target="_blank"}  from **@cms-sw**: Added missing system deps needed by autotools/cmssw created: 2024-06-13 07:08:45 merged: 2024-06-13 13:09:00

20. [9243](http://github.com/cms-sw/cmsdist/pull/9243){:target="_blank"}  from **@cms-sw**: [AARCH64] jemalloc: explicitly set pagesize created: 2024-06-12 09:44:25 merged: 2024-06-12 21:52:25

21. [9242](http://github.com/cms-sw/cmsdist/pull/9242){:target="_blank"}  from **@belforte**: move CRABClient v3.240520 to prod created: 2024-06-12 08:12:09 merged: 2024-06-12 21:52:04

22. [9239](http://github.com/cms-sw/cmsdist/pull/9239){:target="_blank"}  from **@cms-sw**: cmssw-ib: always use latest buildLogAnalyzer without caching it on cmsrep created: 2024-06-11 09:10:52 merged: 2024-06-11 09:11:05

23. [9234](http://github.com/cms-sw/cmsdist/pull/9234){:target="_blank"}  from **@cms-sw**: tornado: update to 6.4.1 which container security fixes created: 2024-06-10 21:41:08 merged: 2024-06-13 13:09:12

24. [9233](http://github.com/cms-sw/cmsdist/pull/9233){:target="_blank"}  from **@cms-sw**: Include tool-conf.file is exists created: 2024-06-10 17:37:25 merged: 2024-06-10 21:06:29

25. [9230](http://github.com/cms-sw/cmsdist/pull/9230){:target="_blank"}  from **@cms-sw**: Force rebuild jemalloc to fix the aarch64 runtime issues created: 2024-06-07 13:55:39 merged: 2024-06-07 14:40:15

26. [9229](http://github.com/cms-sw/cmsdist/pull/9229){:target="_blank"}  from **@gartung**: Update igprof.spec with commit with AL9 changes created: 2024-06-07 13:35:48 merged: 2024-06-09 09:53:29

27. [9228](http://github.com/cms-sw/cmsdist/pull/9228){:target="_blank"}  from **@cms-sw**: Update tag for RecoTracker-LSTCore to V00-01-00 created: 2024-06-06 15:01:05 merged: 2024-06-06 15:01:06

28. [9227](http://github.com/cms-sw/cmsdist/pull/9227){:target="_blank"}  from **@cms-sw**: Update tag for RecoPPS-Local to V00-02-00 created: 2024-06-06 13:47:20 merged: 2024-06-06 13:47:22

29. [9226](http://github.com/cms-sw/cmsdist/pull/9226){:target="_blank"}  from **@cms-sw**: Update tag for L1Trigger-L1TMuon to V01-12-00 created: 2024-06-05 20:04:05 merged: 2024-06-05 20:04:07

30. [9222](http://github.com/cms-sw/cmsdist/pull/9222){:target="_blank"}  from **@iarspider**: [Master] Updated root to tip of branch v6-30-00-patches created: 2024-06-03 08:19:06 merged: 2024-06-03 16:11:40

31. [9218](http://github.com/cms-sw/cmsdist/pull/9218){:target="_blank"}  from **@cms-sw**: scram tool clean; support for building stack without an option tool created: 2024-06-03 07:15:37 merged: 2024-06-06 19:02:09

32. [9216](http://github.com/cms-sw/cmsdist/pull/9216){:target="_blank"}  from **@cms-sw**: Downgrade grpcio-tools to 1.60.1 to match grpcio created: 2024-05-30 09:16:59 merged: 2024-05-30 12:51:48

33. [9214](http://github.com/cms-sw/cmsdist/pull/9214){:target="_blank"}  from **@aloeliger**: Update UTM to 13.0 created: 2024-05-29 15:10:50 merged: 2024-05-30 12:52:01

34. [9210](http://github.com/cms-sw/cmsdist/pull/9210){:target="_blank"}  from **@cms-sw**: Update tag for RecoMuon-TrackerSeedGenerator to V00-07-00 created: 2024-05-28 15:37:15 merged: 2024-05-28 15:37:16

35. [9206](http://github.com/cms-sw/cmsdist/pull/9206){:target="_blank"}  from **@Dominic-Stafford**: Add collier toolfile created: 2024-05-27 10:06:47 merged: 2024-05-28 14:38:46

36. [9205](http://github.com/cms-sw/cmsdist/pull/9205){:target="_blank"}  from **@fwyzard**: Change the default optimisation level to `-O3` created: 2024-05-24 17:43:37 merged: 2024-05-27 16:32:47

37. [9199](http://github.com/cms-sw/cmsdist/pull/9199){:target="_blank"}  from **@aandvalenzuela**: [Master] Updated root to tip of branch v6-30-00-patches in master created: 2024-05-21 09:43:11 merged: 2024-05-27 16:34:40

38. [9196](http://github.com/cms-sw/cmsdist/pull/9196){:target="_blank"}  from **@cms-sw**: updated pip pkg: requests, Jinja2, tqdm, Werkzeug created: 2024-05-21 07:47:47 merged: 2024-05-27 16:31:38
