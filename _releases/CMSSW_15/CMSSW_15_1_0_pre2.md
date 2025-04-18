---
layout: post
rel_link:  "15_1_0_pre2"
title:  "CMSSW_15_1_0_pre2"
date:   2025-04-17 22:04:59
categories: cmssw
relmajor: 15
relminor: 1
relsubminor: 0
relpre: _pre2
---

# CMSSW_15_1_0_pre2
#### Changes since CMSSW_15_1_0_pre1:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_15_1_0_pre1...CMSSW_15_1_0_pre2)



1. [47890](http://github.com/cms-sw/cmssw/pull/47890){:target="_blank"}  from **@Dr15Jones**: Add dictionary for GEMSubDetId needed by RNTuple `simulation` created: 2025-04-16 16:54:32 merged: 2025-04-16 20:00:00

2. [47872](http://github.com/cms-sw/cmssw/pull/47872){:target="_blank"}  from **@mmusich**: Fix  `siPixelDigiMorphing` modifer and create workflows to test it `reconstruction` `pdmv` `upgrade` `trk` created: 2025-04-15 16:04:10 merged: 2025-04-16 19:59:05

3. [47866](http://github.com/cms-sw/cmssw/pull/47866){:target="_blank"}  from **@bsunanda**: Run3-Sim160 Make a test code that could be used to make a shower library for ZDC to be used by Lev Kheyn `simulation` created: 2025-04-15 04:02:24 merged: 2025-04-17 10:39:01

4. [47864](http://github.com/cms-sw/cmssw/pull/47864){:target="_blank"}  from **@AdrianoDee**: Adding 2024 `SKIM` Wfs `pdmv` `upgrade` created: 2025-04-14 15:50:23 merged: 2025-04-15 11:19:11

5. [47860](http://github.com/cms-sw/cmssw/pull/47860){:target="_blank"}  from **@mmusich**: Fix `hltInfo` utility script and add a unit test `hlt` created: 2025-04-13 15:06:41 merged: 2025-04-14 09:48:11

6. [47858](http://github.com/cms-sw/cmssw/pull/47858){:target="_blank"}  from **@mmusich**: change era to `Run3_2025` in a few selected online DQM clients `dqm` created: 2025-04-13 13:11:55 merged: 2025-04-14 18:22:46

7. [47856](http://github.com/cms-sw/cmssw/pull/47856){:target="_blank"}  from **@mmusich**: `L1TStage2uGTTiming`: fix `unprescaledAlgoShortList` for 2025 (removal `L1_AXO_Nominal` in favor of `L1_AXO_Medium`) `dqm` created: 2025-04-13 12:27:24 merged: 2025-04-14 18:21:50

8. [47855](http://github.com/cms-sw/cmssw/pull/47855){:target="_blank"}  from **@bsunanda**: Phase2-hgx363H Correct the dd4hep version of the mixed layer algorithm to be used for V19 versison of HGCal `geometry` `upgrade` created: 2025-04-13 05:16:52 merged: 2025-04-13 18:17:47

9. [47851](http://github.com/cms-sw/cmssw/pull/47851){:target="_blank"}  from **@mmusich**: Removal of illegal `PoolDBESSource` parameters  `alca` `analysis` `dqm` `geometry` `l1` `reconstruction` `simulation` `db` `xpog` `tracking` `trk` `ml` created: 2025-04-12 10:13:34 merged: 2025-04-16 19:56:54

10. [47850](http://github.com/cms-sw/cmssw/pull/47850){:target="_blank"}  from **@bsunanda**: Run3-gex188B Correct the PPS file by Gustavo `geometry` created: 2025-04-11 16:11:28 merged: 2025-04-12 11:00:01

11. [47849](http://github.com/cms-sw/cmssw/pull/47849){:target="_blank"}  from **@kpedro88**: Restore branchless 'and' operations `reconstruction` `tracking` created: 2025-04-11 14:44:07 merged: 2025-04-12 11:00:31

12. [47848](http://github.com/cms-sw/cmssw/pull/47848){:target="_blank"}  from **@bsunanda**: Phase2-hgx363G Correct the DD4hep algorithm for the HGCaal passive elements `geometry` `upgrade` created: 2025-04-11 13:32:01 merged: 2025-04-14 16:44:29

13. [47847](http://github.com/cms-sw/cmssw/pull/47847){:target="_blank"}  from **@Dr15Jones**: Mark more classes with rntupleStreamerMode `reconstruction` `simulation` created: 2025-04-11 13:10:19 merged: 2025-04-12 20:21:33

14. [47845](http://github.com/cms-sw/cmssw/pull/47845){:target="_blank"}  from **@bsunanda**:  Run3-hcx381 Add a checking routine to validate FastSim PU on FullSim signal `dqm` created: 2025-04-11 10:53:29 merged: 2025-04-14 18:21:25

15. [47840](http://github.com/cms-sw/cmssw/pull/47840){:target="_blank"}  from **@makortel**: Add a log message for URLs the XrdAdaptor opens `core` created: 2025-04-10 17:36:19 merged: 2025-04-11 16:01:56

16. [47839](http://github.com/cms-sw/cmssw/pull/47839){:target="_blank"}  from **@perrotta**: Fix the AlCaRecoTriggerBits/SecondaryDataset tag for the first IOVs in Run2 and Run3 data GT `alca` created: 2025-04-10 17:10:26 merged: 2025-04-11 16:01:44

17. [47837](http://github.com/cms-sw/cmssw/pull/47837){:target="_blank"}  from **@smuzaffar**: Do not use command ls with -lh option: Fixes unit test for ASAN IB `db` created: 2025-04-10 15:05:49 merged: 2025-04-11 16:02:26

18. [47834](http://github.com/cms-sw/cmssw/pull/47834){:target="_blank"}  from **@mkirsano**: Add plugins that create HepMC3 products to Herwig7Interface `generators` created: 2025-04-10 13:50:15 merged: 2025-04-13 12:38:16

19. [47833](http://github.com/cms-sw/cmssw/pull/47833){:target="_blank"}  from **@lathomas**: Adding optional deltaR cuts to HLTPMMassFilter `hlt` created: 2025-04-10 11:34:55 merged: 2025-04-11 13:55:51

20. [47832](http://github.com/cms-sw/cmssw/pull/47832){:target="_blank"}  from **@bsunanda**: Phase2-hgx363F Adjust the retraction of the scintillator cassettes in the LD mixed layers of HGCal `geometry` `upgrade` created: 2025-04-10 09:01:42 merged: 2025-04-11 13:55:26

21. [47827](http://github.com/cms-sw/cmssw/pull/47827){:target="_blank"}  from **@lathomas**: Add optional regional vetos to some EcalPFClusterIsolation methods `reconstruction` created: 2025-04-09 10:30:16 merged: 2025-04-10 09:53:18

22. [47825](http://github.com/cms-sw/cmssw/pull/47825){:target="_blank"}  from **@bsunanda**: Run3-gex188A Update the scenario for 2025 `geometry` `upgrade` created: 2025-04-09 05:29:32 merged: 2025-04-13 18:17:02

23. [47824](http://github.com/cms-sw/cmssw/pull/47824){:target="_blank"}  from **@bsunanda**: Phase2-hgx363E Modify the debug statements to enable the testing of the crash in the Digi step for 34034.0 `simulation` `upgrade` created: 2025-04-09 04:29:29 merged: 2025-04-10 13:07:27

24. [47822](http://github.com/cms-sw/cmssw/pull/47822){:target="_blank"}  from **@cms-AlCaDB**: Add transactionId as optional parameter of CondDBESSource `alca` `db` created: 2025-04-08 20:42:44 merged: 2025-04-10 13:28:58

25. [47821](http://github.com/cms-sw/cmssw/pull/47821){:target="_blank"}  from **@civanch**: [FULLSIM] Split Geant4 user actions between Run2,3 and Run4 `simulation` created: 2025-04-08 16:29:23 merged: 2025-04-08 18:42:17

26. [47819](http://github.com/cms-sw/cmssw/pull/47819){:target="_blank"}  from **@Dr15Jones**: Use proper extension for files explicitly from an older step in WorkFlowRunner.py `pdmv` `upgrade` created: 2025-04-08 15:44:44 merged: 2025-04-10 09:52:33

27. [47818](http://github.com/cms-sw/cmssw/pull/47818){:target="_blank"}  from **@bsunanda**: Phase2-hgx363D Modify the validation check of scintillation tiles to put the active cells in the geometry pool for the V19 version `geometry` `upgrade` created: 2025-04-08 14:36:36 merged: 2025-04-10 09:58:08

28. [47817](http://github.com/cms-sw/cmssw/pull/47817){:target="_blank"}  from **@perrotta**: Update autoCond for the first L1T menu of 2025 `alca` created: 2025-04-08 13:59:09 merged: 2025-04-08 18:40:29

29. [47813](http://github.com/cms-sw/cmssw/pull/47813){:target="_blank"}  from **@LinaresToine**: Make ReserveDMu skim throw exception upon mismatch in requested trigg `pdmv` created: 2025-04-08 13:41:28 merged: 2025-04-15 11:17:01

30. [47811](http://github.com/cms-sw/cmssw/pull/47811){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `15_0_X` (4/N)  [`15_1_X`]  `hlt` created: 2025-04-08 13:14:07 merged: 2025-04-08 18:29:47

31. [47809](http://github.com/cms-sw/cmssw/pull/47809){:target="_blank"}  from **@bsunanda**: Run3-gex188 Add cff files for testing 4 RPC specific scenarios `geometry` created: 2025-04-08 09:55:17 merged: 2025-04-08 18:30:40

32. [47804](http://github.com/cms-sw/cmssw/pull/47804){:target="_blank"}  from **@bsunanda**: Phase2-HGC363C Correct the cassette shift for the scintillator tiles in HGCal V19 geometry `geometry` `upgrade` created: 2025-04-08 04:30:22 merged: 2025-04-08 18:30:18

33. [47803](http://github.com/cms-sw/cmssw/pull/47803){:target="_blank"}  from **@slava77**: Revert "speedup SiStripClusterizer(FromRaw) using ThreeThresholdAlgorithm" `alca` `reconstruction` `trk` created: 2025-04-07 23:06:37 merged: 2025-04-08 18:30:02

34. [47796](http://github.com/cms-sw/cmssw/pull/47796){:target="_blank"}  from **@mmusich**: Miscellaneous updates for modules targeting CDC reconstruction at HLT `reconstruction` `tracking` created: 2025-04-07 11:57:21 merged: 2025-04-07 19:08:04

35. [47795](http://github.com/cms-sw/cmssw/pull/47795){:target="_blank"}  from **@VourMa**: Fix docs in relval_gpu.py `pdmv` `upgrade` created: 2025-04-06 20:01:46 merged: 2025-04-14 18:20:55

36. [47794](http://github.com/cms-sw/cmssw/pull/47794){:target="_blank"}  from **@bsunanda**: Phase2-hgx363B Make some corrections to remove certain bugs in the  description of scintillator tiles of HGCal V19 `geometry` `simulation` `upgrade` created: 2025-04-06 13:05:44 merged: 2025-04-07 07:15:57

37. [47789](http://github.com/cms-sw/cmssw/pull/47789){:target="_blank"}  from **@Dr15Jones**: Only use CPUTimer in XrdRequestManager debugging `core` created: 2025-04-03 18:56:07 merged: 2025-04-07 15:11:52

38. [47782](http://github.com/cms-sw/cmssw/pull/47782){:target="_blank"}  from **@mmusich**: fix `TrackToTrackComparisonHists` logic for cosmics `dqm` `tracking` created: 2025-04-03 16:09:32 merged: 2025-04-07 09:37:56

39. [47778](http://github.com/cms-sw/cmssw/pull/47778){:target="_blank"}  from **@hahnjo**: Map unknown exit codes to PlatformStatus.PlatformNotAvailable `heterogeneous` created: 2025-04-03 14:20:08 merged: 2025-04-04 06:32:11

40. [47776](http://github.com/cms-sw/cmssw/pull/47776){:target="_blank"}  from **@thomreis**: Activate ECAL CC timing algorithm for Run3_2025 era `operations` `ecal` created: 2025-04-03 11:20:58 merged: 2025-04-08 05:30:42

41. [47775](http://github.com/cms-sw/cmssw/pull/47775){:target="_blank"}  from **@bsunanda**: Phase2-hgx363A Update the dd4hep versions of V19 algorithms of HGCal geometry `geometry` `upgrade` created: 2025-04-03 10:24:39 merged: 2025-04-04 06:33:31

42. [47772](http://github.com/cms-sw/cmssw/pull/47772){:target="_blank"}  from **@bsunanda**: Phase2-hgx363 Make some changes to initialize V19 reconstruction geometry for HGCal `geometry` `simulation` `upgrade` created: 2025-04-03 08:42:31 merged: 2025-04-04 06:31:22

43. [47770](http://github.com/cms-sw/cmssw/pull/47770){:target="_blank"}  from **@Dr15Jones**: Manage memory for ESGetToken's productLabel `core` created: 2025-04-02 21:18:37 merged: 2025-04-03 14:47:34

44. [47767](http://github.com/cms-sw/cmssw/pull/47767){:target="_blank"}  from **@smorovic**: [DAQ] fix DAQSource race condition (15_1_X) `daq` created: 2025-04-02 19:06:07 merged: 2025-04-03 14:47:02

45. [47766](http://github.com/cms-sw/cmssw/pull/47766){:target="_blank"}  from **@yumeng111**: Update the value of pretrigger-trigger matching configuration parameter: clctPretriggerTriggerZone `l1` `upgrade` created: 2025-04-02 15:36:00 merged: 2025-04-11 16:02:57

46. [47765](http://github.com/cms-sw/cmssw/pull/47765){:target="_blank"}  from **@AuroraPerego**: set `crossedBoundary_` only for classVersion 12 of the `SimTrack`  `simulation` created: 2025-04-02 15:26:09 merged: 2025-04-02 20:28:43

47. [47757](http://github.com/cms-sw/cmssw/pull/47757){:target="_blank"}  from **@fabiocos**: MTD geometry: fix for geometry navigation issues in scenario D119 `geometry` `reconstruction` `upgrade` created: 2025-04-02 11:37:36 merged: 2025-04-06 17:51:51

48. [47756](http://github.com/cms-sw/cmssw/pull/47756){:target="_blank"}  from **@civanch**: [FULLSIM] Set enable EM physics library G4HepEM by default `simulation` created: 2025-04-02 10:17:44 merged: 2025-04-02 20:25:45

49. [47755](http://github.com/cms-sw/cmssw/pull/47755){:target="_blank"}  from **@AdrianoDee**: Allowing No Golden and Run Based Skim Option of `das-up-to-nevents.py` `pdmv` `upgrade` created: 2025-04-02 09:19:33 merged: 2025-04-06 17:51:07

50. [47753](http://github.com/cms-sw/cmssw/pull/47753){:target="_blank"}  from **@smorovic**: [HLTrigger/Egamma] fix swapped eta parameter for photons in Diphoton XGBoost MVA filter (15_1_X) `hlt` created: 2025-04-02 07:50:57 merged: 2025-04-02 20:24:30

51. [47749](http://github.com/cms-sw/cmssw/pull/47749){:target="_blank"}  from **@AdrianoDee**: Adding TeVJet RelVal 2024 Wfs `pdmv` `upgrade` created: 2025-04-01 14:18:56 merged: 2025-04-15 11:18:21

52. [47748](http://github.com/cms-sw/cmssw/pull/47748){:target="_blank"}  from **@kpedro88**: SONIC configuration updates `pdmv` `upgrade` `heterogeneous` created: 2025-04-01 13:38:23 merged: 2025-04-10 09:56:58

53. [47747](http://github.com/cms-sw/cmssw/pull/47747){:target="_blank"}  from **@iarspider**: [GCC14] Silence array-bounds warning in KalmanUtilsMPlex.cc `reconstruction` `tracking` created: 2025-04-01 09:45:09 merged: 2025-04-02 20:23:58

54. [47745](http://github.com/cms-sw/cmssw/pull/47745){:target="_blank"}  from **@mmusich**: add `dqmInfoHLTMon` to `offlineHLTSource` in `DQMOffline_Trigger_cosmics` and enable `showHLTGlobalTag` `dqm` created: 2025-04-01 07:57:17 merged: 2025-04-03 14:47:55

55. [47743](http://github.com/cms-sw/cmssw/pull/47743){:target="_blank"}  from **@fwyzard**: Fix false positive in `testMissingDictionaryCUDA` `heterogeneous` created: 2025-03-31 19:24:16 merged: 2025-04-01 05:20:24

56. [47739](http://github.com/cms-sw/cmssw/pull/47739){:target="_blank"}  from **@patinkaew**: Add filter to skip events without scouting objects in ScoutingNano for ScoutingPFMonitor dataset `pdmv` `upgrade` `xpog` created: 2025-03-31 11:52:51 merged: 2025-04-07 15:13:36

57. [47738](http://github.com/cms-sw/cmssw/pull/47738){:target="_blank"}  from **@civanch**: [SIM] Improved initialisation for calorimeters `simulation` created: 2025-03-31 11:44:49 merged: 2025-04-03 14:48:03

58. [47731](http://github.com/cms-sw/cmssw/pull/47731){:target="_blank"}  from **@fwyzard**: Add a test for missing dictionaries with CUDA headers `heterogeneous` created: 2025-03-28 23:24:00 merged: 2025-03-31 07:37:30

59. [47730](http://github.com/cms-sw/cmssw/pull/47730){:target="_blank"}  from **@Pmeiring**: CALO-L2 EG, Tau, Jet calibrations with conservative ZS for first L1 menu 2025 `l1` created: 2025-03-28 22:22:04 merged: 2025-04-16 20:05:54

60. [47729](http://github.com/cms-sw/cmssw/pull/47729){:target="_blank"}  from **@hqucms**: Reduce memory usage in NANO merge jobs `xpog` created: 2025-03-28 20:20:06 merged: 2025-04-01 05:20:03

61. [47726](http://github.com/cms-sw/cmssw/pull/47726){:target="_blank"}  from **@arsahasransu**: Plugin to obtain the best track index for Run3ScoutingElectron `xpog` created: 2025-03-28 13:44:13 merged: 2025-04-16 10:52:28

62. [47724](http://github.com/cms-sw/cmssw/pull/47724){:target="_blank"}  from **@Dongwoon77**: Update on GEM offlineDQM Cluster plots `dqm` created: 2025-03-28 10:41:22 merged: 2025-04-01 05:21:19

63. [47723](http://github.com/cms-sw/cmssw/pull/47723){:target="_blank"}  from **@RobertJWard**: Change HPSTau input collection from l1tHPSPFTauProducerPF to l1tHPSPFTauProducerPuppi `l1` `xpog` created: 2025-03-28 10:25:47 merged: 2025-04-01 05:22:03

64. [47721](http://github.com/cms-sw/cmssw/pull/47721){:target="_blank"}  from **@etzovara**: Developing offline JetMET DQM for Scouting jets: applying JetID criteria - complementary to PR #47328 `dqm` `reconstruction` created: 2025-03-28 00:22:24 merged: 2025-04-07 15:11:31

65. [47719](http://github.com/cms-sw/cmssw/pull/47719){:target="_blank"}  from **@makortel**: Move RandomNumberGenerator service base class to `FWCore/AbstractServices` `alca` `analysis` `core` `dqm` `fastsim` `generators` `l1` `reconstruction` `simulation` `db` `upgrade` `tracking` `trk` created: 2025-03-27 22:07:18 merged: 2025-04-03 14:48:27

66. [47717](http://github.com/cms-sw/cmssw/pull/47717){:target="_blank"}  from **@makortel**: Remove `edm::GetPassID()` as obsolete `core` `simulation` created: 2025-03-27 19:24:40 merged: 2025-03-31 07:38:07

67. [47712](http://github.com/cms-sw/cmssw/pull/47712){:target="_blank"}  from **@asavincms**: Zero Suppression for L1TCaloLayer1 `l1` created: 2025-03-27 13:18:03 merged: 2025-03-31 07:36:25

68. [47710](http://github.com/cms-sw/cmssw/pull/47710){:target="_blank"}  from **@smuzaffar**: [GCC13] Fix array-bound issue for JetTaggerTableProducer `xpog` created: 2025-03-27 10:58:05 merged: 2025-03-27 14:21:22

69. [47707](http://github.com/cms-sw/cmssw/pull/47707){:target="_blank"}  from **@wddgit**: Fix bug in endUnfinishedLumi `core` created: 2025-03-26 19:45:34 merged: 2025-03-28 08:38:19

70. [47704](http://github.com/cms-sw/cmssw/pull/47704){:target="_blank"}  from **@cms-tsg-storm**: remove hardcoded IP substitution for `dbproxy` option of `hltGetConfiguration` `hlt` created: 2025-03-26 19:27:20 merged: 2025-03-28 08:23:29

71. [47702](http://github.com/cms-sw/cmssw/pull/47702){:target="_blank"}  from **@y19y19**: Add UParT_V01 model Sonic producer and fix a bug in miniAOD_tools.py `operations` `reconstruction` `xpog` created: 2025-03-26 18:07:23 merged: 2025-04-05 07:00:13

72. [47701](http://github.com/cms-sw/cmssw/pull/47701){:target="_blank"}  from **@kakwok**: Update 2025 HMT shower thresholds for pp collision `l1` `operations` created: 2025-03-26 17:01:10 merged: 2025-03-28 08:26:26

73. [47699](http://github.com/cms-sw/cmssw/pull/47699){:target="_blank"}  from **@Dr15Jones**: Allow RelVal workflows to use RNTuple `operations` `pdmv` `upgrade` created: 2025-03-26 14:17:59 merged: 2025-04-04 06:32:37

74. [47696](http://github.com/cms-sw/cmssw/pull/47696){:target="_blank"}  from **@bsunanda**: Phase2-gex187Z Correct the retractions of the Kapton layers in HGCal module for V19 `geometry` `upgrade` created: 2025-03-26 09:53:14 merged: 2025-03-28 08:38:48

75. [47695](http://github.com/cms-sw/cmssw/pull/47695){:target="_blank"}  from **@bsunanda**: Phase2-gex187Y Create the scenario for V19 (still under test) `geometry` `operations` `pdmv` `upgrade` created: 2025-03-26 09:50:47 merged: 2025-03-28 08:37:51

76. [47693](http://github.com/cms-sw/cmssw/pull/47693){:target="_blank"}  from **@jfernan2**: [L1T] DT Trigger Phase-2 Analytical Method (AM) v2.2 `l1` `upgrade` created: 2025-03-25 18:51:46 merged: 2025-04-15 11:23:43

77. [47692](http://github.com/cms-sw/cmssw/pull/47692){:target="_blank"}  from **@Parsifal-2045**: [NGT] Fix some Muon validation plots, allow for summary plots creation  `dqm` `simulation` `trk` created: 2025-03-25 17:56:26 merged: 2025-03-31 08:31:08

78. [47691](http://github.com/cms-sw/cmssw/pull/47691){:target="_blank"}  from **@Ma128-bit**: Include the possibility of combining four objects in the "CandViewShallowCloneCombiner" producer `reconstruction` created: 2025-03-25 17:53:51 merged: 2025-03-28 08:24:13

79. [47690](http://github.com/cms-sw/cmssw/pull/47690){:target="_blank"}  from **@Ma128-bit**: Adding GEM MEs to per-LS scope in Offline DQM `dqm` created: 2025-03-25 17:26:58 merged: 2025-04-07 16:06:38

80. [47689](http://github.com/cms-sw/cmssw/pull/47689){:target="_blank"}  from **@Parsifal-2045**: [NGT] Fix HLT Muon paths for Phase 2 Validation `dqm` created: 2025-03-25 16:50:28 merged: 2025-03-31 08:28:50

81. [47688](http://github.com/cms-sw/cmssw/pull/47688){:target="_blank"}  from **@mmusich**: remove empty `cms.PSet()` from auto-generated `default_CondDBESource_cfi` file `alca` `db` created: 2025-03-25 16:46:33 merged: 2025-03-26 07:57:39

82. [47685](http://github.com/cms-sw/cmssw/pull/47685){:target="_blank"}  from **@iarspider**: [ALCA-DB] Fix dead assignments reported by LLVM analyzer `alca` `db` `trk` created: 2025-03-25 15:36:20 merged: 2025-03-26 07:58:07

83. [47684](http://github.com/cms-sw/cmssw/pull/47684){:target="_blank"}  from **@bsunanda**: Phase2-hgx187X Remove the overlaps in the EE parts of HGCal `geometry` `upgrade` created: 2025-03-25 15:16:49 merged: 2025-03-28 08:23:58

84. [47683](http://github.com/cms-sw/cmssw/pull/47683){:target="_blank"}  from **@iarspider**: [L1] Fix dead assignments reported by LLVM-analyzer `l1` `upgrade` created: 2025-03-25 15:07:18 merged: 2025-04-10 09:57:29

85. [47682](http://github.com/cms-sw/cmssw/pull/47682){:target="_blank"}  from **@AuroraPerego**: Fix missing `CaloParticle`s from pileup `operations` `simulation` `pdmv` `upgrade` created: 2025-03-25 14:45:44 merged: 2025-04-01 05:18:58

86. [47681](http://github.com/cms-sw/cmssw/pull/47681){:target="_blank"}  from **@AuroraPerego**: fix supercluster input in the dumper `reconstruction` `upgrade` created: 2025-03-25 14:13:17 merged: 2025-03-28 08:22:58

87. [47680](http://github.com/cms-sw/cmssw/pull/47680){:target="_blank"}  from **@kandrosov**: Adding L1TauTriggerFilterObjectProducer `hlt` created: 2025-03-25 13:42:37 merged: 2025-03-28 08:22:23

88. [47679](http://github.com/cms-sw/cmssw/pull/47679){:target="_blank"}  from **@iarspider**: Fix use-after-move LLVM analyzer warning in PFClusterEMEnergyCorrector `alca` `l1` `reconstruction` created: 2025-03-25 09:20:41 merged: 2025-03-28 08:20:43

89. [47675](http://github.com/cms-sw/cmssw/pull/47675){:target="_blank"}  from **@mmusich**: fix a bunch of test configuration files for invalid `PoolDBESSoure` parameters `alca` `dqm` `reconstruction` `db` `trk` created: 2025-03-24 09:35:28 merged: 2025-03-25 09:40:13

90. [47672](http://github.com/cms-sw/cmssw/pull/47672){:target="_blank"}  from **@fwyzard**: `AlpakaServiceSerialSync` should always be available `heterogeneous` created: 2025-03-24 00:07:49 merged: 2025-03-25 19:15:54

91. [47670](http://github.com/cms-sw/cmssw/pull/47670){:target="_blank"}  from **@fwyzard**: Fix Service type name displayed in error message `core` created: 2025-03-23 23:47:52 merged: 2025-03-28 08:20:11

92. [47669](http://github.com/cms-sw/cmssw/pull/47669){:target="_blank"}  from **@fwyzard**: Add a unit test for alpaka types' friendly class names `heterogeneous` created: 2025-03-23 17:43:22 merged: 2025-03-25 19:18:02

93. [47667](http://github.com/cms-sw/cmssw/pull/47667){:target="_blank"}  from **@bsunanda**: Run3-gex187W Add the complete list of the new PPS XML files and make muon set with the unmounted GE11 `geometry` `upgrade` created: 2025-03-23 15:13:36 merged: 2025-03-24 07:28:01

94. [47666](http://github.com/cms-sw/cmssw/pull/47666){:target="_blank"}  from **@CTPPS**: New PPS geometry with rotated Roman Pots for Run3 2025 `geometry` created: 2025-03-22 19:02:56 merged: 2025-03-23 11:27:48

95. [47663](http://github.com/cms-sw/cmssw/pull/47663){:target="_blank"}  from **@mmusich**: Follow-up to add HLT tracking monitoring in cosmics `dqm` `pdmv` `upgrade` `tracking` created: 2025-03-22 16:18:31 merged: 2025-03-25 15:51:35

96. [47660](http://github.com/cms-sw/cmssw/pull/47660){:target="_blank"}  from **@fabiocos**: MTD geometry: fix the topology parameters reading for ETL v10 `geometry` `upgrade` created: 2025-03-21 22:33:47 merged: 2025-03-25 19:19:57

97. [47657](http://github.com/cms-sw/cmssw/pull/47657){:target="_blank"}  from **@smorovic**: [DAQ] fix for raw generator creating incorrect raw files in Hilton (15_1_X) `daq` created: 2025-03-21 18:49:49 merged: 2025-03-22 09:05:16

98. [47656](http://github.com/cms-sw/cmssw/pull/47656){:target="_blank"}  from **@SegmentLinking**: Fix resetting of collections in LST `reconstruction` `tracking` created: 2025-03-21 17:29:06 merged: 2025-03-25 19:15:29

99. [47655](http://github.com/cms-sw/cmssw/pull/47655){:target="_blank"}  from **@mmusich**: [TkAlignment] Add DiMuon bias analysis macros `alca` `trk` created: 2025-03-21 16:40:58 merged: 2025-03-23 11:27:02

100. [47648](http://github.com/cms-sw/cmssw/pull/47648){:target="_blank"}  from **@bsunanda**: Run3-gex187V Update the documentation of Run3 scenarios (the Muon components) `geometry` `upgrade` created: 2025-03-21 01:47:45 merged: 2025-03-22 09:04:24

101. [47643](http://github.com/cms-sw/cmssw/pull/47643){:target="_blank"}  from **@bsunanda**: Run3-gex187U Update all Run3 scenarios with he right DTShiel,  GEM and RPC chambers `geometry` `upgrade` created: 2025-03-20 16:12:26 merged: 2025-03-21 06:17:53

102. [47642](http://github.com/cms-sw/cmssw/pull/47642){:target="_blank"}  from **@Dr15Jones**: Can mark Parameters as obsolete in fillDescriptions `core` created: 2025-03-20 15:42:45 merged: 2025-03-25 19:20:31

103. [47641](http://github.com/cms-sw/cmssw/pull/47641){:target="_blank"}  from **@smorovic**: [DAQ] fix input source raw file deletion deadlock (15_1_X) `daq` created: 2025-03-20 15:28:26 merged: 2025-03-20 18:45:55

104. [47639](http://github.com/cms-sw/cmssw/pull/47639){:target="_blank"}  from **@AdrianoDee**: Using Offline GT for 2024 Data RelVals Eras B,C,D,E `pdmv` `upgrade` created: 2025-03-20 14:53:37 merged: 2025-04-01 05:18:03

105. [47638](http://github.com/cms-sw/cmssw/pull/47638){:target="_blank"}  from **@bsunanda**: Run3-gex187T Make DDD-specific Era definitions for the years 2023, 2024, 2025 `operations` created: 2025-03-20 11:14:11 merged: 2025-04-10 10:04:06

106. [47636](http://github.com/cms-sw/cmssw/pull/47636){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `15_0_X` (3/N)  [`15_1_X`]  `hlt` created: 2025-03-20 10:56:09 merged: 2025-03-21 06:16:25

107. [47635](http://github.com/cms-sw/cmssw/pull/47635){:target="_blank"}  from **@perrotta**: Update Run3 data offline and Run3_2024 + Run4 MC GTs in autoCond `alca` created: 2025-03-20 10:47:15 merged: 2025-03-21 06:18:59

108. [47634](http://github.com/cms-sw/cmssw/pull/47634){:target="_blank"}  from **@smuzaffar**: [GCC14]Fix array bound warnings `reconstruction` `tracking` created: 2025-03-20 08:40:34 merged: 2025-03-25 19:21:33

109. [47633](http://github.com/cms-sw/cmssw/pull/47633){:target="_blank"}  from **@bsunanda**: Run3-gex187S Modify the test geometries of 2021, 2023,2024 to accommodate the change in DTShield `geometry` created: 2025-03-20 08:13:21 merged: 2025-03-21 06:17:38

110. [47632](http://github.com/cms-sw/cmssw/pull/47632){:target="_blank"}  from **@smuzaffar**: [GCC14] Fix may be used uninitialized warnings `simulation` created: 2025-03-20 07:59:35 merged: 2025-03-21 06:16:54

111. [47631](http://github.com/cms-sw/cmssw/pull/47631){:target="_blank"}  from **@pietroGru**: Fix typos in exception messages in PluginFactoryBase (EdmPluginRefresh to edmPluginRefresh)  `core` created: 2025-03-19 23:11:56 merged: 2025-03-21 06:15:48

112. [47630](http://github.com/cms-sw/cmssw/pull/47630){:target="_blank"}  from **@mmusich**: provide a `fillDescriptions` method for `CondDBESSource` `alca` `hlt` `db` created: 2025-03-19 20:27:32 merged: 2025-03-23 11:28:03

113. [47626](http://github.com/cms-sw/cmssw/pull/47626){:target="_blank"}  from **@AdrianoDee**: Adding `10224.0` in the `limited` Matrix `pdmv` `upgrade` created: 2025-03-19 14:29:42 merged: 2025-04-15 11:17:21

114. [47622](http://github.com/cms-sw/cmssw/pull/47622){:target="_blank"}  from **@Dr15Jones**: Allow use of Rntuple format in ConfigBuilder `operations` created: 2025-03-18 20:51:39 merged: 2025-03-26 14:09:28

115. [47621](http://github.com/cms-sw/cmssw/pull/47621){:target="_blank"}  from **@cramonal**: Small modification on CRC compuation for HGCAL unpacker `reconstruction` `upgrade` created: 2025-03-18 19:06:00 merged: 2025-03-21 06:17:08

116. [47618](http://github.com/cms-sw/cmssw/pull/47618){:target="_blank"}  from **@SegmentLinking**: Add DNN to Reject Fake T3 Objects in LST `reconstruction` `heterogeneous` `tracking` created: 2025-03-18 17:24:46 merged: 2025-03-25 19:19:24

117. [47616](http://github.com/cms-sw/cmssw/pull/47616){:target="_blank"}  from **@waredjeb**: Fix TICL Energy Regression and PID Model Loading `hlt` `reconstruction` `upgrade` created: 2025-03-18 14:43:37 merged: 2025-03-21 06:15:04

118. [47614](http://github.com/cms-sw/cmssw/pull/47614){:target="_blank"}  from **@smuzaffar**: Added jupyter-notebook unit test `analysis` created: 2025-03-17 20:34:14 merged: 2025-03-19 15:10:56

119. [47613](http://github.com/cms-sw/cmssw/pull/47613){:target="_blank"}  from **@civanch**: [FULLSIM] Updates for Geant4 11.3 testing `simulation` created: 2025-03-17 20:05:04 merged: 2025-03-21 06:15:34

120. [47612](http://github.com/cms-sw/cmssw/pull/47612){:target="_blank"}  from **@mseidel42**: Restore correct HadronizerFilter logic `generators` created: 2025-03-17 15:26:21 merged: 2025-03-17 21:30:05

121. [47610](http://github.com/cms-sw/cmssw/pull/47610){:target="_blank"}  from **@nothingface0**: [DQM] Add print of GT on DQM online clients `dqm` created: 2025-03-17 11:48:49 merged: 2025-03-25 19:17:01

122. [47604](http://github.com/cms-sw/cmssw/pull/47604){:target="_blank"}  from **@mkirsano**: Add reco::GenParticle collection production from HepMC3 event record `analysis` `reconstruction` created: 2025-03-16 15:16:42 merged: 2025-03-17 00:33:27

123. [47602](http://github.com/cms-sw/cmssw/pull/47602){:target="_blank"}  from **@Dr15Jones**: Just in time Principal updates `core` created: 2025-03-14 20:00:28 merged: 2025-03-19 15:13:28

124. [47600](http://github.com/cms-sw/cmssw/pull/47600){:target="_blank"}  from **@cms-tsg-storm**: Add default values for ConfDb in TemplatedSecondaryVertexProducer `reconstruction` created: 2025-03-14 17:41:26 merged: 2025-03-18 16:44:41

125. [47599](http://github.com/cms-sw/cmssw/pull/47599){:target="_blank"}  from **@Dr15Jones**: Improve BDT in L1Trigger/L1TMuonEndCap `l1` created: 2025-03-14 15:22:15 merged: 2025-03-22 09:05:05

126. [47598](http://github.com/cms-sw/cmssw/pull/47598){:target="_blank"}  from **@bsunanda**: Phase2e2-gex187R Provide the geometry checking for some of the new scenarios `simulation` created: 2025-03-14 07:51:04 merged: 2025-03-19 15:12:28

127. [47597](http://github.com/cms-sw/cmssw/pull/47597){:target="_blank"}  from **@bsunanda**: Run3-gex187Q Correct gem11.xml for 2025 version (corrected by Yechen Kang) without the 3 supermodules `geometry` created: 2025-03-14 04:12:10 merged: 2025-03-19 15:10:19

128. [47594](http://github.com/cms-sw/cmssw/pull/47594){:target="_blank"}  from **@hqucms**: [NANOAOD] Add missing trigger filter bits `xpog` created: 2025-03-13 19:16:14 merged: 2025-03-18 16:27:09

129. [47593](http://github.com/cms-sw/cmssw/pull/47593){:target="_blank"}  from **@makortel**: XrdAdaptor: Use inactive sources first before trying to open a new source when handling a failed request `core` created: 2025-03-13 18:01:35 merged: 2025-04-01 05:17:22

130. [47592](http://github.com/cms-sw/cmssw/pull/47592){:target="_blank"}  from **@dsidirop1**: Muon dxy 1D Histograms added to all Electron and Muon directories, extended range for PvMult plots for GEN-SIM-RECO AND MINIAOD directories at DQM/Physics `dqm` created: 2025-03-13 16:07:14 merged: 2025-03-20 07:56:12

131. [47590](http://github.com/cms-sw/cmssw/pull/47590){:target="_blank"}  from **@rsreds**: Fix missing type declaration in EdmEventSize `core` created: 2025-03-13 13:43:48 merged: 2025-03-14 06:17:59

132. [47589](http://github.com/cms-sw/cmssw/pull/47589){:target="_blank"}  from **@bsunanda**: Run3-gex187P Provide a way to avoid saving hits for a list of GEM chambers (eg missing GE11 chambers) `simulation` created: 2025-03-13 13:26:03 merged: 2025-03-14 06:20:05

133. [47587](http://github.com/cms-sw/cmssw/pull/47587){:target="_blank"}  from **@srimanob**: Add protection if non-existent geometry is used `operations` created: 2025-03-13 00:22:54 merged: 2025-04-01 15:25:32

134. [47584](http://github.com/cms-sw/cmssw/pull/47584){:target="_blank"}  from **@Dr15Jones**: Create new main ProductRegistry if input products change `core` created: 2025-03-12 19:21:01 merged: 2025-03-14 06:15:52

135. [47577](http://github.com/cms-sw/cmssw/pull/47577){:target="_blank"}  from **@jlidrych**: Increase threshold of max number of strips clusters for cosmics `hlt` `reconstruction` `tracking` created: 2025-03-12 16:25:57 merged: 2025-03-18 07:31:06

136. [47576](http://github.com/cms-sw/cmssw/pull/47576){:target="_blank"}  from **@AuroraPerego**: Fix the python configuration for the TICLDumper `reconstruction` `pdmv` `upgrade` created: 2025-03-12 15:54:34 merged: 2025-03-25 19:16:45

137. [47575](http://github.com/cms-sw/cmssw/pull/47575){:target="_blank"}  from **@mmusich**: add missing defaults to `MkFitProducer::fillDescriptions` `reconstruction` `tracking` created: 2025-03-12 14:05:06 merged: 2025-03-14 06:14:21

138. [47573](http://github.com/cms-sw/cmssw/pull/47573){:target="_blank"}  from **@nurfikri89**: [MiniAOD, NanoAOD] AK8 subjets pT regression nodes, Photon TrigObj & MET fixes `reconstruction` `xpog` created: 2025-03-12 11:35:03 merged: 2025-03-14 06:20:10

139. [47572](http://github.com/cms-sw/cmssw/pull/47572){:target="_blank"}  from **@mseidel42**: HepMC3 output for HadronizerFilter `generators` created: 2025-03-12 10:59:21 merged: 2025-03-14 06:14:36

140. [47571](http://github.com/cms-sw/cmssw/pull/47571){:target="_blank"}  from **@Parsifal-2045**: Fix endcap assignment of L1 Muon stubs `l1` created: 2025-03-12 10:49:03 merged: 2025-03-14 06:15:26

141. [47566](http://github.com/cms-sw/cmssw/pull/47566){:target="_blank"}  from **@alexandertuna**: Add phase-2 OT cluster size to tracking ntuple `dqm` `tracking` created: 2025-03-11 23:34:03 merged: 2025-03-14 06:22:46

142. [47565](http://github.com/cms-sw/cmssw/pull/47565){:target="_blank"}  from **@wddgit**: Remove configuration support for SubProcess and its tests `core` created: 2025-03-11 19:34:22 merged: 2025-03-14 06:19:06

143. [47564](http://github.com/cms-sw/cmssw/pull/47564){:target="_blank"}  from **@quinnanm**: Changes to prepare for AXOL1TL v5 (15_1_X)  `l1` created: 2025-03-11 17:41:48 merged: 2025-03-19 06:24:21

144. [47561](http://github.com/cms-sw/cmssw/pull/47561){:target="_blank"}  from **@dan131riley**: Remove excessive includes in DataFormats/Provenance `core` created: 2025-03-11 15:22:52 merged: 2025-03-14 06:19:42

145. [47560](http://github.com/cms-sw/cmssw/pull/47560){:target="_blank"}  from **@p2l1-gtEmulator**: Phase-2 GT: Fix cut initialization copy paste errors `l1` `upgrade` created: 2025-03-11 13:51:00 merged: 2025-03-25 19:19:37

146. [47556](http://github.com/cms-sw/cmssw/pull/47556){:target="_blank"}  from **@iarspider**: [GCC14] Fix compiler warnings `dqm` `l1` `reconstruction` `simulation` `upgrade` `tracking` created: 2025-03-11 12:30:22 merged: 2025-03-18 10:49:01

147. [47550](http://github.com/cms-sw/cmssw/pull/47550){:target="_blank"}  from **@Moanwar**: Integrating Particle Flow Network (PFN) Models into TICLv5  `hlt` `reconstruction` `upgrade` created: 2025-03-10 21:28:33 merged: 2025-03-14 06:16:52

148. [47548](http://github.com/cms-sw/cmssw/pull/47548){:target="_blank"}  from **@makortel**: Add Process name, reduced configuration ID, and ParameterSet ID to the JobReport `core` created: 2025-03-10 16:40:11 merged: 2025-03-14 06:18:53

149. [47535](http://github.com/cms-sw/cmssw/pull/47535){:target="_blank"}  from **@fabiocos**: MTD geometry: update ETL geometry to most recent drawings (scenarios v9 and v10) `geometry` `operations` `reconstruction` `simulation` `pdmv` `upgrade` created: 2025-03-08 18:37:23 merged: 2025-03-20 07:55:14

150. [47525](http://github.com/cms-sw/cmssw/pull/47525){:target="_blank"}  from **@LinaresToine**: Repack raw skims `operations` `pdmv` created: 2025-03-07 04:12:21 merged: 2025-03-19 20:18:12

151. [47524](http://github.com/cms-sw/cmssw/pull/47524){:target="_blank"}  from **@makortel**: Small improvements to XrdAdaptor documentation `core` created: 2025-03-06 23:03:47 merged: 2025-04-01 05:17:10

152. [47506](http://github.com/cms-sw/cmssw/pull/47506){:target="_blank"}  from **@mmusich**: Phase-2 HLT menu: refactor `HLTL1Sequence` `hlt` created: 2025-03-05 09:16:01 merged: 2025-04-01 15:25:09

153. [47498](http://github.com/cms-sw/cmssw/pull/47498){:target="_blank"}  from **@iarspider**: [ALCA-DB] Fix static analyzer warnings `alca` `l1` `db` `trk` created: 2025-03-04 09:46:37 merged: 2025-03-20 07:56:47

154. [47490](http://github.com/cms-sw/cmssw/pull/47490){:target="_blank"}  from **@nurfikri89**: [MiniAOD] Update TauID selection for METUncertainties calculation, add pileup Id & UParTv1 for puppiJetMETReclustering `reconstruction` `xpog` created: 2025-03-03 21:16:41 merged: 2025-03-14 06:20:36

155. [47480](http://github.com/cms-sw/cmssw/pull/47480){:target="_blank"}  from **@CMSTrackerDPG**: Lowered cluster charge threshold for pixel L1 `operations` `reconstruction` `trk` created: 2025-02-28 13:50:58 merged: 2025-03-17 20:25:34

156. [47474](http://github.com/cms-sw/cmssw/pull/47474){:target="_blank"}  from **@zhenbinwu**: Phase 2 GMT Update of TPS algo `l1` `upgrade` created: 2025-02-27 16:45:39 merged: 2025-04-02 05:27:04

157. [47467](http://github.com/cms-sw/cmssw/pull/47467){:target="_blank"}  from **@wddgit**: Access PathsAndConsumesOfModules from new signal `core` `daq` `hlt` `heterogeneous` created: 2025-02-26 18:07:51 merged: 2025-04-12 11:56:33

158. [47377](http://github.com/cms-sw/cmssw/pull/47377){:target="_blank"}  from **@AdrianoDee**: Updates for `runTheMatrix.py`: input checks, GPUs repartition, input recycling `pdmv` `upgrade` created: 2025-02-17 16:27:40 merged: 2025-03-25 19:21:12

159. [47343](http://github.com/cms-sw/cmssw/pull/47343){:target="_blank"}  from **@lyazj**: Reduce and unify tagger inputs `xpog` `btv` created: 2025-02-13 15:39:19 merged: 2025-03-14 06:17:41

160. [47324](http://github.com/cms-sw/cmssw/pull/47324){:target="_blank"}  from **@mseidel42**: [NanoAOD,BTVNano] Bugfixes and object linking `xpog` `btv` created: 2025-02-11 17:26:14 merged: 2025-03-25 19:16:12

161. [47306](http://github.com/cms-sw/cmssw/pull/47306){:target="_blank"}  from **@leobeltra**: New constructor for the SoAView and aggregate method for Collections `heterogeneous` created: 2025-02-10 10:24:26 merged: 2025-04-05 06:57:32

162. [47193](http://github.com/cms-sw/cmssw/pull/47193){:target="_blank"}  from **@skkwan**: update GCT eg and hadronic cluster interface to Correlator `l1` `upgrade` created: 2025-01-27 22:47:39 merged: 2025-03-25 19:22:04

163. [47178](http://github.com/cms-sw/cmssw/pull/47178){:target="_blank"}  from **@artlbv**: Custom Phase-2 L1 Trigger NanoAOD `l1` `pdmv` `upgrade` `xpog` created: 2025-01-24 10:00:21 merged: 2025-03-14 06:17:12

164. [47171](http://github.com/cms-sw/cmssw/pull/47171){:target="_blank"}  from **@cms-AlCaDB**: Print diagnostics on ProductResolver's loadTag setIntervalFor and IOVProxy's fetchSequence `alca` `db` created: 2025-01-23 17:36:13 merged: 2025-04-02 05:25:42

165. [46004](http://github.com/cms-sw/cmssw/pull/46004){:target="_blank"}  from **@fwyzard**: Remove legacy CUDA modules for HCAL unpacking and local reconstruction `alca` `dqm` `reconstruction` `simulation` `db` `heterogeneous` created: 2024-09-13 23:04:05 merged: 2025-03-28 08:19:42

166. [45672](http://github.com/cms-sw/cmssw/pull/45672){:target="_blank"}  from **@ryanm124**: Displaced vertexing gbdt `l1` `upgrade` created: 2024-08-08 16:01:55 merged: 2025-04-08 18:28:58

167. [43673](http://github.com/cms-sw/cmssw/pull/43673){:target="_blank"}  from **@dan131riley**: fix minor type issues in L1Trigger/TrackFindingTracklet `l1` created: 2024-01-06 19:31:07 merged: 2025-03-19 15:09:44

#### CMSDIST Changes between Tags REL/CMSSW_15_1_0_pre1/el8_amd64_gcc12 and REL/CMSSW_15_1_0_pre2/el8_amd64_gcc12:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_15_1_0_pre1/el8_amd64_gcc12...REL/CMSSW_15_1_0_pre2/el8_amd64_gcc12)



1. [9802](http://github.com/cms-sw/cmsdist/pull/9802){:target="_blank"}  from **@cms-sw**: cmssw-wm-tools: Fix the execution permission of cmssw_enable_custom_timeout.py created: 2025-04-17 08:31:07 merged: 2025-04-17 08:56:43

2. [9799](http://github.com/cms-sw/cmsdist/pull/9799){:target="_blank"}  from **@cms-sw**: Update tag for L1Trigger-L1TCalorimeter to V01-04-00 created: 2025-04-17 01:35:25 merged: 2025-04-17 01:35:27

3. [9797](http://github.com/cms-sw/cmsdist/pull/9797){:target="_blank"}  from **@cms-sw**: Update tag for L1Trigger-L1TCalorimeter to V01-03-00 created: 2025-04-16 20:04:04 merged: 2025-04-16 20:04:05

4. [9795](http://github.com/cms-sw/cmsdist/pull/9795){:target="_blank"}  from **@cms-sw**: Update tag for Validation-HGCalValidation to V00-09-00 created: 2025-04-16 15:26:20 merged: 2025-04-16 15:26:22

5. [9794](http://github.com/cms-sw/cmsdist/pull/9794){:target="_blank"}  from **@cms-sw**: Update tag for Validation-HGCalValidation to V00-09-00 created: 2025-04-16 15:26:11 merged: 2025-04-16 15:26:14

6. [9793](http://github.com/cms-sw/cmsdist/pull/9793){:target="_blank"}  from **@cms-sw**: added frame_pointer build option created: 2025-04-16 11:00:52 merged: 2025-04-16 13:40:32

7. [9784](http://github.com/cms-sw/cmsdist/pull/9784){:target="_blank"}  from **@belforte**: port fix for crab submit --dryrun to prod created: 2025-04-10 10:48:32 merged: 2025-04-10 13:37:09

8. [9783](http://github.com/cms-sw/cmsdist/pull/9783){:target="_blank"}  from **@belforte**: Bump crab-dev created: 2025-04-09 15:59:50 merged: 2025-04-10 05:21:47

9. [9782](http://github.com/cms-sw/cmsdist/pull/9782){:target="_blank"}  from **@cms-sw**: Update tag for L1Trigger-L1TTrackMatch to V00-02-00 created: 2025-04-08 18:29:02 merged: 2025-04-08 18:29:04

10. [9779](http://github.com/cms-sw/cmsdist/pull/9779){:target="_blank"}  from **@smuzaffar**: ROOT 6.32.12: Updated root to tip of branch v6-32-00-patches created: 2025-04-08 08:46:24 merged: 2025-04-09 06:13:15

11. [9776](http://github.com/cms-sw/cmsdist/pull/9776){:target="_blank"}  from **@cms-sw**: Update cmssw-wm-tools.spec created: 2025-04-07 12:18:08 merged: 2025-04-07 15:46:54

12. [9771](http://github.com/cms-sw/cmsdist/pull/9771){:target="_blank"}  from **@cms-sw**: Update tag for RecoBTag-Combined to V01-28-00 created: 2025-04-05 07:00:49 merged: 2025-04-05 07:00:51

13. [9765](http://github.com/cms-sw/cmsdist/pull/9765){:target="_blank"}  from **@fwyzard**: Generate cuda.pcm if CUDA is available created: 2025-03-28 18:04:16 merged: 2025-03-31 07:37:10

14. [9763](http://github.com/cms-sw/cmsdist/pull/9763){:target="_blank"}  from **@mseidel42**: Rivet 4.1.0 and Yoda 2.1.0 created: 2025-03-28 14:20:30 merged: 2025-04-01 13:32:06

15. [9759](http://github.com/cms-sw/cmsdist/pull/9759){:target="_blank"}  from **@gartung**: Build Tensorflow 2.12.0 with ZenDNN enabled. created: 2025-03-25 20:48:58 merged: 2025-04-08 07:13:38

16. [9757](http://github.com/cms-sw/cmsdist/pull/9757){:target="_blank"}  from **@smuzaffar**: Updated root to tip of branch v6-32-00-patches created: 2025-03-24 12:03:22 merged: 2025-03-24 20:31:43

17. [9756](http://github.com/cms-sw/cmsdist/pull/9756){:target="_blank"}  from **@cms-sw**: GDB:Update to latest version 16.2 created: 2025-03-24 11:13:10 merged: 2025-03-24 14:05:09

18. [9753](http://github.com/cms-sw/cmsdist/pull/9753){:target="_blank"}  from **@cms-sw**: Geant4: Fixed technical problems in Geant4 11.2.2 created: 2025-03-20 11:29:10 merged: 2025-03-20 15:35:48

19. [9751](http://github.com/cms-sw/cmsdist/pull/9751){:target="_blank"}  from **@sinonkt**: hotfix, CRABClient buggy when CMSSW < 12 version, bumped prod to v3.250318. created: 2025-03-18 13:42:48 merged: 2025-03-18 15:58:57

20. [9748](http://github.com/cms-sw/cmsdist/pull/9748){:target="_blank"}  from **@cms-sw**: fix jupyter-server deps: added overrides created: 2025-03-17 20:30:39 merged: 2025-03-17 22:20:39

21. [9747](http://github.com/cms-sw/cmsdist/pull/9747){:target="_blank"}  from **@cms-sw**: cms-common: zsh: avoid autocompletion error message created: 2025-03-17 13:38:27 merged: 2025-03-17 16:26:18

22. [9745](http://github.com/cms-sw/cmsdist/pull/9745){:target="_blank"}  from **@cms-sw**: Update tag for RecoHGCal-TICL to V00-06-00 created: 2025-03-14 06:16:56 merged: 2025-03-14 06:16:58

23. [9741](http://github.com/cms-sw/cmsdist/pull/9741){:target="_blank"}  from **@quinnanm**: Update AXOL1TL.spec with axol1tl v5 created: 2025-03-11 04:17:52 merged: 2025-03-17 10:25:57
