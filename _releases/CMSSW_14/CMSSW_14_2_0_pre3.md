---
layout: post
rel_link:  "14_2_0_pre3"
title:  "CMSSW_14_2_0_pre3"
date:   2024-10-24 12:53:32
categories: cmssw
relmajor: 14
relminor: 2
relsubminor: 0
relpre: _pre3
---

# CMSSW_14_2_0_pre3
#### Changes since CMSSW_14_2_0_pre2:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_14_2_0_pre2...CMSSW_14_2_0_pre3)



1. [46484](http://github.com/cms-sw/cmssw/pull/46484){:target="_blank"}  from **@wddgit**: Fix unlabeled case in mayConsumes EventSetup `core` created: 2024-10-22 21:13:30 merged: 2024-10-23 15:46:08

2. [46476](http://github.com/cms-sw/cmssw/pull/46476){:target="_blank"}  from **@fabiocos**: MTD validation: update vertex density plots `dqm` created: 2024-10-22 13:09:55 merged: 2024-10-23 15:45:29

3. [46473](http://github.com/cms-sw/cmssw/pull/46473){:target="_blank"}  from **@rseidita**: Removing Muon POG DQM sequence from express, with fix for CSC monitoring `dqm` created: 2024-10-22 12:48:07 merged: 2024-10-23 04:52:20

4. [46462](http://github.com/cms-sw/cmssw/pull/46462){:target="_blank"}  from **@JunseokLee3609**: Update new timing seeds for HI `dqm` created: 2024-10-21 11:47:26 merged: 2024-10-22 13:00:08

5. [46461](http://github.com/cms-sw/cmssw/pull/46461){:target="_blank"}  from **@bsunanda**: Run3-alca250 Change thresholds of ECAL energy to make compatible calibrations with Jet-MET studies `alca` created: 2024-10-21 11:08:11 merged: 2024-10-23 04:59:05

6. [46459](http://github.com/cms-sw/cmssw/pull/46459){:target="_blank"}  from **@iarspider**: [AlCa] Fix Wdangling-reference in PixelBaryCentreAnalyzer `alca` `trk` created: 2024-10-21 10:00:14 merged: 2024-10-21 19:03:35

7. [46451](http://github.com/cms-sw/cmssw/pull/46451){:target="_blank"}  from **@mmusich**: make `AlcaBeamMonitor` hoard less memory `dqm` `db` `tracking` created: 2024-10-18 21:18:24 merged: 2024-10-21 18:10:28

8. [46441](http://github.com/cms-sw/cmssw/pull/46441){:target="_blank"}  from **@bsunanda**: Run3-hcx377E Add a test for ZDC Geomery `geometry` created: 2024-10-18 12:26:38 merged: 2024-10-19 06:58:38

9. [46438](http://github.com/cms-sw/cmssw/pull/46438){:target="_blank"}  from **@mmusich**: Update `test_MC_*_setup` unit tests `pdmv` `upgrade` created: 2024-10-18 10:16:49 merged: 2024-10-21 10:03:39

10. [46430](http://github.com/cms-sw/cmssw/pull/46430){:target="_blank"}  from **@bsunanda**: Run2-hcx377 Put all 2015 scenarios using the same hcalRecNumbering.xml file `geometry` `upgrade` created: 2024-10-17 18:09:36 merged: 2024-10-23 18:38:38

11. [46429](http://github.com/cms-sw/cmssw/pull/46429){:target="_blank"}  from **@matt2275**: ZDC Reconstruction Bug Fixes `reconstruction` created: 2024-10-17 18:03:25 merged: 2024-10-18 14:51:30

12. [46426](http://github.com/cms-sw/cmssw/pull/46426){:target="_blank"}  from **@AuroraPerego**: Generalize warp size in pixel clustering kernel `reconstruction` `trk` created: 2024-10-17 16:40:31 merged: 2024-10-18 12:34:26

13. [46423](http://github.com/cms-sw/cmssw/pull/46423){:target="_blank"}  from **@SanghyunKo**: Adding unbiased superclusters to miniAOD and EGM nano `reconstruction` `xpog` `egamma` created: 2024-10-17 13:05:31 merged: 2024-10-22 11:07:15

14. [46420](http://github.com/cms-sw/cmssw/pull/46420){:target="_blank"}  from **@perrotta**: Update the run3_data GT in autoCond to the version intended for the 2022, 2023, 2024CDE rereco `alca` created: 2024-10-17 10:53:54 merged: 2024-10-18 05:45:05

15. [46419](http://github.com/cms-sw/cmssw/pull/46419){:target="_blank"}  from **@AdrianoDee**: New Tests PR Tests for HIN 2023 and 2024 `pdmv` `upgrade` created: 2024-10-17 09:31:05 merged: 2024-10-17 14:29:03

16. [46418](http://github.com/cms-sw/cmssw/pull/46418){:target="_blank"}  from **@mmusich**: make `{DIGI,RECO}HI2024MIX` steps consume the HIon HLT menu `pdmv` `upgrade` created: 2024-10-17 09:26:15 merged: 2024-10-17 13:20:58

17. [46417](http://github.com/cms-sw/cmssw/pull/46417){:target="_blank"}  from **@smuzaffar**: [UBSAN][Math] Suppress signed-integer-overflow for approx_exp `reconstruction` created: 2024-10-17 08:35:33 merged: 2024-10-18 12:34:59

18. [46414](http://github.com/cms-sw/cmssw/pull/46414){:target="_blank"}  from **@mmusich**: Fix `SiStripG2GainsValidator` `db` `trk` created: 2024-10-16 20:37:39 merged: 2024-10-17 09:56:25

19. [46413](http://github.com/cms-sw/cmssw/pull/46413){:target="_blank"}  from **@bsunanda**: Run3-hcx377D Provide a scenario for post-Run2 geometry for which the cfi file existed in Geometry/CMSCommonData/python `geometry` `upgrade` created: 2024-10-16 16:09:56 merged: 2024-10-19 08:20:32

20. [46412](http://github.com/cms-sw/cmssw/pull/46412){:target="_blank"}  from **@RSalvatico**: Fix beamspot in PATElectronProducer `reconstruction` `xpog` `egamma` created: 2024-10-16 15:43:22 merged: 2024-10-18 05:40:17

21. [46410](http://github.com/cms-sw/cmssw/pull/46410){:target="_blank"}  from **@bsunanda**: Run3-alca249 Modify calibration macros to use the current IsoTrack calibration `alca` created: 2024-10-16 14:24:10 merged: 2024-10-18 05:42:32

22. [46409](http://github.com/cms-sw/cmssw/pull/46409){:target="_blank"}  from **@smuzaffar**: [UBSAN][PatCandidates/Tau] Reference binding to null pointer `reconstruction` `xpog` created: 2024-10-16 14:22:54 merged: 2024-10-21 15:36:51

23. [46408](http://github.com/cms-sw/cmssw/pull/46408){:target="_blank"}  from **@fabiocos**: MTD Validation: Add printouts and protection for optional plots in BtlLocalRecoValidation `dqm` created: 2024-10-16 14:16:02 merged: 2024-10-17 09:51:31

24. [46404](http://github.com/cms-sw/cmssw/pull/46404){:target="_blank"}  from **@bsunanda**: Run3-377C Add the testing code for the ZDC Topology class `geometry` created: 2024-10-16 12:17:27 merged: 2024-10-17 06:51:23

25. [46401](http://github.com/cms-sw/cmssw/pull/46401){:target="_blank"}  from **@stahlleiton**: Add dedxLikelihood to 2023 UPC rereco `reconstruction` `xpog` `tracking` created: 2024-10-16 09:26:50 merged: 2024-10-18 05:40:22

26. [46398](http://github.com/cms-sw/cmssw/pull/46398){:target="_blank"}  from **@mmusich**: Update 2023 and 2024 Heavy Ion relval workflows for 2024 HLT menu `pdmv` `upgrade` created: 2024-10-15 19:23:07 merged: 2024-10-16 10:48:05

27. [46397](http://github.com/cms-sw/cmssw/pull/46397){:target="_blank"}  from **@mmusich**: restructure `CalibTracker/SiPixelESProducers` fake conditions `ESProducer`s `alca` `db` `trk` created: 2024-10-15 15:44:03 merged: 2024-10-16 10:48:58

28. [46393](http://github.com/cms-sw/cmssw/pull/46393){:target="_blank"}  from **@Dr15Jones**: Issue message if DB IOV updated during job `db` created: 2024-10-15 14:45:29 merged: 2024-10-16 09:50:10

29. [46388](http://github.com/cms-sw/cmssw/pull/46388){:target="_blank"}  from **@iarspider**: [Core] Mark cms::Exception and edm::Exception functions that throw exceptions as noreturn `core` created: 2024-10-15 12:18:55 merged: 2024-10-18 05:41:45

30. [46386](http://github.com/cms-sw/cmssw/pull/46386){:target="_blank"}  from **@bsunanda**: Run3-hcx377A Correct a few test scripts in CondTools/Geometry `db` created: 2024-10-15 11:49:36 merged: 2024-10-16 05:56:24

31. [46382](http://github.com/cms-sw/cmssw/pull/46382){:target="_blank"}  from **@mmusich**: Restructure `test_SiStripG2GainsValidator` `db` `trk` created: 2024-10-14 18:50:07 merged: 2024-10-15 12:03:45

32. [46380](http://github.com/cms-sw/cmssw/pull/46380){:target="_blank"}  from **@smuzaffar**: [UBSAN] Initialize PerigeeTrajectoryError::weightIsAvailable `reconstruction` `tracking` created: 2024-10-14 15:53:23 merged: 2024-10-15 12:04:17

33. [46379](http://github.com/cms-sw/cmssw/pull/46379){:target="_blank"}  from **@perrotta**: Update a few MC Gts in autoCond to the latest version available on 14/10/2024 `alca` created: 2024-10-14 15:30:21 merged: 2024-10-15 12:06:50

34. [46377](http://github.com/cms-sw/cmssw/pull/46377){:target="_blank"}  from **@iarspider**: Fix Wdangling-reference (probably after merging #46200) `alca` `heterogeneous` created: 2024-10-14 14:42:48 merged: 2024-10-15 16:06:34

35. [46375](http://github.com/cms-sw/cmssw/pull/46375){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `14_1_X` (2/N) [`14_2_X`] `hlt` created: 2024-10-14 14:31:55 merged: 2024-10-15 06:48:00

36. [46374](http://github.com/cms-sw/cmssw/pull/46374){:target="_blank"}  from **@bsunanda**: Run3-hcx376Z Updated hcalRecNumbering XML files in view of the modified Era dependent topology modes `geometry` created: 2024-10-14 14:22:30 merged: 2024-10-15 06:37:48

37. [46369](http://github.com/cms-sw/cmssw/pull/46369){:target="_blank"}  from **@bsunanda**: Run3-hc376Z Update the topology class and tester in view of all modified run conditions `geometry` created: 2024-10-14 09:37:39 merged: 2024-10-15 06:38:48

38. [46368](http://github.com/cms-sw/cmssw/pull/46368){:target="_blank"}  from **@nurfikri89**: Jet updates for Mini and (JME)Nano, add recipe for puppi JetMET reclustering `reconstruction` `xpog` created: 2024-10-14 09:31:27 merged: 2024-10-15 12:05:46

39. [46364](http://github.com/cms-sw/cmssw/pull/46364){:target="_blank"}  from **@fabiocos**: DQM: restore Muon POG sequence (and CSC Monitor), revert #46293 `dqm` created: 2024-10-12 20:32:56 merged: 2024-10-13 11:10:54

40. [46363](http://github.com/cms-sw/cmssw/pull/46363){:target="_blank"}  from **@bsunanda**: Run3-376Y Modify the testing code of HcalTopology `geometry` created: 2024-10-12 14:23:13 merged: 2024-10-13 08:27:26

41. [46362](http://github.com/cms-sw/cmssw/pull/46362){:target="_blank"}  from **@mmusich**: Improvements to `hltPhase2UpgradeIntegrationTests` `hlt` created: 2024-10-12 10:16:50 merged: 2024-10-12 19:28:13

42. [46361](http://github.com/cms-sw/cmssw/pull/46361){:target="_blank"}  from **@mmusich**: fix Compare / Diff / Ratio by partition plots for SiStrip Payload Inspector plugins `db` `trk` created: 2024-10-12 10:16:46 merged: 2024-10-14 16:44:05

43. [46358](http://github.com/cms-sw/cmssw/pull/46358){:target="_blank"}  from **@iarspider**: [LLVM Analyzer][DB] Cleanup LLVM analyzer warnings `db` `trk` created: 2024-10-11 14:42:53 merged: 2024-10-15 16:07:44

44. [46357](http://github.com/cms-sw/cmssw/pull/46357){:target="_blank"}  from **@bsunanda**: Run3-hcx376 Get rid of the obsolete constructor of the HcalTopology class `geometry` created: 2024-10-11 14:36:43 merged: 2024-10-12 06:30:31

45. [46356](http://github.com/cms-sw/cmssw/pull/46356){:target="_blank"}  from **@Dr15Jones**: Pass memory address to AllocMonitors `core` created: 2024-10-11 14:32:57 merged: 2024-10-23 04:54:30

46. [46351](http://github.com/cms-sw/cmssw/pull/46351){:target="_blank"}  from **@bsunanda**: Run3-hcx375 Extend the topology modes to accommodate different scenarios during the Run2 period `geometry` created: 2024-10-11 09:56:57 merged: 2024-10-12 06:30:26

47. [46348](http://github.com/cms-sw/cmssw/pull/46348){:target="_blank"}  from **@kyungminparkdrums**: Add ByLS DQM plots for ES `dqm` created: 2024-10-11 00:31:57 merged: 2024-10-14 16:46:24

48. [46345](http://github.com/cms-sw/cmssw/pull/46345){:target="_blank"}  from **@JHiltbrand**: Two Small Changes Related to ZDC LUTs `alca` `l1` `db` created: 2024-10-10 18:09:51 merged: 2024-10-11 10:34:59

49. [46344](http://github.com/cms-sw/cmssw/pull/46344){:target="_blank"}  from **@iarspider**: [LLVM Analyzer][AlCa] Cleanup clang analyzer warnings `alca` `trk` created: 2024-10-10 17:26:09 merged: 2024-10-11 07:16:01

50. [46340](http://github.com/cms-sw/cmssw/pull/46340){:target="_blank"}  from **@p2l1-gtEmulator**: Add Phase-2 GT to EventContent `l1` created: 2024-10-10 14:28:54 merged: 2024-10-21 13:02:25

51. [46338](http://github.com/cms-sw/cmssw/pull/46338){:target="_blank"}  from **@bsunanda**: Phase2-hgx360D Replace cout with logvervatim `geometry` `upgrade` created: 2024-10-10 13:20:23 merged: 2024-10-11 08:42:31

52. [46334](http://github.com/cms-sw/cmssw/pull/46334){:target="_blank"}  from **@smuzaffar**: Fix DQM config test: Increase number of sequence to test `dqm` created: 2024-10-10 08:59:29 merged: 2024-10-15 06:47:13

53. [46330](http://github.com/cms-sw/cmssw/pull/46330){:target="_blank"}  from **@wddgit**: Fix potential data race in ESProductResolver `core` created: 2024-10-09 22:00:41 merged: 2024-10-11 15:47:01

54. [46325](http://github.com/cms-sw/cmssw/pull/46325){:target="_blank"}  from **@trackreco**: Phase-2 mkFit: propagation to plane / Kalman operations on plane / Matriplex with support for scalar operations and VDT `reconstruction` `tracking` created: 2024-10-09 16:54:32 merged: 2024-10-17 12:02:36

55. [46324](http://github.com/cms-sw/cmssw/pull/46324){:target="_blank"}  from **@trackreco**: Tracking validation updates/improvements `dqm` `tracking` created: 2024-10-09 15:01:53 merged: 2024-10-22 05:37:14

56. [46322](http://github.com/cms-sw/cmssw/pull/46322){:target="_blank"}  from **@mmusich**: SiPixelAlignment PCL harvester, add option to ignore exceeding thresholds on inactive modules when vetoing payload upload `alca` `trk` created: 2024-10-09 11:21:30 merged: 2024-10-10 14:55:43

57. [46321](http://github.com/cms-sw/cmssw/pull/46321){:target="_blank"}  from **@smuzaffar**: [RECONSTRUCTION] [Clang]Cleanup clang-analyzer warnings `reconstruction` `tracking` created: 2024-10-09 10:27:02 merged: 2024-10-10 09:02:04

58. [46320](http://github.com/cms-sw/cmssw/pull/46320){:target="_blank"}  from **@smuzaffar**: [DB] [Clang]Cleanup clang-analyzer warnings `db` created: 2024-10-09 10:26:58 merged: 2024-10-11 07:19:08

59. [46317](http://github.com/cms-sw/cmssw/pull/46317){:target="_blank"}  from **@smuzaffar**: [ANALYSIS] [Clang]Cleanup clang-analyzer warnings `analysis` created: 2024-10-09 10:26:32 merged: 2024-10-09 15:10:33

60. [46315](http://github.com/cms-sw/cmssw/pull/46315){:target="_blank"}  from **@iarspider**: Fix testAOTTools for non-amd64 arch `ml` created: 2024-10-09 09:29:43 merged: 2024-10-10 09:02:46

61. [46312](http://github.com/cms-sw/cmssw/pull/46312){:target="_blank"}  from **@stahlleiton**: Fix crash in DeDxEstimatorRekeyer `reconstruction` `xpog` created: 2024-10-08 19:42:35 merged: 2024-10-09 15:09:20

62. [46310](http://github.com/cms-sw/cmssw/pull/46310){:target="_blank"}  from **@bsunanda**: Run3-hcx374 Update the scenarios for providing the correct set of initializing cfis `geometry` `upgrade` created: 2024-10-08 19:06:28 merged: 2024-10-09 19:00:46

63. [46308](http://github.com/cms-sw/cmssw/pull/46308){:target="_blank"}  from **@bsunanda**: Run3-hcx373 Correct the HcalTopology class for 2 new geometry modes `geometry` `db` created: 2024-10-08 18:11:06 merged: 2024-10-11 07:58:52

64. [46306](http://github.com/cms-sw/cmssw/pull/46306){:target="_blank"}  from **@Dr15Jones**: Improved scripts used to write 2024 Geom DB payloads `geometry` `db` created: 2024-10-08 15:18:41 merged: 2024-10-10 09:04:06

65. [46299](http://github.com/cms-sw/cmssw/pull/46299){:target="_blank"}  from **@nurfikri89**: [NanoAOD] Add UParT electron and muon raw scores `xpog` created: 2024-10-08 07:30:19 merged: 2024-10-15 06:46:13

66. [46295](http://github.com/cms-sw/cmssw/pull/46295){:target="_blank"}  from **@matt2275**: Update ZdcSimpleRecAlgo_Run3.cc `reconstruction` created: 2024-10-07 23:10:44 merged: 2024-10-08 19:27:35

67. [46293](http://github.com/cms-sw/cmssw/pull/46293){:target="_blank"}  from **@rseidita**: Removing Muon POG DQM sequence from Express pipeline `dqm` created: 2024-10-07 16:31:23 merged: 2024-10-08 13:43:21

68. [46289](http://github.com/cms-sw/cmssw/pull/46289){:target="_blank"}  from **@Dr15Jones**: Improve constructor for PhotonIsolationCalculator `reconstruction` created: 2024-10-07 14:05:04 merged: 2024-10-08 08:52:12

69. [46288](http://github.com/cms-sw/cmssw/pull/46288){:target="_blank"}  from **@Ming-Yan**: [BTVNano] add NegTag for UParT `reconstruction` `xpog` created: 2024-10-07 13:09:08 merged: 2024-10-21 18:11:43

70. [46286](http://github.com/cms-sw/cmssw/pull/46286){:target="_blank"}  from **@bsunanda**: Run3-hcx369 Allow only valid ZDChits to enter the digitization phase `geometry` `simulation` created: 2024-10-07 12:46:50 merged: 2024-10-08 06:52:10

71. [46283](http://github.com/cms-sw/cmssw/pull/46283){:target="_blank"}  from **@sroychow**: Increase threshold of max number of pixel clusters for cosmic tracking `reconstruction` `tracking` created: 2024-10-07 10:37:34 merged: 2024-10-07 16:46:30

72. [46279](http://github.com/cms-sw/cmssw/pull/46279){:target="_blank"}  from **@iarspider**: [LLVM Analyzer][ML] Remove dead assignment in PhysicsTools/MVAComputer/src/Spline.cc `ml` created: 2024-10-07 08:35:08 merged: 2024-10-09 13:12:37

73. [46277](http://github.com/cms-sw/cmssw/pull/46277){:target="_blank"}  from **@iarspider**: [LLVM Analyzer][DB] Fix dead assignment in FEConfigLUTGroupDat `db` created: 2024-10-07 08:05:28 merged: 2024-10-08 06:52:15

74. [46276](http://github.com/cms-sw/cmssw/pull/46276){:target="_blank"}  from **@Dr15Jones**: Modernize RecoEgamma/PhotonIdentification helpers `reconstruction` created: 2024-10-05 15:43:38 merged: 2024-10-07 16:38:01

75. [46271](http://github.com/cms-sw/cmssw/pull/46271){:target="_blank"}  from **@Dr15Jones**: Pass pointer to EgammaRecHitIsolation::getEtSum `dqm` `reconstruction` created: 2024-10-04 15:52:42 merged: 2024-10-07 16:48:51

76. [46270](http://github.com/cms-sw/cmssw/pull/46270){:target="_blank"}  from **@iarspider**: [LLVM Analyzer][L1] Remove dead code `l1` created: 2024-10-04 15:19:33 merged: 2024-10-07 11:59:30

77. [46268](http://github.com/cms-sw/cmssw/pull/46268){:target="_blank"}  from **@smuzaffar**: [ROOT6] Disable NanoAODRNuple plugin `xpog` created: 2024-10-04 15:07:39 merged: 2024-10-05 08:45:31

78. [46264](http://github.com/cms-sw/cmssw/pull/46264){:target="_blank"}  from **@BenjaminRS**: Updating phase2_realistic to point to 141X_mcRun4_realistic_v2 `alca` created: 2024-10-04 14:21:14 merged: 2024-10-06 15:36:58

79. [46262](http://github.com/cms-sw/cmssw/pull/46262){:target="_blank"}  from **@iarspider**: [LLVM Analyzer][ALCA,ANALYSIS] Remove dead assignments `alca` `analysis` created: 2024-10-04 13:15:46 merged: 2024-10-08 06:50:35

80. [46261](http://github.com/cms-sw/cmssw/pull/46261){:target="_blank"}  from **@iarspider**: [LLVM Analyzer][Heterogeneous] Remove dead assignments `heterogeneous` created: 2024-10-04 13:11:59 merged: 2024-10-06 15:37:28

81. [46259](http://github.com/cms-sw/cmssw/pull/46259){:target="_blank"}  from **@smuzaffar**: [CORE] [Clang]Cleanup clang-analyzer warnings `core` created: 2024-10-04 12:50:18 merged: 2024-10-08 06:50:05

82. [46258](http://github.com/cms-sw/cmssw/pull/46258){:target="_blank"}  from **@smuzaffar**: [RECONSTRUCTION] [Clang]Cleanup clang-analyzer warnings `reconstruction` `tracking` created: 2024-10-04 12:49:41 merged: 2024-10-08 08:53:08

83. [46257](http://github.com/cms-sw/cmssw/pull/46257){:target="_blank"}  from **@barvic**: DQM CSCMonitorModule: crash fix for corrupted events with missing ALCT data (14_2_X) `dqm` `csc` created: 2024-10-04 12:32:30 merged: 2024-10-07 16:44:01

84. [46256](http://github.com/cms-sw/cmssw/pull/46256){:target="_blank"}  from **@TomasKello**: Minimal bugfix on the missing lumifilter for the MTS validation. `alca` `trk` created: 2024-10-04 12:27:58 merged: 2024-10-05 11:17:14

85. [46245](http://github.com/cms-sw/cmssw/pull/46245){:target="_blank"}  from **@mmusich**: Miscellaneous fixes for HLT online DQM  `dqm` `hlt` created: 2024-10-04 07:12:02 merged: 2024-10-07 16:49:04

86. [46243](http://github.com/cms-sw/cmssw/pull/46243){:target="_blank"}  from **@Dr15Jones**: Improve TPSAlgorithm `l1` created: 2024-10-03 19:26:07 merged: 2024-10-10 13:25:11

87. [46241](http://github.com/cms-sw/cmssw/pull/46241){:target="_blank"}  from **@tomalin**: Increase field width in MessageLogger Summary `core` created: 2024-10-03 16:51:47 merged: 2024-10-22 13:42:52

88. [46237](http://github.com/cms-sw/cmssw/pull/46237){:target="_blank"}  from **@smuzaffar**: [L1] [Clang]Cleanup clang-analyzer warnings `l1` created: 2024-10-03 15:55:59 merged: 2024-10-07 12:35:35

89. [46236](http://github.com/cms-sw/cmssw/pull/46236){:target="_blank"}  from **@rdelliga**: MTD Validation: speed up LocalRecoValidation plus other fixes `dqm` `mtd` created: 2024-10-03 15:32:19 merged: 2024-10-07 16:42:46

90. [46235](http://github.com/cms-sw/cmssw/pull/46235){:target="_blank"}  from **@smuzaffar**: Removed cmsScimark2 exec and scripts `core` created: 2024-10-03 14:37:53 merged: 2024-10-07 16:41:11

91. [46228](http://github.com/cms-sw/cmssw/pull/46228){:target="_blank"}  from **@smuzaffar**: [DQM-GENERATORS] [Clang]Cleanup clang-analyzer warnings `dqm` `generators` created: 2024-10-03 13:25:01 merged: 2024-10-07 16:35:21

92. [46227](http://github.com/cms-sw/cmssw/pull/46227){:target="_blank"}  from **@smuzaffar**: [DQM] [Clang]Cleanup clang-analyzer warnings `dqm` created: 2024-10-03 13:18:10 merged: 2024-10-07 16:34:51

93. [46225](http://github.com/cms-sw/cmssw/pull/46225){:target="_blank"}  from **@smuzaffar**: [ClangAna][HcalHits] Remove dead code; suppress false-positive warnings `dqm` created: 2024-10-03 11:57:01 merged: 2024-10-07 12:00:57

94. [46218](http://github.com/cms-sw/cmssw/pull/46218){:target="_blank"}  from **@smuzaffar**: [L1-UPGRADE] Applying code checks/format `l1` `upgrade` created: 2024-10-03 07:30:02 merged: 2024-10-11 07:41:41

95. [46217](http://github.com/cms-sw/cmssw/pull/46217){:target="_blank"}  from **@smuzaffar**: [L1] Applying code checks/format `l1` created: 2024-10-03 07:29:37 merged: 2024-10-07 11:58:20

96. [46216](http://github.com/cms-sw/cmssw/pull/46216){:target="_blank"}  from **@smuzaffar**: [DQM] Applying code checks/format `dqm` `trk` created: 2024-10-03 07:29:18 merged: 2024-10-07 12:01:49

97. [46215](http://github.com/cms-sw/cmssw/pull/46215){:target="_blank"}  from **@smuzaffar**: [GENERATORS] Applying code checks/format `generators` created: 2024-10-03 07:29:08 merged: 2024-10-07 16:36:51

98. [46204](http://github.com/cms-sw/cmssw/pull/46204){:target="_blank"}  from **@wddgit**: More of the DataProxy to ESProductResolver renaming `analysis` `core` created: 2024-10-02 22:05:40 merged: 2024-10-05 11:17:51

99. [46203](http://github.com/cms-sw/cmssw/pull/46203){:target="_blank"}  from **@hqucms**: Fix memory leak in GenParticles2HepMCConverter `generators` `xpog` created: 2024-10-02 19:15:44 merged: 2024-10-23 15:45:41

100. [46200](http://github.com/cms-sw/cmssw/pull/46200){:target="_blank"}  from **@iarspider**: edm::FileInPath: return reference to paths; cleanup code `core` created: 2024-10-02 14:26:37 merged: 2024-10-11 15:46:26

101. [46199](http://github.com/cms-sw/cmssw/pull/46199){:target="_blank"}  from **@iarspider**: [LLVM Analyzer] Fix use-after-free warning in VariableComputerTest::VariableComputerTest `analysis` created: 2024-10-02 12:35:11 merged: 2024-10-09 15:14:48

102. [46197](http://github.com/cms-sw/cmssw/pull/46197){:target="_blank"}  from **@iarspider**: [LLVM Analyzer] Fix use-after-free in DQM/SiStripMonitorSummary/bin/makePlots.cc `dqm` `trk` created: 2024-10-02 10:19:01 merged: 2024-10-07 11:58:33

103. [46196](http://github.com/cms-sw/cmssw/pull/46196){:target="_blank"}  from **@mbluj**: Move "hybrid" tau production from nano to mini step `dqm` `reconstruction` `simulation` `xpog` created: 2024-10-02 10:14:53 merged: 2024-10-18 05:40:52

104. [46187](http://github.com/cms-sw/cmssw/pull/46187){:target="_blank"}  from **@mmusich**: Add standalone unit test for DQM/TrackingMonitorSource plugins `dqm` `tracking` created: 2024-10-01 20:11:02 merged: 2024-10-07 09:07:17

105. [46181](http://github.com/cms-sw/cmssw/pull/46181){:target="_blank"}  from **@iarspider**: [LLVM Analyzer] Avoid storing pointer to a temporary string's internal buffer in SiPixelFakeGenErrorDBObjectESSource::produce and SiPixelTemplateDBObjectReader::analyze  `alca` `db` `trk` created: 2024-10-01 13:34:21 merged: 2024-10-12 12:48:36

106. [46176](http://github.com/cms-sw/cmssw/pull/46176){:target="_blank"}  from **@iarspider**: [L1] Fix syntax in python scripts `l1` `upgrade` created: 2024-10-01 09:52:46 merged: 2024-10-15 06:35:47

107. [46166](http://github.com/cms-sw/cmssw/pull/46166){:target="_blank"}  from **@iarspider**: [DQM] Fix syntax in python scripts `dqm` `tracking` `trk` created: 2024-10-01 08:14:28 merged: 2024-10-07 09:08:39

108. [46159](http://github.com/cms-sw/cmssw/pull/46159){:target="_blank"}  from **@tomalin**: Fix d0 bug `l1` `upgrade` created: 2024-09-30 15:55:34 merged: 2024-10-15 16:05:15

109. [46151](http://github.com/cms-sw/cmssw/pull/46151){:target="_blank"}  from **@hqucms**: Remove run3_nanoAOD_122 & 124 modifiers `operations` `xpog` created: 2024-09-30 09:47:30 merged: 2024-10-08 13:49:48

110. [46128](http://github.com/cms-sw/cmssw/pull/46128){:target="_blank"}  from **@Dr15Jones**: Protect getenv in Pythia8Interface `generators` created: 2024-09-25 21:02:09 merged: 2024-10-11 10:35:34

111. [46114](http://github.com/cms-sw/cmssw/pull/46114){:target="_blank"}  from **@kpedro88**: Simplify and generalize ibeos `core` `pdmv` `upgrade` created: 2024-09-24 15:19:11 merged: 2024-10-10 14:54:22

112. [46112](http://github.com/cms-sw/cmssw/pull/46112){:target="_blank"}  from **@cms-tau-pog**: Boosted DeepTauID v2.0 `reconstruction` `xpog` created: 2024-09-24 12:05:16 merged: 2024-10-15 16:03:39

113. [46091](http://github.com/cms-sw/cmssw/pull/46091){:target="_blank"}  from **@smuzaffar**: [GENERATORS] [PY312] String formatting to fix SyntaxWarning `generators` created: 2024-09-23 08:09:29 merged: 2024-10-07 16:45:57

114. [46087](http://github.com/cms-sw/cmssw/pull/46087){:target="_blank"}  from **@stahlleiton**: Era for UPC re-reco of 2016 pPb data `alca` `operations` `reconstruction` `pdmv` `upgrade` `tracking` created: 2024-09-21 23:48:18 merged: 2024-10-09 15:11:40

115. [46079](http://github.com/cms-sw/cmssw/pull/46079){:target="_blank"}  from **@guitargeek**: Follow up on recent Minuit 2 code changes `alca` `reconstruction` `db` `tracking` created: 2024-09-20 18:24:50 merged: 2024-10-10 09:04:52

116. [46072](http://github.com/cms-sw/cmssw/pull/46072){:target="_blank"}  from **@BlancoFS**: Fix duplication of TrigObj in nanoAOD `xpog` created: 2024-09-20 12:30:12 merged: 2024-10-07 17:54:48

117. [46010](http://github.com/cms-sw/cmssw/pull/46010){:target="_blank"}  from **@RSalvatico**: Enable DNN supercluster in Phase2 HLT `hlt` `reconstruction` `pdmv` `upgrade` `egamma` created: 2024-09-17 06:19:32 merged: 2024-10-18 12:37:01

118. [46001](http://github.com/cms-sw/cmssw/pull/46001){:target="_blank"}  from **@langufo**: Introduce support for cluster splitting and JetCore iteration in Phase-2 track reconstruction `operations` `reconstruction` `pdmv` `upgrade` `tracking` `trk` created: 2024-09-13 15:15:30 merged: 2024-10-23 09:14:30

119. [45992](http://github.com/cms-sw/cmssw/pull/45992){:target="_blank"}  from **@felicepantaleo**: Fix: Avoid adding HGCalUncalibRecHits to the event if digis do not exist `reconstruction` `upgrade` `hgcal` created: 2024-09-12 14:36:29 merged: 2024-10-14 16:44:39

120. [45975](http://github.com/cms-sw/cmssw/pull/45975){:target="_blank"}  from **@amecca**: Porting the Pixel Barycentre tool in the All-in-One framework `alca` `trk` created: 2024-09-11 10:45:45 merged: 2024-10-18 05:46:07

121. [45865](http://github.com/cms-sw/cmssw/pull/45865){:target="_blank"}  from **@felicepantaleo**: Redesign of the association maps, multivector manager, HGCAL Rechits and Validation with significant speedup of Phase-2 workflows `dqm` `hlt` `reconstruction` `simulation` `upgrade` created: 2024-09-03 13:42:22 merged: 2024-10-15 06:43:02

#### CMSDIST Changes between Tags REL/CMSSW_14_2_0_pre2/el8_amd64_gcc12 and REL/CMSSW_14_2_0_pre3/el8_amd64_gcc12:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_14_2_0_pre2/el8_amd64_gcc12...REL/CMSSW_14_2_0_pre3/el8_amd64_gcc12)



1. [9475](http://github.com/cms-sw/cmsdist/pull/9475){:target="_blank"}  from **@cms-sw**: xrootd: Update to version 5.7.1 created: 2024-10-21 13:35:20 merged: 2024-10-22 07:18:03

2. [9474](http://github.com/cms-sw/cmsdist/pull/9474){:target="_blank"}  from **@aspiringmind-code**: Update crab-prod and crab-pre to the latest version created: 2024-10-21 08:00:23 merged: 2024-10-21 15:29:34

3. [9470](http://github.com/cms-sw/cmsdist/pull/9470){:target="_blank"}  from **@cms-sw**: [vdt]Apply patch to avoid UBSan signed integer overflow error created: 2024-10-17 09:43:17 merged: 2024-10-19 16:15:45

4. [9469](http://github.com/cms-sw/cmsdist/pull/9469){:target="_blank"}  from **@cms-sw**: add CMS_X_SANITIZER macros created: 2024-10-17 06:36:18 merged: 2024-10-17 08:27:12

5. [9467](http://github.com/cms-sw/cmsdist/pull/9467){:target="_blank"}  from **@cms-sw**: Update tag for RecoTauTag-TrainingFiles to V00-10-00 created: 2024-10-15 16:04:49 merged: 2024-10-15 16:04:50

6. [9464](http://github.com/cms-sw/cmsdist/pull/9464){:target="_blank"}  from **@cms-sw**: Unify geat4 deps and vecgeom selection created: 2024-10-15 09:48:51 merged: 2024-10-16 14:52:42

7. [9463](http://github.com/cms-sw/cmsdist/pull/9463){:target="_blank"}  from **@cms-sw**: [SCRAM] scram setup to create external symlinks created: 2024-10-15 09:35:49 merged: 2024-10-16 05:21:12

8. [9456](http://github.com/cms-sw/cmsdist/pull/9456){:target="_blank"}  from **@cms-sw**: ThePeg/Herwig7 build with cms default standard i.e. c++20 created: 2024-10-07 12:24:35 merged: 2024-10-08 07:38:11

9. [9455](http://github.com/cms-sw/cmsdist/pull/9455){:target="_blank"}  from **@cms-sw**: g4hepem/dd4hep: Added xerces-c/expat dep created: 2024-10-07 05:25:22 merged: 2024-10-07 14:20:33

10. [9453](http://github.com/cms-sw/cmsdist/pull/9453){:target="_blank"}  from **@cms-sw**: update dwz, fix g4hepem and celeritas deps created: 2024-10-05 16:30:39 merged: 2024-10-06 09:09:20
