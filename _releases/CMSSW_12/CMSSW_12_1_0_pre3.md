---
layout: post
rel_link:  "12_1_0_pre3"
title:  "CMSSW_12_1_0_pre3"
date:   2021-09-16 00:35:09
categories: cmssw
relmajor: 12
relminor: 1
relsubminor: 0
relpre: _pre3
---

# CMSSW_12_1_0_pre3
#### Changes since CMSSW_12_1_0_pre2:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_12_1_0_pre2...CMSSW_12_1_0_pre3)



1. [35282](http://github.com/cms-sw/cmssw/pull/35282){:target="_blank"}  from **@bsunanda**: Run3-alca200 Bug fix to 2 classes in Calibration/HcalCalibAlgos `alca` created: 2021-09-15 11:29:15 merged: 2021-09-15 19:24:00

2. [35271](http://github.com/cms-sw/cmssw/pull/35271){:target="_blank"}  from **@mmusich**: complete esConsumes migration of `Alignment/CommonAlignmentProducer` `alca` created: 2021-09-14 17:05:57 merged: 2021-09-15 01:27:40

3. [35266](http://github.com/cms-sw/cmssw/pull/35266){:target="_blank"}  from **@mmusich**: `Alignment/OfflineValidation` improvements from CRUZET'21 data analysis `alca` `dqm` created: 2021-09-14 13:24:51 merged: 2021-09-14 20:29:07

4. [35265](http://github.com/cms-sw/cmssw/pull/35265){:target="_blank"}  from **@mmusich**: modernize `SiStripDetInfoFileWriter` `alca` created: 2021-09-14 12:58:39 merged: 2021-09-14 20:30:29

5. [35254](http://github.com/cms-sw/cmssw/pull/35254){:target="_blank"}  from **@mmusich**: modernize `Alignment/TrackerAlignment` `alca` created: 2021-09-13 14:54:23 merged: 2021-09-14 00:35:04

6. [35253](http://github.com/cms-sw/cmssw/pull/35253){:target="_blank"}  from **@Dr15Jones**: Change current path in cmsExternalGenerator not cmsRun `generators` created: 2021-09-13 14:53:59 merged: 2021-09-14 11:19:40

7. [35245](http://github.com/cms-sw/cmssw/pull/35245){:target="_blank"}  from **@civanch**: Cleanup Geant4 termination `simulation` created: 2021-09-13 10:01:03 merged: 2021-09-13 20:56:34

8. [35244](http://github.com/cms-sw/cmssw/pull/35244){:target="_blank"}  from **@mmusich**: Miscellaneous graphical payload inspector fixes `hlt` `db` created: 2021-09-13 08:41:02 merged: 2021-09-14 00:33:02

9. [35241](http://github.com/cms-sw/cmssw/pull/35241){:target="_blank"}  from **@bsunanda**: Run3-hcx320 Use of ESGetToken in RecoLocalCalo/HcalRecAlgos (replacing #35234) `reconstruction` created: 2021-09-12 19:45:07 merged: 2021-09-14 14:53:12

10. [35240](http://github.com/cms-sw/cmssw/pull/35240){:target="_blank"}  from **@bsunanda**: Run3-alca199 Split HOCalibAnalyzer.cc to take out the post analysis part in separate macros `alca` created: 2021-09-12 14:20:43 merged: 2021-09-14 20:36:12

11. [35239](http://github.com/cms-sw/cmssw/pull/35239){:target="_blank"}  from **@apsallid**: [HGCAL] Updates on validation scripts  `dqm` `geometry` created: 2021-09-12 11:30:22 merged: 2021-09-14 00:44:21

12. [35238](http://github.com/cms-sw/cmssw/pull/35238){:target="_blank"}  from **@Dr15Jones**: Properly set L1 and L2 values in CSCL1TPLookupTableEP `alca` created: 2021-09-11 16:26:22 merged: 2021-09-11 20:18:45

13. [35233](http://github.com/cms-sw/cmssw/pull/35233){:target="_blank"}  from **@malbouis**: Add new ECAL PF RecHit thresholds for 2021 Run 3 MC `alca` created: 2021-09-10 20:34:04 merged: 2021-09-13 20:49:49

14. [35228](http://github.com/cms-sw/cmssw/pull/35228){:target="_blank"}  from **@Dr15Jones**: Added esConsumes to HBHERecHitProducerGPU `reconstruction` created: 2021-09-10 15:38:28 merged: 2021-09-14 13:11:32

15. [35224](http://github.com/cms-sw/cmssw/pull/35224){:target="_blank"}  from **@Dr15Jones**: Remove throwing of test Exception in SherpaHadronizer `generators` created: 2021-09-09 23:31:23 merged: 2021-09-10 08:22:09

16. [35220](http://github.com/cms-sw/cmssw/pull/35220){:target="_blank"}  from **@Purva-Chaudhari**: Clear unrequired headers of boost lexical_cast `analysis` `dqm` `generators` `geometry` `reconstruction` created: 2021-09-09 18:16:18 merged: 2021-09-13 08:26:48

17. [35218](http://github.com/cms-sw/cmssw/pull/35218){:target="_blank"}  from **@smorovic**: DAQ optimized usage of FU file locking `daq` `reconstruction` created: 2021-09-09 17:47:23 merged: 2021-09-10 13:55:01

18. [35217](http://github.com/cms-sw/cmssw/pull/35217){:target="_blank"}  from **@bsunanda**: Run3-hcx331 Rearrange all plugins to the plugins directory in Calibration/HcalAlCaRecoProducers `alca` created: 2021-09-09 16:14:58 merged: 2021-09-10 18:01:52

19. [35215](http://github.com/cms-sw/cmssw/pull/35215){:target="_blank"}  from **@guitargeek**: Clean unused dependencies from BuildFiles `alca` `dqm` `fastsim` `l1` `reconstruction` `simulation` `upgrade` created: 2021-09-09 14:21:20 merged: 2021-09-14 11:00:51

20. [35213](http://github.com/cms-sw/cmssw/pull/35213){:target="_blank"}  from **@makortel**: Revert "Have embedded root files send close reports" `core` created: 2021-09-09 14:15:19 merged: 2021-09-10 04:12:34

21. [35211](http://github.com/cms-sw/cmssw/pull/35211){:target="_blank"}  from **@Purva-Chaudhari**: removed boost lexical_cast dependency `reconstruction` `visualization` created: 2021-09-09 13:29:40 merged: 2021-09-11 00:58:06

22. [35210](http://github.com/cms-sw/cmssw/pull/35210){:target="_blank"}  from **@bsunanda**: Run3-gex92Z Small fixes and adding several material files in view of G4 testing with new reference versions `geometry` `upgrade` created: 2021-09-09 13:25:09 merged: 2021-09-14 21:31:11

23. [35209](http://github.com/cms-sw/cmssw/pull/35209){:target="_blank"}  from **@apsallid**: [HGCAL] Updates for dEdx weights calculation  `simulation` created: 2021-09-09 13:00:15 merged: 2021-09-11 00:53:10

24. [35208](http://github.com/cms-sw/cmssw/pull/35208){:target="_blank"}  from **@namapane**: Cleanup of DTRecoUncertainties/DTRecoUncertaintiesRcd `alca` `dqm` created: 2021-09-09 12:38:05 merged: 2021-09-10 08:14:31

25. [35207](http://github.com/cms-sw/cmssw/pull/35207){:target="_blank"}  from **@cms-tsg-storm**: Update of HLT GTs for Run3 `hlt` created: 2021-09-09 12:12:59 merged: 2021-09-09 15:53:16

26. [35205](http://github.com/cms-sw/cmssw/pull/35205){:target="_blank"}  from **@watson-ij**: Update TrackReco HitPattern in light of GEM now including GE0 `reconstruction` created: 2021-09-09 05:52:33 merged: 2021-09-11 00:59:55

27. [35204](http://github.com/cms-sw/cmssw/pull/35204){:target="_blank"}  from **@Dr15Jones**: Fixed exceptional case handling in SherpaHadronizer `generators` created: 2021-09-08 23:08:53 merged: 2021-09-09 20:09:28

28. [35203](http://github.com/cms-sw/cmssw/pull/35203){:target="_blank"}  from **@therwig**: Susy gen fragment for trigger validation `generators` created: 2021-09-08 21:52:37 merged: 2021-09-09 14:52:31

29. [35202](http://github.com/cms-sw/cmssw/pull/35202){:target="_blank"}  from **@francescobrivio**: New Run3 offline GT `alca` `pdmv` `upgrade` created: 2021-09-08 21:47:15 merged: 2021-09-10 18:09:46

30. [35201](http://github.com/cms-sw/cmssw/pull/35201){:target="_blank"}  from **@Dr15Jones**: Handle more generator problems in external generator `generators` created: 2021-09-08 21:24:52 merged: 2021-09-09 20:08:49

31. [35199](http://github.com/cms-sw/cmssw/pull/35199){:target="_blank"}  from **@trackreco**: Update of mkFit for 12_1_0_pre3 `reconstruction` created: 2021-09-08 16:57:05 merged: 2021-09-10 20:57:39

32. [35197](http://github.com/cms-sw/cmssw/pull/35197){:target="_blank"}  from **@emilbols**: [UBSAN] Fix overloaded enum in TemplatedSecondaryVertexTagInfo `reconstruction` created: 2021-09-08 14:43:11 merged: 2021-09-11 06:13:29

33. [35196](http://github.com/cms-sw/cmssw/pull/35196){:target="_blank"}  from **@jeongeun**: Migrate module config in Validation{RecoVertex} to use default cfipython `dqm` created: 2021-09-08 12:16:19 merged: 2021-09-08 20:58:00

34. [35195](http://github.com/cms-sw/cmssw/pull/35195){:target="_blank"}  from **@jeongeun**: Migrate module configuration in RecoVertex to use default cfipython v2 `alca` `reconstruction` created: 2021-09-08 11:27:22 merged: 2021-09-10 12:16:23

35. [35192](http://github.com/cms-sw/cmssw/pull/35192){:target="_blank"}  from **@archiron**: /validation/RecoEgamma PHASE2 modifications `dqm` created: 2021-09-08 09:53:45 merged: 2021-09-14 07:06:43

36. [35191](http://github.com/cms-sw/cmssw/pull/35191){:target="_blank"}  from **@lecriste**: Parallelize SeparateValidation `dqm` created: 2021-09-08 09:48:37 merged: 2021-09-08 21:00:40

37. [35190](http://github.com/cms-sw/cmssw/pull/35190){:target="_blank"}  from **@perrotta**: Restore DataFormats/GeometrySurface/interface/private/extTkRotation.h `simulation` created: 2021-09-08 08:06:55 merged: 2021-09-08 08:43:31

38. [35189](http://github.com/cms-sw/cmssw/pull/35189){:target="_blank"}  from **@Purva-Chaudhari**: Remove boost lexical_cast dependency in CalibTracker `alca` created: 2021-09-08 05:06:16 merged: 2021-09-08 15:22:55

39. [35186](http://github.com/cms-sw/cmssw/pull/35186){:target="_blank"}  from **@bsunanda**: Run3-hcx330 Make use of ESGetToken in DPGAnalysis/HcalTools `dqm` created: 2021-09-07 22:55:56 merged: 2021-09-09 15:02:36

40. [35184](http://github.com/cms-sw/cmssw/pull/35184){:target="_blank"}  from **@Dr15Jones**: Added esConsumes calls to code in RecoLocalMuon `alca` `dqm` `l1` `reconstruction` `upgrade` created: 2021-09-07 22:29:21 merged: 2021-09-14 13:09:18

41. [35183](http://github.com/cms-sw/cmssw/pull/35183){:target="_blank"}  from **@cvuosalo**: Add TrackerAdditionalParametersPerDet_cfi to prevent exception in Tracker test script `geometry` created: 2021-09-07 22:07:42 merged: 2021-09-08 21:02:08

42. [35182](http://github.com/cms-sw/cmssw/pull/35182){:target="_blank"}  from **@makortel**: Set numberOfConcurrentLuminosityBlocks to 1 for GEN steps that have EDModules that are not going to support concurrent lumis `generators` `operations` created: 2021-09-07 20:15:27 merged: 2021-09-14 07:44:38

43. [35179](http://github.com/cms-sw/cmssw/pull/35179){:target="_blank"}  from **@thomreis**: ECAL esConsumes migration of remaining file in RecoMET `reconstruction` created: 2021-09-07 14:01:11 merged: 2021-09-14 15:20:35

44. [35178](http://github.com/cms-sw/cmssw/pull/35178){:target="_blank"}  from **@cms-tsg-storm**: HLT menu migration to 12_1_0_pre2 template `hlt` created: 2021-09-07 12:41:54 merged: 2021-09-07 19:50:49

45. [35177](http://github.com/cms-sw/cmssw/pull/35177){:target="_blank"}  from **@CTPPS**: PPS: preparation for 2022 conditions `alca` `dqm` created: 2021-09-07 12:23:35 merged: 2021-09-09 03:28:17

46. [35176](http://github.com/cms-sw/cmssw/pull/35176){:target="_blank"}  from **@thomreis**: ECAL esConsumes migration for remaining SimCalorimetry occurrences `simulation` created: 2021-09-07 11:53:26 merged: 2021-09-08 21:10:28

47. [35175](http://github.com/cms-sw/cmssw/pull/35175){:target="_blank"}  from **@Purva-Chaudhari**: Removed boost lexical_cast dependency in OnlineDB `db` created: 2021-09-07 04:46:13 merged: 2021-09-08 08:31:13

48. [35173](http://github.com/cms-sw/cmssw/pull/35173){:target="_blank"}  from **@suchandradutta**: Tracker Phase2 Digitizer framework update for BrickedPixel  `simulation` `upgrade` created: 2021-09-06 18:24:51 merged: 2021-09-10 08:25:38

49. [35172](http://github.com/cms-sw/cmssw/pull/35172){:target="_blank"}  from **@Purva-Chaudhari**: Removed lexical_cast boost dependency in DQM `dqm` created: 2021-09-06 16:26:47 merged: 2021-09-07 08:48:44

50. [35168](http://github.com/cms-sw/cmssw/pull/35168){:target="_blank"}  from **@Purva-Chaudhari**: Remove boost lexical_cast dependency in EventFilter `l1` `daq` `reconstruction` created: 2021-09-06 15:00:43 merged: 2021-09-13 01:19:35

51. [35167](http://github.com/cms-sw/cmssw/pull/35167){:target="_blank"}  from **@yuanchao**: Remove unused headers for RECO & SIM packages `reconstruction` `simulation` created: 2021-09-06 14:54:09 merged: 2021-09-14 20:37:49

52. [35165](http://github.com/cms-sw/cmssw/pull/35165){:target="_blank"}  from **@PFCal-dev**: Updating the radiation map to be used with GeometryExtended2026D86Reco `simulation` `upgrade` created: 2021-09-06 14:44:02 merged: 2021-09-08 13:06:07

53. [35163](http://github.com/cms-sw/cmssw/pull/35163){:target="_blank"}  from **@abhih1**: Fix laser correction timing error in Ecal DQM `dqm` created: 2021-09-06 14:15:17 merged: 2021-09-07 08:31:07

54. [35159](http://github.com/cms-sw/cmssw/pull/35159){:target="_blank"}  from **@srimanob**: Update README Configuration/Geometry `geometry` `upgrade` created: 2021-09-06 03:40:48 merged: 2021-09-06 11:39:36

55. [35158](http://github.com/cms-sw/cmssw/pull/35158){:target="_blank"}  from **@lecriste**: [HGCAL] Introduce SimTracksters linking `dqm` `reconstruction` `upgrade` created: 2021-09-05 21:41:11 merged: 2021-09-08 18:17:21

56. [35157](http://github.com/cms-sw/cmssw/pull/35157){:target="_blank"}  from **@sroychow**: Migrate CondTools-Ecal modules to use esconsumes `db` created: 2021-09-05 18:02:00 merged: 2021-09-06 16:07:12

57. [35156](http://github.com/cms-sw/cmssw/pull/35156){:target="_blank"}  from **@bsunanda**: Run3-hcx319 Make use of ESGetToken in SimCalorimetry/HcalSimProducers `simulation` created: 2021-09-05 14:42:29 merged: 2021-09-06 01:02:08

58. [35155](http://github.com/cms-sw/cmssw/pull/35155){:target="_blank"}  from **@bsunanda**: Run3-371X Use of ESGetToken in Calibration/HcalCalibAlgos `alca` created: 2021-09-05 14:35:50 merged: 2021-09-06 00:48:06

59. [35154](http://github.com/cms-sw/cmssw/pull/35154){:target="_blank"}  from **@abdoulline**: HCAL Simulation : reformatted HF Shower Library for Run3 `geometry` `simulation` created: 2021-09-05 09:59:23 merged: 2021-09-07 06:47:55

60. [35153](http://github.com/cms-sw/cmssw/pull/35153){:target="_blank"}  from **@bsunanda**: Run3-hcx318 Correct a few analyzers in Calibration/HcalCalibAlgos aganist static analyzers `alca` created: 2021-09-04 20:58:17 merged: 2021-09-05 21:16:12

61. [35151](http://github.com/cms-sw/cmssw/pull/35151){:target="_blank"}  from **@Dr15Jones**: esConsumes for PhotonProducer/GsfPhotonProducer `reconstruction` created: 2021-09-03 21:37:51 merged: 2021-09-09 15:51:52

62. [35149](http://github.com/cms-sw/cmssw/pull/35149){:target="_blank"}  from **@thomreis**: ECAL esConsumes migration various packages `reconstruction` `db` created: 2021-09-03 16:58:25 merged: 2021-09-08 00:33:42

63. [35148](http://github.com/cms-sw/cmssw/pull/35148){:target="_blank"}  from **@smuzaffar**: [GCC11] Fix compilation warning for EcalMatacqDigi `simulation` created: 2021-09-03 16:05:04 merged: 2021-09-06 21:24:11

64. [35147](http://github.com/cms-sw/cmssw/pull/35147){:target="_blank"}  from **@bsunanda**: Run3-hcx316 Add a few collection for carrying out AlCaReco studies `alca` created: 2021-09-03 15:59:47 merged: 2021-09-04 01:22:05

65. [35145](http://github.com/cms-sw/cmssw/pull/35145){:target="_blank"}  from **@Dr15Jones**: Add esConsumes to modules that inherit from TrackProducerBase `reconstruction` created: 2021-09-03 15:38:56 merged: 2021-09-09 04:38:09

66. [35144](http://github.com/cms-sw/cmssw/pull/35144){:target="_blank"}  from **@smuzaffar**: [GCC11] Fix compilation warning for CommonTools `reconstruction` created: 2021-09-03 15:23:58 merged: 2021-09-03 20:11:12

67. [35143](http://github.com/cms-sw/cmssw/pull/35143){:target="_blank"}  from **@smuzaffar**: [GCC11] Fix compilation warning for FW/ToyIntProducers `core` created: 2021-09-03 15:22:09 merged: 2021-09-03 20:12:40

68. [35140](http://github.com/cms-sw/cmssw/pull/35140){:target="_blank"}  from **@srimanob**: Disable JME Nano workflows due to Nano-prompt dev `pdmv` `upgrade` created: 2021-09-03 09:00:34 merged: 2021-09-06 05:51:40

69. [35139](http://github.com/cms-sw/cmssw/pull/35139){:target="_blank"}  from **@smuzaffar**: [DBG] Fixed compilation errors `alca` created: 2021-09-03 05:12:39 merged: 2021-09-03 12:22:35

70. [35137](http://github.com/cms-sw/cmssw/pull/35137){:target="_blank"}  from **@wddgit**: Partial esConsumes migration for TrajectorySeedProducer `fastsim` `reconstruction` created: 2021-09-02 22:17:50 merged: 2021-09-10 19:26:44

71. [35136](http://github.com/cms-sw/cmssw/pull/35136){:target="_blank"}  from **@bsunanda**: Run3-hcx315 Rearrange the files properly in the plugins directory and define the python scripts from the code in Calibration/HcalIsolatedTrackReco `alca` created: 2021-09-02 20:45:50 merged: 2021-09-04 01:22:55

72. [35135](http://github.com/cms-sw/cmssw/pull/35135){:target="_blank"}  from **@dildick**: Add CSC TP efficiency producer in standard DQM sequence `dqm` `simulation` created: 2021-09-02 19:08:13 merged: 2021-09-05 13:00:19

73. [35134](http://github.com/cms-sw/cmssw/pull/35134){:target="_blank"}  from **@Dr15Jones**: Added esConsumes to modules in SimMuon/MCTruth `simulation` created: 2021-09-02 18:27:31 merged: 2021-09-05 12:50:49

74. [35133](http://github.com/cms-sw/cmssw/pull/35133){:target="_blank"}  from **@thomreis**: ECAL esConsumes migration of CaloOnlineTools/EcalTools `alca` created: 2021-09-02 16:54:05 merged: 2021-09-04 01:18:58

75. [35131](http://github.com/cms-sw/cmssw/pull/35131){:target="_blank"}  from **@fwyzard**: Fix the TriggerResultsFilter default configuration to skip the current process `hlt` created: 2021-09-02 16:25:30 merged: 2021-09-03 15:23:38

76. [35129](http://github.com/cms-sw/cmssw/pull/35129){:target="_blank"}  from **@ptcox**: Fix filling and multiplicity ranges `dqm` created: 2021-09-02 14:56:50 merged: 2021-09-03 12:25:05

77. [35128](http://github.com/cms-sw/cmssw/pull/35128){:target="_blank"}  from **@VinInn**: improve math in broken-line fit `reconstruction` created: 2021-09-02 14:14:26 merged: 2021-09-04 01:16:27

78. [35122](http://github.com/cms-sw/cmssw/pull/35122){:target="_blank"}  from **@smuzaffar**: Remove duplicate include statements `reconstruction` created: 2021-09-02 07:45:49 merged: 2021-09-02 13:46:57

79. [35121](http://github.com/cms-sw/cmssw/pull/35121){:target="_blank"}  from **@srimanob**: disable 136.72413 in relval_standard `pdmv` `upgrade` created: 2021-09-02 06:04:30 merged: 2021-09-02 11:52:48

80. [35120](http://github.com/cms-sw/cmssw/pull/35120){:target="_blank"}  from **@Dr15Jones**: Enable services in concurrent endJob processing `core` created: 2021-09-02 02:59:32 merged: 2021-09-02 12:56:20

81. [35119](http://github.com/cms-sw/cmssw/pull/35119){:target="_blank"}  from **@srimanob**: Adding fake alignment to make tracker geometry test work `geometry` created: 2021-09-02 02:55:08 merged: 2021-09-02 12:30:04

82. [35115](http://github.com/cms-sw/cmssw/pull/35115){:target="_blank"}  from **@bsunanda**: Run3-gex90X Clean up a few cfi's for HCAL and SimDB geometry `geometry` `upgrade` created: 2021-09-01 18:03:33 merged: 2021-09-04 01:20:34

83. [35114](http://github.com/cms-sw/cmssw/pull/35114){:target="_blank"}  from **@smuzaffar**: [GCC11] Ignore used uninitialized warning in DTDigiSimLink `simulation` created: 2021-09-01 17:49:24 merged: 2021-09-02 13:58:39

84. [35113](http://github.com/cms-sw/cmssw/pull/35113){:target="_blank"}  from **@smuzaffar**: [GCC11] Fix compiler warnings for RecoPPS `reconstruction` created: 2021-09-01 17:03:53 merged: 2021-09-02 02:39:08

85. [35112](http://github.com/cms-sw/cmssw/pull/35112){:target="_blank"}  from **@smuzaffar**: [GCC11] Fix comopiler warnings for LumiProducer `reconstruction` created: 2021-09-01 16:47:14 merged: 2021-09-02 02:38:32

86. [35110](http://github.com/cms-sw/cmssw/pull/35110){:target="_blank"}  from **@smuzaffar**: [GCC11] Fix warnings for EgammaHLTProducers `hlt` created: 2021-09-01 16:04:25 merged: 2021-09-02 13:39:36

87. [35107](http://github.com/cms-sw/cmssw/pull/35107){:target="_blank"}  from **@thomreis**: ECAL esConsumes migration of Calibration packages `alca` created: 2021-09-01 14:25:21 merged: 2021-09-03 12:35:35

88. [35106](http://github.com/cms-sw/cmssw/pull/35106){:target="_blank"}  from **@mmusich**: Modernize `Configuration/Skimming` and `DPGAnalysis/Skims` `pdmv` created: 2021-09-01 12:16:27 merged: 2021-09-07 12:53:41

89. [35104](http://github.com/cms-sw/cmssw/pull/35104){:target="_blank"}  from **@apsallid**: [HGCAL] Adding comments in HGCAL associators `simulation` `upgrade` created: 2021-09-01 11:10:40 merged: 2021-09-07 14:20:24

90. [35102](http://github.com/cms-sw/cmssw/pull/35102){:target="_blank"}  from **@perrotta**: Get rid of the unneeded conf_ class member in SiPixelPhase1EfficiencyExtras `dqm` created: 2021-09-01 07:08:51 merged: 2021-09-01 12:56:52

91. [35101](http://github.com/cms-sw/cmssw/pull/35101){:target="_blank"}  from **@jeongeun**: Migrate module configuration in PhysicsTools{PatUtils} to use default cfipython `reconstruction` created: 2021-09-01 03:07:22 merged: 2021-09-01 12:09:03

92. [35097](http://github.com/cms-sw/cmssw/pull/35097){:target="_blank"}  from **@Dr15Jones**: Run endStream concurrently as part of endJob `core` created: 2021-08-31 19:29:15 merged: 2021-09-01 01:33:57

93. [35096](http://github.com/cms-sw/cmssw/pull/35096){:target="_blank"}  from **@mmusich**: Migrate `CondTools/RunInfo` to esConsumes `db` created: 2021-08-31 18:28:04 merged: 2021-09-06 16:00:15

94. [35095](http://github.com/cms-sw/cmssw/pull/35095){:target="_blank"}  from **@Dr15Jones**: Finish esConsumes migration for L1TMuonBarrelTrackProducer `l1` created: 2021-08-31 17:34:20 merged: 2021-09-14 11:59:43

95. [35093](http://github.com/cms-sw/cmssw/pull/35093){:target="_blank"}  from **@bsunanda**: Run3-hcx314 Reorganize the files in SimCalorimetry/CastorTechTrigProducer and merge .h files `simulation` created: 2021-08-31 16:21:39 merged: 2021-09-02 02:42:44

96. [35092](http://github.com/cms-sw/cmssw/pull/35092){:target="_blank"}  from **@srimanob**: Fix 2021 Reco Geometry Config files `geometry` `upgrade` created: 2021-08-31 16:17:48 merged: 2021-09-01 05:43:50

97. [35091](http://github.com/cms-sw/cmssw/pull/35091){:target="_blank"}  from **@Purva-Chaudhari**: Removed lexical_cast boost dependency in CondFormats `alca` `db` created: 2021-08-31 15:39:25 merged: 2021-09-06 11:40:11

98. [35089](http://github.com/cms-sw/cmssw/pull/35089){:target="_blank"}  from **@CTPPS**: PPS: fix of isPixelHit `alca` created: 2021-08-31 14:48:20 merged: 2021-09-03 20:08:22

99. [35088](http://github.com/cms-sw/cmssw/pull/35088){:target="_blank"}  from **@bsunanda**: Run3-sim108 Fully resolve the issue of usinng dd4hep in CherenkovAnalysis `simulation` created: 2021-08-31 14:07:47 merged: 2021-09-01 01:35:02

100. [35086](http://github.com/cms-sw/cmssw/pull/35086){:target="_blank"}  from **@mmusich**: fix undefined behavior in `MultiTrackValidator` `dqm` created: 2021-08-31 08:21:43 merged: 2021-09-14 20:39:42

101. [35085](http://github.com/cms-sw/cmssw/pull/35085){:target="_blank"}  from **@CTPPS**: PPS: update scoring plane z positions `dqm` created: 2021-08-31 08:15:45 merged: 2021-09-07 11:56:36

102. [35083](http://github.com/cms-sw/cmssw/pull/35083){:target="_blank"}  from **@bsunanda**: Run3-sim107 Clean the code - removed the usage of cout and updated the cfg's `simulation` created: 2021-08-31 02:53:56 merged: 2021-08-31 21:21:22

103. [35081](http://github.com/cms-sw/cmssw/pull/35081){:target="_blank"}  from **@makortel**: Move "inverse of Bz at origin in GeV" from PixelRecoUtilities to MagneticField `fastsim` `reconstruction` created: 2021-08-31 01:45:06 merged: 2021-09-13 15:23:47

104. [35080](http://github.com/cms-sw/cmssw/pull/35080){:target="_blank"}  from **@Dr15Jones**: Added missing esConsumes to DTTrackFinder `l1` created: 2021-08-30 21:36:38 merged: 2021-09-14 00:50:50

105. [35079](http://github.com/cms-sw/cmssw/pull/35079){:target="_blank"}  from **@sroychow**: Migrate CondTools-Ecal modules to use esconsumes `db` created: 2021-08-30 19:10:30 merged: 2021-09-14 04:36:24

106. [35078](http://github.com/cms-sw/cmssw/pull/35078){:target="_blank"}  from **@Dr15Jones**: Modernized JetTagProducer `reconstruction` created: 2021-08-30 17:57:01 merged: 2021-09-01 19:29:39

107. [35077](http://github.com/cms-sw/cmssw/pull/35077){:target="_blank"}  from **@thomreis**: ECAL esConsumes migration of CalibCalorimetry packages `alca` `l1` created: 2021-08-30 17:29:25 merged: 2021-09-14 13:16:35

108. [35074](http://github.com/cms-sw/cmssw/pull/35074){:target="_blank"}  from **@Dr15Jones**: Have embedded root files send close reports `core` created: 2021-08-30 15:55:57 merged: 2021-08-31 14:48:35

109. [35073](http://github.com/cms-sw/cmssw/pull/35073){:target="_blank"}  from **@makortel**: Set numberOfConcurrentLuminosityBlocks to 1 for ALCA sequences that have EDModules that are not planned to support concurrent lumis `alca` `operations` created: 2021-08-30 15:00:34 merged: 2021-08-31 00:57:08

110. [35072](http://github.com/cms-sw/cmssw/pull/35072){:target="_blank"}  from **@colizz**: Fix the random segfault of RelVal workflow 573 `generators` `pdmv` `upgrade` created: 2021-08-30 14:40:31 merged: 2021-08-31 11:54:57

111. [35071](http://github.com/cms-sw/cmssw/pull/35071){:target="_blank"}  from **@yuanchao**: Remove unused headers in DataFormats package `core` `reconstruction` `simulation` created: 2021-08-30 11:24:34 merged: 2021-09-07 13:35:36

112. [35070](http://github.com/cms-sw/cmssw/pull/35070){:target="_blank"}  from **@Purva-Chaudhari**: removed lexical_cast boost dependency `l1` created: 2021-08-30 10:45:06 merged: 2021-08-31 15:45:09

113. [35068](http://github.com/cms-sw/cmssw/pull/35068){:target="_blank"}  from **@abdoulline**: [UBSAN] DataFormats/CaloTowers  initialization fix `reconstruction` created: 2021-08-30 10:32:38 merged: 2021-09-02 13:51:06

114. [35067](http://github.com/cms-sw/cmssw/pull/35067){:target="_blank"}  from **@CTPPS**: PPS Pixel data unpacking `reconstruction` created: 2021-08-30 08:44:43 merged: 2021-09-04 06:25:08

115. [35066](http://github.com/cms-sw/cmssw/pull/35066){:target="_blank"}  from **@mrodozov**: Initialize fields in ProcessCallGraph and HLTRegionalEcalResonanceFilter `hlt` created: 2021-08-28 22:31:32 merged: 2021-08-30 06:35:46

116. [35065](http://github.com/cms-sw/cmssw/pull/35065){:target="_blank"}  from **@bsunanda**: Run3-trk08 Make sure the dd4hep algorithms provide the namespace to all created solids/volumes `geometry` created: 2021-08-28 21:56:00 merged: 2021-08-31 15:55:11

117. [35064](http://github.com/cms-sw/cmssw/pull/35064){:target="_blank"}  from **@mrodozov**: Initialize enum field in CaloPoint class `fastsim` created: 2021-08-28 19:59:13 merged: 2021-08-31 17:38:13

118. [35063](http://github.com/cms-sw/cmssw/pull/35063){:target="_blank"}  from **@mrodozov**: Initialize member var in class DQClient `dqm` created: 2021-08-28 18:20:23 merged: 2021-08-29 16:47:38

119. [35062](http://github.com/cms-sw/cmssw/pull/35062){:target="_blank"}  from **@fabiocos**: MTD reconstruction: replace specific forward layer with the general mother class `reconstruction` `upgrade` created: 2021-08-28 17:08:15 merged: 2021-08-29 12:17:21

120. [35060](http://github.com/cms-sw/cmssw/pull/35060){:target="_blank"}  from **@perrotta**: Initalize flag in SiStripQualityChecker `dqm` created: 2021-08-28 15:15:55 merged: 2021-08-29 16:44:39

121. [35059](http://github.com/cms-sw/cmssw/pull/35059){:target="_blank"}  from **@perrotta**: Get rid of a dead increment in SiStripMonitorClient `dqm` created: 2021-08-28 09:34:02 merged: 2021-08-29 16:45:05

122. [35057](http://github.com/cms-sw/cmssw/pull/35057){:target="_blank"}  from **@makortel**: Modernize BetaBoostEvtVtxGenerator `generators` created: 2021-08-27 22:23:21 merged: 2021-09-10 13:03:21

123. [35056](http://github.com/cms-sw/cmssw/pull/35056){:target="_blank"}  from **@wddgit**: Migrate FastSimulation modules to use esConsumes `fastsim` created: 2021-08-27 21:32:19 merged: 2021-09-13 08:34:15

124. [35055](http://github.com/cms-sw/cmssw/pull/35055){:target="_blank"}  from **@gartung**: Utilities/StaticAnalyzer: Add base classes of producers to list of producers for a module `core` created: 2021-08-27 19:13:09 merged: 2021-09-13 00:59:31

125. [35054](http://github.com/cms-sw/cmssw/pull/35054){:target="_blank"}  from **@Dr15Jones**: Removed undefined use of union in libminifloat `core` `reconstruction` created: 2021-08-27 18:51:24 merged: 2021-09-02 13:45:31

126. [35053](http://github.com/cms-sw/cmssw/pull/35053){:target="_blank"}  from **@fabferro**: PPS: solving issue 35033 for CTPPSPixelRecHits `reconstruction` created: 2021-08-27 18:50:38 merged: 2021-08-28 13:35:05

127. [35052](http://github.com/cms-sw/cmssw/pull/35052){:target="_blank"}  from **@makortel**: Make GenHIEventProducer edm::global `generators` created: 2021-08-27 18:05:10 merged: 2021-09-10 13:02:55

128. [35051](http://github.com/cms-sw/cmssw/pull/35051){:target="_blank"}  from **@Dr15Jones**: Removed undefined use of union in getAnyPtr `core` created: 2021-08-27 17:32:14 merged: 2021-08-30 19:10:14

129. [35050](http://github.com/cms-sw/cmssw/pull/35050){:target="_blank"}  from **@bsunanda**: Run3-sim106 Investigating dd4hep initialization with root name other than cms::OCMS `geometry` `simulation` created: 2021-08-27 16:58:59 merged: 2021-08-30 06:38:00

130. [35049](http://github.com/cms-sw/cmssw/pull/35049){:target="_blank"}  from **@swagata87**: [EGM HLT] Phase out calotower & use HCAL recHits directly `hlt` created: 2021-08-27 16:37:44 merged: 2021-09-01 09:37:13

131. [35048](http://github.com/cms-sw/cmssw/pull/35048){:target="_blank"}  from **@ggovi**: Centralise payload ptr ownership for condition updating workflows `alca` `reconstruction` `simulation` `db` created: 2021-08-27 15:16:37 merged: 2021-08-31 16:24:21

132. [35045](http://github.com/cms-sw/cmssw/pull/35045){:target="_blank"}  from **@afiqaize**: address UB in EnergyUncertaintyPhotonSpecific.cc `reconstruction` created: 2021-08-27 14:14:59 merged: 2021-08-28 01:20:56

133. [35044](http://github.com/cms-sw/cmssw/pull/35044){:target="_blank"}  from **@iarspider**: [GCC11] Fix warnings: loop variable binds to a temporary `reconstruction` created: 2021-08-27 12:52:10 merged: 2021-08-28 06:28:04

134. [35043](http://github.com/cms-sw/cmssw/pull/35043){:target="_blank"}  from **@Sam-Harper**: Adding protections to PATTriggerProducer when the path has zero filters: 12_1 `reconstruction` created: 2021-08-27 12:06:29 merged: 2021-08-28 01:25:21

135. [35042](http://github.com/cms-sw/cmssw/pull/35042){:target="_blank"}  from **@eyigitba**: Disabled duplicate GEM TP warnings in EMTF GEM unpacker `l1` created: 2021-08-27 11:10:00 merged: 2021-08-31 15:43:09

136. [35041](http://github.com/cms-sw/cmssw/pull/35041){:target="_blank"}  from **@iarspider**: [GCC11] Fix warning: loop variable binds to temporary `dqm` created: 2021-08-27 08:03:33 merged: 2021-08-28 08:19:39

137. [35039](http://github.com/cms-sw/cmssw/pull/35039){:target="_blank"}  from **@smorovic**: DataFormats/FEDRawData UBSAN warning fixed `daq` created: 2021-08-27 07:25:56 merged: 2021-08-28 21:19:24

138. [35032](http://github.com/cms-sw/cmssw/pull/35032){:target="_blank"}  from **@bsunanda**: Run3-sum105 Add a utility function to print all solids with their shape type `simulation` created: 2021-08-26 20:24:11 merged: 2021-08-30 06:40:49

139. [35029](http://github.com/cms-sw/cmssw/pull/35029){:target="_blank"}  from **@ChrisMisan**: PCL of diamond sampic offset calibration `alca` `dqm` `operations` created: 2021-08-26 12:18:32 merged: 2021-09-06 01:16:55

140. [35027](http://github.com/cms-sw/cmssw/pull/35027){:target="_blank"}  from **@thomreis**: EcalRawToDigi pointer overflow fix `reconstruction` created: 2021-08-26 10:56:22 merged: 2021-08-27 15:31:15

141. [35024](http://github.com/cms-sw/cmssw/pull/35024){:target="_blank"}  from **@iarspider**: [GCC11] CalibPPS/AlignmentRelative: Fix warning:  `alca` created: 2021-08-26 08:44:15 merged: 2021-08-27 15:21:36

142. [35023](http://github.com/cms-sw/cmssw/pull/35023){:target="_blank"}  from **@sroychow**: Migrate Condtools-DT modules to esConsumes `db` created: 2021-08-26 03:51:41 merged: 2021-09-14 04:40:27

143. [35021](http://github.com/cms-sw/cmssw/pull/35021){:target="_blank"}  from **@Dr15Jones**: Modernize some EGamma Reco modules `reconstruction` created: 2021-08-26 00:26:48 merged: 2021-09-01 15:49:52

144. [35020](http://github.com/cms-sw/cmssw/pull/35020){:target="_blank"}  from **@makortel**: Migrate RPCUnpackingModule to esConsumes() `reconstruction` created: 2021-08-25 20:26:50 merged: 2021-08-27 13:36:42

145. [35018](http://github.com/cms-sw/cmssw/pull/35018){:target="_blank"}  from **@Dr15Jones**: Modernized some modules in RecoBTag `reconstruction` created: 2021-08-25 18:12:47 merged: 2021-08-27 20:59:15

146. [35017](http://github.com/cms-sw/cmssw/pull/35017){:target="_blank"}  from **@stahlleiton**: Adapt CAConstants for HIon `reconstruction` `heterogeneous` created: 2021-08-25 16:35:21 merged: 2021-09-01 16:04:59

147. [35016](http://github.com/cms-sw/cmssw/pull/35016){:target="_blank"}  from **@TomasKello**: Fix on compile issues with DMR, MTS and GC validation scripts. `alca` created: 2021-08-25 15:33:51 merged: 2021-08-27 15:07:07

148. [35015](http://github.com/cms-sw/cmssw/pull/35015){:target="_blank"}  from **@bsunanda**: Run3-sim104 Update the tools to investigate geometry setups `dqm` `geometry` `simulation` created: 2021-08-25 15:05:11 merged: 2021-08-27 21:04:15

149. [35000](http://github.com/cms-sw/cmssw/pull/35000){:target="_blank"}  from **@makortel**: Migrate RecoTracker/CkfPattern, and ClusterShapeTrajectoryFilter to esConsumes `reconstruction` created: 2021-08-24 20:23:35 merged: 2021-08-27 15:00:42

150. [34997](http://github.com/cms-sw/cmssw/pull/34997){:target="_blank"}  from **@Dr15Jones**: use esConsumes in PhysicsTools/PatAlgos modules `reconstruction` created: 2021-08-24 16:16:53 merged: 2021-08-27 14:33:42

151. [34995](http://github.com/cms-sw/cmssw/pull/34995){:target="_blank"}  from **@makortel**: Migrate some modules in SimCalorimetry to esConsumes `simulation` created: 2021-08-24 13:52:44 merged: 2021-08-28 07:48:01

152. [34989](http://github.com/cms-sw/cmssw/pull/34989){:target="_blank"}  from **@makortel**: Migrate some modules in SimPPS to esConsumes `simulation` created: 2021-08-23 20:01:15 merged: 2021-08-31 21:25:22

153. [34988](http://github.com/cms-sw/cmssw/pull/34988){:target="_blank"}  from **@aperloff**: Updates to the TTTrack/TTTrack_TrackWord DataFormats `l1` `upgrade` created: 2021-08-23 19:56:54 merged: 2021-09-01 01:36:28

154. [34986](http://github.com/cms-sw/cmssw/pull/34986){:target="_blank"}  from **@bsunanda**: Run3-hcx312 Rearrange the files and collapse .h files in SimCalorimetry/HcalTrigPrimProducers `l1` created: 2021-08-23 16:34:37 merged: 2021-08-31 15:59:02

155. [34985](http://github.com/cms-sw/cmssw/pull/34985){:target="_blank"}  from **@pieterdavid**: Add SiStripCalCosmics ALCANANO `alca` `operations` `pdmv` `upgrade` `xpog` created: 2021-08-23 16:26:36 merged: 2021-09-15 01:23:00

156. [34966](http://github.com/cms-sw/cmssw/pull/34966){:target="_blank"}  from **@CMSTrackerDPG**: TkDQM: Fix tracker maps for run3 `dqm` created: 2021-08-20 18:20:38 merged: 2021-08-30 01:10:30

157. [34955](http://github.com/cms-sw/cmssw/pull/34955){:target="_blank"}  from **@jeongeun**: Migrate module configuration in PhysicsTools{PatAlgos} to use default cfipython `reconstruction` created: 2021-08-19 13:33:04 merged: 2021-08-27 13:26:47

158. [34942](http://github.com/cms-sw/cmssw/pull/34942){:target="_blank"}  from **@Dr15Jones**: Make operator functions 'hidden' friends of ExpressionAST `fastsim` created: 2021-08-18 21:58:32 merged: 2021-08-31 00:25:30

159. [34933](http://github.com/cms-sw/cmssw/pull/34933){:target="_blank"}  from **@ggovi**: Delete unused headers/test files (DB packages) `alca` `l1` `db` created: 2021-08-18 14:34:18 merged: 2021-09-01 12:31:07

160. [34932](http://github.com/cms-sw/cmssw/pull/34932){:target="_blank"}  from **@Purva-Chaudhari**: Removed lexical_cast boost dependency in CondCore `alca` `hlt` `db` created: 2021-08-18 14:22:34 merged: 2021-09-07 08:47:12

161. [34902](http://github.com/cms-sw/cmssw/pull/34902){:target="_blank"}  from **@makortel**: Migrate BMixingModule and EcalShapeBase-derived classes to esConsumes `alca` `dqm` `l1` `reconstruction` `simulation` created: 2021-08-17 01:02:11 merged: 2021-09-01 12:20:15

162. [34898](http://github.com/cms-sw/cmssw/pull/34898){:target="_blank"}  from **@smuzaffar**: [EventFilter] Move private headers in plugins dir; merge plugins cc/h files `l1` `reconstruction` created: 2021-08-16 17:53:20 merged: 2021-09-01 05:34:54

163. [34895](http://github.com/cms-sw/cmssw/pull/34895){:target="_blank"}  from **@smuzaffar**: [L1Trigger] Move public headers in to interface directory `l1` created: 2021-08-16 16:18:38 merged: 2021-09-01 11:05:20

164. [34882](http://github.com/cms-sw/cmssw/pull/34882){:target="_blank"}  from **@czangela**: Follow up to PR review of CPEFast to better reproduce Generic and #34400 `geometry` `reconstruction` created: 2021-08-16 07:54:24 merged: 2021-08-28 01:32:06

165. [34860](http://github.com/cms-sw/cmssw/pull/34860){:target="_blank"}  from **@lathomas**: Bug fix for track MET in MET correction tools `reconstruction` created: 2021-08-12 18:39:33 merged: 2021-08-27 13:28:17

166. [34840](http://github.com/cms-sw/cmssw/pull/34840){:target="_blank"}  from **@yeckang**: Reducing the GEMDigiSimLink size and turning off gem multi bx readout during Run3 `dqm` `simulation` `upgrade` created: 2021-08-11 09:32:39 merged: 2021-08-27 13:53:39

167. [34805](http://github.com/cms-sw/cmssw/pull/34805){:target="_blank"}  from **@TaeunKwon**: HCAL: fixing pulse containment correction algorithm for Run3 trigger primitives `alca` `l1` created: 2021-08-05 20:15:52 merged: 2021-09-01 12:07:37

168. [34801](http://github.com/cms-sw/cmssw/pull/34801){:target="_blank"}  from **@dinyar**: Correct RegionalMuon (un)packer when running on EMTF data `l1` created: 2021-08-05 18:37:22 merged: 2021-09-02 02:41:41

169. [34779](http://github.com/cms-sw/cmssw/pull/34779){:target="_blank"}  from **@dildick**: Move CSC trigger and GEM-CSC trigger lookup tables into eventsetup objects (CCLUT-17) `alca` `dqm` `l1` `db` created: 2021-08-04 16:47:23 merged: 2021-09-03 00:57:19

170. [34714](http://github.com/cms-sw/cmssw/pull/34714){:target="_blank"}  from **@mariadalfonso**: NANO: rework for Prompt (part3) `operations` `pdmv` `upgrade` `xpog` created: 2021-08-01 20:28:34 merged: 2021-09-01 01:45:36

171. [34615](http://github.com/cms-sw/cmssw/pull/34615){:target="_blank"}  from **@guitargeek**: Merge .h and .cc files of plugins in several PhysicsTools packages `analysis` `reconstruction` created: 2021-07-25 09:27:34 merged: 2021-09-01 14:09:54

172. [34384](http://github.com/cms-sw/cmssw/pull/34384){:target="_blank"}  from **@SissonJ**: DQM Pixel Phase 1: Several new Efficiency trend plots `dqm` created: 2021-07-07 14:35:08 merged: 2021-08-30 01:16:13

173. [33885](http://github.com/cms-sw/cmssw/pull/33885){:target="_blank"}  from **@ahinzmann**: Unify vertex association between CHS and PUPPI `reconstruction` created: 2021-05-28 15:48:54 merged: 2021-09-14 06:46:58

#### CMSDIST Changes between Tags REL/CMSSW_12_1_0_pre2/slc7_amd64_gcc900 and REL/CMSSW_12_1_0_pre3/slc7_amd64_gcc900:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_12_1_0_pre2/slc7_amd64_gcc900...REL/CMSSW_12_1_0_pre3/slc7_amd64_gcc900)



1. [7312](http://github.com/cms-sw/cmsdist/pull/7312){:target="_blank"}  from **@cms-sw**: cmssw-wm-tools: fixes case where parameter is not set created: 2021-09-15 18:35:22 merged: 2021-09-15 18:35:33

2. [7310](http://github.com/cms-sw/cmsdist/pull/7310){:target="_blank"}  from **@cms-sw**: Update form and clean up recipe created: 2021-09-15 10:50:31 merged: 2021-09-15 16:04:06

3. [7308](http://github.com/cms-sw/cmsdist/pull/7308){:target="_blank"}  from **@cms-sw**: Drop fitsio spec created: 2021-09-15 08:52:42 merged: 2021-09-15 13:06:21

4. [7306](http://github.com/cms-sw/cmsdist/pull/7306){:target="_blank"}  from **@cms-sw**: remove unused data package Geometry-TrackerCommonData created: 2021-09-14 12:25:25 merged: 2021-09-14 16:11:27

5. [7305](http://github.com/cms-sw/cmsdist/pull/7305){:target="_blank"}  from **@cms-sw**: use default aiohttp version 3.7.4 created: 2021-09-14 08:49:20 merged: 2021-09-14 09:09:34

6. [7304](http://github.com/cms-sw/cmsdist/pull/7304){:target="_blank"}  from **@cms-sw**: added dummy test-download package to show how to use custom download command created: 2021-09-14 08:26:54 merged: 2021-09-14 08:52:48

7. [7303](http://github.com/cms-sw/cmsdist/pull/7303){:target="_blank"}  from **@cms-sw**: Remove unused pip files created: 2021-09-14 08:14:51 merged: 2021-09-14 08:52:15

8. [7302](http://github.com/cms-sw/cmsdist/pull/7302){:target="_blank"}  from **@cms-sw**: Drop dmtcp package, keeping the spec in archive created: 2021-09-14 07:41:05 merged: 2021-09-14 08:54:09

9. [7301](http://github.com/cms-sw/cmsdist/pull/7301){:target="_blank"}  from **@cms-sw**: Updated correctionlib version 2.0.0 and its dependencies created: 2021-09-13 15:30:20 merged: 2021-09-14 08:51:31

10. [7298](http://github.com/cms-sw/cmsdist/pull/7298){:target="_blank"}  from **@cms-sw**: Update tag for RecoTracker-MkFit to V00-04-00 created: 2021-09-10 20:57:35 merged: 2021-09-10 21:00:18

11. [7297](http://github.com/cms-sw/cmsdist/pull/7297){:target="_blank"}  from **@cms-sw**: cleanup data package generation created: 2021-09-10 18:09:03 merged: 2021-09-10 18:38:58

12. [7296](http://github.com/cms-sw/cmsdist/pull/7296){:target="_blank"}  from **@cms-sw**: drop openssl from bootstrap bundle created: 2021-09-10 10:57:56 merged: 2021-09-10 15:01:57

13. [7295](http://github.com/cms-sw/cmsdist/pull/7295){:target="_blank"}  from **@cms-sw**: Drop unused spec created: 2021-09-10 07:42:50 merged: 2021-09-10 11:01:05

14. [7294](http://github.com/cms-sw/cmsdist/pull/7294){:target="_blank"}  from **@cms-sw**: Remove doxygen from cmssw dist created: 2021-09-10 07:35:15 merged: 2021-09-10 11:00:30

15. [7293](http://github.com/cms-sw/cmsdist/pull/7293){:target="_blank"}  from **@cms-sw**: [BuildRules] Use CUDA runtime compatibility to set cuda env created: 2021-09-09 20:00:14 merged: 2021-09-09 20:56:30

16. [7288](http://github.com/cms-sw/cmsdist/pull/7288){:target="_blank"}  from **@ddaina**: update crab-dev to v3.210909 and set to use 1.5.2 wmcore created: 2021-09-09 09:02:24 merged: 2021-09-09 18:07:24

17. [7287](http://github.com/cms-sw/cmsdist/pull/7287){:target="_blank"}  from **@mmasciov**: Update mkfit to V3.2.0-0 created: 2021-09-08 16:49:19 merged: 2021-09-10 20:57:10

18. [7285](http://github.com/cms-sw/cmsdist/pull/7285){:target="_blank"}  from **@cms-sw**: Update CLHEP created: 2021-09-08 13:51:42 merged: 2021-09-09 09:41:53

19. [7284](http://github.com/cms-sw/cmsdist/pull/7284){:target="_blank"}  from **@cms-sw**: Update cgal created: 2021-09-08 11:39:51 merged: 2021-09-09 21:04:10

20. [7282](http://github.com/cms-sw/cmsdist/pull/7282){:target="_blank"}  from **@cms-sw**: Update tag for CalibPPS-ESProducers to V01-04-00 created: 2021-09-08 09:59:07 merged: 2021-09-09 03:27:27

21. [7280](http://github.com/cms-sw/cmsdist/pull/7280){:target="_blank"}  from **@cms-sw**: Drop byacc created: 2021-09-08 08:50:47 merged: 2021-09-08 14:28:26

22. [7279](http://github.com/cms-sw/cmsdist/pull/7279){:target="_blank"}  from **@fwyzard**: Add the cuda-compatible-runtime test as a new external created: 2021-09-08 08:09:07 merged: 2021-09-09 19:58:46

23. [7278](http://github.com/cms-sw/cmsdist/pull/7278){:target="_blank"}  from **@fwyzard**: Enable the use of cuDNN in ONNX on ARM for CentOS 8 created: 2021-09-08 08:06:36 merged: 2021-09-09 05:56:25

24. [7277](http://github.com/cms-sw/cmsdist/pull/7277){:target="_blank"}  from **@fwyzard**: Update to CUDA 11.4.2 created: 2021-09-08 08:02:28 merged: 2021-09-09 05:59:25

25. [7269](http://github.com/cms-sw/cmsdist/pull/7269){:target="_blank"}  from **@cms-sw**: [HFShowerLibrary] Update to version v6 created: 2021-09-05 07:48:54 merged: 2021-09-07 06:51:19

26. [7268](http://github.com/cms-sw/cmsdist/pull/7268){:target="_blank"}  from **@belforte**: update crab-dev with latest bug fix created: 2021-09-03 20:49:14 merged: 2021-09-03 21:47:15

27. [7266](http://github.com/cms-sw/cmsdist/pull/7266){:target="_blank"}  from **@cms-sw**: Update tag for L1Trigger-CSCTriggerPrimitives to V00-11-00 created: 2021-09-03 00:56:10 merged: 2021-09-03 00:56:45

28. [7265](http://github.com/cms-sw/cmsdist/pull/7265){:target="_blank"}  from **@cms-sw**: [cmssw-ib] Use latest buildLogAnalyzer.py which treats private header usage as build errors created: 2021-09-02 12:47:45 merged: 2021-09-02 12:48:06

29. [7264](http://github.com/cms-sw/cmsdist/pull/7264){:target="_blank"}  from **@cms-sw**: [BuildRules] treat private header usage as error created: 2021-09-02 08:53:23 merged: 2021-09-02 13:29:35

30. [7263](http://github.com/cms-sw/cmsdist/pull/7263){:target="_blank"}  from **@cms-sw**: Updates python packages to their latest version created: 2021-09-01 15:09:58 merged: 2021-09-06 07:27:10

31. [7261](http://github.com/cms-sw/cmsdist/pull/7261){:target="_blank"}  from **@cms-sw**: [Herwig7] Patch FXFX.h to match thepeg/LesHouches.h created: 2021-09-01 13:31:48 merged: 2021-09-01 20:15:01

32. [7260](http://github.com/cms-sw/cmsdist/pull/7260){:target="_blank"}  from **@cms-sw**: ThePEG - remove `-g` flag from the compilation created: 2021-09-01 09:12:10 merged: 2021-09-01 19:20:02

33. [7259](http://github.com/cms-sw/cmsdist/pull/7259){:target="_blank"}  from **@ddaina**: update crab-dev to v3.210831 created: 2021-08-31 14:40:42 merged: 2021-08-31 15:31:23

34. [7258](http://github.com/cms-sw/cmsdist/pull/7258){:target="_blank"}  from **@fwyzard**: Update LLVM to version 12.0.1 created: 2021-08-31 10:45:11 merged: 2021-09-01 15:46:21

35. [7257](http://github.com/cms-sw/cmsdist/pull/7257){:target="_blank"}  from **@fwyzard**: Update to CUDA 11.4.1 created: 2021-08-31 08:19:01 merged: 2021-09-01 08:18:12

36. [7256](http://github.com/cms-sw/cmsdist/pull/7256){:target="_blank"}  from **@fwyzard**: Update OpenMPI to version 4.1.1 created: 2021-08-31 08:14:24 merged: 2021-09-01 08:18:24

37. [7250](http://github.com/cms-sw/cmsdist/pull/7250){:target="_blank"}  from **@cms-sw**: multi-vector build fixes after toolfile migration created: 2021-08-28 10:51:46 merged: 2021-08-29 18:04:40

38. [7249](http://github.com/cms-sw/cmsdist/pull/7249){:target="_blank"}  from **@ddaina**: update crab-dev to v3.210827 created: 2021-08-27 14:39:40 merged: 2021-08-27 16:55:00

39. [7248](http://github.com/cms-sw/cmsdist/pull/7248){:target="_blank"}  from **@cms-sw**: remove gcc deps from gcc-fixincludes created: 2021-08-27 06:11:02 merged: 2021-08-27 10:58:17

40. [7247](http://github.com/cms-sw/cmsdist/pull/7247){:target="_blank"}  from **@ddaina**: update crab-prod to v3.210825 created: 2021-08-26 12:13:35 merged: 2021-08-27 05:41:49

41. [7245](http://github.com/cms-sw/cmsdist/pull/7245){:target="_blank"}  from **@cms-sw**: [BuildRules] Cleanup debug messages created: 2021-08-26 07:35:41 merged: 2021-08-27 05:25:02

42. [7243](http://github.com/cms-sw/cmsdist/pull/7243){:target="_blank"}  from **@cms-sw**: [Tensorflow] Update to version 2.6.0 created: 2021-08-26 06:55:01 merged: 2021-08-27 16:54:23

43. [7241](http://github.com/cms-sw/cmsdist/pull/7241){:target="_blank"}  from **@cms-sw**: Update cmssw-wm-tools.spec created: 2021-08-25 16:54:24 merged: 2021-08-27 05:42:08
