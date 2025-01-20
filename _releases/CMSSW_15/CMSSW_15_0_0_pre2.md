---
layout: post
rel_link:  "15_0_0_pre2"
title:  "CMSSW_15_0_0_pre2"
date:   2025-01-20 09:32:03
categories: cmssw
relmajor: 15
relminor: 0
relsubminor: 0
relpre: _pre2
---

# CMSSW_15_0_0_pre2
#### Changes since CMSSW_15_0_0_pre1:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_15_0_0_pre1...CMSSW_15_0_0_pre2)



1. [47135](http://github.com/cms-sw/cmssw/pull/47135){:target="_blank"}  from **@mmusich**: fix miscellaneous python configuration files `reconstruction` `tracking` `trk` created: 2025-01-19 19:10:52 merged: 2025-01-20 08:48:48

2. [47121](http://github.com/cms-sw/cmssw/pull/47121){:target="_blank"}  from **@fwyzard**: Remove deprecated `cudaLimitDevRuntimeSyncDepth` functionality `heterogeneous` created: 2025-01-17 12:55:12 merged: 2025-01-17 14:50:53

3. [47115](http://github.com/cms-sw/cmssw/pull/47115){:target="_blank"}  from **@fabiocos**: MTD geometry: temporarily revert the BTL numbering scheme update `geometry` `reconstruction` `simulation` `upgrade` `tracking` `mtd` created: 2025-01-16 14:08:50 merged: 2025-01-17 09:50:38

4. [47112](http://github.com/cms-sw/cmssw/pull/47112){:target="_blank"}  from **@bsunanda**: Phase2-hgx361D Simplify the scripts in SimG4Core/PrintGeomInfo/test/python by using a new tool that finds th right ERA and Global Tag `simulation` created: 2025-01-16 04:24:54 merged: 2025-01-17 09:51:33

5. [47111](http://github.com/cms-sw/cmssw/pull/47111){:target="_blank"}  from **@makortel**: Enable implicit host-to-device copy for Alpaka EDProducers `heterogeneous` created: 2025-01-15 19:56:17 merged: 2025-01-16 05:14:04

6. [47110](http://github.com/cms-sw/cmssw/pull/47110){:target="_blank"}  from **@mmusich**: Partial revert of #47079: do not use `ifValue` switches in `fillDescriptions` affecting confDB parsing `alca` `hlt` `reconstruction` created: 2025-01-15 18:07:41 merged: 2025-01-16 08:42:56

7. [47108](http://github.com/cms-sw/cmssw/pull/47108){:target="_blank"}  from **@fwyzard**: Replace `ALPAKA_STATIC_ACC_MEM_GLOBAL` with `HOST_DEVICE_CONSTANT` `reconstruction` `tracking` `trk` created: 2025-01-15 14:00:10 merged: 2025-01-16 08:43:31

8. [47107](http://github.com/cms-sw/cmssw/pull/47107){:target="_blank"}  from **@mmusich**: add `fillDescriptions` to several plugins used at HLT (4/N) `dqm` `hlt` `reconstruction` `tracking` created: 2025-01-15 12:44:25 merged: 2025-01-17 13:54:41

9. [47106](http://github.com/cms-sw/cmssw/pull/47106){:target="_blank"}  from **@trackreco**: Speedup of mkFit hit converters, and introduction of mkFit HLT customization for 2025 `reconstruction` `tracking` created: 2025-01-15 11:50:25 merged: 2025-01-17 09:45:52

10. [47103](http://github.com/cms-sw/cmssw/pull/47103){:target="_blank"}  from **@bsunanda**: Phase2-hgx361C Update the remaining test scripts i Validation/HGCalValidation.test/python with the new tool that finds the right ERA and Global tag for a Phase2 scenario `dqm` created: 2025-01-15 03:29:48 merged: 2025-01-17 14:30:12

11. [47098](http://github.com/cms-sw/cmssw/pull/47098){:target="_blank"}  from **@bsunanda**: Phase2-hgx361B Update some of the test scripts in Validation/HGCalValidation/test/python using a new tool which finds the right ERA and Global Tag `dqm` created: 2025-01-14 16:19:08 merged: 2025-01-17 14:32:03

12. [47097](http://github.com/cms-sw/cmssw/pull/47097){:target="_blank"}  from **@bsunanda**: Phase2-hgx361A Update some of the test scripts in Validation/HGCalValidation/test/python using a new tool that finds the right ERA and Global Tag `dqm` created: 2025-01-14 15:31:48 merged: 2025-01-17 14:30:28

13. [47096](http://github.com/cms-sw/cmssw/pull/47096){:target="_blank"}  from **@bsunanda**: Run3-hcx381 Provide a test code to provide # of readout cells for the calorimeters `geometry` created: 2025-01-14 06:50:16 merged: 2025-01-15 12:06:52

14. [47088](http://github.com/cms-sw/cmssw/pull/47088){:target="_blank"}  from **@missirol**: revert #46026 (L1-uGT emulator) `l1` created: 2025-01-12 17:19:21 merged: 2025-01-15 15:54:50

15. [47087](http://github.com/cms-sw/cmssw/pull/47087){:target="_blank"}  from **@makortel**: Replicate the mocked version -based reduced ProcessHistory tests for streamer file format `core` created: 2025-01-10 22:50:58 merged: 2025-01-16 05:15:14

16. [47085](http://github.com/cms-sw/cmssw/pull/47085){:target="_blank"}  from **@makortel**: Make all RunLumiEventAnalyzer instances to use `vector<unsigned long long>` `core` created: 2025-01-10 22:15:20 merged: 2025-01-13 19:08:39

17. [47080](http://github.com/cms-sw/cmssw/pull/47080){:target="_blank"}  from **@rmankel**: Update of Millepede production system (MPS): large campaigns `alca` `trk` created: 2025-01-10 13:07:00 merged: 2025-01-14 07:43:25

18. [47079](http://github.com/cms-sw/cmssw/pull/47079){:target="_blank"}  from **@mmusich**: add `fillDescriptions` to several plugins used at HLT (3/N) `alca` `analysis` `hlt` `reconstruction` `upgrade` `tracking` `trk` created: 2025-01-10 10:43:41 merged: 2025-01-12 08:51:50

19. [47078](http://github.com/cms-sw/cmssw/pull/47078){:target="_blank"}  from **@AdrianoDee**: Fix for HI Alpaka Pixel Configs `reconstruction` `trk` created: 2025-01-10 07:30:48 merged: 2025-01-11 21:05:35

20. [47077](http://github.com/cms-sw/cmssw/pull/47077){:target="_blank"}  from **@Pruthvi-ch**: Update to Cell areas and valid cells for v18/v19 version of HGCAL `geometry` `upgrade` created: 2025-01-10 06:52:30 merged: 2025-01-17 09:45:01

21. [47075](http://github.com/cms-sw/cmssw/pull/47075){:target="_blank"}  from **@pianonick411**: Add Mother Indices to LHEPart  `xpog` created: 2025-01-09 21:59:21 merged: 2025-01-13 08:36:41

22. [47074](http://github.com/cms-sw/cmssw/pull/47074){:target="_blank"}  from **@smuzaffar**: [UBSAN]Properly initialize datamembers for move operator `generators` created: 2025-01-09 20:19:27 merged: 2025-01-10 09:09:23

23. [47073](http://github.com/cms-sw/cmssw/pull/47073){:target="_blank"}  from **@Dr15Jones**: Improve behavior of streamer system `core` created: 2025-01-09 19:44:05 merged: 2025-01-11 21:05:05

24. [47070](http://github.com/cms-sw/cmssw/pull/47070){:target="_blank"}  from **@missirol**: move per-run changes of L1-uGT emulator to `beginRun` (incl. loading of AXOL1TL model) `l1` created: 2025-01-09 18:06:45 merged: 2025-01-14 17:27:03

25. [47068](http://github.com/cms-sw/cmssw/pull/47068){:target="_blank"}  from **@smorovic**: [DAQ] Input source improvements and initial Phase-2 DTH format support `daq` created: 2025-01-09 15:14:26 merged: 2025-01-12 08:51:35

26. [47065](http://github.com/cms-sw/cmssw/pull/47065){:target="_blank"}  from **@Parsifal-2045**: Remove all `SealModules` from the `RecoMuon` package `hlt` `reconstruction` created: 2025-01-09 11:28:55 merged: 2025-01-09 15:26:09

27. [47064](http://github.com/cms-sw/cmssw/pull/47064){:target="_blank"}  from **@mmusich**: re-organize `RecoMuon/L3TrackFinder` such that all plugins are defined in `plugins` folder `hlt` `reconstruction` created: 2025-01-08 20:54:17 merged: 2025-01-09 14:07:05

28. [47061](http://github.com/cms-sw/cmssw/pull/47061){:target="_blank"}  from **@slava77**: speedup SiStripClusterizer(FromRaw) using ThreeThresholdAlgorithm `alca` `reconstruction` `trk` created: 2025-01-08 19:22:55 merged: 2025-01-09 10:17:09

29. [47060](http://github.com/cms-sw/cmssw/pull/47060){:target="_blank"}  from **@Dr15Jones**: Updated test of edm::Ref use from a merged ROOT file `core` created: 2025-01-08 18:17:17 merged: 2025-01-09 21:15:40

30. [47059](http://github.com/cms-sw/cmssw/pull/47059){:target="_blank"}  from **@perrotta**: Update SiPixelAliHGRcd_prod.json `alca` `db` created: 2025-01-08 16:23:31 merged: 2025-01-09 10:27:40

31. [47055](http://github.com/cms-sw/cmssw/pull/47055){:target="_blank"}  from **@cms-trackeralign**: Introduce a `Generic` validation tool for dataset validation in the alignment all-in-one tool `alca` `trk` created: 2025-01-08 10:30:56 merged: 2025-01-09 10:21:00

32. [47054](http://github.com/cms-sw/cmssw/pull/47054){:target="_blank"}  from **@mmusich**: update `customiseHybrid` to comply with new definition of `siStripClusters` `reconstruction` `trk` created: 2025-01-08 09:31:52 merged: 2025-01-08 17:50:25

33. [47053](http://github.com/cms-sw/cmssw/pull/47053){:target="_blank"}  from **@Dr15Jones**: Removed TFWLiteSelector system `core` created: 2025-01-07 21:40:22 merged: 2025-01-09 07:33:32

34. [47052](http://github.com/cms-sw/cmssw/pull/47052){:target="_blank"}  from **@mmusich**: `jetTools`: do not run `svClustering` for `pfDeepCSV{*}TagInfos` `reconstruction` `xpog` created: 2025-01-07 21:11:19 merged: 2025-01-08 13:53:54

35. [47051](http://github.com/cms-sw/cmssw/pull/47051){:target="_blank"}  from **@Dr15Jones**: Moved construction of ProductResolvers to a separate function `core` `dqm` `simulation` `trk` created: 2025-01-07 19:26:44 merged: 2025-01-13 19:09:01

36. [47049](http://github.com/cms-sw/cmssw/pull/47049){:target="_blank"}  from **@Parsifal-2045**: [NGT] Fix double inclusion of Phase2HLTMuonSelectorForL3 module  `hlt` `reconstruction` created: 2025-01-07 15:34:51 merged: 2025-01-08 17:48:50

37. [47048](http://github.com/cms-sw/cmssw/pull/47048){:target="_blank"}  from **@smuzaffar**: Update lost dict def for EcalRecHitSoA `core` created: 2025-01-07 11:30:57 merged: 2025-01-08 17:48:39

38. [47047](http://github.com/cms-sw/cmssw/pull/47047){:target="_blank"}  from **@makortel**: Replace configuration-copying Alpaka ESProducers with MoveToDeviceCache `alca` `hlt` `reconstruction` `db` `heterogeneous` created: 2025-01-07 00:02:33 merged: 2025-01-14 15:48:01

39. [47046](http://github.com/cms-sw/cmssw/pull/47046){:target="_blank"}  from **@thomreis**: ECAL - Fix compilation issue with gcc13 `alca` `db` `ecal` created: 2025-01-06 11:46:57 merged: 2025-01-07 15:51:28

40. [47045](http://github.com/cms-sw/cmssw/pull/47045){:target="_blank"}  from **@mmusich**: add `fillDescriptions` to several more plugins in the reco area used at HLT (2/N) `hlt` `reconstruction` `tracking` created: 2025-01-06 08:55:58 merged: 2025-01-07 12:53:38

41. [47044](http://github.com/cms-sw/cmssw/pull/47044){:target="_blank"}  from **@mmusich**: Add `BeamSpotCompatibilityChecker` to all alignment offline validation configuration files `alca` `reconstruction` `tracking` `trk` created: 2025-01-06 08:55:54 merged: 2025-01-07 13:08:49

42. [47042](http://github.com/cms-sw/cmssw/pull/47042){:target="_blank"}  from **@bsunanda**: Run3-alca252X Update the macros to study the forward-backward asymmetry in the correction factors `alca` created: 2025-01-04 10:13:26 merged: 2025-01-06 08:28:47

43. [47041](http://github.com/cms-sw/cmssw/pull/47041){:target="_blank"}  from **@bsunanda**: Run3-gex185 Modify the 2025 scenario by including th corrected GE21 geometry with 4 instead of 5 added chmbers `geometry` `upgrade` created: 2025-01-04 04:24:09 merged: 2025-01-15 15:51:14

44. [47040](http://github.com/cms-sw/cmssw/pull/47040){:target="_blank"}  from **@makortel**: Remove commented-out `putenv()` calls from `SiPixelFedCablingMapWriter` `alca` `trk` created: 2025-01-03 22:03:30 merged: 2025-01-05 11:44:40

45. [47039](http://github.com/cms-sw/cmssw/pull/47039){:target="_blank"}  from **@makortel**: Remove `ReadBase` as unused `dqm` `db` created: 2025-01-03 21:59:58 merged: 2025-01-12 08:51:20

46. [47036](http://github.com/cms-sw/cmssw/pull/47036){:target="_blank"}  from **@makortel**: Add StreamID parameter to Transformer callback functions `core` `heterogeneous` created: 2025-01-02 23:37:15 merged: 2025-01-07 15:51:58

47. [47035](http://github.com/cms-sw/cmssw/pull/47035){:target="_blank"}  from **@makortel**: Make implicit copy of `TrackingRecHitsSoACollection<TrackerTraits>` to host asynchronous `reconstruction` `heterogeneous` `tracking` created: 2025-01-02 17:54:50 merged: 2025-01-05 11:44:46

48. [47034](http://github.com/cms-sw/cmssw/pull/47034){:target="_blank"}  from **@makortel**: Make Alpaka ESProducers asynchronous for non-host backends `heterogeneous` created: 2025-01-02 16:53:23 merged: 2025-01-07 06:05:37

49. [47032](http://github.com/cms-sw/cmssw/pull/47032){:target="_blank"}  from **@makortel**: Add a new test for reduced ProcessHistory `core` created: 2024-12-30 16:02:39 merged: 2025-01-10 07:38:34

50. [47031](http://github.com/cms-sw/cmssw/pull/47031){:target="_blank"}  from **@namapane**: Add muonBestTrackType value `xpog` created: 2024-12-28 18:16:58 merged: 2025-01-09 21:15:29

51. [47030](http://github.com/cms-sw/cmssw/pull/47030){:target="_blank"}  from **@missirol**: add BX info to `GlobalObjectMap` (L1uGT emulation) `hlt` `l1` created: 2024-12-28 16:40:59 merged: 2025-01-14 21:46:06

52. [47029](http://github.com/cms-sw/cmssw/pull/47029){:target="_blank"}  from **@makortel**: Use `WaitingTaskHolder` to signal `doneWaiting()` instead of `WaitingTaskWithArenaHolder` in framework `core` created: 2024-12-27 21:43:56 merged: 2025-01-10 07:38:29

53. [47028](http://github.com/cms-sw/cmssw/pull/47028){:target="_blank"}  from **@makortel**: Add central `synchronize` configuration parameter to Alpaka modules `heterogeneous` created: 2024-12-27 20:33:12 merged: 2024-12-30 21:27:07

54. [47026](http://github.com/cms-sw/cmssw/pull/47026){:target="_blank"}  from **@bsunanda**: Run3-gem82 Change in GE21 setup in view of last minute changes `geometry` `upgrade` created: 2024-12-25 08:24:41 merged: 2024-12-27 09:46:44

55. [47025](http://github.com/cms-sw/cmssw/pull/47025){:target="_blank"}  from **@Dr15Jones**: Reduce memory held between Events in PFProducer `reconstruction` created: 2024-12-23 15:40:43 merged: 2024-12-24 09:09:39

56. [47024](http://github.com/cms-sw/cmssw/pull/47024){:target="_blank"}  from **@smuzaffar**: ParameterSet/Config.py: Use realpath of  cmssw area to avoid symlink issue `core` created: 2024-12-23 10:22:17 merged: 2024-12-24 09:10:40

57. [47023](http://github.com/cms-sw/cmssw/pull/47023){:target="_blank"}  from **@missirol**: speed up shared-hits cleaning in `TrackerSeedCleaner` `reconstruction` created: 2024-12-22 18:18:25 merged: 2024-12-24 09:10:05

58. [47022](http://github.com/cms-sw/cmssw/pull/47022){:target="_blank"}  from **@bsunanda**: Run3-alca252 Updat the IsoTrack calibration codes to finalize 2024 and 2025 calibrations `alca` created: 2024-12-21 07:00:29 merged: 2025-01-03 13:07:28

59. [47019](http://github.com/cms-sw/cmssw/pull/47019){:target="_blank"}  from **@smuzaffar**: clang19 fix: template argument list is expected after a name prefixed `reconstruction` `xpog` created: 2024-12-20 17:17:24 merged: 2025-01-07 13:09:31

60. [47018](http://github.com/cms-sw/cmssw/pull/47018){:target="_blank"}  from **@martinamalberti**: MTD simulation: fix association tracking particle - MtdSimLayerCluster `simulation` `upgrade` created: 2024-12-20 13:12:32 merged: 2025-01-07 13:09:02

61. [47017](http://github.com/cms-sw/cmssw/pull/47017){:target="_blank"}  from **@mmusich**: add `fillDescriptions` to a bunch of plugins in the `EventFilter` and `Reco` areas used at HLT (1/N) `daq` `hlt` `reconstruction` `tracking` `trk` created: 2024-12-20 11:35:57 merged: 2025-01-07 13:08:29

62. [47015](http://github.com/cms-sw/cmssw/pull/47015){:target="_blank"}  from **@Dr15Jones**: Decrease temporary memory held by PuppiProducer `reconstruction` created: 2024-12-19 21:57:07 merged: 2024-12-20 09:41:25

63. [47013](http://github.com/cms-sw/cmssw/pull/47013){:target="_blank"}  from **@makortel**: Remove redundant data members from InputFileCatalog to reduce memory use `core` created: 2024-12-19 14:31:37 merged: 2025-01-09 07:26:11

64. [47011](http://github.com/cms-sw/cmssw/pull/47011){:target="_blank"}  from **@Dr15Jones**: Handle case where modules share memory in ModuleEventAllocMonitor `core` created: 2024-12-18 21:40:01 merged: 2024-12-20 09:42:24

65. [47008](http://github.com/cms-sw/cmssw/pull/47008){:target="_blank"}  from **@martinamalberti**: MTD Validation: add efficiency plots for correct reco match `dqm` `mtd` created: 2024-12-18 13:20:37 merged: 2024-12-19 10:19:21

66. [47006](http://github.com/cms-sw/cmssw/pull/47006){:target="_blank"}  from **@smuzaffar**: [ALCA-DB] Apply code checks/format `alca` `db` `trk` created: 2024-12-18 07:42:42 merged: 2025-01-03 13:08:28

67. [47005](http://github.com/cms-sw/cmssw/pull/47005){:target="_blank"}  from **@smuzaffar**: [DB-L1] Apply code checks/format `l1` `db` created: 2024-12-18 07:42:11 merged: 2025-01-03 13:11:38

68. [47004](http://github.com/cms-sw/cmssw/pull/47004){:target="_blank"}  from **@smuzaffar**: [DB-HLT] Apply code checks/format `hlt` `db` created: 2024-12-18 07:42:05 merged: 2025-01-03 13:08:42

69. [47003](http://github.com/cms-sw/cmssw/pull/47003){:target="_blank"}  from **@smuzaffar**: [RECONSTRUCTION] Apply code checks/format `reconstruction` `tracking` created: 2024-12-18 07:42:00 merged: 2024-12-19 10:25:56

70. [47001](http://github.com/cms-sw/cmssw/pull/47001){:target="_blank"}  from **@smuzaffar**: [L1-XPOG] Apply code checks/format `l1` `xpog` created: 2024-12-18 07:41:30 merged: 2024-12-19 10:19:07

71. [47000](http://github.com/cms-sw/cmssw/pull/47000){:target="_blank"}  from **@smuzaffar**: [ALCA-DB-L1] Apply code checks/format `alca` `l1` `db` created: 2024-12-18 07:41:24 merged: 2025-01-03 13:11:02

72. [46999](http://github.com/cms-sw/cmssw/pull/46999){:target="_blank"}  from **@smuzaffar**: [CORE] Apply code checks/format `core` created: 2024-12-18 07:40:46 merged: 2024-12-20 09:42:39

73. [46998](http://github.com/cms-sw/cmssw/pull/46998){:target="_blank"}  from **@smuzaffar**: [RECONSTRUCTION-XPOG] Apply code checks/format `reconstruction` `xpog` created: 2024-12-18 07:40:41 merged: 2024-12-19 10:29:08

74. [46997](http://github.com/cms-sw/cmssw/pull/46997){:target="_blank"}  from **@smuzaffar**: [L1] Apply code checks/format `l1` created: 2024-12-18 07:40:36 merged: 2024-12-19 10:23:38

75. [46996](http://github.com/cms-sw/cmssw/pull/46996){:target="_blank"}  from **@smuzaffar**: [GEOMETRY] Apply code checks/format `geometry` created: 2024-12-18 07:39:24 merged: 2024-12-19 10:23:56

76. [46995](http://github.com/cms-sw/cmssw/pull/46995){:target="_blank"}  from **@smuzaffar**: [DAQ] Apply code checks/format `daq` created: 2024-12-18 07:39:22 merged: 2024-12-19 10:26:47

77. [46994](http://github.com/cms-sw/cmssw/pull/46994){:target="_blank"}  from **@smuzaffar**: [FASTSIM] Apply code checks/format `fastsim` created: 2024-12-18 07:39:14 merged: 2024-12-19 10:19:55

78. [46993](http://github.com/cms-sw/cmssw/pull/46993){:target="_blank"}  from **@smuzaffar**: [GEOMETRY-UPGRADE] Apply code checks/format `geometry` `upgrade` created: 2024-12-18 07:38:30 merged: 2024-12-19 10:20:23

79. [46992](http://github.com/cms-sw/cmssw/pull/46992){:target="_blank"}  from **@smuzaffar**: [GENERATORS] Apply code checks/format `generators` created: 2024-12-18 07:38:24 merged: 2025-01-09 10:19:11

80. [46991](http://github.com/cms-sw/cmssw/pull/46991){:target="_blank"}  from **@smuzaffar**: [VISUALIZATION] Apply code checks/format `visualization` created: 2024-12-18 07:38:19 merged: 2025-01-06 17:06:50

81. [46990](http://github.com/cms-sw/cmssw/pull/46990){:target="_blank"}  from **@smuzaffar**: [DAQ-L1] Apply code checks/format `daq` `l1` created: 2024-12-18 07:38:02 merged: 2024-12-19 10:19:26

82. [46989](http://github.com/cms-sw/cmssw/pull/46989){:target="_blank"}  from **@smuzaffar**: [L1-UPGRADE] Apply code checks/format `l1` `upgrade` created: 2024-12-18 07:37:54 merged: 2024-12-19 10:29:03

83. [46988](http://github.com/cms-sw/cmssw/pull/46988){:target="_blank"}  from **@smuzaffar**: [HLT] Apply code checks/format `hlt` created: 2024-12-18 07:37:49 merged: 2024-12-19 10:25:25

84. [46987](http://github.com/cms-sw/cmssw/pull/46987){:target="_blank"}  from **@smuzaffar**: [SIMULATION-UPGRADE] Apply code checks/format `simulation` `upgrade` created: 2024-12-18 07:37:17 merged: 2024-12-19 10:24:10

85. [46986](http://github.com/cms-sw/cmssw/pull/46986){:target="_blank"}  from **@smuzaffar**: [RECONSTRUCTION-UPGRADE] Apply code checks/format `reconstruction` `upgrade` created: 2024-12-18 07:37:12 merged: 2024-12-19 10:18:15

86. [46985](http://github.com/cms-sw/cmssw/pull/46985){:target="_blank"}  from **@smuzaffar**: [SIMULATION] Apply code checks/format `simulation` created: 2024-12-18 07:37:06 merged: 2024-12-19 10:18:06

87. [46984](http://github.com/cms-sw/cmssw/pull/46984){:target="_blank"}  from **@smuzaffar**: [ML] Apply code checks/format `ml` created: 2024-12-18 07:36:45 merged: 2024-12-19 10:17:43

88. [46983](http://github.com/cms-sw/cmssw/pull/46983){:target="_blank"}  from **@smuzaffar**: [XPOG] Apply code checks/format `xpog` created: 2024-12-18 07:35:11 merged: 2024-12-19 10:16:35

89. [46982](http://github.com/cms-sw/cmssw/pull/46982){:target="_blank"}  from **@smuzaffar**: [ANALYSIS] Apply code checks/format `analysis` created: 2024-12-18 07:33:38 merged: 2024-12-19 10:24:41

90. [46981](http://github.com/cms-sw/cmssw/pull/46981){:target="_blank"}  from **@nurfikri89**: [MiniAOD] Remove slimmedGenJets minimum pt cut `reconstruction` `xpog` created: 2024-12-17 21:37:46 merged: 2025-01-08 17:49:49

91. [46979](http://github.com/cms-sw/cmssw/pull/46979){:target="_blank"}  from **@AuroraPerego**: Add additional information to the `SimTrack`s `simulation` created: 2024-12-17 17:02:31 merged: 2025-01-11 21:04:25

92. [46977](http://github.com/cms-sw/cmssw/pull/46977){:target="_blank"}  from **@cquarant**: MTD Geometry - Numbering scheme update `geometry` `reconstruction` `simulation` `upgrade` `tracking` `mtd` created: 2024-12-17 15:41:13 merged: 2024-12-20 09:43:06

93. [46976](http://github.com/cms-sw/cmssw/pull/46976){:target="_blank"}  from **@mmusich**: clean-up unused inclusions in HLT paths in Phase2 HLT menu `hlt` created: 2024-12-17 15:08:51 merged: 2024-12-22 12:23:05

94. [46974](http://github.com/cms-sw/cmssw/pull/46974){:target="_blank"}  from **@iarspider**: [Visualization] Replace fabs with std::abs to fix clang compilation warnings `visualization` created: 2024-12-17 10:49:10 merged: 2024-12-18 07:54:34

95. [46973](http://github.com/cms-sw/cmssw/pull/46973){:target="_blank"}  from **@iarspider**: [Geometry] Use std::abs to fix clang compilation warnings `geometry` created: 2024-12-17 10:47:05 merged: 2024-12-22 16:21:00

96. [46971](http://github.com/cms-sw/cmssw/pull/46971){:target="_blank"}  from **@iarspider**: [DQM] Replace fabs with std::abs to fix clang warnings `dqm` `trk` created: 2024-12-17 10:12:52 merged: 2024-12-19 10:16:15

97. [46970](http://github.com/cms-sw/cmssw/pull/46970){:target="_blank"}  from **@fabiocos**: MTD simulation: update hit classification, extend it to ETL, add last stored ancestor information to TrackInformation `simulation` created: 2024-12-17 10:10:52 merged: 2024-12-19 10:17:12

98. [46969](http://github.com/cms-sw/cmssw/pull/46969){:target="_blank"}  from **@iarspider**: [ALCA] Replace abs with std::abs to fix clang warnings `alca` `trk` created: 2024-12-17 10:07:35 merged: 2025-01-03 13:08:57

99. [46967](http://github.com/cms-sw/cmssw/pull/46967){:target="_blank"}  from **@SegmentLinking**: Improvements to the LST workflows and small general LST fixes `dqm` `reconstruction` `pdmv` `upgrade` `tracking` created: 2024-12-16 22:07:06 merged: 2024-12-21 13:42:05

100. [46962](http://github.com/cms-sw/cmssw/pull/46962){:target="_blank"}  from **@felicepantaleo**: Make HGCAL Validation reproducible `dqm` `simulation` `upgrade` created: 2024-12-16 13:40:05 merged: 2025-01-09 07:25:50

101. [46956](http://github.com/cms-sw/cmssw/pull/46956){:target="_blank"}  from **@cms-trackeralign**: Addition of RelVal to HLT HG Combined PCL workflow `pdmv` `upgrade` created: 2024-12-16 10:02:00 merged: 2024-12-17 16:23:11

102. [46955](http://github.com/cms-sw/cmssw/pull/46955){:target="_blank"}  from **@smuzaffar**: Added CMSSW_FULL_RELEASE_BASE in to valid cmssw import paths `core` created: 2024-12-16 07:28:18 merged: 2024-12-16 18:19:40

103. [46952](http://github.com/cms-sw/cmssw/pull/46952){:target="_blank"}  from **@fwyzard**: Fix `HOST_DEVICE_CONSTANT` macro for AMD GPUs `core` created: 2024-12-15 14:37:16 merged: 2024-12-16 18:18:34

104. [46951](http://github.com/cms-sw/cmssw/pull/46951){:target="_blank"}  from **@dan131riley**: disable -Ofast for MkFitCore/src/IterationConfig.cc due to json.hpp use of IEEE infinities `reconstruction` `tracking` created: 2024-12-15 14:20:42 merged: 2024-12-16 18:16:13

105. [46948](http://github.com/cms-sw/cmssw/pull/46948){:target="_blank"}  from **@vlimant**: simplify flat mixing configuration `operations` `simulation` created: 2024-12-15 11:24:34 merged: 2024-12-17 07:27:05

106. [46945](http://github.com/cms-sw/cmssw/pull/46945){:target="_blank"}  from **@perrotta**: Update MC GTs for Winter25 and 2024 HI/ppRef in autoCond - CMSSW_150X `alca` created: 2024-12-14 15:56:09 merged: 2024-12-16 09:48:22

107. [46944](http://github.com/cms-sw/cmssw/pull/46944){:target="_blank"}  from **@dan131riley**: silence clang vectorization warnings `reconstruction` `tracking` created: 2024-12-14 14:47:49 merged: 2024-12-16 09:49:06

108. [46941](http://github.com/cms-sw/cmssw/pull/46941){:target="_blank"}  from **@Dr15Jones**: Clear memory at end of event in DeepFlavourONNXJetTagsProducer `reconstruction` created: 2024-12-13 19:14:29 merged: 2024-12-16 09:46:02

109. [46938](http://github.com/cms-sw/cmssw/pull/46938){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `14_2_X` (1/N)  [`15_0_X`] `hlt` created: 2024-12-13 16:45:18 merged: 2024-12-16 09:45:42

110. [46936](http://github.com/cms-sw/cmssw/pull/46936){:target="_blank"}  from **@Dr15Jones**: Improved calculation of CRC32 `core` `l1` created: 2024-12-13 15:33:01 merged: 2024-12-16 09:46:43

111. [46935](http://github.com/cms-sw/cmssw/pull/46935){:target="_blank"}  from **@thomreis**: ECAL - Make EcalUncalibRecHitSoAToLegacy a global module `hlt` `reconstruction` `ecal` created: 2024-12-13 15:04:52 merged: 2024-12-16 18:21:13

112. [46934](http://github.com/cms-sw/cmssw/pull/46934){:target="_blank"}  from **@kodolova**: Change ElectronID to the latest in python configuration for JetPlusTrack algoritm `reconstruction` created: 2024-12-13 11:48:18 merged: 2024-12-19 10:16:00

113. [46931](http://github.com/cms-sw/cmssw/pull/46931){:target="_blank"}  from **@martinamalberti**: [MTD Validation]: update to MtdTracksValidation `dqm` created: 2024-12-13 08:52:26 merged: 2024-12-16 09:43:27

114. [46930](http://github.com/cms-sw/cmssw/pull/46930){:target="_blank"}  from **@smuzaffar**: Update clang-tidy test `core` created: 2024-12-13 07:48:16 merged: 2024-12-19 10:14:51

115. [46928](http://github.com/cms-sw/cmssw/pull/46928){:target="_blank"}  from **@Dr15Jones**: Improve L1TRawToDigi `dqm` `l1` created: 2024-12-12 21:37:43 merged: 2025-01-09 11:48:07

116. [46924](http://github.com/cms-sw/cmssw/pull/46924){:target="_blank"}  from **@rdewanje**: Add Electron Tau cross-trigger to the HLT Phase-2 menu `hlt` created: 2024-12-12 11:48:53 merged: 2025-01-03 13:10:03

117. [46923](http://github.com/cms-sw/cmssw/pull/46923){:target="_blank"}  from **@iarspider**: Fix DQM config test: Increase number of sequences to process `dqm` created: 2024-12-12 09:49:26 merged: 2024-12-16 09:50:23

118. [46920](http://github.com/cms-sw/cmssw/pull/46920){:target="_blank"}  from **@mmusich**: add stub of `DeDxCalibration` Payload Inspector `db` created: 2024-12-12 08:39:05 merged: 2024-12-16 09:42:10

119. [46918](http://github.com/cms-sw/cmssw/pull/46918){:target="_blank"}  from **@Dr15Jones**: Fixed memory leak in RegionalMuonGMTUnpacker `l1` created: 2024-12-11 22:52:58 merged: 2024-12-16 09:41:02

120. [46907](http://github.com/cms-sw/cmssw/pull/46907){:target="_blank"}  from **@smuzaffar**: [UBSAN]Fix runtime error for invalid bool value assignment `generators` created: 2024-12-10 12:52:24 merged: 2025-01-09 10:19:05

121. [46897](http://github.com/cms-sw/cmssw/pull/46897){:target="_blank"}  from **@Parsifal-2045**: [NGT] Implement new seeding module for HLT Standalone Muon seeding and streamline HLT L3 Tracker Muon reconstruction  `dqm` `hlt` `l1` `operations` `reconstruction` `pdmv` `upgrade` created: 2024-12-09 13:36:52 merged: 2024-12-20 09:44:10

122. [46881](http://github.com/cms-sw/cmssw/pull/46881){:target="_blank"}  from **@jroloff**: Fixing sherpack location finder for local case `generators` created: 2024-12-05 16:43:25 merged: 2025-01-14 15:47:24

123. [46880](http://github.com/cms-sw/cmssw/pull/46880){:target="_blank"}  from **@AdrianoDee**: Standard 2024(2022,2023) Wfs For PR Testing `pdmv` `upgrade` created: 2024-12-05 15:18:53 merged: 2024-12-19 10:15:28

124. [46859](http://github.com/cms-sw/cmssw/pull/46859){:target="_blank"}  from **@makortel**: Extend `SimpleMemoryCheck` service to report jemalloc and smaps information, and on early termination signal `core` created: 2024-12-03 23:04:57 merged: 2024-12-16 09:41:48

125. [46853](http://github.com/cms-sw/cmssw/pull/46853){:target="_blank"}  from **@AdrianoDee**: Removing CUDA/`gpu` from Pixel code configs and dropping all CUDA wfs `alca` `dqm` `operations` `reconstruction` `pdmv` `upgrade` `heterogeneous` `tracking` `trk` created: 2024-12-03 14:08:55 merged: 2025-01-09 10:20:37

126. [46848](http://github.com/cms-sw/cmssw/pull/46848){:target="_blank"}  from **@Dr15Jones**: Added ModuleEventAllocMonitor Service `core` created: 2024-12-02 19:31:24 merged: 2024-12-16 09:51:23

127. [46809](http://github.com/cms-sw/cmssw/pull/46809){:target="_blank"}  from **@kyungminparkdrums**: Add Et distributions for BC & SC energy ECAL DQM plots `dqm` created: 2024-11-27 10:54:49 merged: 2024-12-20 09:43:18

128. [46750](http://github.com/cms-sw/cmssw/pull/46750){:target="_blank"}  from **@NJManganelli**: Phase 2 L1Trigger GTT subsystem docs `l1` `upgrade` created: 2024-11-20 18:10:57 merged: 2025-01-06 19:00:11

129. [46702](http://github.com/cms-sw/cmssw/pull/46702){:target="_blank"}  from **@patinkaew**: Add support for adding variable-size attributes (std::vector) within objects for NanoAOD `reconstruction` `xpog` created: 2024-11-14 16:46:10 merged: 2025-01-09 07:35:26

130. [46650](http://github.com/cms-sw/cmssw/pull/46650){:target="_blank"}  from **@iarspider**: Update CMS LLVM Analyzers `core` created: 2024-11-11 10:09:38 merged: 2024-12-18 08:52:28

131. [46627](http://github.com/cms-sw/cmssw/pull/46627){:target="_blank"}  from **@pasenov**: trackGenJetAK4 added `xpog` created: 2024-11-07 18:08:46 merged: 2025-01-13 19:06:43

132. [46573](http://github.com/cms-sw/cmssw/pull/46573){:target="_blank"}  from **@hqucms**: [NANO] Implement a check on the number of scale variation weights in GenWeightsTableProducer `xpog` created: 2024-10-31 18:15:46 merged: 2025-01-11 21:03:55

133. [46516](http://github.com/cms-sw/cmssw/pull/46516){:target="_blank"}  from **@patinkaew**: Improve ScoutingNano integration with autoNano `pdmv` `upgrade` `xpog` created: 2024-10-25 12:03:54 merged: 2024-12-18 07:54:43

134. [46453](http://github.com/cms-sw/cmssw/pull/46453){:target="_blank"}  from **@thomreis**: ECAL RecHit producer Alpaka migration `alca` `dqm` `operations` `reconstruction` `pdmv` `db` `upgrade` `heterogeneous` `ecal` created: 2024-10-19 23:17:16 merged: 2025-01-03 13:12:34

135. [46350](http://github.com/cms-sw/cmssw/pull/46350){:target="_blank"}  from **@smuzaffar**: [ML][Clang]clang-analyzer, initialize memory and add protection against `ml` created: 2024-10-11 09:11:39 merged: 2025-01-11 21:03:18

136. [45759](http://github.com/cms-sw/cmssw/pull/45759){:target="_blank"}  from **@sihyunjeon**: quarter core processor for HL-LHC inner tracker developments `daq` `reconstruction` `upgrade` `trk` created: 2024-08-21 08:08:54 merged: 2025-01-06 17:06:06

137. [45665](http://github.com/cms-sw/cmssw/pull/45665){:target="_blank"}  from **@CMS-HGCAL**: HGCal raw data handling: Unpacker, Geometry, Local Reco `alca` `geometry` `reconstruction` `simulation` `db` `upgrade` `heterogeneous` created: 2024-08-07 16:12:05 merged: 2025-01-17 09:35:08

138. [43969](http://github.com/cms-sw/cmssw/pull/43969){:target="_blank"}  from **@makortel**: Add {Copy,Move}ToDeviceCache<T> class templates and moveToDeviceAsync function template `heterogeneous` created: 2024-02-14 22:17:47 merged: 2024-12-18 07:52:56

#### CMSDIST Changes between Tags REL/CMSSW_15_0_0_pre1/el8_amd64_gcc12 and REL/CMSSW_15_0_0_pre2/el8_amd64_gcc12:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_15_0_0_pre1/el8_amd64_gcc12...REL/CMSSW_15_0_0_pre2/el8_amd64_gcc12)



1. [9626](http://github.com/cms-sw/cmsdist/pull/9626){:target="_blank"}  from **@cms-sw**: Bug fix: Only create poison edm cache if the multi-arch dir exists created: 2025-01-17 18:04:47 merged: 2025-01-17 21:40:22

2. [9625](http://github.com/cms-sw/cmsdist/pull/9625){:target="_blank"}  from **@cms-sw**: ONNXRuntime: Update to version 1.20.1 created: 2025-01-17 13:47:17 merged: 2025-01-19 12:25:38

3. [9624](http://github.com/cms-sw/cmsdist/pull/9624){:target="_blank"}  from **@cms-sw**: BuildRules: Fixes for python/Pkg/__init__.py and force linking libs created: 2025-01-17 11:14:40 merged: 2025-01-17 18:03:09

4. [9623](http://github.com/cms-sw/cmsdist/pull/9623){:target="_blank"}  from **@cms-sw**: Update tag for Geometry-TestReference to V00-18-00 created: 2025-01-17 09:50:59 merged: 2025-01-17 09:51:01

5. [9622](http://github.com/cms-sw/cmsdist/pull/9622){:target="_blank"}  from **@cms-sw**: Update tag for RecoTracker-MkFit to V00-15-00 created: 2025-01-17 09:48:22 merged: 2025-01-17 09:48:24

6. [9621](http://github.com/cms-sw/cmsdist/pull/9621){:target="_blank"}  from **@cms-sw**: Revert "Update tag for Geometry-TestReference to V00-17-00" created: 2025-01-17 09:07:52 merged: 2025-01-17 09:53:11

7. [9617](http://github.com/cms-sw/cmsdist/pull/9617){:target="_blank"}  from **@cms-sw**: Buildrule: fixes when extra micro-arch is subset of default microarch created: 2025-01-16 07:16:17 merged: 2025-01-17 08:15:33

8. [9615](http://github.com/cms-sw/cmsdist/pull/9615){:target="_blank"}  from **@mseidel42**: Rivet 4.0.2 and YODA 2.0.2 created: 2025-01-15 10:13:49 merged: 2025-01-17 08:15:15

9. [9614](http://github.com/cms-sw/cmsdist/pull/9614){:target="_blank"}  from **@cms-sw**: Update tag for Validation-HGCalValidation to V00-08-00 created: 2025-01-15 08:50:53 merged: 2025-01-15 08:50:54

10. [9613](http://github.com/cms-sw/cmsdist/pull/9613){:target="_blank"}  from **@mkirsano**: compile HepMC3 interface in the package photospp created: 2025-01-14 09:34:34 merged: 2025-01-17 21:58:54

11. [9607](http://github.com/cms-sw/cmsdist/pull/9607){:target="_blank"}  from **@cms-sw**: Update py3 packages luigi and jinja2 created: 2025-01-10 10:14:52 merged: 2025-01-10 16:40:07

12. [9606](http://github.com/cms-sw/cmsdist/pull/9606){:target="_blank"}  from **@missirol**: update `hls4mlEmulatorExtras` to v1.1.4 created: 2025-01-10 10:07:00 merged: 2025-01-13 15:37:56

13. [9605](http://github.com/cms-sw/cmsdist/pull/9605){:target="_blank"}  from **@slava77**: Update valgrind to 3.24 created: 2025-01-09 22:39:35 merged: 2025-01-10 07:24:16

14. [9599](http://github.com/cms-sw/cmsdist/pull/9599){:target="_blank"}  from **@cms-sw**: Update tag for GeneratorInterface-EvtGenInterface to V02-10-00 created: 2025-01-08 11:15:03 merged: 2025-01-08 11:15:04

15. [9596](http://github.com/cms-sw/cmsdist/pull/9596){:target="_blank"}  from **@belforte**: Update crab-dev.spec to latest created: 2025-01-08 09:06:52 merged: 2025-01-08 11:46:56

16. [9594](http://github.com/cms-sw/cmsdist/pull/9594){:target="_blank"}  from **@nikodemas**: Update monit tools version created: 2025-01-06 12:40:05 merged: 2025-01-07 13:50:42

17. [9590](http://github.com/cms-sw/cmsdist/pull/9590){:target="_blank"}  from **@cms-sw**: Update tag for Geometry-TestReference to V00-17-00 created: 2024-12-20 17:40:36 merged: 2024-12-20 17:40:37

18. [9589](http://github.com/cms-sw/cmsdist/pull/9589){:target="_blank"}  from **@wouf**: Update hydjet2: version 2.4.4 with bugfix on mc code 10333 created: 2024-12-19 14:18:02 merged: 2025-01-06 14:14:47

19. [9588](http://github.com/cms-sw/cmsdist/pull/9588){:target="_blank"}  from **@cms-sw**: added gperf profiler and tcmalloc_and_profiler tools created: 2024-12-19 10:12:17 merged: 2024-12-19 22:08:09

20. [9587](http://github.com/cms-sw/cmsdist/pull/9587){:target="_blank"}  from **@cms-sw**: cmssw-osenv: Restore --show-command behaviour created: 2024-12-19 08:05:52 merged: 2024-12-19 09:06:12

21. [9586](http://github.com/cms-sw/cmsdist/pull/9586){:target="_blank"}  from **@cms-sw**: git: cleanup relocation of removed file created: 2024-12-18 14:30:41 merged: 2024-12-18 20:56:40

22. [9584](http://github.com/cms-sw/cmsdist/pull/9584){:target="_blank"}  from **@cms-sw**: [BuildRules] For PR test: drop additional microarch release/externals lib/bindirs created: 2024-12-17 20:03:28 merged: 2024-12-18 09:22:21

23. [9583](http://github.com/cms-sw/cmsdist/pull/9583){:target="_blank"}  from **@cms-sw**: [BuildRules] patch release build fix: use realpath for import python module created: 2024-12-17 15:12:31 merged: 2024-12-17 19:01:13

24. [9575](http://github.com/cms-sw/cmsdist/pull/9575){:target="_blank"}  from **@cms-sw**: [BuildRule]Fix for code checks created: 2024-12-13 08:20:41 merged: 2024-12-17 15:09:53

25. [9569](http://github.com/cms-sw/cmsdist/pull/9569){:target="_blank"}  from **@cms-sw**: Added git-lfs and update git to version 2.47.1 created: 2024-12-11 15:51:59 merged: 2024-12-17 10:53:46

26. [9541](http://github.com/cms-sw/cmsdist/pull/9541){:target="_blank"}  from **@cms-sw**: Make ROOT 6.32 as default for 15.0.X created: 2024-11-28 08:46:41 merged: 2024-12-16 09:54:51
