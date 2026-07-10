---
layout: post
rel_link:  "20_1_0_pre1"
title:  "CMSSW_20_1_0_pre1"
date:   2026-07-08 18:43:03
categories: cmssw
relmajor: 20
relminor: 1
relsubminor: 0
relpre: _pre1
---

# CMSSW_20_1_0_pre1
#### Changes since CMSSW_20_0_0_pre1:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_20_0_0_pre1...CMSSW_20_1_0_pre1)



1. [51434](http://github.com/cms-sw/cmssw/pull/51434){:target="_blank"}  from **@ericcano**: Fixes helper templated overloads for `watch{Pre,Post}{Open,Close}OutputFiles()` `core` created: 2026-07-07 14:17:11 merged: 2026-07-08 05:26:12

2. [51432](http://github.com/cms-sw/cmssw/pull/51432){:target="_blank"}  from **@smuzaffar**: Fix needed for change in root io protocol root-project/root#22744 `core` created: 2026-07-07 09:58:21 merged: 2026-07-08 05:29:07

3. [51431](http://github.com/cms-sw/cmssw/pull/51431){:target="_blank"}  from **@mkirsano**: Fix order of actions in HepMC3 Pythia8 EGun `generators` created: 2026-07-07 08:13:12 merged: 2026-07-08 05:26:08

4. [51428](http://github.com/cms-sw/cmssw/pull/51428){:target="_blank"}  from **@ericcano**: Fix wrong signal tagging in HDF5ProductResolver `db` created: 2026-07-06 19:29:09 merged: 2026-07-08 05:28:47

5. [51412](http://github.com/cms-sw/cmssw/pull/51412){:target="_blank"}  from **@felicepantaleo**: RecoHGCal/TICL: dedicated muon interpretation for TICL candidates `reconstruction` created: 2026-07-05 08:05:21 merged: 2026-07-08 05:26:40

6. [51410](http://github.com/cms-sw/cmssw/pull/51410){:target="_blank"}  from **@cms-ngt-hlt**: fix bug in `hltMkFitEventOfHits`, do not use the offline beamspot at HLT `hlt` created: 2026-07-04 09:54:39 merged: 2026-07-05 06:56:46

7. [51409](http://github.com/cms-sw/cmssw/pull/51409){:target="_blank"}  from **@smuzaffar**: fix for UBSAN build errors, GCC constexpr incompatibility `simulation` created: 2026-07-04 08:40:59 merged: 2026-07-05 06:56:59

8. [51408](http://github.com/cms-sw/cmssw/pull/51408){:target="_blank"}  from **@cms-ngt-hlt**: Add `passThrough` option to `RecoTrackSelectorBase` for `ngtScouting` HLT tracks `dqm` `hlt` `reconstruction` `tracking` created: 2026-07-04 07:30:54 merged: 2026-07-06 17:29:44

9. [51399](http://github.com/cms-sw/cmssw/pull/51399){:target="_blank"}  from **@felicepantaleo**: Make GPU pixel clustering and CA fishbone reproducible `reconstruction` `tracking` `trk` created: 2026-07-03 10:12:52 merged: 2026-07-07 07:35:13

10. [51391](http://github.com/cms-sw/cmssw/pull/51391){:target="_blank"}  from **@mmusich**: Re-activation of more file-based unit tests in the `Alignment` area `alca` `reconstruction` `tracking` `trk` created: 2026-07-02 06:45:42 merged: 2026-07-04 05:47:58

11. [51390](http://github.com/cms-sw/cmssw/pull/51390){:target="_blank"}  from **@felicepantaleo**: do not emit pixel tracks with NaN parameters `reconstruction` `tracking` created: 2026-07-02 05:06:04 merged: 2026-07-07 15:42:52

12. [51389](http://github.com/cms-sw/cmssw/pull/51389){:target="_blank"}  from **@Dr15Jones**: Remove support for non-concurrent EventSetupRecordIntervalFinders  `core` created: 2026-07-01 21:43:59 merged: 2026-07-07 07:36:48

13. [51388](http://github.com/cms-sw/cmssw/pull/51388){:target="_blank"}  from **@Dr15Jones**: Made CTPPSCompositeESSource a concurrent Finder `alca` created: 2026-07-01 18:08:51 merged: 2026-07-03 07:56:02

14. [51385](http://github.com/cms-sw/cmssw/pull/51385){:target="_blank"}  from **@bsunanda**: Phase2-hgx368A: Modify the debug statements in HGCScintillatorDetId to make them simpler and user friendly `simulation` created: 2026-07-01 09:04:38 merged: 2026-07-03 07:56:56

15. [51382](http://github.com/cms-sw/cmssw/pull/51382){:target="_blank"}  from **@bsunanda**: Phase2-hgx368 Modify the debug statements in HGCSiliconDetId to make them simpler and user friendly `simulation` created: 2026-07-01 03:53:18 merged: 2026-07-03 08:04:33

16. [51379](http://github.com/cms-sw/cmssw/pull/51379){:target="_blank"}  from **@mroguljic**: Store SiPixelDigi collections in AlCaRecos that store pixel clusters `alca` `trk` created: 2026-06-30 14:07:41 merged: 2026-07-03 07:57:13

17. [51376](http://github.com/cms-sw/cmssw/pull/51376){:target="_blank"}  from **@mmusich**: [NGT] first implementation of `TrigObjP4FlatTableProducer` `hlt` `pdmv` created: 2026-06-30 12:28:56 merged: 2026-07-07 07:35:25

18. [51371](http://github.com/cms-sw/cmssw/pull/51371){:target="_blank"}  from **@Dr15Jones**: Remove excessive recursion from InputSource::nextitemType_ `core` created: 2026-06-29 15:45:39 merged: 2026-07-03 07:58:48

19. [51370](http://github.com/cms-sw/cmssw/pull/51370){:target="_blank"}  from **@mmusich**: Produce more TkAl ALCARECO flavours in phase-2 by default `alca` `pdmv` created: 2026-06-29 15:04:21 merged: 2026-07-03 07:58:06

20. [51359](http://github.com/cms-sw/cmssw/pull/51359){:target="_blank"}  from **@fabiocos**: MTD reconstruction and validation: fix FTLHit methods, add optional test printouts in Validation code `dqm` `reconstruction` created: 2026-06-29 10:29:46 merged: 2026-07-03 07:56:41

21. [51352](http://github.com/cms-sw/cmssw/pull/51352){:target="_blank"}  from **@mmusich**:  More unit tests fixes for TkAl offline validation tools for Phase-2 `alca` `trk` created: 2026-06-29 07:34:13 merged: 2026-07-03 07:56:27

22. [51351](http://github.com/cms-sw/cmssw/pull/51351){:target="_blank"}  from **@felicepantaleo**: pyTICL configuration framework for TICL `reconstruction` created: 2026-06-28 18:17:26 merged: 2026-07-06 07:50:01

23. [51349](http://github.com/cms-sw/cmssw/pull/51349){:target="_blank"}  from **@mmusich**: `convertToRaw`: Handle missing `CMSSW_FULL_RELEASE_BASE` environment variable `hlt` created: 2026-06-28 12:20:06 merged: 2026-06-29 05:01:06

24. [51346](http://github.com/cms-sw/cmssw/pull/51346){:target="_blank"}  from **@felicepantaleo**: RecoHGCal/TICL: coding-rules compliance  `reconstruction` created: 2026-06-28 07:09:33 merged: 2026-06-30 07:44:57

25. [51345](http://github.com/cms-sw/cmssw/pull/51345){:target="_blank"}  from **@felicepantaleo**: HLTrigger/Configuration: fix mis-wired L1-seeded TICL Recovery sequence `hlt` created: 2026-06-28 06:12:55 merged: 2026-06-30 04:58:44

26. [51344](http://github.com/cms-sw/cmssw/pull/51344){:target="_blank"}  from **@felicepantaleo**: RecoHGCal/TICL: seeding, layer-tile and barrel config fixes `reconstruction` created: 2026-06-28 06:11:31 merged: 2026-06-30 04:59:23

27. [51343](http://github.com/cms-sw/cmssw/pull/51343){:target="_blank"}  from **@felicepantaleo**: RecoHGCal/TICL: TICLDumper fixes `reconstruction` created: 2026-06-28 06:09:46 merged: 2026-06-30 05:05:43

28. [51342](http://github.com/cms-sw/cmssw/pull/51342){:target="_blank"}  from **@felicepantaleo**: RecoHGCal/TICL: linking and inference fixes `reconstruction` created: 2026-06-28 06:08:58 merged: 2026-06-30 07:46:16

29. [51341](http://github.com/cms-sw/cmssw/pull/51341){:target="_blank"}  from **@felicepantaleo**: RecoHGCal/TICL: avoid NaN energies in PF and superclustering `reconstruction` created: 2026-06-28 06:07:30 merged: 2026-06-30 04:23:17

30. [51340](http://github.com/cms-sw/cmssw/pull/51340){:target="_blank"}  from **@felicepantaleo**: RecoHGCal/TICL: pattern-recognition correctness fixes `reconstruction` created: 2026-06-28 06:06:42 merged: 2026-06-30 04:58:13

31. [51338](http://github.com/cms-sw/cmssw/pull/51338){:target="_blank"}  from **@mmusich**: `compareMemoryProfiles`: support just one file in input `hlt` created: 2026-06-27 13:24:43 merged: 2026-06-28 08:46:05

32. [51335](http://github.com/cms-sw/cmssw/pull/51335){:target="_blank"}  from **@Dr15Jones**: Remove delayed call to EventSetupsController::finishConfiguration `core` created: 2026-06-26 18:46:07 merged: 2026-06-28 08:43:28

33. [51333](http://github.com/cms-sw/cmssw/pull/51333){:target="_blank"}  from **@slava77**: LST: set T5 occupancy threshold at 100K `hlt` `reconstruction` `tracking` created: 2026-06-26 17:15:38 merged: 2026-07-07 15:47:59

34. [51332](http://github.com/cms-sw/cmssw/pull/51332){:target="_blank"}  from **@Dr15Jones**: non concurrent ESSources may only be in 1 thread jobs `core` created: 2026-06-26 14:32:56 merged: 2026-06-30 07:44:20

35. [51331](http://github.com/cms-sw/cmssw/pull/51331){:target="_blank"}  from **@AdrianoDee**: Reclycing GEN-SIM Only for the Default Run4 Geometry `pdmv` created: 2026-06-26 13:51:21 merged: 2026-06-28 08:42:49

36. [51330](http://github.com/cms-sw/cmssw/pull/51330){:target="_blank"}  from **@eyigitba**: [L1T] Adding a reduced data format: phase2_l1scout for use in the Spring24 MC Campaign (Phase 2) `l1` `operations` created: 2026-06-26 07:36:06 merged: 2026-06-28 08:45:45

37. [51329](http://github.com/cms-sw/cmssw/pull/51329){:target="_blank"}  from **@waredjeb**: Split CLUE distance parameters `hlt` `reconstruction` created: 2026-06-26 07:34:53 merged: 2026-06-30 04:19:06

38. [51324](http://github.com/cms-sw/cmssw/pull/51324){:target="_blank"}  from **@bsunanda**: Phase2-hgx367L1 Correct a bug in HGCalGeomParameters.cc to make it work correctly for the ColdBox mode of HGCal `geometry` created: 2026-06-26 04:31:21 merged: 2026-06-28 08:44:07

39. [51323](http://github.com/cms-sw/cmssw/pull/51323){:target="_blank"}  from **@bsunanda**: Phase2-hgx367M1 Correct the testing code for finding neghbours of HGCal silicon cells `geometry` created: 2026-06-26 04:25:18 merged: 2026-06-28 08:43:14

40. [51321](http://github.com/cms-sw/cmssw/pull/51321){:target="_blank"}  from **@fwyzard**: Extend convertToRaw to support streamer files `hlt` created: 2026-06-25 15:42:55 merged: 2026-06-28 08:43:54

41. [51318](http://github.com/cms-sw/cmssw/pull/51318){:target="_blank"}  from **@Annnnya**: Fix edmMpiConfigSplitter logic when grouping with dublicated modules `heterogeneous` created: 2026-06-25 12:42:49 merged: 2026-06-26 06:36:52

42. [51312](http://github.com/cms-sw/cmssw/pull/51312){:target="_blank"}  from **@kpedro88**: Fix incorrect loop and memory leak in Phase 2 SIM code `simulation` created: 2026-06-24 22:33:59 merged: 2026-06-25 16:51:17

43. [51310](http://github.com/cms-sw/cmssw/pull/51310){:target="_blank"}  from **@Moanwar**: Adding GSFtracks Indices in SimTICLCandidate `reconstruction` created: 2026-06-24 18:05:57 merged: 2026-07-03 07:58:26

44. [51307](http://github.com/cms-sw/cmssw/pull/51307){:target="_blank"}  from **@TomasKello**: Re-enable unit tests for TkAl offline validation tools for Phase-2 `alca` `trk` created: 2026-06-24 11:50:09 merged: 2026-06-28 08:43:03

45. [51306](http://github.com/cms-sw/cmssw/pull/51306){:target="_blank"}  from **@mmusich**: add a unit test for `hltDiff` `hlt` created: 2026-06-24 10:56:36 merged: 2026-06-24 16:56:21

46. [51295](http://github.com/cms-sw/cmssw/pull/51295){:target="_blank"}  from **@mmusich**: add a test for coverage of configuration validation of plugins used at HLT `hlt` created: 2026-06-23 15:23:09 merged: 2026-06-24 11:13:38

47. [51283](http://github.com/cms-sw/cmssw/pull/51283){:target="_blank"}  from **@michael-pitt**: Update GenProton NanoAOD acceptance for Run 3 `xpog` created: 2026-06-23 06:49:09 merged: 2026-06-24 16:56:46

48. [51280](http://github.com/cms-sw/cmssw/pull/51280){:target="_blank"}  from **@Dr15Jones**: Avoid race condition when conditionally starting Lumi begin stream `core` created: 2026-06-22 19:34:28 merged: 2026-06-30 04:17:14

49. [51279](http://github.com/cms-sw/cmssw/pull/51279){:target="_blank"}  from **@martinamalberti**: [MTD]: BTL readout mapping - first implementation in CondFormats `alca` `db` `geometry` `reconstruction` created: 2026-06-22 16:16:18 merged: 2026-07-05 06:57:36

50. [51276](http://github.com/cms-sw/cmssw/pull/51276){:target="_blank"}  from **@mmusich**: re-organization of HGCal local reconstruction HLT products, add unseeded EGamma GSF tracks to FEVTHLT `operations` `reconstruction` created: 2026-06-22 12:15:55 merged: 2026-06-24 11:15:40

51. [51275](http://github.com/cms-sw/cmssw/pull/51275){:target="_blank"}  from **@namapane**: Fix tree ownership issue in NanoAODTools `xpog` created: 2026-06-22 08:54:33 merged: 2026-06-24 11:14:32

52. [51274](http://github.com/cms-sw/cmssw/pull/51274){:target="_blank"}  from **@smuzaffar**: DQM/Physics: clang warning fixes for unused variables `dqm` created: 2026-06-22 06:35:20 merged: 2026-06-24 11:14:58

53. [51273](http://github.com/cms-sw/cmssw/pull/51273){:target="_blank"}  from **@mmusich**: Provide configuration descriptions to MTD local reconstruction modules `reconstruction` created: 2026-06-21 17:11:56 merged: 2026-06-23 07:36:36

54. [51266](http://github.com/cms-sw/cmssw/pull/51266){:target="_blank"}  from **@smuzaffar**: [TrackerGeometry]Fix nvcc warings: type qualifier on return type is meaningless `geometry` `trk` created: 2026-06-19 12:59:53 merged: 2026-06-20 06:10:10

55. [51264](http://github.com/cms-sw/cmssw/pull/51264){:target="_blank"}  from **@bsunanda**: Phase2-hgx367K Update the testing code for neighour searches of HGCal silicon cells `geometry` created: 2026-06-19 07:00:52 merged: 2026-06-20 06:09:23

56. [51262](http://github.com/cms-sw/cmssw/pull/51262){:target="_blank"}  from **@smorovic**: [DAQ] update DTH tests and drop file locking `daq` created: 2026-06-18 20:25:51 merged: 2026-06-20 06:11:17

57. [51261](http://github.com/cms-sw/cmssw/pull/51261){:target="_blank"}  from **@slava77**: LST updates to handle "pixel tracks" with OT hits `hlt` `reconstruction` `tracking` created: 2026-06-18 15:38:19 merged: 2026-06-20 06:10:22

58. [51260](http://github.com/cms-sw/cmssw/pull/51260){:target="_blank"}  from **@mmusich**: Clean-up of Phase-2 HLT menus `hlt` created: 2026-06-18 14:18:17 merged: 2026-06-21 17:56:29

59. [51254](http://github.com/cms-sw/cmssw/pull/51254){:target="_blank"}  from **@raoatifshad**: [WarningFix]: Alignment/OfflineValidation- Fix static thread-safety w `alca` `trk` created: 2026-06-18 11:46:22 merged: 2026-06-20 06:11:41

60. [51249](http://github.com/cms-sw/cmssw/pull/51249){:target="_blank"}  from **@bsunanda**: Phase2-hgx367H Update the new scenario D128 to use I21 for MTD instead of I22 `geometry` created: 2026-06-18 08:09:40 merged: 2026-06-18 20:38:37

61. [51246](http://github.com/cms-sw/cmssw/pull/51246){:target="_blank"}  from **@mmusich**: `runHLTTiming`: improve logging of error keywords found in benchmark jobs `hlt` created: 2026-06-17 21:40:21 merged: 2026-06-18 08:42:06

62. [51242](http://github.com/cms-sw/cmssw/pull/51242){:target="_blank"}  from **@waredjeb**: Add HGCAL/TICL NanoAOD for offline `hlt` `pdmv` `reconstruction` `xpog` created: 2026-06-17 12:04:50 merged: 2026-07-06 17:30:21

63. [51237](http://github.com/cms-sw/cmssw/pull/51237){:target="_blank"}  from **@mmusich**: Follow-up to MTD reconstruction at HLT `dqm` `operations` `reconstruction` `simulation` created: 2026-06-17 07:31:43 merged: 2026-06-23 07:36:29

64. [51232](http://github.com/cms-sw/cmssw/pull/51232){:target="_blank"}  from **@Dr15Jones**: Removed FWLiteESSource `analysis` created: 2026-06-16 18:56:26 merged: 2026-06-17 09:00:02

65. [51231](http://github.com/cms-sw/cmssw/pull/51231){:target="_blank"}  from **@Dr15Jones**: Move to EventSetupRecordInfiniteIntervalFinder `alca` `core` `db` `geometry` `ml` `reconstruction` `simulation` `tracking` `trk` created: 2026-06-16 18:24:01 merged: 2026-06-19 05:01:24

66. [51230](http://github.com/cms-sw/cmssw/pull/51230){:target="_blank"}  from **@dan131riley**: Protect isMergeable() from types with no dictionary `core` created: 2026-06-16 17:29:02 merged: 2026-06-17 09:00:31

67. [51228](http://github.com/cms-sw/cmssw/pull/51228){:target="_blank"}  from **@makortel**: Fix SciTag values `core` created: 2026-06-16 13:52:12 merged: 2026-06-17 08:59:23

68. [51226](http://github.com/cms-sw/cmssw/pull/51226){:target="_blank"}  from **@raoatifshad**: [WarningFix] Alignment/Geners: remove unnecessary const_cast/static-l `alca` created: 2026-06-16 12:15:53 merged: 2026-06-17 08:58:07

69. [51225](http://github.com/cms-sw/cmssw/pull/51225){:target="_blank"}  from **@AdrianoDee**: Disabling GEN-SIM recycling for pre Run4 wfs `pdmv` created: 2026-06-16 09:54:31 merged: 2026-06-17 18:02:11

70. [51224](http://github.com/cms-sw/cmssw/pull/51224){:target="_blank"}  from **@suchandradutta**: Bug fix in Phase2 Tracker Digitizer in cross talk calculation  `simulation` `trk` created: 2026-06-16 08:09:07 merged: 2026-06-19 04:55:19

71. [51221](http://github.com/cms-sw/cmssw/pull/51221){:target="_blank"}  from **@kpedro88**: Remove unnecessary use of imp `alca` `dqm` `geometry` `trk` created: 2026-06-15 20:30:17 merged: 2026-06-17 08:57:55

72. [51220](http://github.com/cms-sw/cmssw/pull/51220){:target="_blank"}  from **@Dr15Jones**: Make CalibPPS ESSources concurrent capable `alca` created: 2026-06-15 19:45:03 merged: 2026-06-20 06:11:06

73. [51219](http://github.com/cms-sw/cmssw/pull/51219){:target="_blank"}  from **@Dr15Jones**: Make Lumi ESSources concurrent capable `reconstruction` created: 2026-06-15 15:58:11 merged: 2026-06-17 08:57:42

74. [51217](http://github.com/cms-sw/cmssw/pull/51217){:target="_blank"}  from **@waredjeb**: Fix TICLDumper Configuration `reconstruction` created: 2026-06-15 14:01:33 merged: 2026-06-16 05:05:03

75. [51216](http://github.com/cms-sw/cmssw/pull/51216){:target="_blank"}  from **@cms-tsg-storm**: re-activate Phase2 HLT timing script, using samples produced in `CMSSW_20_0_0_pre1` `hlt` created: 2026-06-15 13:29:27 merged: 2026-06-16 05:04:23

76. [51215](http://github.com/cms-sw/cmssw/pull/51215){:target="_blank"}  from **@raoatifshad**: [WarningFix]:CondCore/CondHDF5ESSource- avoids dead store in zstd dec `db` created: 2026-06-15 11:08:16 merged: 2026-06-17 20:44:57

77. [51211](http://github.com/cms-sw/cmssw/pull/51211){:target="_blank"}  from **@fwyzard**: Update CUDAService for CUDA 13.x `heterogeneous` created: 2026-06-13 12:01:13 merged: 2026-06-14 06:06:00

78. [51208](http://github.com/cms-sw/cmssw/pull/51208){:target="_blank"}  from **@raoatifshad**: [WarningFix]:CalibCalorimetry/EcalTrivialCondModules-Check fgets() re `alca` created: 2026-06-12 14:31:34 merged: 2026-06-14 06:15:10

79. [51203](http://github.com/cms-sw/cmssw/pull/51203){:target="_blank"}  from **@smuzaffar**: PyTorch: Added rocm unit tests `ml` created: 2026-06-12 10:34:08 merged: 2026-06-17 08:59:44

80. [51202](http://github.com/cms-sw/cmssw/pull/51202){:target="_blank"}  from **@hatakeyamak**: PF validation on-the-fly update, MLPF support `dqm` `pf` created: 2026-06-11 22:36:01 merged: 2026-06-15 08:53:41

81. [51201](http://github.com/cms-sw/cmssw/pull/51201){:target="_blank"}  from **@alexstrel**: Corrected template parameters for Alpaka PF MD Clusterizer Epilogue kernels   `heterogeneous` `pf` `reconstruction` created: 2026-06-11 14:56:15 merged: 2026-06-25 08:18:57

82. [51199](http://github.com/cms-sw/cmssw/pull/51199){:target="_blank"}  from **@AdrianoDee**: New Inputs For Run4 D121 Workflows `pdmv` created: 2026-06-11 12:00:57 merged: 2026-06-15 16:17:03

83. [51198](http://github.com/cms-sw/cmssw/pull/51198){:target="_blank"}  from **@cms-ngt-hlt**: [NGT] Bug fix for tau prevalidation sequence in Run2 workflow `dqm` `simulation` created: 2026-06-11 09:24:28 merged: 2026-06-12 20:09:06

84. [51193](http://github.com/cms-sw/cmssw/pull/51193){:target="_blank"}  from **@makortel**: Include reduced ProcessingHistory ID to `DiagStreamerFile` checks `core` created: 2026-06-10 21:09:52 merged: 2026-06-12 15:03:06

85. [51188](http://github.com/cms-sw/cmssw/pull/51188){:target="_blank"}  from **@cms-tsg-storm**: complete disabling of MC based TSG integration tests in IBs `hlt` created: 2026-06-10 17:01:16 merged: 2026-06-10 20:37:27

86. [51187](http://github.com/cms-sw/cmssw/pull/51187){:target="_blank"}  from **@Dr15Jones**: Add test for Pythia8ConcurrentHadronizerFilter `generators` created: 2026-06-10 16:07:08 merged: 2026-06-17 09:00:14

87. [51186](http://github.com/cms-sw/cmssw/pull/51186){:target="_blank"}  from **@cms-ngt-hlt**: Minor adjustments for `ngtScouting`-modified ph2 HLT menus `hlt` created: 2026-06-10 15:33:02 merged: 2026-06-11 11:01:31

88. [51183](http://github.com/cms-sw/cmssw/pull/51183){:target="_blank"}  from **@smuzaffar**: Drop Geometry/CommonDetUnit package `geometry` created: 2026-06-10 14:42:04 merged: 2026-06-17 08:58:42

89. [51182](http://github.com/cms-sw/cmssw/pull/51182){:target="_blank"}  from **@Dr15Jones**: Mark XMLIdealGeometryESSource as concurrent capable `geometry` created: 2026-06-10 14:13:26 merged: 2026-06-14 06:14:00

90. [51181](http://github.com/cms-sw/cmssw/pull/51181){:target="_blank"}  from **@Dr15Jones**: Mark SiPhase2BadStripConfigurableFakeESSource as concurrent `alca` `trk` created: 2026-06-10 14:06:42 merged: 2026-06-11 06:16:44

91. [51178](http://github.com/cms-sw/cmssw/pull/51178){:target="_blank"}  from **@bsunanda**: Phase2-hgx367A Add the changes suggested by Vadim with one example SimG4CMS/Calo/test/python/runHGCalColdbox_cfg.py `geometry` `simulation` created: 2026-06-10 10:53:10 merged: 2026-06-14 06:14:35

92. [51177](http://github.com/cms-sw/cmssw/pull/51177){:target="_blank"}  from **@Dr15Jones**: Mark CSCL1TPLookupTableEP as concurrent capable `alca` created: 2026-06-09 20:25:07 merged: 2026-06-10 13:58:29

93. [51176](http://github.com/cms-sw/cmssw/pull/51176){:target="_blank"}  from **@Dr15Jones**: Mark PPSPixelTopologyESSource as concurrent capable `alca` created: 2026-06-09 20:19:22 merged: 2026-06-10 13:58:59

94. [51175](http://github.com/cms-sw/cmssw/pull/51175){:target="_blank"}  from **@Dr15Jones**: Mark Hcal ESSources as concurrent capable `alca` created: 2026-06-09 20:11:22 merged: 2026-06-10 14:00:29

95. [51174](http://github.com/cms-sw/cmssw/pull/51174){:target="_blank"}  from **@Dr15Jones**: Mark HepPDTESSource as concurrent capable `simulation` created: 2026-06-09 19:58:43 merged: 2026-06-10 14:00:36

96. [51173](http://github.com/cms-sw/cmssw/pull/51173){:target="_blank"}  from **@Dr15Jones**: Mark EmptyESSource as concurrent capable `core` created: 2026-06-09 19:41:41 merged: 2026-06-10 14:01:28

97. [51170](http://github.com/cms-sw/cmssw/pull/51170){:target="_blank"}  from **@cms-ngt-hlt**: Implement MIP Timing Detector reconstruction sequence for Phase-2 HLT  `dqm` `hlt` `operations` `pdmv` created: 2026-06-09 17:28:16 merged: 2026-06-15 08:54:15

98. [51168](http://github.com/cms-sw/cmssw/pull/51168){:target="_blank"}  from **@bfonta**: Fix separate option in HGCAL validation `dqm` `tracking` created: 2026-06-09 16:57:36 merged: 2026-06-12 20:09:30

99. [51159](http://github.com/cms-sw/cmssw/pull/51159){:target="_blank"}  from **@makortel**: Remove Run 3 PU GPU workflows `pdmv` created: 2026-06-09 15:11:13 merged: 2026-06-17 18:01:49

100. [51158](http://github.com/cms-sw/cmssw/pull/51158){:target="_blank"}  from **@tomalin**: Fix bug in P2 Tracker cluster EDAnalyzer `reconstruction` `trk` created: 2026-06-09 15:09:19 merged: 2026-06-10 15:42:54

101. [51156](http://github.com/cms-sw/cmssw/pull/51156){:target="_blank"}  from **@Dr15Jones**: [bugfix] Must use streamer when writing CSCSegment to RNTuple `reconstruction` created: 2026-06-09 15:00:51 merged: 2026-06-10 14:01:49

102. [51155](http://github.com/cms-sw/cmssw/pull/51155){:target="_blank"}  from **@raoatifshad**: [WarningFix]CommonTools/CandUtils: remove unnecessary const_cast `reconstruction` created: 2026-06-09 12:56:55 merged: 2026-06-10 15:10:04

103. [51153](http://github.com/cms-sw/cmssw/pull/51153){:target="_blank"}  from **@raoatifshad**: [WarningFix]:unused static QieCalibMap cache from HcalPedestalAnalysi `alca` created: 2026-06-09 11:24:10 merged: 2026-06-11 06:27:30

104. [51144](http://github.com/cms-sw/cmssw/pull/51144){:target="_blank"}  from **@felicepantaleo**: HGCAL Cassette test stand  `reconstruction` created: 2026-06-08 13:26:11 merged: 2026-06-09 14:00:42

105. [51142](http://github.com/cms-sw/cmssw/pull/51142){:target="_blank"}  from **@SegmentLinking**: Simplification in the definition of Phase 2 HLT workflows `pdmv` created: 2026-06-08 12:10:30 merged: 2026-06-12 06:56:28

106. [51141](http://github.com/cms-sw/cmssw/pull/51141){:target="_blank"}  from **@cms-tsg-storm**: Disable MC-based TSG tests in 20_1_X `hlt` created: 2026-06-08 11:40:51 merged: 2026-06-09 10:24:47

107. [51140](http://github.com/cms-sw/cmssw/pull/51140){:target="_blank"}  from **@SegmentLinking**: mkfit for LST-seeded in offline phase-2 `dqm` `pdmv` `reconstruction` `tracking` created: 2026-06-08 11:19:12 merged: 2026-06-30 04:16:59

108. [51128](http://github.com/cms-sw/cmssw/pull/51128){:target="_blank"}  from **@slava77**: remove PixelTriplets_InvPrbl_prec from automatic unit tests `reconstruction` `tracking` created: 2026-06-05 17:18:09 merged: 2026-06-09 20:35:26

109. [51127](http://github.com/cms-sw/cmssw/pull/51127){:target="_blank"}  from **@fabiocos**: MTD Geometry: clean compiler warnings  `geometry` `simulation` created: 2026-06-05 15:03:11 merged: 2026-06-14 06:06:06

110. [51125](http://github.com/cms-sw/cmssw/pull/51125){:target="_blank"}  from **@raoatifshad**: Alignment/MuonAlignmentAlgorithms: fix static analyzer warnings `alca` created: 2026-06-04 11:28:22 merged: 2026-06-10 14:13:40

111. [51123](http://github.com/cms-sw/cmssw/pull/51123){:target="_blank"}  from **@tomalin**: Make unpacking RAW data easier for newcomers `daq` created: 2026-06-03 12:49:13 merged: 2026-06-10 14:12:05

112. [51122](http://github.com/cms-sw/cmssw/pull/51122){:target="_blank"}  from **@raoatifshad**: Fix static analyzer warnings in ESHandle and bloom filter generator `core` created: 2026-06-03 12:24:02 merged: 2026-06-10 20:38:38

113. [51118](http://github.com/cms-sw/cmssw/pull/51118){:target="_blank"}  from **@makortel**: Allow `cms::Exception::format()` to be chained, and move `RunLumiEventAnalyzer` to `FWCore/TestModules` `core` created: 2026-06-02 20:32:46 merged: 2026-06-10 15:01:10

114. [51117](http://github.com/cms-sw/cmssw/pull/51117){:target="_blank"}  from **@kpedro88**: remove Transform3DPJ from FastSim `fastsim` created: 2026-06-02 20:27:23 merged: 2026-06-10 20:37:03

115. [51101](http://github.com/cms-sw/cmssw/pull/51101){:target="_blank"}  from **@sakura-ngt**: [NGT] Improvements to `ScoutingTrackMonitor` `dqm` `hlt` `tracking` `xpog` created: 2026-06-01 07:14:02 merged: 2026-06-10 20:36:32

116. [51095](http://github.com/cms-sw/cmssw/pull/51095){:target="_blank"}  from **@gartung**: Perftools/AllocMonitor: add script to generate module event alloc monitor circles json file. `core` created: 2026-05-29 17:41:19 merged: 2026-06-10 15:46:36

117. [51092](http://github.com/cms-sw/cmssw/pull/51092){:target="_blank"}  from **@cms-ngt-hlt**: [NGT] Implement new strategy for Tau Validation at HLT and RECO in Phase-2 `dqm` `operations` `simulation` created: 2026-05-29 12:44:45 merged: 2026-06-10 17:30:08

118. [51086](http://github.com/cms-sw/cmssw/pull/51086){:target="_blank"}  from **@CMSTrackerDPG**: Fixed value of `lastPixels` which triggered warnings in `PixelClustering.h' `reconstruction` `trk` created: 2026-05-28 22:33:48 merged: 2026-06-09 20:35:04

119. [51080](http://github.com/cms-sw/cmssw/pull/51080){:target="_blank"}  from **@bsunanda**: Phase2-hgx367 Try to create a scenario with T37, C27, N17, I22, F9 `geometry` `operations` `pdmv` created: 2026-05-28 11:04:24 merged: 2026-06-11 13:08:35

120. [51078](http://github.com/cms-sw/cmssw/pull/51078){:target="_blank"}  from **@ljuckett**: [DQM][Validation] Phase2 - Update test scripts and add missing histograms to DQM/Validation sequence `dqm` `trk` created: 2026-05-28 10:22:37 merged: 2026-06-10 20:36:18

121. [51077](http://github.com/cms-sw/cmssw/pull/51077){:target="_blank"}  from **@smuzaffar**: [XPOG] Drop Geometry/CommonDetUnit package `xpog` created: 2026-05-28 10:02:39 merged: 2026-06-10 15:49:16

122. [51065](http://github.com/cms-sw/cmssw/pull/51065){:target="_blank"}  from **@smuzaffar**: [RECONSTRUCTION-XPOG] Drop Geometry/CommonDetUnit package `reconstruction` `xpog` created: 2026-05-28 10:00:13 merged: 2026-06-10 15:44:39

123. [51053](http://github.com/cms-sw/cmssw/pull/51053){:target="_blank"}  from **@fnenna**: ME0 integration in PFMuon algorithm `hlt` `reconstruction` created: 2026-05-27 15:31:48 merged: 2026-06-27 08:15:51

124. [50955](http://github.com/cms-sw/cmssw/pull/50955){:target="_blank"}  from **@shimashimarin**: update Sherpack name with SCRAM_ARCH and CMSSW_VERSION `generators` created: 2026-05-15 22:31:03 merged: 2026-06-17 08:57:27

125. [50916](http://github.com/cms-sw/cmssw/pull/50916){:target="_blank"}  from **@dan131riley**: BuildFile dependency cleaning, 1st round `alca` `analysis` `core` `daq` `db` `dqm` `fastsim` `generators` `geometry` `heterogeneous` `hlt` `l1` `pdmv` `reconstruction` `simulation` `tracking` `trk` `xpog` created: 2026-05-11 15:26:18 merged: 2026-06-09 20:34:30

126. [50889](http://github.com/cms-sw/cmssw/pull/50889){:target="_blank"}  from **@ghyls**: Prevent the MPI modules from `throw`ing upon race conditions or hanging at the end of a run. `heterogeneous` created: 2026-05-05 23:50:42 merged: 2026-06-20 06:09:58

127. [50887](http://github.com/cms-sw/cmssw/pull/50887){:target="_blank"}  from **@alexstrel**: Hotfix  for Alpaka MD PF clusterizer  (CPU backend) `heterogeneous` `reconstruction` created: 2026-05-05 19:34:49 merged: 2026-06-10 17:30:58

128. [50843](http://github.com/cms-sw/cmssw/pull/50843){:target="_blank"}  from **@Dr15Jones**: Refactor control of Source in EventProcessor `core` created: 2026-04-30 21:40:47 merged: 2026-06-10 17:30:24

129. [50782](http://github.com/cms-sw/cmssw/pull/50782){:target="_blank"}  from **@AdrianoDee**: Adding `skipEvents` option to `cmsDriver` `operations` created: 2026-04-22 10:57:28 merged: 2026-06-16 09:46:14

130. [50679](http://github.com/cms-sw/cmssw/pull/50679){:target="_blank"}  from **@SegmentLinking**: LST: add LSTGeometry package and associated ESProducer `hlt` `reconstruction` `tracking` created: 2026-04-07 15:58:50 merged: 2026-06-18 08:43:34

131. [50282](http://github.com/cms-sw/cmssw/pull/50282){:target="_blank"}  from **@jroloff**: PF DQM updates `dqm` `pf` created: 2026-02-27 19:40:17 merged: 2026-07-03 07:57:42

132. [50032](http://github.com/cms-sw/cmssw/pull/50032){:target="_blank"}  from **@mbluj**: Updates L1T OMTF for Phase 2 `l1` created: 2026-02-04 13:57:27 merged: 2026-07-01 07:58:43

133. [49942](http://github.com/cms-sw/cmssw/pull/49942){:target="_blank"}  from **@ghyls**: Update MPI Test software `heterogeneous` created: 2026-01-26 14:01:39 merged: 2026-06-29 05:06:16

134. [49821](http://github.com/cms-sw/cmssw/pull/49821){:target="_blank"}  from **@cms-ngt-hlt**: update phase-2 HLT timing script and use `alpaka` modifier in NGT workflows `hlt` `pdmv` created: 2026-01-14 13:03:07 merged: 2026-06-09 13:14:21

#### CMSDIST Changes between Tags REL/CMSSW_20_0_0_pre1/el9_amd64_gcc13 and REL/CMSSW_20_1_0_pre1/el9_amd64_gcc13:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_20_0_0_pre1/el9_amd64_gcc13...REL/CMSSW_20_1_0_pre1/el9_amd64_gcc13)



1. [10704](http://github.com/cms-sw/cmsdist/pull/10704){:target="_blank"}  from **@fwyzard**: Update CUDA to version 13.3.1 created: 2026-07-04 07:20:35 merged: 2026-07-06 08:42:53

2. [10703](http://github.com/cms-sw/cmsdist/pull/10703){:target="_blank"}  from **@cms-sw**: bug fix: make sure to fail if patchsrc not applied created: 2026-07-03 14:39:02 merged: 2026-07-03 18:56:05

3. [10700](http://github.com/cms-sw/cmsdist/pull/10700){:target="_blank"}  from **@cms-sw**: [DD4Hep] Update to v01-37 with fixes for ROOT6/GCC15/LLVM22 created: 2026-07-03 09:18:22 merged: 2026-07-04 10:20:38

4. [10696](http://github.com/cms-sw/cmsdist/pull/10696){:target="_blank"}  from **@cms-sw**: [cuda] install libnvidia-pkcs11 only for x86_64 created: 2026-07-01 22:46:35 merged: 2026-07-02 07:23:48

5. [10695](http://github.com/cms-sw/cmsdist/pull/10695){:target="_blank"}  from **@belforte**: Bump crabclient to latest created: 2026-07-01 12:42:20 merged: 2026-07-02 07:26:13

6. [10692](http://github.com/cms-sw/cmsdist/pull/10692){:target="_blank"}  from **@cms-sw**: BuidlRule: Add verify_asan_link_order=0 to run gridpacks under ASAN env created: 2026-07-01 10:14:04 merged: 2026-07-01 15:33:12

7. [10690](http://github.com/cms-sw/cmsdist/pull/10690){:target="_blank"}  from **@cms-sw**: Update tag for L1Trigger-L1TMuon to V01-13-00 created: 2026-07-01 08:17:15 merged: 2026-07-01 08:17:18

8. [10688](http://github.com/cms-sw/cmsdist/pull/10688){:target="_blank"}  from **@belforte**: Update crabclient and crabserver versions created: 2026-06-30 09:41:50 merged: 2026-06-30 18:26:57

9. [10682](http://github.com/cms-sw/cmsdist/pull/10682){:target="_blank"}  from **@fwyzard**: Update UCX to version 1.21.0 created: 2026-06-24 15:39:56 merged: 2026-07-01 07:58:35

10. [10680](http://github.com/cms-sw/cmsdist/pull/10680){:target="_blank"}  from **@cms-sw**: setup cms env for scram-based project during build created: 2026-06-24 07:21:30 merged: 2026-06-24 08:45:20

11. [10678](http://github.com/cms-sw/cmsdist/pull/10678){:target="_blank"}  from **@fwyzard**: Update the NVIDIA compatibility and stub libraries for CUDA 13.3 created: 2026-06-23 12:45:59 merged: 2026-07-01 12:01:52

12. [10677](http://github.com/cms-sw/cmsdist/pull/10677){:target="_blank"}  from **@todor-ivanov**: Update dasgoclient version to v02.04.53 created: 2026-06-22 13:58:44 merged: 2026-06-23 08:50:35

13. [10674](http://github.com/cms-sw/cmsdist/pull/10674){:target="_blank"}  from **@cms-sw**: Python packages update to get security fixes created: 2026-06-22 06:23:45 merged: 2026-06-23 18:24:48

14. [10673](http://github.com/cms-sw/cmsdist/pull/10673){:target="_blank"}  from **@cms-sw**: added override_microarch_name  for vectorized packages created: 2026-06-21 17:23:56 merged: 2026-06-22 04:25:24

15. [10672](http://github.com/cms-sw/cmsdist/pull/10672){:target="_blank"}  from **@cms-sw**: added default_pkgname for different varient of torch packages created: 2026-06-20 22:12:25 merged: 2026-06-21 17:10:18

16. [10671](http://github.com/cms-sw/cmsdist/pull/10671){:target="_blank"}  from **@cms-sw**: Add default package name definition for vectorization created: 2026-06-20 20:26:26 merged: 2026-06-21 17:10:37

17. [10670](http://github.com/cms-sw/cmsdist/pull/10670){:target="_blank"}  from **@cms-sw**: triton: added optional support for cuda created: 2026-06-20 13:07:35 merged: 2026-06-20 13:52:02

18. [10668](http://github.com/cms-sw/cmsdist/pull/10668){:target="_blank"}  from **@felicepantaleo**: Add perfetto external (v56.1) created: 2026-06-20 06:15:16 merged: 2026-06-20 13:52:24

19. [10666](http://github.com/cms-sw/cmsdist/pull/10666){:target="_blank"}  from **@cms-sw**: Added support for overriding c++ standard for package via command-line created: 2026-06-19 09:58:43 merged: 2026-06-20 20:24:38

20. [10665](http://github.com/cms-sw/cmsdist/pull/10665){:target="_blank"}  from **@artlbv**: Add NNPuppiTauModel external spec and toolfile created: 2026-06-19 04:31:12 merged: 2026-07-01 19:11:35

21. [10664](http://github.com/cms-sw/cmsdist/pull/10664){:target="_blank"}  from **@cms-sw**: pyg-lib: Do not build for native arch created: 2026-06-18 18:33:08 merged: 2026-06-18 21:08:43

22. [10663](http://github.com/cms-sw/cmsdist/pull/10663){:target="_blank"}  from **@cms-sw**: enable multi-vectorization for ucx version 1.20.1 created: 2026-06-18 11:11:04 merged: 2026-06-23 08:55:53

23. [10662](http://github.com/cms-sw/cmsdist/pull/10662){:target="_blank"}  from **@cms-sw**: change cryptography order to avoid Dependabot alerts created: 2026-06-18 10:16:32 merged: 2026-06-18 10:17:07

24. [10661](http://github.com/cms-sw/cmsdist/pull/10661){:target="_blank"}  from **@cms-sw**: use cryptography==46.0.7 for el8 created: 2026-06-18 09:54:30 merged: 2026-06-18 10:10:26

25. [10659](http://github.com/cms-sw/cmsdist/pull/10659){:target="_blank"}  from **@cms-sw**: PyTorch 2.12.1 created: 2026-06-17 18:10:40 merged: 2026-06-20 20:23:43

26. [10656](http://github.com/cms-sw/cmsdist/pull/10656){:target="_blank"}  from **@cms-sw**: Update python module to get security fixes created: 2026-06-17 11:09:58 merged: 2026-06-17 17:42:16

27. [10655](http://github.com/cms-sw/cmsdist/pull/10655){:target="_blank"}  from **@cms-sw**: Boost version 1.91.0 created: 2026-06-17 07:56:16 merged: 2026-06-17 17:50:50

28. [10650](http://github.com/cms-sw/cmsdist/pull/10650){:target="_blank"}  from **@fwyzard**: Set `ROCM_PATH` to the CMSSW ROCm installation created: 2026-06-17 05:16:57 merged: 2026-06-17 17:40:22

29. [10649](http://github.com/cms-sw/cmsdist/pull/10649){:target="_blank"}  from **@cms-sw**: Build all ROCM components created: 2026-06-16 21:06:48 merged: 2026-07-06 17:56:35

30. [10642](http://github.com/cms-sw/cmsdist/pull/10642){:target="_blank"}  from **@cms-sw**: Update tag for Configuration-Generator to V01-14-00 created: 2026-06-16 14:44:16 merged: 2026-06-16 14:44:19

31. [10641](http://github.com/cms-sw/cmsdist/pull/10641){:target="_blank"}  from **@cms-sw**: Update xrootd to version 6.0.2 created: 2026-06-16 12:26:24 merged: 2026-06-16 18:53:59

32. [10640](http://github.com/cms-sw/cmsdist/pull/10640){:target="_blank"}  from **@cms-sw**: Update tag for RecoTracker-MkFit to V00-20-00 created: 2026-06-16 11:57:22 merged: 2026-06-16 11:57:25

33. [10638](http://github.com/cms-sw/cmsdist/pull/10638){:target="_blank"}  from **@cms-sw**: cmsLHEtoEOSManager: used cmssdt cache instead of hitting github created: 2026-06-16 09:26:08 merged: 2026-06-16 14:59:42

34. [10633](http://github.com/cms-sw/cmsdist/pull/10633){:target="_blank"}  from **@fwyzard**: Update ROCm to version 7.2.4 created: 2026-06-13 17:10:44 merged: 2026-06-16 07:07:44

35. [10632](http://github.com/cms-sw/cmsdist/pull/10632){:target="_blank"}  from **@cms-sw**: git: update version to 2.54.0 and drop GIT_SSL_CAINFO env created: 2026-06-13 14:21:14 merged: 2026-06-13 18:20:40

36. [10631](http://github.com/cms-sw/cmsdist/pull/10631){:target="_blank"}  from **@cms-sw**: Update SCRAMV1 and V2 to support unsetting env e.g GIT_SSL_CAINFO created: 2026-06-13 13:06:22 merged: 2026-06-13 15:11:18

37. [10628](http://github.com/cms-sw/cmsdist/pull/10628){:target="_blank"}  from **@cms-sw**: cms-common: GIT_SSL_CAINFO fix for slc5/6/7 created: 2026-06-12 12:37:22 merged: 2026-06-12 13:36:02

38. [10625](http://github.com/cms-sw/cmsdist/pull/10625){:target="_blank"}  from **@cms-sw**: SCRAMV1  V3_00_93: Added support control statements like for/foreach created: 2026-06-12 08:18:58 merged: 2026-06-12 17:11:10

39. [10618](http://github.com/cms-sw/cmsdist/pull/10618){:target="_blank"}  from **@cms-sw**: Update tag for RecoTracker-PixelLowPtUtilities to V00-01-00 created: 2026-06-09 19:52:33 merged: 2026-06-09 19:52:36

40. [10617](http://github.com/cms-sw/cmsdist/pull/10617){:target="_blank"}  from **@fwyzard**: Update CUDA to version 13.3.0 created: 2026-06-09 16:29:26 merged: 2026-06-15 09:17:55

41. [10615](http://github.com/cms-sw/cmsdist/pull/10615){:target="_blank"}  from **@fwyzard**: ONNXRuntime: update to version 1.26.0 created: 2026-06-09 09:18:49 merged: 2026-06-10 07:35:49

42. [10591](http://github.com/cms-sw/cmsdist/pull/10591){:target="_blank"}  from **@Brainz22**: Updated TOoLLiP to version 3.1.0. created: 2026-05-28 22:09:26 merged: 2026-06-10 08:09:54
