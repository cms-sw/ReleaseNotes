---
layout: post
rel_link:  "13_1_0_pre4"
title:  "CMSSW_13_1_0_pre4"
date:   2023-05-03 10:55:59
categories: cmssw
relmajor: 13
relminor: 1
relsubminor: 0
relpre: _pre4
---

# CMSSW_13_1_0_pre4
#### Changes since CMSSW_13_1_0_pre3:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_13_1_0_pre3...CMSSW_13_1_0_pre4)



1. [41494](http://github.com/cms-sw/cmssw/pull/41494){:target="_blank"}  from **@wddgit**: Add unit test for FEDRawDataCollection format `daq` created: 2023-05-02 21:18:01 merged: 2023-05-03 08:35:06

2. [41488](http://github.com/cms-sw/cmssw/pull/41488){:target="_blank"}  from **@smuzaffar**: [CLANG] Fix warnings about set but unused variables `l1` `simulation` `trk` created: 2023-05-02 14:21:58 merged: 2023-05-03 07:50:57

3. [41480](http://github.com/cms-sw/cmssw/pull/41480){:target="_blank"}  from **@bsunanda**: Phase2-gex160Z Remove overlaps in the Phase2 scenarios which used to be caused by an error in zdc.xml `geometry` `upgrade` created: 2023-05-01 16:41:45 merged: 2023-05-03 08:56:44

4. [41473](http://github.com/cms-sw/cmssw/pull/41473){:target="_blank"}  from **@mandrenguyen**: Remove PF candidates with nan for energy `reconstruction` `pf` created: 2023-04-30 21:18:26 merged: 2023-05-01 06:08:58

5. [41469](http://github.com/cms-sw/cmssw/pull/41469){:target="_blank"}  from **@missirol**: re-improve check on size of L1-uGT digis in `HLTL1TSeed` plugin `hlt` created: 2023-04-30 11:11:01 merged: 2023-04-30 17:15:15

6. [41466](http://github.com/cms-sw/cmssw/pull/41466){:target="_blank"}  from **@missirol**: guard `HLTRecHitInAllL1RegionsProducer<T>` against empty collection of L1T candidates `hlt` created: 2023-04-30 09:16:53 merged: 2023-04-30 17:15:29

7. [41465](http://github.com/cms-sw/cmssw/pull/41465){:target="_blank"}  from **@Dr15Jones**: Improve thread efficiency of CSCTriggerPrimitivesProducer `l1` created: 2023-04-29 16:12:42 merged: 2023-05-02 11:41:41

8. [41462](http://github.com/cms-sw/cmssw/pull/41462){:target="_blank"}  from **@civanch**: Clean sensitive detector and printouts `simulation` created: 2023-04-28 17:35:52 merged: 2023-04-30 06:28:14

9. [41458](http://github.com/cms-sw/cmssw/pull/41458){:target="_blank"}  from **@smuzaffar**: Added extra Invalid = -1 enum to avoid llvm16 build errors `alca` `l1` `db` created: 2023-04-28 14:54:46 merged: 2023-04-30 18:44:19

10. [41455](http://github.com/cms-sw/cmssw/pull/41455){:target="_blank"}  from **@iarspider**: Disable CondToolsLHCInfoNewPopConTest for non-AMD64 `db` created: 2023-04-28 10:13:48 merged: 2023-05-02 12:53:43

11. [41453](http://github.com/cms-sw/cmssw/pull/41453){:target="_blank"}  from **@missirol**: remove Patatrack-related RelVals for 2018 conditions `pdmv` `upgrade` created: 2023-04-28 07:37:18 merged: 2023-04-29 05:37:21

12. [41452](http://github.com/cms-sw/cmssw/pull/41452){:target="_blank"}  from **@bundocka**: L1T: read pt compression bit depth from LUT for JEC `l1` created: 2023-04-27 22:35:12 merged: 2023-04-28 13:53:10

13. [41450](http://github.com/cms-sw/cmssw/pull/41450){:target="_blank"}  from **@swagata87**: Add protection to avoid crash in `lowPtGsfEleGsfTracks` `reconstruction` `tracking` created: 2023-04-27 18:47:53 merged: 2023-04-28 11:58:41

14. [41448](http://github.com/cms-sw/cmssw/pull/41448){:target="_blank"}  from **@dinyar**: Add loose showers to uGMT shower bit vs. BX DQM plot `dqm` created: 2023-04-27 14:49:38 merged: 2023-04-28 19:26:54

15. [41447](http://github.com/cms-sw/cmssw/pull/41447){:target="_blank"}  from **@dzuolo**: [13_1_X] Reverting BeamSpot Legacy DQM client error scale to 1p2 `dqm` created: 2023-04-27 14:17:37 merged: 2023-04-28 13:39:22

16. [41438](http://github.com/cms-sw/cmssw/pull/41438){:target="_blank"}  from **@abhih1**: Change ECAL Presample RMS threshold `dqm` created: 2023-04-27 09:58:03 merged: 2023-04-28 16:46:47

17. [41437](http://github.com/cms-sw/cmssw/pull/41437){:target="_blank"}  from **@saumyaphor4252**: Update L1TCaloParams in 2022 and 2023 HI MC GTs `alca` created: 2023-04-27 09:56:14 merged: 2023-04-28 07:56:46

18. [41435](http://github.com/cms-sw/cmssw/pull/41435){:target="_blank"}  from **@smuzaffar**: drop numba and llvmlite tests `analysis` `reconstruction` created: 2023-04-26 19:02:39 merged: 2023-04-27 14:08:25

19. [41433](http://github.com/cms-sw/cmssw/pull/41433){:target="_blank"}  from **@vshang**: Updating base caloParams class with HCal FB LUT parameters `l1` created: 2023-04-26 17:28:20 merged: 2023-04-27 08:30:47

20. [41432](http://github.com/cms-sw/cmssw/pull/41432){:target="_blank"}  from **@bsunanda**: Run3-gex160X Update the overlap finding scripts for Run3/Run2 scenarios `simulation` `geometry` `upgrade` created: 2023-04-26 17:16:41 merged: 2023-04-28 12:03:33

21. [41430](http://github.com/cms-sw/cmssw/pull/41430){:target="_blank"}  from **@cms-tsg-storm**: Update of L1T pp menu in TSG GTs to `L1Menu_Collisions2023_v1_1_0_xml` `hlt` created: 2023-04-26 17:05:46 merged: 2023-04-26 21:17:54

22. [41429](http://github.com/cms-sw/cmssw/pull/41429){:target="_blank"}  from **@smuzaffar**: [SIMULATION-UPGRADE] [LLVM14] Apply clang-tidy and clang-format changes `simulation` `upgrade` created: 2023-04-26 15:40:00 merged: 2023-04-26 16:07:38

23. [41428](http://github.com/cms-sw/cmssw/pull/41428){:target="_blank"}  from **@smuzaffar**: [VISUALIZATION] [LLVM14] Apply clang-tidy and clang-format changes `visualization` created: 2023-04-26 15:39:40 merged: 2023-04-26 21:19:00

24. [41427](http://github.com/cms-sw/cmssw/pull/41427){:target="_blank"}  from **@smuzaffar**: [GEOMETRY-UPGRADE] [LLVM14] Apply clang-tidy and clang-format changes `geometry` `upgrade` created: 2023-04-26 15:39:31 merged: 2023-04-27 11:40:34

25. [41426](http://github.com/cms-sw/cmssw/pull/41426){:target="_blank"}  from **@smuzaffar**: [CORE] [LLVM14] Apply clang-tidy and clang-format changes `core` created: 2023-04-26 15:39:24 merged: 2023-04-27 04:29:23

26. [41425](http://github.com/cms-sw/cmssw/pull/41425){:target="_blank"}  from **@smuzaffar**: [DB] [LLVM14] Apply clang-tidy and clang-format changes `db` `trk` created: 2023-04-26 15:38:49 merged: 2023-04-28 07:57:49

27. [41424](http://github.com/cms-sw/cmssw/pull/41424){:target="_blank"}  from **@smuzaffar**: [HLT] [LLVM14] Apply clang-tidy and clang-format changes `hlt` created: 2023-04-26 15:38:40 merged: 2023-04-27 04:49:31

28. [41423](http://github.com/cms-sw/cmssw/pull/41423){:target="_blank"}  from **@smuzaffar**: [GEOMETRY] [LLVM14] Apply clang-tidy and clang-format changes `geometry` `trk` created: 2023-04-26 15:38:32 merged: 2023-04-26 21:19:34

29. [41422](http://github.com/cms-sw/cmssw/pull/41422){:target="_blank"}  from **@smuzaffar**: [ANALYSIS] [LLVM14] Apply clang-tidy and clang-format changes `analysis` created: 2023-04-26 15:38:12 merged: 2023-04-27 04:25:13

30. [41421](http://github.com/cms-sw/cmssw/pull/41421){:target="_blank"}  from **@smuzaffar**: [SIMULATION] [LLVM14] Apply clang-tidy and clang-format changes `simulation` created: 2023-04-26 15:38:04 merged: 2023-04-27 04:51:00

31. [41420](http://github.com/cms-sw/cmssw/pull/41420){:target="_blank"}  from **@smuzaffar**: [L1-UPGRADE] [LLVM14] Apply clang-tidy and clang-format changes `l1` `upgrade` created: 2023-04-26 15:37:56 merged: 2023-04-27 11:47:38

32. [41419](http://github.com/cms-sw/cmssw/pull/41419){:target="_blank"}  from **@smuzaffar**: [DAQ] [LLVM14] Apply clang-tidy and clang-format changes `daq` created: 2023-04-26 15:37:34 merged: 2023-04-26 21:21:40

33. [41418](http://github.com/cms-sw/cmssw/pull/41418){:target="_blank"}  from **@smuzaffar**: [RECONSTRUCTION] [LLVM14] Apply clang-tidy and clang-format changes `reconstruction` `tracking` `trk` created: 2023-04-26 15:37:27 merged: 2023-04-30 14:31:06

34. [41417](http://github.com/cms-sw/cmssw/pull/41417){:target="_blank"}  from **@smuzaffar**: [L1] [LLVM14] Apply clang-tidy and clang-format changes `l1` created: 2023-04-26 15:37:18 merged: 2023-04-28 14:02:09

35. [41416](http://github.com/cms-sw/cmssw/pull/41416){:target="_blank"}  from **@smuzaffar**: [ALCA] [LLVM14] Apply clang-tidy and clang-format changes `alca` created: 2023-04-26 15:03:04 merged: 2023-04-27 16:33:40

36. [41415](http://github.com/cms-sw/cmssw/pull/41415){:target="_blank"}  from **@smuzaffar**: [DQM] [LLVM14] Apply clang-tidy and clang-format changes `dqm` created: 2023-04-26 15:02:49 merged: 2023-05-02 14:32:54

37. [41412](http://github.com/cms-sw/cmssw/pull/41412){:target="_blank"}  from **@bsunanda**: Run3-gex160 Modify the correct combination of ZDC xml files in Phase2 scenarios which are useful for dd4hep version `geometry` `upgrade` created: 2023-04-26 13:46:16 merged: 2023-04-28 05:32:47

38. [41411](http://github.com/cms-sw/cmssw/pull/41411){:target="_blank"}  from **@mmusich**: add `PileupSummaryInfos_addPileupInfo` to `SiPixelCalSingleMuonTight` output data-tier `alca` `trk` created: 2023-04-26 13:37:48 merged: 2023-05-02 12:51:57

39. [41409](http://github.com/cms-sw/cmssw/pull/41409){:target="_blank"}  from **@yuanchao**: Payload Inspector for JetCorrector `db` created: 2023-04-26 10:24:37 merged: 2023-05-02 12:57:44

40. [41406](http://github.com/cms-sw/cmssw/pull/41406){:target="_blank"}  from **@bsunanda**: Phase2-hgx338B Next step to introduce calibration cells for HGCal silicon sensors `geometry` `upgrade` created: 2023-04-26 07:42:34 merged: 2023-04-28 05:35:55

41. [41405](http://github.com/cms-sw/cmssw/pull/41405){:target="_blank"}  from **@Dr15Jones**: Add option to control printing of Pythia banner `generators` created: 2023-04-25 20:04:51 merged: 2023-04-28 05:25:02

42. [41404](http://github.com/cms-sw/cmssw/pull/41404){:target="_blank"}  from **@civanch**: Different Geant4 SteppingActions for Run3 and Phase2 `simulation` created: 2023-04-25 18:01:58 merged: 2023-04-26 10:44:36

43. [41403](http://github.com/cms-sw/cmssw/pull/41403){:target="_blank"}  from **@slava77**: cleanup spurious change introduced in PAT photon/muon producer auto fwd-port in 2015 `reconstruction` `xpog` created: 2023-04-25 17:01:06 merged: 2023-04-27 15:06:54

44. [41401](http://github.com/cms-sw/cmssw/pull/41401){:target="_blank"}  from **@aloeliger**: Update GlobalAlgBlkUnpacker to throw error in the case of headers received in the wrong order `l1` created: 2023-04-25 12:40:32 merged: 2023-04-25 19:29:38

45. [41395](http://github.com/cms-sw/cmssw/pull/41395){:target="_blank"}  from **@wddgit**: Add unit test for TriggerResults format `core` created: 2023-04-24 16:46:55 merged: 2023-04-29 04:40:31

46. [41393](http://github.com/cms-sw/cmssw/pull/41393){:target="_blank"}  from **@mmusich**: fix some bugs in the TrackerAlignment `DiMuonValidation` code `alca` `trk` created: 2023-04-24 14:50:03 merged: 2023-04-25 13:50:46

47. [41392](http://github.com/cms-sw/cmssw/pull/41392){:target="_blank"}  from **@hahnjo**: Remove checks for Geant4 version `simulation` created: 2023-04-24 10:10:29 merged: 2023-04-25 14:22:43

48. [41390](http://github.com/cms-sw/cmssw/pull/41390){:target="_blank"}  from **@bsunanda**: Phase2-hgx338A First step to introduce calibration cells for HGCAL silicon sensors `geometry` `upgrade` created: 2023-04-24 07:23:35 merged: 2023-04-25 14:05:49

49. [41387](http://github.com/cms-sw/cmssw/pull/41387){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `13_0_X` (7/N) [`13_1_X`] `hlt` created: 2023-04-23 11:47:09 merged: 2023-04-23 21:00:30

50. [41385](http://github.com/cms-sw/cmssw/pull/41385){:target="_blank"}  from **@bsunanda**: Phase2-TB70X Try to make an example to run the setup used for investigating radiation damage studies of HGCal module `generators` `geometry` `simulation` `upgrade` created: 2023-04-22 10:15:06 merged: 2023-05-02 17:15:27

51. [41384](http://github.com/cms-sw/cmssw/pull/41384){:target="_blank"}  from **@jshlee**: [GEM] DataFormat Bugfix - remove unused bits from VFat dataformat `simulation` `upgrade` created: 2023-04-22 00:21:02 merged: 2023-04-27 11:42:43

52. [41380](http://github.com/cms-sw/cmssw/pull/41380){:target="_blank"}  from **@bsunanda**: Phase2-hgx337B Try to solve the cassette shift issue and fix a bug in Geometry/HGCalCommonData `geometry` `simulation` `upgrade` created: 2023-04-20 09:28:03 merged: 2023-04-24 13:55:08

53. [41378](http://github.com/cms-sw/cmssw/pull/41378){:target="_blank"}  from **@mmusich**: Improve vertexing monitoring for Tracker Alignment AlCaReco samples `alca` `trk` created: 2023-04-20 08:46:29 merged: 2023-04-25 13:55:31

54. [41377](http://github.com/cms-sw/cmssw/pull/41377){:target="_blank"}  from **@iarspider**: Remove PhysicsTools/MXNet (cms-sw/cmssw#30432) `reconstruction` created: 2023-04-20 08:26:07 merged: 2023-04-25 14:11:21

55. [41375](http://github.com/cms-sw/cmssw/pull/41375){:target="_blank"}  from **@jfernan2**: DQM perLS in one shot (part 2) `dqm` created: 2023-04-19 14:48:57 merged: 2023-04-25 14:49:53

56. [41372](http://github.com/cms-sw/cmssw/pull/41372){:target="_blank"}  from **@AWildridge**: Fixed bug. Missing edm::InputTag src default value in fillDescriptions `generators` created: 2023-04-19 07:05:55 merged: 2023-05-02 17:28:33

57. [41370](http://github.com/cms-sw/cmssw/pull/41370){:target="_blank"}  from **@civanch**: [SIM] MCtruth cleanup `simulation` created: 2023-04-18 18:35:20 merged: 2023-04-19 18:32:39

58. [41369](http://github.com/cms-sw/cmssw/pull/41369){:target="_blank"}  from **@consuegs**: Re-adding cosmic track collection ALCARECOTkAlCosmicsCosmicTF0T `alca` created: 2023-04-18 17:07:10 merged: 2023-04-18 21:22:43

59. [41365](http://github.com/cms-sw/cmssw/pull/41365){:target="_blank"}  from **@makortel**: Add missing dictionaries in DataFormats/CTPPSReco `reconstruction` created: 2023-04-17 21:04:26 merged: 2023-04-21 12:43:27

60. [41355](http://github.com/cms-sw/cmssw/pull/41355){:target="_blank"}  from **@bsunanda**: Phase2-hgx337A Further attempts to diagnose cassette shift studies for HGCal geometry (relevant for the V18 version) `geometry` `simulation` `upgrade` created: 2023-04-17 08:36:26 merged: 2023-04-19 09:11:36

61. [41354](http://github.com/cms-sw/cmssw/pull/41354){:target="_blank"}  from **@missirol**: add GPU RelVals using 2023 HLT menu `pdmv` `upgrade` created: 2023-04-17 07:14:59 merged: 2023-04-21 11:25:27

62. [41353](http://github.com/cms-sw/cmssw/pull/41353){:target="_blank"}  from **@jking79**: Ecal CC timing reconstruction deployment `reconstruction` `simulation` `ecal` created: 2023-04-16 23:15:33 merged: 2023-05-02 17:12:30

63. [41350](http://github.com/cms-sw/cmssw/pull/41350){:target="_blank"}  from **@missirol**: change input file of `testTriggerEventAnalyzers` unit test `hlt` created: 2023-04-16 14:52:44 merged: 2023-04-16 19:22:07

64. [41349](http://github.com/cms-sw/cmssw/pull/41349){:target="_blank"}  from **@makortel**: Make sure to report an error if process.options.numberOfThreads has wrong type `core` created: 2023-04-14 20:56:59 merged: 2023-04-17 15:35:45

65. [41345](http://github.com/cms-sw/cmssw/pull/41345){:target="_blank"}  from **@bsunanda**: Phase2-gex159 Modify the GE0 Shield structure to match engineering drawing `geometry` created: 2023-04-14 05:12:34 merged: 2023-04-18 20:44:03

66. [41341](http://github.com/cms-sw/cmssw/pull/41341){:target="_blank"}  from **@fwyzard**: Drop support for the old alpaka accelerator framework `heterogeneous` created: 2023-04-14 01:03:58 merged: 2023-04-14 13:11:11

67. [41339](http://github.com/cms-sw/cmssw/pull/41339){:target="_blank"}  from **@igv4321**: Fix for HcalPFCuts_unittest `db` created: 2023-04-13 20:04:09 merged: 2023-04-14 07:12:35

68. [41336](http://github.com/cms-sw/cmssw/pull/41336){:target="_blank"}  from **@cerminar**: Phase-2 L1T: fix isolation type for GT e/g objects `l1` `upgrade` created: 2023-04-13 15:36:36 merged: 2023-04-17 17:14:34

69. [41333](http://github.com/cms-sw/cmssw/pull/41333){:target="_blank"}  from **@mbluj**: Add ParticleNet info to taus in NanoAOD `reconstruction` `xpog` `tau` created: 2023-04-13 12:31:08 merged: 2023-04-27 16:34:14

70. [41330](http://github.com/cms-sw/cmssw/pull/41330){:target="_blank"}  from **@srimanob**: Fix FastSim PreMixing configuration for Run-3 `simulation` created: 2023-04-12 17:33:54 merged: 2023-04-13 12:25:12

71. [41329](http://github.com/cms-sw/cmssw/pull/41329){:target="_blank"}  from **@Dr15Jones**: Catch and rethrow xml exceptions in TotemDAQMappingESSourceXML `alca` created: 2023-04-12 17:31:39 merged: 2023-04-13 05:47:35

72. [41328](http://github.com/cms-sw/cmssw/pull/41328){:target="_blank"}  from **@wddgit**: Implement return value for ESProducer acquire function `core` created: 2023-04-12 15:51:22 merged: 2023-04-20 20:14:22

73. [41327](http://github.com/cms-sw/cmssw/pull/41327){:target="_blank"}  from **@saumyaphor4252**: Include HcalPFCuts Rcd and update SiPixel Dynamic Inefficiency tags in MC GTs `alca` created: 2023-04-12 14:50:57 merged: 2023-04-13 05:50:06

74. [41325](http://github.com/cms-sw/cmssw/pull/41325){:target="_blank"}  from **@menglu21**: renew matched lepton ids for every jet `xpog` created: 2023-04-12 14:05:02 merged: 2023-04-25 14:32:24

75. [41324](http://github.com/cms-sw/cmssw/pull/41324){:target="_blank"}  from **@Dr15Jones**: Move to steady_clock in the framework `core` created: 2023-04-12 13:49:34 merged: 2023-04-12 21:27:08

76. [41322](http://github.com/cms-sw/cmssw/pull/41322){:target="_blank"}  from **@iarspider**: TagProbeFitter: replace call to deprecated overload of RooPdf::paramOn `analysis` created: 2023-04-12 09:22:35 merged: 2023-04-13 05:50:23

77. [41319](http://github.com/cms-sw/cmssw/pull/41319){:target="_blank"}  from **@sunilUIET**: [13_1_X]changing Era to Run3_2023 for 2023 WFs `pdmv` `upgrade` created: 2023-04-11 16:34:30 merged: 2023-04-18 13:05:28

78. [41318](http://github.com/cms-sw/cmssw/pull/41318){:target="_blank"}  from **@fabiocos**: MTD simulation: update Track ID stored in MTD SimHits `geometry` `simulation` `upgrade` created: 2023-04-11 15:01:14 merged: 2023-04-14 07:10:26

79. [41314](http://github.com/cms-sw/cmssw/pull/41314){:target="_blank"}  from **@MaryShooshtari**: adding DeepJet pass to HLT-BTV validation plots `dqm` created: 2023-04-11 12:13:28 merged: 2023-04-20 06:20:17

80. [41312](http://github.com/cms-sw/cmssw/pull/41312){:target="_blank"}  from **@elfontan**: Adding the new muon track finder index and three eta cuts features in the GT emulator `l1` created: 2023-04-11 08:08:33 merged: 2023-04-19 21:17:03

81. [41310](http://github.com/cms-sw/cmssw/pull/41310){:target="_blank"}  from **@mmusich**: fix `RecoTracker/Pixel*` subsystems header file inclusions guards to comply with cmssw rule 4.1 `reconstruction` `tracking` created: 2023-04-11 07:18:31 merged: 2023-04-14 12:11:04

82. [41308](http://github.com/cms-sw/cmssw/pull/41308){:target="_blank"}  from **@Dr15Jones**: Make thread safe statistics accounting in TStorageFactoryFile `core` created: 2023-04-07 19:03:18 merged: 2023-04-12 17:05:14

83. [41307](http://github.com/cms-sw/cmssw/pull/41307){:target="_blank"}  from **@trackreco**: mkFit: minor fixes to a Makefile for standalone build only `reconstruction` `tracking` created: 2023-04-07 18:20:41 merged: 2023-04-13 22:08:42

84. [41282](http://github.com/cms-sw/cmssw/pull/41282){:target="_blank"}  from **@PixelTracksAlpaka**: Pixel Alpaka Migration: Modification to Existing Modules [I] `reconstruction` `geometry` `tracking` created: 2023-04-05 15:47:26 merged: 2023-04-18 11:55:01

85. [41276](http://github.com/cms-sw/cmssw/pull/41276){:target="_blank"}  from **@valsdav**: Improved options handling for TensorFlow sessions `reconstruction` created: 2023-04-04 21:22:42 merged: 2023-04-12 21:31:51

86. [41271](http://github.com/cms-sw/cmssw/pull/41271){:target="_blank"}  from **@swagata87**: New Run3 era for updated HB thresholds in 2023 `operations` `reconstruction` created: 2023-04-04 13:18:51 merged: 2023-04-17 20:44:17

87. [41266](http://github.com/cms-sw/cmssw/pull/41266){:target="_blank"}  from **@AdrianoDee**: Add `--nEvents` option to `runTheMatrix.py` `pdmv` `upgrade` created: 2023-04-04 09:13:20 merged: 2023-04-13 22:12:56

88. [41234](http://github.com/cms-sw/cmssw/pull/41234){:target="_blank"}  from **@CMS-HGCAL**: Re-inforce time of arrival threshold in aged scenarios `simulation` `upgrade` created: 2023-03-30 13:03:23 merged: 2023-04-17 20:37:58

89. [41196](http://github.com/cms-sw/cmssw/pull/41196){:target="_blank"}  from **@jfernan2**: DQM perLS in one shot `dqm` created: 2023-03-27 14:41:31 merged: 2023-04-13 07:09:56

90. [41175](http://github.com/cms-sw/cmssw/pull/41175){:target="_blank"}  from **@abhih1**: Adding the Ecal Endcaps to the ML based online ECAL DQM `dqm` `ecal` created: 2023-03-24 13:03:37 merged: 2023-04-18 06:54:25

91. [41164](http://github.com/cms-sw/cmssw/pull/41164){:target="_blank"}  from **@makortel**: Use std::optional to work around maybe-uninitialized warning `reconstruction` `tracking` created: 2023-03-23 19:53:26 merged: 2023-04-17 09:05:20

92. [41101](http://github.com/cms-sw/cmssw/pull/41101){:target="_blank"}  from **@bsunanda**: Run3-alca141X Modify the macros in view of using depth-dependent and phi-dependent correction factors in the estimation of overall correction factors `alca` created: 2023-03-20 07:30:44 merged: 2023-04-30 18:46:59

93. [40817](http://github.com/cms-sw/cmssw/pull/40817){:target="_blank"}  from **@CTPPS**: PPS lhcInfo split: per fill and per LS PopCon `db` created: 2023-02-20 01:11:42 merged: 2023-04-27 16:35:44

94. [40643](http://github.com/cms-sw/cmssw/pull/40643){:target="_blank"}  from **@aehart**: Displaced regional tracking iteration `dqm` `operations` `reconstruction` `pdmv` `upgrade` `tracking` created: 2023-01-31 00:18:21 merged: 2023-05-03 08:45:24

#### CMSDIST Changes between Tags REL/CMSSW_13_1_0_pre3/el8_amd64_gcc11 and REL/CMSSW_13_1_0_pre4/el8_amd64_gcc11:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_13_1_0_pre3/el8_amd64_gcc11...REL/CMSSW_13_1_0_pre4/el8_amd64_gcc11)



1. [8489](http://github.com/cms-sw/cmsdist/pull/8489){:target="_blank"}  from **@cms-sw**: Update tag for DataFormats-FEDRawData to V00-01-00 created: 2023-05-03 08:35:21 merged: 2023-05-03 08:36:06

2. [8487](http://github.com/cms-sw/cmsdist/pull/8487){:target="_blank"}  from **@cms-sw**: Fix for llvm-static checks created: 2023-05-02 17:31:15 merged: 2023-05-03 04:06:32

3. [8485](http://github.com/cms-sw/cmsdist/pull/8485){:target="_blank"}  from **@cms-sw**: fastjet 3.4.1 and fastjet-contrib 1.051 created: 2023-05-02 13:32:04 merged: 2023-05-03 10:35:35

4. [8480](http://github.com/cms-sw/cmsdist/pull/8480){:target="_blank"}  from **@cms-sw**: openloops: Fixes for scon and python3 created: 2023-05-02 06:40:46 merged: 2023-05-02 12:48:29

5. [8479](http://github.com/cms-sw/cmsdist/pull/8479){:target="_blank"}  from **@cms-sw**: Update tag for DataFormats-Common to V00-01-00 created: 2023-04-28 22:49:58 merged: 2023-04-28 22:51:02

6. [8478](http://github.com/cms-sw/cmsdist/pull/8478){:target="_blank"}  from **@cms-sw**: build google-benchmark with -fPIE created: 2023-04-28 15:51:02 merged: 2023-04-30 19:26:52

7. [8476](http://github.com/cms-sw/cmsdist/pull/8476){:target="_blank"}  from **@cms-sw**: Update tag for DQM-EcalMonitorClient to V00-03-00 created: 2023-04-27 16:38:14 merged: 2023-04-27 18:11:24

8. [8474](http://github.com/cms-sw/cmsdist/pull/8474){:target="_blank"}  from **@cms-sw**: use static rust build instead of build from sources created: 2023-04-27 07:14:55 merged: 2023-04-27 15:09:20

9. [8473](http://github.com/cms-sw/cmsdist/pull/8473){:target="_blank"}  from **@cms-sw**: drop numba and llvmlite created: 2023-04-27 05:59:03 merged: 2023-04-27 15:08:06

10. [8471](http://github.com/cms-sw/cmsdist/pull/8471){:target="_blank"}  from **@cms-sw**: [rust] Delete .git files which are breaking slc7 builds created: 2023-04-26 14:26:17 merged: 2023-04-26 18:26:28

11. [8469](http://github.com/cms-sw/cmsdist/pull/8469){:target="_blank"}  from **@cms-sw**: llvm does not support -fno-fat-lto-objects created: 2023-04-26 05:36:21 merged: 2023-04-26 07:31:14

12. [8466](http://github.com/cms-sw/cmsdist/pull/8466){:target="_blank"}  from **@cms-sw**: Search for unpack containers under /cvmfs/singularity.opensciencegrid.org too created: 2023-04-25 09:38:53 merged: 2023-04-25 13:10:23

13. [8465](http://github.com/cms-sw/cmsdist/pull/8465){:target="_blank"}  from **@cms-sw**: Update tag for Configuration-Generator to V01-05-00 created: 2023-04-25 07:23:06 merged: 2023-04-25 07:29:38

14. [8464](http://github.com/cms-sw/cmsdist/pull/8464){:target="_blank"}  from **@cms-sw**: Mount /etc/pki/ca-trust from host  to avoid rebuilding containers with updated trusted ca created: 2023-04-24 16:10:43 merged: 2023-04-25 06:39:10

15. [8459](http://github.com/cms-sw/cmsdist/pull/8459){:target="_blank"}  from **@cms-sw**: Update RecoMuon-TrackerSeedGenerator to V00-05-00 created: 2023-04-21 16:34:30 merged: 2023-04-21 20:49:29

16. [8457](http://github.com/cms-sw/cmsdist/pull/8457){:target="_blank"}  from **@cms-sw**: Update tag for RecoBTag-Combined to V01-16-00 created: 2023-04-21 16:24:31 merged: 2023-04-21 16:25:49

17. [8454](http://github.com/cms-sw/cmsdist/pull/8454){:target="_blank"}  from **@belforte**: bump CRABClient to v3.230417 created: 2023-04-20 14:18:44 merged: 2023-04-20 15:15:47

18. [8453](http://github.com/cms-sw/cmsdist/pull/8453){:target="_blank"}  from **@cms-sw**: [BuildRules] allow to enable disable dedicated unit test directory created: 2023-04-20 13:55:26 merged: 2023-04-20 19:57:54

19. [8451](http://github.com/cms-sw/cmsdist/pull/8451){:target="_blank"}  from **@cms-sw**: Drop mxnet (cms-sw/cmssw#30432) created: 2023-04-20 08:26:19 merged: 2023-04-25 21:19:46

20. [8450](http://github.com/cms-sw/cmsdist/pull/8450){:target="_blank"}  from **@SiewYan**: Update sherpa to 2.2.15 created: 2023-04-19 12:37:46 merged: 2023-04-19 19:32:07

21. [8449](http://github.com/cms-sw/cmsdist/pull/8449){:target="_blank"}  from **@cms-sw**: [BuildRules] cuda/rocm tests and multi-vec env selection created: 2023-04-19 11:46:31 merged: 2023-04-20 07:13:11

22. [8448](http://github.com/cms-sw/cmsdist/pull/8448){:target="_blank"}  from **@cms-sw**: [BuildRules] Rocm/Cuda unit test improvement created: 2023-04-19 07:16:59 merged: 2023-04-19 10:39:42

23. [8447](http://github.com/cms-sw/cmsdist/pull/8447){:target="_blank"}  from **@cms-sw**: Update frontier_client to 2.10.1 created: 2023-04-18 20:02:50 merged: 2023-04-25 15:28:21

24. [8441](http://github.com/cms-sw/cmsdist/pull/8441){:target="_blank"}  from **@belforte**: bump crab client to v3.230417 created: 2023-04-17 11:45:38 merged: 2023-04-17 20:48:05

25. [8440](http://github.com/cms-sw/cmsdist/pull/8440){:target="_blank"}  from **@cms-sw**: Update tag for Configuration-Generator to V01-04-00 created: 2023-04-16 15:52:59 merged: 2023-04-16 20:22:22

26. [8438](http://github.com/cms-sw/cmsdist/pull/8438){:target="_blank"}  from **@cms-sw**: Update tag for Configuration-Generator to V01-03-00 created: 2023-04-15 13:42:16 merged: 2023-04-15 13:44:32

27. [8437](http://github.com/cms-sw/cmsdist/pull/8437){:target="_blank"}  from **@cms-sw**: created cmssw-el[5,6,7] scripts created: 2023-04-13 12:57:22 merged: 2023-04-14 11:11:23

28. [8435](http://github.com/cms-sw/cmsdist/pull/8435){:target="_blank"}  from **@iarspider**: Updated root to tip of branch v6-26-00-patches created: 2023-04-11 08:14:51 merged: 2023-04-12 20:57:55

29. [8429](http://github.com/cms-sw/cmsdist/pull/8429){:target="_blank"}  from **@cms-sw**: Mass-update python packages created: 2023-04-05 12:40:52 merged: 2023-05-01 20:50:19

30. [8213](http://github.com/cms-sw/cmsdist/pull/8213){:target="_blank"}  from **@cms-sw**: Update LLVM to version 14.0.6 created: 2022-11-30 23:26:40 merged: 2023-04-26 08:44:40
