---
layout: post
rel_link:  "8_1_0_pre2"
title:  "CMSSW_8_1_0_pre2"
date:   2016-04-05 18:51:30
categories: cmssw
relmajor: 8
relminor: 1
relsubminor: 0
relpre: _pre2
---

# CMSSW_8_1_0_pre2
#### Changes since CMSSW_8_1_0_pre1:

[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_8_1_0_pre1...CMSSW_8_1_0_pre2)



1. [13941](http://github.com/cms-sw/cmssw/pull/13941){:target="_blank"}  from **@davidlange6**: more era migration in relval matrix  `comparison`  `pdmv`  created: 2016-04-05 18:36:15 merged: 2016-04-05 18:50:07

2. [13939](http://github.com/cms-sw/cmssw/pull/13939){:target="_blank"}  from **@mdhildreth**: PreMixing era switch for Stage 2 L1 configuration `comparison`  `operations`  created: 2016-04-05 17:58:11 merged: 2016-04-05 18:50:26

3. [13919](http://github.com/cms-sw/cmssw/pull/13919){:target="_blank"}  from **@davidlange6**: move to 2016 era and 2016 hlt where it is working in relvals `alca`  `core`  `hlt`  `l1`  `pdmv`  created: 2016-04-04 17:36:29 merged: 2016-04-04 20:35:31

4. [13913](http://github.com/cms-sw/cmssw/pull/13913){:target="_blank"}  from **@ianna**: Remove Obsolete Customizations `geometry`  created: 2016-04-04 13:09:22 merged: 2016-04-05 14:28:50

5. [13903](http://github.com/cms-sw/cmssw/pull/13903){:target="_blank"}  from **@cms-l1t-offline**: HLT L1T interface updates - trhow exceptions and L1GlobalDecision  80x `hlt`  created: 2016-04-03 19:04:46 merged: 2016-04-04 17:51:34

6. [13901](http://github.com/cms-sw/cmssw/pull/13901){:target="_blank"}  from **@wmtan**: use std::make_shared in framework (again) `core`  created: 2016-04-02 19:21:35 merged: 2016-04-04 19:56:59

7. [13899](http://github.com/cms-sw/cmssw/pull/13899){:target="_blank"}  from **@wmtan**: Use std::shared_ptr and std::make_shared (EventSetup in Simulation) `reconstruction`  `simulation`  created: 2016-04-02 15:38:12 merged: 2016-04-04 21:54:39

8. [13898](http://github.com/cms-sw/cmssw/pull/13898){:target="_blank"}  from **@wmtan**: use std::shared_ptr and std::make_shared (EventSetup in Reco) `alca`  `reconstruction`  created: 2016-04-02 15:34:12 merged: 2016-04-04 21:54:56

9. [13897](http://github.com/cms-sw/cmssw/pull/13897){:target="_blank"}  from **@wmtan**: use std::shared_ptr and std::make_shared (EventSetup in Geometry/Alignment/Visualization) `alca`  `geometry`  `visualization`  created: 2016-04-02 15:27:34 merged: 2016-04-04 17:49:46

10. [13896](http://github.com/cms-sw/cmssw/pull/13896){:target="_blank"}  from **@wmtan**: Use std::shared_ptr and std::make_shared (EventSetup in FastSim) `fastsim`  created: 2016-04-02 15:23:08 merged: 2016-04-04 17:50:08

11. [13895](http://github.com/cms-sw/cmssw/pull/13895){:target="_blank"}  from **@wmtan**: use std::shared_ptr and std::make_shared (EventSetup in Calibration) `alca`  `l1`  created: 2016-04-02 15:19:58 merged: 2016-04-05 14:29:11

12. [13891](http://github.com/cms-sw/cmssw/pull/13891){:target="_blank"}  from **@cms-l1t-offline**: L1Trigger DQM Combo PR 13800 fixed merge conflict `dqm`  `l1`  created: 2016-04-02 11:33:26 merged: 2016-04-05 14:41:15

13. [13885](http://github.com/cms-sw/cmssw/pull/13885){:target="_blank"}  from **@makortel**: Fix compilation under EDM_ML_DEBUG `analysis`  `reconstruction`  created: 2016-04-01 15:01:04 merged: 2016-04-02 06:38:16

14. [13873](http://github.com/cms-sw/cmssw/pull/13873){:target="_blank"}  from **@Sam-Harper**: Bug fix for Electron Tracker Isolation used by HEEP   `reconstruction`  created: 2016-03-31 11:37:47 merged: 2016-04-02 06:38:32

15. [13872](http://github.com/cms-sw/cmssw/pull/13872){:target="_blank"}  from **@bsunanda**: bsunanda:Phase2-hgx47 Update the ganging for BH as discussed in the simulation meeting `geometry`  created: 2016-03-30 16:21:22 merged: 2016-04-02 06:38:47

16. [13870](http://github.com/cms-sw/cmssw/pull/13870){:target="_blank"}  from **@smuzaffar**: remove unused testRandomNumberGenerators binary `core`  created: 2016-03-30 14:37:31 merged: 2016-03-31 07:46:17

17. [13869](http://github.com/cms-sw/cmssw/pull/13869){:target="_blank"}  from **@Sam-Harper**: Eg HLT PM module fixes for the auto->unique ptr central migration `hlt`  created: 2016-03-30 13:37:26 merged: 2016-03-30 16:25:37

18. [13868](http://github.com/cms-sw/cmssw/pull/13868){:target="_blank"}  from **@akhukhun**: fix HF TP transcoder crash. `alca`  `l1`  created: 2016-03-30 12:39:11 merged: 2016-04-02 08:13:03

19. [13867](http://github.com/cms-sw/cmssw/pull/13867){:target="_blank"}  from **@davidlange6**: add some phase2 (sim only) workflows to the default matrix `pdmv`  created: 2016-03-30 12:01:55 merged: 2016-04-02 08:12:23

20. [13866](http://github.com/cms-sw/cmssw/pull/13866){:target="_blank"}  from **@smuzaffar**: Move L1Trigger/CSCTrackFinder/src/core_ files to external package `l1`  created: 2016-03-30 10:59:32 merged: 2016-04-04 17:50:27

21. [13860](http://github.com/cms-sw/cmssw/pull/13860){:target="_blank"}  from **@alja**: 80x Fireworks: Set classic root gui style `comparison`  `visualization`  created: 2016-03-29 21:16:34 merged: 2016-03-30 07:49:46

22. [13859](http://github.com/cms-sw/cmssw/pull/13859){:target="_blank"}  from **@Dr15Jones**: mv test record.cppunit.cpp from DataFormats/FWLite to PhysicsTools/Co `analysis`  `core`  created: 2016-03-29 19:32:14 merged: 2016-03-30 07:45:48

23. [13857](http://github.com/cms-sw/cmssw/pull/13857){:target="_blank"}  from **@jruizvar**: Adding double-electron triggers to EXO DQM (81X) `dqm`  created: 2016-03-29 17:38:42 merged: 2016-03-31 07:50:42

24. [13855](http://github.com/cms-sw/cmssw/pull/13855){:target="_blank"}  from **@wmtan**: Change auto_ptr to unique_ptr in text `core`  created: 2016-03-29 16:38:56 merged: 2016-03-30 07:46:04

25. [13852](http://github.com/cms-sw/cmssw/pull/13852){:target="_blank"}  from **@Martin-Grunewald**: Less verbose HLTPrescaleProvider (81X) `hlt`  created: 2016-03-29 12:14:12 merged: 2016-03-30 07:46:41

26. [13850](http://github.com/cms-sw/cmssw/pull/13850){:target="_blank"}  from **@alja**: 8x Fireworks: move clipping cone apex in 3D region view  `comparison`  `visualization`  created: 2016-03-28 21:38:50 merged: 2016-03-29 08:33:03

27. [13848](http://github.com/cms-sw/cmssw/pull/13848){:target="_blank"}  from **@bsunanda**: bsunanda:Phase2-gem12 Get geometry information of GEM detector `geometry`  created: 2016-03-28 15:36:51 merged: 2016-03-30 07:46:58

28. [13846](http://github.com/cms-sw/cmssw/pull/13846){:target="_blank"}  from **@Sam-Harper**: E/g HLT Pixel Match Variable Producer `hlt`  created: 2016-03-27 08:04:24 merged: 2016-03-30 07:54:44

29. [13834](http://github.com/cms-sw/cmssw/pull/13834){:target="_blank"}  from **@bsunanda**: bsunanda:Phase2-gem11 More realistic ME0 geometry and extended GE21 geometry `geometry`  created: 2016-03-24 19:35:01 merged: 2016-04-02 08:11:27

30. [13831](http://github.com/cms-sw/cmssw/pull/13831){:target="_blank"}  from **@VinInn**: Speedup Gsf component merging, return components by const reference `analysis`  `reconstruction`  created: 2016-03-24 15:17:07 merged: 2016-04-04 17:50:49

31. [13823](http://github.com/cms-sw/cmssw/pull/13823){:target="_blank"}  from **@lihux25**: Fix crash in HcalDumpConditions.cc  `comparison`  `db`  created: 2016-03-24 05:11:19 merged: 2016-03-26 08:13:23

32. [13822](http://github.com/cms-sw/cmssw/pull/13822){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-hcx76 Remove obsolete parameter definitions for relabelling at DIGI step `geometry`  `simulation`  created: 2016-03-23 22:28:22 merged: 2016-03-30 07:54:39

33. [13821](http://github.com/cms-sw/cmssw/pull/13821){:target="_blank"}  from **@mmusich**: Introducing realistic phase-I simuation key `alca`  `pdmv`  `simulation`  created: 2016-03-23 21:59:44 merged: 2016-03-28 10:18:18

34. [13820](http://github.com/cms-sw/cmssw/pull/13820){:target="_blank"}  from **@wmtan**: Use unique_ptr, not auto_ptr `analysis`  `core`  `reconstruction`  created: 2016-03-23 20:03:30 merged: 2016-03-28 20:44:27

35. [13819](http://github.com/cms-sw/cmssw/pull/13819){:target="_blank"}  from **@VinInn**: Speed seeding for HLT `geometry`  `reconstruction`  `simulation`  created: 2016-03-23 15:08:10 merged: 2016-04-04 17:51:02

36. [13814](http://github.com/cms-sw/cmssw/pull/13814){:target="_blank"}  from **@hroskes**: Fix consumes for alignment validations `alca`  `reconstruction`  created: 2016-03-23 13:43:41 merged: 2016-03-28 10:17:56

37. [13809](http://github.com/cms-sw/cmssw/pull/13809){:target="_blank"}  from **@cms-l1t-offline**: Fix crash in CorrelationConditions uGT emulator `l1`  created: 2016-03-23 07:23:50 merged: 2016-03-24 08:36:17

38. [13808](http://github.com/cms-sw/cmssw/pull/13808){:target="_blank"}  from **@cms-l1t-offline**: Fix crash in CorrelationConditions uGT emulator  `l1`  created: 2016-03-23 07:22:12 merged: 2016-03-23 18:09:14

39. [13803](http://github.com/cms-sw/cmssw/pull/13803){:target="_blank"}  from **@akhukhun**: Adjusting 1x1 HF output LUTs `alca`  `comparison`  `l1`  created: 2016-03-22 16:49:16 merged: 2016-03-24 10:47:20

40. [13801](http://github.com/cms-sw/cmssw/pull/13801){:target="_blank"}  from **@mtosi**: drop pixel vertices (they are not available since run2 !) `dqm`  created: 2016-03-22 16:18:37 merged: 2016-03-25 06:33:21

41. [13799](http://github.com/cms-sw/cmssw/pull/13799){:target="_blank"}  from **@bsunanda**: bsunanda:Phase2-hgx46 Update a test cfi file for testing finer segmentation of BH `geometry`  created: 2016-03-22 14:04:20 merged: 2016-03-28 20:41:15

42. [13797](http://github.com/cms-sw/cmssw/pull/13797){:target="_blank"}  from **@hengne**: relval matrix updates  `pdmv`  created: 2016-03-22 10:49:25 merged: 2016-03-28 10:22:17

43. [13793](http://github.com/cms-sw/cmssw/pull/13793){:target="_blank"}  from **@jdolen**: Update miniAOD AK8 userFloat content. Add PUPPI substructure. Remove CMSTT. `analysis`  `comparison`  `reconstruction`  created: 2016-03-21 18:26:25 merged: 2016-03-28 10:20:16

44. [13792](http://github.com/cms-sw/cmssw/pull/13792){:target="_blank"}  from **@Martin-Grunewald**: Fix forgotten saveTags default switchover (81X) `hlt`  created: 2016-03-21 15:32:00 merged: 2016-03-22 16:52:15

45. [13791](http://github.com/cms-sw/cmssw/pull/13791){:target="_blank"}  from **@Martin-Grunewald**: Fix forgotten saveTags default switchover `hlt`  created: 2016-03-21 15:28:26 merged: 2016-03-22 16:40:46

46. [13790](http://github.com/cms-sw/cmssw/pull/13790){:target="_blank"}  from **@mmusich**: Adding the Stage-II L1 menu to phase-I upgrade simulation `alca`  created: 2016-03-21 13:53:50 merged: 2016-03-22 16:40:59

47. [13787](http://github.com/cms-sw/cmssw/pull/13787){:target="_blank"}  from **@cms-l1t-offline**: Fixes in L1T Calo packers - useful for data taking - 81x `l1`  created: 2016-03-21 12:34:24 merged: 2016-03-22 16:51:52

48. [13786](http://github.com/cms-sw/cmssw/pull/13786){:target="_blank"}  from **@cms-l1t-offline**: Fixes in L1T Calo packers - useful for data taking - 80x `l1`  created: 2016-03-21 10:53:18 merged: 2016-03-22 16:40:21

49. [13784](http://github.com/cms-sw/cmssw/pull/13784){:target="_blank"}  from **@mmusich**: Adding the Stage-II L1 menu to phase-I upgrade simulation `alca`  created: 2016-03-21 08:55:57 merged: 2016-03-21 18:33:58

50. [13782](http://github.com/cms-sw/cmssw/pull/13782){:target="_blank"}  from **@cms-l1t-offline**: Change LogWarning to LogTrace `hlt`  created: 2016-03-20 13:26:18 merged: 2016-03-21 07:35:31

51. [13781](http://github.com/cms-sw/cmssw/pull/13781){:target="_blank"}  from **@cms-l1t-offline**: Change LogWarning to LogTrace `hlt`  created: 2016-03-20 13:25:40 merged: 2016-03-21 07:36:36

52. [13780](http://github.com/cms-sw/cmssw/pull/13780){:target="_blank"}  from **@cms-l1t-offline**: Fix TriggerObjectMap filling with a long L1T menu. `l1`  created: 2016-03-19 02:52:13 merged: 2016-03-22 16:40:35

53. [13779](http://github.com/cms-sw/cmssw/pull/13779){:target="_blank"}  from **@cms-l1t-offline**: Fix TriggerObjectMap filling with a long L1T menu. `l1`  created: 2016-03-19 02:48:20 merged: 2016-03-22 16:52:32

54. [13778](http://github.com/cms-sw/cmssw/pull/13778){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-hcx75 Backport the changes from PR 13683 (2016 Geometry of Hcal) needed to work on updating constants to Hcal DB `geometry`  created: 2016-03-18 21:58:15 merged: 2016-03-22 16:42:16

55. [13774](http://github.com/cms-sw/cmssw/pull/13774){:target="_blank"}  from **@civanch**: cleanup of the TestBeam `simulation`  created: 2016-03-18 16:16:35 merged: 2016-03-19 07:39:20

56. [13773](http://github.com/cms-sw/cmssw/pull/13773){:target="_blank"}  from **@mandrenguyen**: Filter to select HLT paths corresponding to peripheral HI events `reconstruction`  created: 2016-03-18 16:04:20 merged: 2016-03-23 10:51:04

57. [13772](http://github.com/cms-sw/cmssw/pull/13772){:target="_blank"}  from **@jpazzini**: FEDid-wheel mapping fixed for +1 and +2 `comparison`  `l1`  created: 2016-03-18 11:22:20 merged: 2016-03-22 16:54:18

58. [13770](http://github.com/cms-sw/cmssw/pull/13770){:target="_blank"}  from **@ggovi**: Allow empty user text in tag log entries `db`  created: 2016-03-18 09:36:08 merged: 2016-03-25 06:32:48

59. [13769](http://github.com/cms-sw/cmssw/pull/13769){:target="_blank"}  from **@wmtan**: Deep const correctness for edm::value_ptr `core`  created: 2016-03-18 03:35:14 merged: 2016-03-21 18:33:41

60. [13768](http://github.com/cms-sw/cmssw/pull/13768){:target="_blank"}  from **@cms-l1t-offline**: Bring L1T emulation up to date with l1t-tsg-v4 tag `alca`  `db`  `l1`  created: 2016-03-18 03:13:08 merged: 2016-04-01 08:28:51

61. [13766](http://github.com/cms-sw/cmssw/pull/13766){:target="_blank"}  from **@CTPPS**: Adding new detectors - integration of RomanPot detectors for CTPPS project `comparison`  `simulation`  created: 2016-03-17 19:39:27 merged: 2016-03-21 08:54:07

62. [13765](http://github.com/cms-sw/cmssw/pull/13765){:target="_blank"}  from **@wmtan**: Remove duplicated functions in Provenance.h `core`  `dqm`  `hlt`  created: 2016-03-17 19:22:59 merged: 2016-03-18 08:29:58

63. [13762](http://github.com/cms-sw/cmssw/pull/13762){:target="_blank"}  from **@mplaner**: updated DQM module for Higgs->diphoton 2016 trigger `dqm`  created: 2016-03-17 19:04:28 merged: 2016-03-22 16:59:40

64. [13756](http://github.com/cms-sw/cmssw/pull/13756){:target="_blank"}  from **@thuer**: Cmssw 81 x sherpa weights `generators`  created: 2016-03-17 15:00:50 merged: 2016-03-22 17:32:21

65. [13755](http://github.com/cms-sw/cmssw/pull/13755){:target="_blank"}  from **@boudoul**: Revert "updating  TrackerGeometry in Geometry/TrackerGeometryBuilder to accom" `geometry`  `simulation`  created: 2016-03-17 14:12:03 merged: 2016-03-19 07:39:35

66. [13753](http://github.com/cms-sw/cmssw/pull/13753){:target="_blank"}  from **@makortel**: Quadruplet seeding by propagating triplet to 4th layer `alca`  `hlt`  `reconstruction`  created: 2016-03-17 12:10:02 merged: 2016-03-29 08:37:52

67. [13751](http://github.com/cms-sw/cmssw/pull/13751){:target="_blank"}  from **@cms-btv-pog**: Bugfix in the BoostedDoubleSV tagger (80X) `reconstruction`  created: 2016-03-17 11:06:48 merged: 2016-03-21 07:29:46

68. [13749](http://github.com/cms-sw/cmssw/pull/13749){:target="_blank"}  from **@cms-btv-pog**: Bugfix in the BoostedDoubleSV tagger (81X) `reconstruction`  created: 2016-03-17 11:04:44 merged: 2016-03-19 07:39:46

69. [13748](http://github.com/cms-sw/cmssw/pull/13748){:target="_blank"}  from **@lgray**: Fix non-linearity from C++ in HGCDigitizer `simulation`  created: 2016-03-17 09:26:00 merged: 2016-03-18 13:16:31

70. [13747](http://github.com/cms-sw/cmssw/pull/13747){:target="_blank"}  from **@slava77**: locally named load of FEVT in hotlineSkims (same as #13746) `alca`  created: 2016-03-17 07:44:06 merged: 2016-03-17 09:03:20

71. [13746](http://github.com/cms-sw/cmssw/pull/13746){:target="_blank"}  from **@slava77**: locally named load of FEVT in hotlineSkims `alca`  created: 2016-03-17 07:42:41 merged: 2016-03-17 09:02:18

72. [13745](http://github.com/cms-sw/cmssw/pull/13745){:target="_blank"}  from **@wmtan**: Remove Obsolete Header HideStdUniquePtrFromRoot.h `core`  `reconstruction`  created: 2016-03-16 22:26:48 merged: 2016-03-18 08:30:12

73. [13742](http://github.com/cms-sw/cmssw/pull/13742){:target="_blank"}  from **@jpazzini**: FEDid-wheel mapping fixed for +1 and +2 `l1`  created: 2016-03-16 15:39:26 merged: 2016-03-22 16:53:41

74. [13741](http://github.com/cms-sw/cmssw/pull/13741){:target="_blank"}  from **@alja**: 80x Fireworks: Port change in FWSiPixelClusterPB from 71 `comparison`  `visualization`  created: 2016-03-16 14:02:44 merged: 2016-03-17 09:04:16

75. [13740](http://github.com/cms-sw/cmssw/pull/13740){:target="_blank"}  from **@mmusich**: Global Tag updates for 80x: introducing new L1 uGT stage-II menu and MC updates for Digi-Reco `alca`  `pdmv`  created: 2016-03-16 13:55:36 merged: 2016-03-21 08:33:32

76. [13739](http://github.com/cms-sw/cmssw/pull/13739){:target="_blank"}  from **@jsalfeld**: 80 x add 2016 spring mc pileup scenario v1 `comparison`  `operations`  `simulation`  created: 2016-03-16 13:40:13 merged: 2016-03-16 13:41:03

77. [13738](http://github.com/cms-sw/cmssw/pull/13738){:target="_blank"}  from **@makortel**: Fix typo in Types.py `core`  created: 2016-03-16 12:02:35 merged: 2016-03-17 09:01:59

78. [13737](http://github.com/cms-sw/cmssw/pull/13737){:target="_blank"}  from **@ianna**: Add 2023 Scenarios `comparison`  `visualization`  created: 2016-03-16 09:55:11 merged: 2016-03-17 09:01:45

79. [13736](http://github.com/cms-sw/cmssw/pull/13736){:target="_blank"}  from **@makortel**: Introduce new tracking sequence for phase1 (2017) `dqm`  `operations`  `reconstruction`  created: 2016-03-16 07:55:18 merged: 2016-03-22 17:32:52

80. [13735](http://github.com/cms-sw/cmssw/pull/13735){:target="_blank"}  from **@wmtan**: Remove unneeded selector `core`  created: 2016-03-15 21:17:23 merged: 2016-03-16 16:47:04

81. [13732](http://github.com/cms-sw/cmssw/pull/13732){:target="_blank"}  from **@Martin-Grunewald**: Need unqiue cfi file names in fillDescription to avoid overwriting in HLT (81X) `alca`  `hlt`  created: 2016-03-15 16:38:21 merged: 2016-03-16 12:42:52

82. [13730](http://github.com/cms-sw/cmssw/pull/13730){:target="_blank"}  from **@makortel**: Fix RectangularEtaPhiTrackingRegion (80X) `reconstruction`  created: 2016-03-15 16:38:09 merged: 2016-03-17 09:03:35

83. [13729](http://github.com/cms-sw/cmssw/pull/13729){:target="_blank"}  from **@makortel**: Fix RectangularEtaPhiTrackingRegion `reconstruction`  created: 2016-03-15 16:37:50 merged: 2016-03-17 09:01:31

84. [13728](http://github.com/cms-sw/cmssw/pull/13728){:target="_blank"}  from **@Martin-Grunewald**: Need unqiue cfi file names in fillDescription to avoid overwriting in HLT (80X) `alca`  `hlt`  created: 2016-03-15 16:34:12 merged: 2016-03-16 13:17:38

85. [13727](http://github.com/cms-sw/cmssw/pull/13727){:target="_blank"}  from **@Dr15Jones**: Made EarlyDeleteHelper thread-safe `core`  created: 2016-03-15 13:57:31 merged: 2016-03-15 16:47:38

86. [13724](http://github.com/cms-sw/cmssw/pull/13724){:target="_blank"}  from **@dimattia**: Implementation of the new gain Calibration paradigma in 8_1_X `alca`  `dqm`  `operations`  `pdmv`  created: 2016-03-15 11:12:16 merged: 2016-03-24 08:45:26

87. [13722](http://github.com/cms-sw/cmssw/pull/13722){:target="_blank"}  from **@wmtan**: Avoid unneeded retrievel of per event provenance `alca`  `analysis`  `core`  `dqm`  `reconstruction`  `visualization`  created: 2016-03-15 03:33:56 merged: 2016-03-16 12:48:57

88. [13720](http://github.com/cms-sw/cmssw/pull/13720){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-alca37 Fix bug to avoid run-time error for Pythia8 `generators`  created: 2016-03-14 19:23:29 merged: 2016-03-15 14:43:56

89. [13719](http://github.com/cms-sw/cmssw/pull/13719){:target="_blank"}  from **@bsunanda**: bsunanda"Phase2-hgx44 Complete the example of TB for HGCal `reconstruction`  `simulation`  created: 2016-03-14 18:44:57 merged: 2016-03-17 09:01:17

90. [13718](http://github.com/cms-sw/cmssw/pull/13718){:target="_blank"}  from **@Dr15Jones**: Pass non nullptr to std::unique_ptr guard `core`  created: 2016-03-14 17:06:05 merged: 2016-03-15 08:41:57

91. [13716](http://github.com/cms-sw/cmssw/pull/13716){:target="_blank"}  from **@hengne**: Fix re-reco golden json, adding 50ns lumi blocks coverage `pdmv`  created: 2016-03-14 15:12:49 merged: 2016-03-15 08:43:57

92. [13715](http://github.com/cms-sw/cmssw/pull/13715){:target="_blank"}  from **@hengne**: Fix re-reco golden json, adding 50ns lumi blocks coverage `pdmv`  created: 2016-03-14 15:08:08 merged: 2016-03-16 13:10:34

93. [13714](http://github.com/cms-sw/cmssw/pull/13714){:target="_blank"}  from **@ianna**: Sync Materials in 2015 Dev Scenario `geometry`  created: 2016-03-14 14:12:22 merged: 2016-03-15 11:08:58

94. [13711](http://github.com/cms-sw/cmssw/pull/13711){:target="_blank"}  from **@ghellwig**: Multi-IOV weak mode constraints (Backport of #13710) `alca`  created: 2016-03-14 13:13:12 merged: 2016-03-22 16:41:20

95. [13710](http://github.com/cms-sw/cmssw/pull/13710){:target="_blank"}  from **@ghellwig**: Multi-IOV weak mode constraints `alca`  created: 2016-03-14 13:11:41 merged: 2016-03-17 08:59:21

96. [13709](http://github.com/cms-sw/cmssw/pull/13709){:target="_blank"}  from **@mmusich**: Global Tag updates for 81x: introducing new L1 uGT stage-II menu and MC updates for Digi-Reco  `alca`  `pdmv`  created: 2016-03-14 13:01:00 merged: 2016-03-18 12:13:32

97. [13708](http://github.com/cms-sw/cmssw/pull/13708){:target="_blank"}  from **@lgray**: Picosecond stepping for HGC and FastTimer SDs `simulation`  created: 2016-03-14 12:57:12 merged: 2016-03-19 07:39:56

98. [13707](http://github.com/cms-sw/cmssw/pull/13707){:target="_blank"}  from **@cms-l1t-offline**: Rekovic hlt 802 seed unpacked gt (pruning on top of PR 13703) `hlt`  created: 2016-03-14 10:54:36 merged: 2016-03-15 08:42:18

99. [13706](http://github.com/cms-sw/cmssw/pull/13706){:target="_blank"}  from **@suchandradutta**: updating  TrackerGeometry in Geometry/TrackerGeometryBuilder to accom `geometry`  `simulation`  created: 2016-03-14 10:47:40 merged: 2016-03-15 09:39:19

100. [13705](http://github.com/cms-sw/cmssw/pull/13705){:target="_blank"}  from **@ianna**: Fix Validation Script `db`  `dqm`  `geometry`  created: 2016-03-14 10:46:21 merged: 2016-03-15 16:48:01

101. [13703](http://github.com/cms-sw/cmssw/pull/13703){:target="_blank"}  from **@cms-l1t-offline**: Rekovic hlt 802 seed unpacked gt `hlt`  created: 2016-03-12 15:53:41 merged: 2016-03-14 08:46:49

102. [13702](http://github.com/cms-sw/cmssw/pull/13702){:target="_blank"}  from **@cms-l1t-offline**: Rekovic hlt 802 seed unpacked gt `hlt`  created: 2016-03-12 15:52:13 merged: 2016-03-15 09:32:39

103. [13698](http://github.com/cms-sw/cmssw/pull/13698){:target="_blank"}  from **@Dr15Jones**: Refactored ProductHolders `core`  created: 2016-03-11 20:30:03 merged: 2016-03-14 08:40:00

104. [13695](http://github.com/cms-sw/cmssw/pull/13695){:target="_blank"}  from **@jsalfeld**: 80 x add 2016 spring mc pileup scenario v1 `operations`  `simulation`  created: 2016-03-11 14:36:04 merged: 2016-03-16 13:40:22

105. [13693](http://github.com/cms-sw/cmssw/pull/13693){:target="_blank"}  from **@Martin-Grunewald**:  Fix: 50ns used legacy L1 (backport of #13692) `operations`  created: 2016-03-11 13:25:29 merged: 2016-03-15 17:04:45

106. [13691](http://github.com/cms-sw/cmssw/pull/13691){:target="_blank"}  from **@dmitrijus**: Fix DQM/L1TMonitor BuildFile `dqm`  created: 2016-03-11 11:42:36 merged: 2016-03-15 08:42:38

107. [13688](http://github.com/cms-sw/cmssw/pull/13688){:target="_blank"}  from **@slava77**: cleanup unnamed sequences in TrackingDQMSourceTier0\* `dqm`  created: 2016-03-11 08:31:25 merged: 2016-03-15 08:43:00

108. [13687](http://github.com/cms-sw/cmssw/pull/13687){:target="_blank"}  from **@bsunanda**: bsunanda:Phase2-hgx43 Takes care of half cell positions `geometry`  created: 2016-03-11 02:52:02 merged: 2016-03-15 08:43:11

109. [13686](http://github.com/cms-sw/cmssw/pull/13686){:target="_blank"}  from **@cms-btv-pog**: PAT btag update (80X) `analysis`  `reconstruction`  created: 2016-03-11 02:13:44 merged: 2016-03-17 09:05:38

110. [13685](http://github.com/cms-sw/cmssw/pull/13685){:target="_blank"}  from **@cms-btv-pog**: PAT btag update (81X) `analysis`  `reconstruction`  created: 2016-03-11 02:05:31 merged: 2016-03-17 08:57:58

111. [13684](http://github.com/cms-sw/cmssw/pull/13684){:target="_blank"}  from **@bendavid**: Changes needed for SUSY parameter scans (80x) `analysis`  `generators`  `reconstruction`  created: 2016-03-10 21:41:32 merged: 2016-03-17 09:05:12

112. [13683](http://github.com/cms-sw/cmssw/pull/13683){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-hcx74 Add scenario to help testing 2016 HCAL setup `geometry`  created: 2016-03-10 19:13:30 merged: 2016-03-17 18:45:49

113. [13682](http://github.com/cms-sw/cmssw/pull/13682){:target="_blank"}  from **@slava77**:  delete loaded cleanPatJets after the temporary load if it was not around already (same as #13681 ) `analysis`  created: 2016-03-10 19:02:45 merged: 2016-03-17 09:07:25

114. [13681](http://github.com/cms-sw/cmssw/pull/13681){:target="_blank"}  from **@slava77**: delete loaded cleanPatJets after the temporary load if it was not around already `analysis`  created: 2016-03-10 19:00:30 merged: 2016-03-12 07:13:59

115. [13680](http://github.com/cms-sw/cmssw/pull/13680){:target="_blank"}  from **@ianna**: Migrate to CondDB Configuration `db`  created: 2016-03-10 15:42:41 merged: 2016-03-15 09:37:35

116. [13679](http://github.com/cms-sw/cmssw/pull/13679){:target="_blank"}  from **@vanbesien**: Fixed the missing linking between plot and refplot (8_1_X) `dqm`  created: 2016-03-10 15:14:06 merged: 2016-03-12 07:13:42

117. [13678](http://github.com/cms-sw/cmssw/pull/13678){:target="_blank"}  from **@vanbesien**: Fixed the missing linking between plot and refplot (8_0_X) `dqm`  created: 2016-03-10 15:14:03 merged: 2016-03-15 17:05:21

118. [13677](http://github.com/cms-sw/cmssw/pull/13677){:target="_blank"}  from **@lgray**: Add accessor to HGCalDDDConstants `geometry`  created: 2016-03-10 14:41:25 merged: 2016-03-11 09:54:51

119. [13676](http://github.com/cms-sw/cmssw/pull/13676){:target="_blank"}  from **@mbandrews**: Fix binning in ZS filter SRTask plots `dqm`  created: 2016-03-10 12:03:00 merged: 2016-03-15 17:06:13

120. [13675](http://github.com/cms-sw/cmssw/pull/13675){:target="_blank"}  from **@mbandrews**: Add channel status (with fixed desc). Add laser threshold. `dqm`  created: 2016-03-10 11:50:45 merged: 2016-03-15 17:06:00

121. [13672](http://github.com/cms-sw/cmssw/pull/13672){:target="_blank"}  from **@bouril**: Changed the struct Count to avoid thread safety warnings `simulation`  created: 2016-03-09 22:22:19 merged: 2016-03-14 08:46:31

122. [13671](http://github.com/cms-sw/cmssw/pull/13671){:target="_blank"}  from **@boudoul**: Workflows for 2023 including Phase2 Tracker (gensim step) `geometry`  `operations`  `pdmv`  `simulation`  created: 2016-03-09 18:03:03 merged: 2016-03-10 19:45:35

123. [13668](http://github.com/cms-sw/cmssw/pull/13668){:target="_blank"}  from **@mdhildreth**: Add automatic turn-off of tracker digiSimLink production in standard production mode `simulation`  created: 2016-03-09 16:12:09 merged: 2016-03-15 17:06:58

124. [13666](http://github.com/cms-sw/cmssw/pull/13666){:target="_blank"}  from **@makortel**: Migrate remaining 2017 reco customizations to era `operations`  `reconstruction`  `simulation`  created: 2016-03-09 15:17:06 merged: 2016-03-15 09:36:25

125. [13665](http://github.com/cms-sw/cmssw/pull/13665){:target="_blank"}  from **@pargali**: Top dqm singletopbtagfix `dqm`  created: 2016-03-09 15:09:26 merged: 2016-03-24 08:33:47

126. [13663](http://github.com/cms-sw/cmssw/pull/13663){:target="_blank"}  from **@deguio**: add protection for T0 configuration query `dqm`  created: 2016-03-09 13:33:00 merged: 2016-03-15 17:05:32

127. [13654](http://github.com/cms-sw/cmssw/pull/13654){:target="_blank"}  from **@bsunanda**: bsunanda:Phase2-hgx42 Making an application for TB simulation of HGCal `geometry`  `simulation`  created: 2016-03-08 21:57:07 merged: 2016-03-10 19:46:46

128. [13644](http://github.com/cms-sw/cmssw/pull/13644){:target="_blank"}  from **@ghellwig**: Declare 'seedOnlyFromAbove_' as 'int' (Backport of #13643). `alca`  created: 2016-03-08 16:25:34 merged: 2016-03-17 09:13:12

129. [13641](http://github.com/cms-sw/cmssw/pull/13641){:target="_blank"}  from **@ahinzmann**: Add PU id working points to MiniAOD `analysis`  `reconstruction`  created: 2016-03-08 14:16:02 merged: 2016-03-17 09:05:56

130. [13626](http://github.com/cms-sw/cmssw/pull/13626){:target="_blank"}  from **@bsunanda**: bsunanda:Phase2 hgx41Validation code due to Maksat `dqm`  `simulation`  created: 2016-03-07 15:50:10 merged: 2016-03-18 16:23:28

131. [13623](http://github.com/cms-sw/cmssw/pull/13623){:target="_blank"}  from **@gpetruc**: Trigger matching with tracker muons (80X) `analysis`  `comparison`  created: 2016-03-07 14:57:39 merged: 2016-03-17 09:08:22

132. [13621](http://github.com/cms-sw/cmssw/pull/13621){:target="_blank"}  from **@Martin-Grunewald**: Remove extra parameter from HLTL1TSeed module `hlt`  created: 2016-03-07 13:35:50 merged: 2016-03-15 09:39:54

133. [13606](http://github.com/cms-sw/cmssw/pull/13606){:target="_blank"}  from **@ferencek**: Protect default PAT jet configuration (81X) `analysis`  `reconstruction`  created: 2016-03-04 23:59:23 merged: 2016-03-14 08:41:53

134. [13605](http://github.com/cms-sw/cmssw/pull/13605){:target="_blank"}  from **@ferencek**: Protect default PAT jet configuration (80X) `analysis`  `reconstruction`  created: 2016-03-04 22:26:48 merged: 2016-03-17 11:12:28

135. [13603](http://github.com/cms-sw/cmssw/pull/13603){:target="_blank"}  from **@mandrenguyen**: Added customizations to run pp reco on peripheral HI events `reconstruction`  created: 2016-03-04 18:51:39 merged: 2016-03-12 07:17:38

136. [13596](http://github.com/cms-sw/cmssw/pull/13596){:target="_blank"}  from **@ssekmen**: Hlt hcal movemodulestol1t `alca`  `hlt`  `reconstruction`  created: 2016-03-04 13:50:28 merged: 2016-03-15 09:31:09

137. [13590](http://github.com/cms-sw/cmssw/pull/13590){:target="_blank"}  from **@makortel**: Enable all working DQM and validation modules for 2017 `dqm`  `simulation`  created: 2016-03-04 09:23:16 merged: 2016-03-17 18:50:41

138. [13577](http://github.com/cms-sw/cmssw/pull/13577){:target="_blank"}  from **@degano**: [CondFormats/SiPixelObjects] Solve warning found by gcc 5.3.0 `alca`  `db`  created: 2016-03-03 11:15:07 merged: 2016-03-25 06:29:08

139. [13572](http://github.com/cms-sw/cmssw/pull/13572){:target="_blank"}  from **@sarafiorendi**: migration to stage-2 L1 for muon modules `hlt`  `reconstruction`  created: 2016-03-03 10:55:08 merged: 2016-03-15 09:30:56

140. [13566](http://github.com/cms-sw/cmssw/pull/13566){:target="_blank"}  from **@jasperlauwers**: Correct QuadPFJet pathnames `dqm`  created: 2016-03-03 09:47:23 merged: 2016-03-15 14:50:15

141. [13558](http://github.com/cms-sw/cmssw/pull/13558){:target="_blank"}  from **@Sam-Harper**: EG L1S1 to L1S2 migration `hlt`  created: 2016-03-02 17:31:43 merged: 2016-03-15 09:23:46

142. [13520](http://github.com/cms-sw/cmssw/pull/13520){:target="_blank"}  from **@ianna**: 2016 Geometry Scenario Scripts `db`  created: 2016-02-29 15:26:28 merged: 2016-03-11 09:55:45

143. [13496](http://github.com/cms-sw/cmssw/pull/13496){:target="_blank"}  from **@mmusich**: Fixing 80X relval alcareco in express test `pdmv`  created: 2016-02-26 15:25:07 merged: 2016-03-17 09:17:37

144. [13484](http://github.com/cms-sw/cmssw/pull/13484){:target="_blank"}  from **@alberto-sanchez**: Adding tracks from V0, and fixing bug in photon conversion producer for 80x `analysis`  `comparison`  created: 2016-02-25 19:56:13 merged: 2016-03-17 09:08:50

145. [13460](http://github.com/cms-sw/cmssw/pull/13460){:target="_blank"}  from **@jruizvar**: Remove obsolete files in the HLT SUSY Validation package `dqm`  created: 2016-02-24 16:52:27 merged: 2016-03-17 09:16:18

146. [13413](http://github.com/cms-sw/cmssw/pull/13413){:target="_blank"}  from **@rrabadan**: StoNCorrOnTrack in  modules with the highest values `dqm`  created: 2016-02-20 21:29:53 merged: 2016-03-17 09:16:42

147. [13404](http://github.com/cms-sw/cmssw/pull/13404){:target="_blank"}  from **@schneiml**: DQM TrackerMonitorTrack improvements (80X version) `alca`  `dqm`  created: 2016-02-19 09:35:10 merged: 2016-03-17 09:18:33

148. [13398](http://github.com/cms-sw/cmssw/pull/13398){:target="_blank"}  from **@schneiml**: Add cuts to SiStripMonitorTrack `dqm`  created: 2016-02-18 17:14:20 merged: 2016-03-17 09:18:45

149. [13393](http://github.com/cms-sw/cmssw/pull/13393){:target="_blank"}  from **@schneiml**: DQM TrackerMonitorTrack improvements `alca`  `dqm`  created: 2016-02-18 14:23:44 merged: 2016-03-15 08:43:40

150. [13373](http://github.com/cms-sw/cmssw/pull/13373){:target="_blank"}  from **@alexeybaskakov**: CompHEP interface to Pythia8 `comparison`  `generators`  created: 2016-02-18 10:06:40 merged: 2016-03-17 13:22:39

151. [13361](http://github.com/cms-sw/cmssw/pull/13361){:target="_blank"}  from **@matz-e**: Fix the hcaletValue function. `alca`  `db`  `dqm`  `l1`  created: 2016-02-18 10:03:24 merged: 2016-03-17 14:22:49

152. [13347](http://github.com/cms-sw/cmssw/pull/13347){:target="_blank"}  from **@clacaputo**: Validation module for ME0 Detector (Phase2 Upgrade) `dqm`  created: 2016-02-18 09:59:38 merged: 2016-03-28 10:08:38

153. [13295](http://github.com/cms-sw/cmssw/pull/13295){:target="_blank"}  from **@mbandrews**: ECALbyLumi+Timing `dqm`  created: 2016-02-15 23:57:42 merged: 2016-03-17 09:20:17

154. [13115](http://github.com/cms-sw/cmssw/pull/13115){:target="_blank"}  from **@cms-met**: MET PAT tool update + update of MET significance `analysis`  `reconstruction`  created: 2016-01-28 19:16:06 merged: 2016-03-17 09:07:07

155. [12985](http://github.com/cms-sw/cmssw/pull/12985){:target="_blank"}  from **@jfernan2**: Added DaqSource emulator using DaqFakeReader `alca`  created: 2016-01-19 10:09:06 merged: 2016-03-22 16:42:03

#### CMSDIST Changes between Tags REL/CMSSW_8_1_0_pre1/slc6_amd64_gcc530 and REL/CMSSW_8_1_0_pre2/slc6_amd64_gcc530:

[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_8_1_0_pre1/slc6_amd64_gcc530...REL/CMSSW_8_1_0_pre2/slc6_amd64_gcc530)



1. [2219](http://github.com/cms-sw/cmsdist/pull/2219){:target="_blank"}  from **@smuzaffar**: Move L1Trigger/CSCTrackFinder/src/core_ files to external package created: 2016-03-30 10:58:21 merged: 2016-04-04 17:50:34

2. [2215](http://github.com/cms-sw/cmsdist/pull/2215){:target="_blank"}  from **@smuzaffar**: back-port cmsswdata changes from next to stable branch created: 2016-03-24 08:06:51 merged: 2016-03-24 08:07:05

3. [2214](http://github.com/cms-sw/cmsdist/pull/2214){:target="_blank"}  from **@smuzaffar**: Updated root to tip of 39e926b created: 2016-03-23 21:05:13 merged: 2016-03-23 21:05:18

4. [2208](http://github.com/cms-sw/cmsdist/pull/2208){:target="_blank"}  from **@degano**: Add data files for L1Trigger/L1THGCal. created: 2016-03-21 13:44:28 merged: 2016-03-21 13:44:33

5. [2206](http://github.com/cms-sw/cmsdist/pull/2206){:target="_blank"}  from **@degano**: Advance data for L1Trigger/ L1TCalorimeter, L1TGlobal and L1TMuon. created: 2016-03-19 18:15:14 merged: 2016-03-19 18:15:42

6. [2204](http://github.com/cms-sw/cmsdist/pull/2204){:target="_blank"}  from **@smuzaffar**: Updated root to tip of 3abd13e created: 2016-03-18 10:17:36 merged: 2016-03-18 10:17:48

7. [2202](http://github.com/cms-sw/cmsdist/pull/2202){:target="_blank"}  from **@degano**: Advance data for L1Trigger/ L1TCalorimeter, L1TGlobal and L1TMuon. created: 2016-03-18 09:18:46 merged: 2016-03-18 13:11:10

8. [2197](http://github.com/cms-sw/cmsdist/pull/2197){:target="_blank"}  from **@degano**: New release for GeneratorInterface/EvtGenInterface. created: 2016-03-17 09:18:28 merged: 2016-03-18 09:07:53

9. [2194](http://github.com/cms-sw/cmsdist/pull/2194){:target="_blank"}  from **@smuzaffar**: properly update buildfile dependency information for patch releases created: 2016-03-16 21:59:15 merged: 2016-03-16 21:59:22

10. [2193](http://github.com/cms-sw/cmsdist/pull/2193){:target="_blank"}  from **@smuzaffar**: Update tkonline 80x created: 2016-03-16 19:45:57 merged: 2016-03-16 21:54:53

11. [2181](http://github.com/cms-sw/cmsdist/pull/2181){:target="_blank"}  from **@degano**: Advance data for Fireworks/Geometry. created: 2016-03-04 15:08:04 merged: 2016-03-07 10:38:58

12. [2161](http://github.com/cms-sw/cmsdist/pull/2161){:target="_blank"}  from **@TaiSakuma**: update pandas version to 0.17.1 for 8_0_X created: 2016-02-24 14:31:32 merged: 2016-03-07 10:38:48
