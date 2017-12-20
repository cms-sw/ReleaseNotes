---
layout: post
rel_link:  "9_4_0_pre3"
title:  "CMSSW_9_4_0_pre3"
date:   2017-10-24 07:11:18
categories: cmssw
relmajor: 9
relminor: 4
relsubminor: 0
relpre: _pre3
---

# CMSSW_9_4_0_pre3
#### Changes since CMSSW_9_4_0_pre2:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_9_4_0_pre2...CMSSW_9_4_0_pre3)



1. [20993](http://github.com/cms-sw/cmssw/pull/20993){:target="_blank"}  from **@davidlange6**: remove plugins from lib `dqm`  created: 2017-10-23 17:01:13 merged: 2017-10-23 17:04:44

2. [20992](http://github.com/cms-sw/cmssw/pull/20992){:target="_blank"}  from **@davidlange6**: protect against non-stage2 eras in DigiToRawDM `operations`  created: 2017-10-23 15:03:12 merged: 2017-10-24 05:51:25

3. [20991](http://github.com/cms-sw/cmssw/pull/20991){:target="_blank"}  from **@davidlange6**: Add needed changes to L1 digi to raw for premixing `operations`  created: 2017-10-23 09:12:30 merged: 2017-10-23 09:13:07

4. [20981](http://github.com/cms-sw/cmssw/pull/20981){:target="_blank"}  from **@rappoccio**: Adding "else" clause to jet tokens `reconstruction`  created: 2017-10-20 16:16:49 merged: 2017-10-23 15:30:51

5. [20975](http://github.com/cms-sw/cmssw/pull/20975){:target="_blank"}  from **@alberto-sanchez**: converting filters to global `generators`  created: 2017-10-19 18:44:37 merged: 2017-10-23 15:31:05

6. [20968](http://github.com/cms-sw/cmssw/pull/20968){:target="_blank"}  from **@perrotta**: Solve an issue spot by the Static Analyzer in PixelCPETemplateReco.cc `reconstruction`  created: 2017-10-18 22:01:34 merged: 2017-10-19 14:12:36

7. [20965](http://github.com/cms-sw/cmssw/pull/20965){:target="_blank"}  from **@capalmer85**: add smeared, projected PU for 2017 data `comparison`  `operations`  `simulation`  created: 2017-10-18 16:07:23 merged: 2017-10-21 17:25:24

8. [20957](http://github.com/cms-sw/cmssw/pull/20957){:target="_blank"}  from **@rekovic**: Revert "Revert "[94X] L1 no hack conditions - cleaned"" `alca`  `core`  `dqm`  `l1`  `operations`  created: 2017-10-18 12:55:37 merged: 2017-10-20 18:51:53

9. [20956](http://github.com/cms-sw/cmssw/pull/20956){:target="_blank"}  from **@hroskes**: Fix compiling PlotAlignmentValidation `alca`  created: 2017-10-18 12:20:04 merged: 2017-10-23 15:38:00

10. [20954](http://github.com/cms-sw/cmssw/pull/20954){:target="_blank"}  from **@fabozzi**: fixing statistics of 2017 QCD flat_pT relval `pdmv`  `upgrade`  created: 2017-10-18 10:29:01 merged: 2017-10-19 09:19:12

11. [20953](http://github.com/cms-sw/cmssw/pull/20953){:target="_blank"}  from **@slehti**: HLTTauDQM: updated t&p probe single muon trigger for mu+tau40 monitoring `dqm`  created: 2017-10-18 10:24:55 merged: 2017-10-19 09:26:04

12. [20952](http://github.com/cms-sw/cmssw/pull/20952){:target="_blank"}  from **@efeyazgan**: Update GenXSecAnalyzer.cc `generators`  created: 2017-10-18 09:18:09 merged: 2017-10-19 09:19:51

13. [20951](http://github.com/cms-sw/cmssw/pull/20951){:target="_blank"}  from **@ashtipliyski**: Add DQM event by event comparison plots summarising CALOL2 outputs and uGT inputs `dqm`  created: 2017-10-18 09:06:36 merged: 2017-10-19 09:23:46

14. [20949](http://github.com/cms-sw/cmssw/pull/20949){:target="_blank"}  from **@slava77**: disable ecorr computations in phase-2 because they are too slow for high-PU `analysis`  `reconstruction`  `upgrade`  created: 2017-10-18 05:48:42 merged: 2017-10-19 09:24:00

15. [20944](http://github.com/cms-sw/cmssw/pull/20944){:target="_blank"}  from **@thomreis**: L1T RegionalMuonCand constructor upgrade `l1`  created: 2017-10-17 14:40:48 merged: 2017-10-18 07:10:48

16. [20943](http://github.com/cms-sw/cmssw/pull/20943){:target="_blank"}  from **@jfernan2**: Extended DT DQM selection for HI runs `dqm`  created: 2017-10-17 14:17:47 merged: 2017-10-18 18:34:20

17. [20942](http://github.com/cms-sw/cmssw/pull/20942){:target="_blank"}  from **@crovelli**: ECAL containment in simulation update `simulation`  created: 2017-10-17 14:07:01 merged: 2017-10-18 18:34:34

18. [20941](http://github.com/cms-sw/cmssw/pull/20941){:target="_blank"}  from **@Dr15Jones**: Add TotalLoopTime to framework job report `core`  created: 2017-10-17 14:03:27 merged: 2017-10-18 07:10:05

19. [20938](http://github.com/cms-sw/cmssw/pull/20938){:target="_blank"}  from **@VinInn**: Introducing "Inactive" inner/outer hits... `alca`  `analysis`  `dqm`  `hlt`  `pdmv`  `reconstruction`  `visualization`  created: 2017-10-17 10:17:27 merged: 2017-10-21 17:13:15

after introduction of inactive hits to inner and outer parts of the HitPattern, the HitPattern interface was updated, including removal of an existing [now ambiguous] method in order to avoid incorrect result. See PR description for details.



20. [20935](http://github.com/cms-sw/cmssw/pull/20935){:target="_blank"}  from **@thomreis**: L1T online DQM - set efficiency flags `dqm`  created: 2017-10-17 08:42:53 merged: 2017-10-19 09:24:12

21. [20928](http://github.com/cms-sw/cmssw/pull/20928){:target="_blank"}  from **@bsunanda**: Run2-alca101 Make the codes and macros updated with the current versions used for calibration `alca`  created: 2017-10-16 14:16:02 merged: 2017-10-24 05:53:26

22. [20926](http://github.com/cms-sw/cmssw/pull/20926){:target="_blank"}  from **@thomreis**: L1T online DQM uGMT zero suppression plot axis range change `dqm`  created: 2017-10-16 11:07:08 merged: 2017-10-18 09:04:20

23. [20925](http://github.com/cms-sw/cmssw/pull/20925){:target="_blank"}  from **@natalia-korneeva**: Moving to Clopper-Pearson uncertainties in efficiency histograms `dqm`  created: 2017-10-16 10:02:06 merged: 2017-10-18 09:03:45

24. [20923](http://github.com/cms-sw/cmssw/pull/20923){:target="_blank"}  from **@thomreis**: L1TOffline DQM - add efficiency flag to efficiency ME `dqm`  `l1`  created: 2017-10-16 07:48:40 merged: 2017-10-18 09:04:00

25. [20922](http://github.com/cms-sw/cmssw/pull/20922){:target="_blank"}  from **@arunhep**: GT Updates with Pixel Local Reco conditions for V2 MC `alca`  created: 2017-10-16 06:16:31 merged: 2017-10-18 07:09:53

26. [20921](http://github.com/cms-sw/cmssw/pull/20921){:target="_blank"}  from **@cms-sw**: Revert "[94X] L1 no hack conditions - cleaned" `comparison`  `core`  `dqm`  `l1`  `operations`  created: 2017-10-14 19:25:09 merged: 2017-10-15 07:14:07

27. [20919](http://github.com/cms-sw/cmssw/pull/20919){:target="_blank"}  from **@dinardo**: Fixed HI tracking sequence `dqm`  created: 2017-10-13 20:58:42 merged: 2017-10-18 18:36:41

28. [20914](http://github.com/cms-sw/cmssw/pull/20914){:target="_blank"}  from **@rekovic**: [94x] L1T Calo Layer1 packer unpacker `l1`  created: 2017-10-13 09:00:06 merged: 2017-10-17 08:24:50

29. [20911](http://github.com/cms-sw/cmssw/pull/20911){:target="_blank"}  from **@lgray**: Fill time and uncertainties for slimmed primary vertices `analysis`  `reconstruction`  `upgrade`  created: 2017-10-12 23:24:27 merged: 2017-10-19 10:07:06

30. [20908](http://github.com/cms-sw/cmssw/pull/20908){:target="_blank"}  from **@Dr15Jones**: Converted GenFilters to be edm::global modules `generators`  created: 2017-10-12 18:51:57 merged: 2017-10-13 09:21:57

31. [20907](http://github.com/cms-sw/cmssw/pull/20907){:target="_blank"}  from **@mrodozov**: Add test for Theano `analysis`  created: 2017-10-12 16:45:17 merged: 2017-10-13 10:16:34

32. [20906](http://github.com/cms-sw/cmssw/pull/20906){:target="_blank"}  from **@mrodozov**: Remove unused variables to fix warnings `analysis`  created: 2017-10-12 14:49:49 merged: 2017-10-13 16:16:18

33. [20905](http://github.com/cms-sw/cmssw/pull/20905){:target="_blank"}  from **@arizzi**: NanoAOD: runTheMatrix and cmsDriver support `operations`  `pdmv`  `upgrade`  created: 2017-10-12 12:18:21 merged: 2017-10-14 09:44:25

34. [20904](http://github.com/cms-sw/cmssw/pull/20904){:target="_blank"}  from **@ahinzmann**: Fix negative error cases `reconstruction`  created: 2017-10-12 11:37:36 merged: 2017-10-19 06:40:00

35. [20903](http://github.com/cms-sw/cmssw/pull/20903){:target="_blank"}  from **@Sam-Harper**: adding good e/gamma flag to PackedCandidate for MiniAOD `analysis`  `reconstruction`  created: 2017-10-11 23:10:34 merged: 2017-10-14 13:01:06

36. [20900](http://github.com/cms-sw/cmssw/pull/20900){:target="_blank"}  from **@cms-tau-pog**: increase of pT threshold for photons to be considered for tau reconstruction and ID `reconstruction`  created: 2017-10-11 19:43:55 merged: 2017-10-17 07:07:16

37. [20899](http://github.com/cms-sw/cmssw/pull/20899){:target="_blank"}  from **@rvenditti**: Repair Zmu skim muon selector `pdmv`  created: 2017-10-11 19:28:01 merged: 2017-10-11 19:32:35

38. [20898](http://github.com/cms-sw/cmssw/pull/20898){:target="_blank"}  from **@Michael-Krohn**: DQM for AK8 btag HLT  `dqm`  created: 2017-10-11 19:27:59 merged: 2017-10-18 07:16:00

39. [20896](http://github.com/cms-sw/cmssw/pull/20896){:target="_blank"}  from **@slava77**: reduce max errors/warnings selected for LogError skim per kind to at most 1 per LS `core`  created: 2017-10-11 16:28:01 merged: 2017-10-12 08:17:35

40. [20895](http://github.com/cms-sw/cmssw/pull/20895){:target="_blank"}  from **@Wilsker**: Aesthetic changes to off-track cluster histograms `dqm`  created: 2017-10-11 15:44:37 merged: 2017-10-18 07:16:58

41. [20893](http://github.com/cms-sw/cmssw/pull/20893){:target="_blank"}  from **@bsunanda**: Run2-hcx158 Remove casting of some collections which was causing memory leaks `reconstruction`  created: 2017-10-11 13:56:08 merged: 2017-10-12 14:46:26

42. [20891](http://github.com/cms-sw/cmssw/pull/20891){:target="_blank"}  from **@makortel**: Add fillDescriptions to MeasurementTrackerEventProducer `reconstruction`  created: 2017-10-11 10:19:45 merged: 2017-10-13 09:23:06

43. [20887](http://github.com/cms-sw/cmssw/pull/20887){:target="_blank"}  from **@gpetruc**: Support Comp2RefEqualH DQM quality test also on TProfile `dqm`  created: 2017-10-10 21:12:26 merged: 2017-10-18 07:09:32

44. [20885](http://github.com/cms-sw/cmssw/pull/20885){:target="_blank"}  from **@Dr15Jones**: TableExaminer usage `core`  created: 2017-10-10 20:45:25 merged: 2017-10-11 07:39:12

45. [20883](http://github.com/cms-sw/cmssw/pull/20883){:target="_blank"}  from **@wddgit**: Bug fix. Add 2 overrides to LHESource `core`  `generators`  created: 2017-10-10 19:52:51 merged: 2017-10-13 09:23:19

46. [20878](http://github.com/cms-sw/cmssw/pull/20878){:target="_blank"}  from **@gpetruc**: introduce semi-deterministic smearing for e/gamma objects `analysis`  created: 2017-10-10 14:36:30 merged: 2017-10-12 13:54:15

47. [20876](http://github.com/cms-sw/cmssw/pull/20876){:target="_blank"}  from **@mrodozov**: Fix unused vars warnings in Reco pkgs `reconstruction`  created: 2017-10-10 13:02:21 merged: 2017-10-11 19:37:11

48. [20875](http://github.com/cms-sw/cmssw/pull/20875){:target="_blank"}  from **@mrodozov**: Fix DataFormats/HeavyIonEvent pkg comp warnings after clang-tidy `reconstruction`  created: 2017-10-10 12:39:02 merged: 2017-10-11 07:37:59

49. [20874](http://github.com/cms-sw/cmssw/pull/20874){:target="_blank"}  from **@mrodozov**: Fix Fireworks/* pkgs comp warnings after clang-tidy `visualization`  created: 2017-10-10 12:30:29 merged: 2017-10-11 07:38:12

50. [20872](http://github.com/cms-sw/cmssw/pull/20872){:target="_blank"}  from **@cms-tsg-storm**: HLT V4.0 Mercury (94X) `core`  `hlt`  created: 2017-10-10 09:21:54 merged: 2017-10-20 07:55:40

51. [20871](http://github.com/cms-sw/cmssw/pull/20871){:target="_blank"}  from **@rekovic**: [94X] L1 no hack conditions - cleaned `core`  `dqm`  `l1`  `operations`  created: 2017-10-10 07:55:18 merged: 2017-10-11 07:50:18

52. [20870](http://github.com/cms-sw/cmssw/pull/20870){:target="_blank"}  from **@DryRun**: HCALDQM: fix castorDigis.InputLabel for heavy ion run type `dqm`  created: 2017-10-10 04:02:44 merged: 2017-10-11 07:51:01

53. [20869](http://github.com/cms-sw/cmssw/pull/20869){:target="_blank"}  from **@bcmcms**: Hcal rel val update9 xy v2 `dqm`  created: 2017-10-09 22:32:24 merged: 2017-10-19 10:02:19

54. [20868](http://github.com/cms-sw/cmssw/pull/20868){:target="_blank"}  from **@bsunanda**: Run2-hcx157 Update getGeometry method for HcalGeometry to enable standard access `geometry`  created: 2017-10-09 20:32:36 merged: 2017-10-16 11:19:16

55. [20865](http://github.com/cms-sw/cmssw/pull/20865){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for EgammaAnalysis `analysis`  created: 2017-10-09 16:27:52 merged: 2017-10-10 06:22:52

56. [20864](http://github.com/cms-sw/cmssw/pull/20864){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for ElectroWeakAnalysis `analysis`  created: 2017-10-09 16:27:51 merged: 2017-10-10 06:23:04

57. [20861](http://github.com/cms-sw/cmssw/pull/20861){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for Fireworks `visualization`  created: 2017-10-09 16:26:29 merged: 2017-10-09 18:35:56

58. [20860](http://github.com/cms-sw/cmssw/pull/20860){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for HLTrigger `hlt`  created: 2017-10-09 16:26:28 merged: 2017-10-10 06:23:23

59. [20859](http://github.com/cms-sw/cmssw/pull/20859){:target="_blank"}  from **@rekovic**: [94x] L1T OMTF introduce packer, unpacker, config DQM `dqm`  `l1`  created: 2017-10-09 15:38:09 merged: 2017-10-21 17:09:00

60. [20858](http://github.com/cms-sw/cmssw/pull/20858){:target="_blank"}  from **@perrotta**: Get rid of unused variables in reco particle flow pf tracking `reconstruction`  created: 2017-10-09 15:02:55 merged: 2017-10-12 15:17:36

61. [20857](http://github.com/cms-sw/cmssw/pull/20857){:target="_blank"}  from **@mrodozov**: Fix build errors and comp warnings in L1Trigger/L1TMuonEndCap `l1`  created: 2017-10-09 14:42:34 merged: 2017-10-10 06:26:17

62. [20854](http://github.com/cms-sw/cmssw/pull/20854){:target="_blank"}  from **@mrodozov**: Fix comp warngns in Alignment/CocoaDaq-CocoaFit `alca`  created: 2017-10-09 12:41:03 merged: 2017-10-10 09:08:11

63. [20853](http://github.com/cms-sw/cmssw/pull/20853){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for FastSimulation `fastsim`  created: 2017-10-09 12:28:48 merged: 2017-10-09 19:07:02

64. [20852](http://github.com/cms-sw/cmssw/pull/20852){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for FastSimDataFormats `fastsim`  created: 2017-10-09 12:28:47 merged: 2017-10-09 19:59:32

65. [20851](http://github.com/cms-sw/cmssw/pull/20851){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for EventFilter `daq`  `l1`  `reconstruction`  created: 2017-10-09 12:28:45 merged: 2017-10-10 06:26:31

66. [20850](http://github.com/cms-sw/cmssw/pull/20850){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for RecoPixelVertexing `reconstruction`  created: 2017-10-09 12:28:44 merged: 2017-10-10 06:26:43

67. [20849](http://github.com/cms-sw/cmssw/pull/20849){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for RecoParticleFlow `reconstruction`  created: 2017-10-09 12:28:43 merged: 2017-10-09 19:59:07

68. [20848](http://github.com/cms-sw/cmssw/pull/20848){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for RecoMuon `hlt`  `reconstruction`  created: 2017-10-09 12:28:43 merged: 2017-10-10 06:27:03

69. [20847](http://github.com/cms-sw/cmssw/pull/20847){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for RecoMET `analysis`  `reconstruction`  created: 2017-10-09 12:28:42 merged: 2017-10-09 18:36:13

70. [20846](http://github.com/cms-sw/cmssw/pull/20846){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for RecoLuminosity `reconstruction`  created: 2017-10-09 12:28:41 merged: 2017-10-09 19:05:40

71. [20845](http://github.com/cms-sw/cmssw/pull/20845){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for RecoLocalTracker `reconstruction`  `upgrade`  created: 2017-10-09 12:28:40 merged: 2017-10-09 20:28:10

72. [20844](http://github.com/cms-sw/cmssw/pull/20844){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for RecoLocalMuon `reconstruction`  `upgrade`  created: 2017-10-09 12:28:39 merged: 2017-10-10 06:27:17

73. [20843](http://github.com/cms-sw/cmssw/pull/20843){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for RecoLocalFastTime `reconstruction`  `upgrade`  created: 2017-10-09 12:28:38 merged: 2017-10-09 19:59:19

74. [20842](http://github.com/cms-sw/cmssw/pull/20842){:target="_blank"}  from **@mrodozov**: Fix compilation warnings (ClassDef macro) `alca`  `core`  created: 2017-10-09 10:15:35 merged: 2017-10-09 18:34:24

75. [20841](http://github.com/cms-sw/cmssw/pull/20841){:target="_blank"}  from **@mrodozov**: Fix multiple comp warnings for unused variables `alca`  `db`  `dqm`  `pdmv`  `reconstruction`  created: 2017-10-09 10:01:24 merged: 2017-10-09 19:06:09

76. [20840](http://github.com/cms-sw/cmssw/pull/20840){:target="_blank"}  from **@arizzi**: MiniAOD: use all genParticles for patJets partonFlavour `analysis`  `reconstruction`  created: 2017-10-09 09:07:36 merged: 2017-10-11 11:26:46

77. [20836](http://github.com/cms-sw/cmssw/pull/20836){:target="_blank"}  from **@davidlange6**: fix compilation error in IB ( l1 muon) `l1`  created: 2017-10-09 07:36:59 merged: 2017-10-09 08:48:03

78. [20835](http://github.com/cms-sw/cmssw/pull/20835){:target="_blank"}  from **@wmtford**: Remove unnecessary find()s, commented couts; tidy `dqm`  created: 2017-10-09 02:35:20 merged: 2017-10-11 07:37:47

79. [20834](http://github.com/cms-sw/cmssw/pull/20834){:target="_blank"}  from **@rekovic**: [94x] L1T BMTF introduce packer and small emulator fix `l1`  created: 2017-10-09 01:24:36 merged: 2017-10-23 17:07:59

80. [20832](http://github.com/cms-sw/cmssw/pull/20832){:target="_blank"}  from **@rekovic**: [94x] L1T TwinMux `alca`  `db`  `l1`  `operations`  created: 2017-10-08 23:56:41 merged: 2017-10-20 08:59:15

81. [20831](http://github.com/cms-sw/cmssw/pull/20831){:target="_blank"}  from **@stahlleiton**: OnlineDQM : Tune L1T Muon QTs v3 `dqm`  created: 2017-10-08 23:52:34 merged: 2017-10-11 07:36:41

82. [20830](http://github.com/cms-sw/cmssw/pull/20830){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for RecoLocalCalo `reconstruction`  `upgrade`  created: 2017-10-08 17:25:08 merged: 2017-10-09 07:21:36

83. [20829](http://github.com/cms-sw/cmssw/pull/20829){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for RecoJets `reconstruction`  created: 2017-10-08 17:25:07 merged: 2017-10-09 07:21:18

84. [20828](http://github.com/cms-sw/cmssw/pull/20828){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for RecoHI `reconstruction`  created: 2017-10-08 17:25:06 merged: 2017-10-09 07:21:01

85. [20827](http://github.com/cms-sw/cmssw/pull/20827){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for RecoEgamma `hlt`  `reconstruction`  created: 2017-10-08 17:25:05 merged: 2017-10-09 07:20:46

86. [20826](http://github.com/cms-sw/cmssw/pull/20826){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for RecoEcal `reconstruction`  created: 2017-10-08 17:25:04 merged: 2017-10-09 07:20:23

87. [20825](http://github.com/cms-sw/cmssw/pull/20825){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for RecoCTPPS `reconstruction`  created: 2017-10-08 17:25:03 merged: 2017-10-09 07:20:09

88. [20824](http://github.com/cms-sw/cmssw/pull/20824){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for RecoBTau `reconstruction`  created: 2017-10-08 17:25:02 merged: 2017-10-09 07:19:55

89. [20822](http://github.com/cms-sw/cmssw/pull/20822){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for QCDAnalysis `analysis`  created: 2017-10-08 17:25:00 merged: 2017-10-09 07:19:40

90. [20821](http://github.com/cms-sw/cmssw/pull/20821){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for MuonAnalysis `analysis`  created: 2017-10-08 11:33:15 merged: 2017-10-09 07:19:26

91. [20820](http://github.com/cms-sw/cmssw/pull/20820){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for Mixing `simulation`  created: 2017-10-08 11:33:14 merged: 2017-10-09 07:19:11

92. [20819](http://github.com/cms-sw/cmssw/pull/20819){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for MagneticField `reconstruction`  created: 2017-10-08 11:33:13 merged: 2017-10-09 07:18:57

93. [20818](http://github.com/cms-sw/cmssw/pull/20818){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for L1TriggerOffline `l1`  created: 2017-10-08 11:33:13 merged: 2017-10-09 07:18:43

94. [20814](http://github.com/cms-sw/cmssw/pull/20814){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for IgTools `analysis`  `core`  created: 2017-10-07 18:48:23 merged: 2017-10-08 07:31:14

95. [20813](http://github.com/cms-sw/cmssw/pull/20813){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for IORawData `alca`  `analysis`  created: 2017-10-07 18:48:22 merged: 2017-10-08 07:30:56

96. [20812](http://github.com/cms-sw/cmssw/pull/20812){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for IOPool `analysis`  `core`  created: 2017-10-07 18:48:21 merged: 2017-10-08 07:30:36

97. [20811](http://github.com/cms-sw/cmssw/pull/20811){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for IOMC `analysis`  `core`  `generators`  `simulation`  created: 2017-10-07 18:48:20 merged: 2017-10-08 07:30:15

98. [20810](http://github.com/cms-sw/cmssw/pull/20810){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for HiggsAnalysis `analysis`  created: 2017-10-07 18:48:19 merged: 2017-10-08 07:29:54

99. [20808](http://github.com/cms-sw/cmssw/pull/20808){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for HLTriggerOffline `analysis`  `dqm`  created: 2017-10-07 18:48:17 merged: 2017-10-08 07:29:34

100. [20807](http://github.com/cms-sw/cmssw/pull/20807){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for RecoVertex `alca`  `reconstruction`  created: 2017-10-07 17:23:50 merged: 2017-10-08 07:29:07

101. [20806](http://github.com/cms-sw/cmssw/pull/20806){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for RecoVZero `reconstruction`  created: 2017-10-07 17:23:49 merged: 2017-10-08 07:28:44

102. [20805](http://github.com/cms-sw/cmssw/pull/20805){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for RecoTracker `reconstruction`  created: 2017-10-07 17:23:48 merged: 2017-10-08 07:28:30

103. [20804](http://github.com/cms-sw/cmssw/pull/20804){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for RecoTauTag `hlt`  `reconstruction`  created: 2017-10-07 17:23:47 merged: 2017-10-08 07:27:49

104. [20803](http://github.com/cms-sw/cmssw/pull/20803){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for RecoTBCalo `reconstruction`  created: 2017-10-07 17:23:46 merged: 2017-10-08 07:27:04

105. [20802](http://github.com/cms-sw/cmssw/pull/20802){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for RecoRomanPot `reconstruction`  created: 2017-10-07 17:23:45 merged: 2017-10-08 07:26:49

106. [20800](http://github.com/cms-sw/cmssw/pull/20800){:target="_blank"}  from **@davidlange6**: fix directory comparison in relmon tool `reconstruction`  created: 2017-10-07 15:29:23 merged: 2017-10-07 18:42:51

107. [20799](http://github.com/cms-sw/cmssw/pull/20799){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for SUSYBSMAnalysis `analysis`  created: 2017-10-07 14:50:07 merged: 2017-10-08 07:26:35

108. [20798](http://github.com/cms-sw/cmssw/pull/20798){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for TBDataFormats `analysis`  created: 2017-10-07 14:50:06 merged: 2017-10-08 18:30:56

109. [20797](http://github.com/cms-sw/cmssw/pull/20797){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for SimTransport `simulation`  created: 2017-10-07 14:50:05 merged: 2017-10-07 20:33:09

110. [20795](http://github.com/cms-sw/cmssw/pull/20795){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for Utilities `core`  created: 2017-10-07 12:12:24 merged: 2017-10-07 17:17:38

111. [20793](http://github.com/cms-sw/cmssw/pull/20793){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for TrackingTools `reconstruction`  created: 2017-10-07 12:12:22 merged: 2017-10-08 18:31:53

112. [20792](http://github.com/cms-sw/cmssw/pull/20792){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for TrackPropagation `reconstruction`  `simulation`  created: 2017-10-07 12:12:21 merged: 2017-10-07 17:18:09

113. [20791](http://github.com/cms-sw/cmssw/pull/20791){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for TopQuarkAnalysis `analysis`  created: 2017-10-07 12:12:20 merged: 2017-10-07 17:18:53

114. [20790](http://github.com/cms-sw/cmssw/pull/20790){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for TauAnalysis `analysis`  `simulation`  created: 2017-10-07 12:12:19 merged: 2017-10-07 17:18:29

115. [20789](http://github.com/cms-sw/cmssw/pull/20789){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for DataFormats `alca`  `analysis`  `core`  `daq`  `generators`  `hlt`  `l1`  `reconstruction`  `simulation`  `upgrade`  created: 2017-10-07 08:01:35 merged: 2017-10-09 12:41:02

116. [20788](http://github.com/cms-sw/cmssw/pull/20788){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for DQMServices `dqm`  created: 2017-10-07 08:01:34 merged: 2017-10-07 13:03:11

117. [20787](http://github.com/cms-sw/cmssw/pull/20787){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for DQMOffline `dqm`  `l1`  created: 2017-10-07 08:01:33 merged: 2017-10-07 16:02:09

118. [20786](http://github.com/cms-sw/cmssw/pull/20786){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for DQM `dqm`  `hlt`  created: 2017-10-07 08:01:32 merged: 2017-10-07 13:35:45

119. [20785](http://github.com/cms-sw/cmssw/pull/20785){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for DPGAnalysis `analysis`  `pdmv`  created: 2017-10-07 08:01:31 merged: 2017-10-07 13:35:07

120. [20784](http://github.com/cms-sw/cmssw/pull/20784){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for Configuration `pdmv`  created: 2017-10-07 08:01:30 merged: 2017-10-07 13:02:29

121. [20783](http://github.com/cms-sw/cmssw/pull/20783){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for CondTools `alca`  `db`  `dqm`  `hlt`  `l1`  created: 2017-10-07 08:01:29 merged: 2017-10-07 13:30:39

122. [20782](http://github.com/cms-sw/cmssw/pull/20782){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for CondFormats `alca`  `analysis`  `db`  `l1`  created: 2017-10-07 08:01:28 merged: 2017-10-07 16:01:48

123. [20781](http://github.com/cms-sw/cmssw/pull/20781){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for CondCore `alca`  `db`  created: 2017-10-07 08:01:27 merged: 2017-10-07 13:02:03

124. [20780](http://github.com/cms-sw/cmssw/pull/20780){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for CommonTools `analysis`  `reconstruction`  created: 2017-10-07 08:01:27 merged: 2017-10-07 16:01:29

125. [20779](http://github.com/cms-sw/cmssw/pull/20779){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for CaloOnlineTools `alca`  `db`  created: 2017-10-07 08:01:26 merged: 2017-10-07 13:01:50

126. [20778](http://github.com/cms-sw/cmssw/pull/20778){:target="_blank"}  from **@davidlange6**: Clang-tidy checks for Calibration `alca`  created: 2017-10-07 08:01:25 merged: 2017-10-07 13:00:51

127. [20777](http://github.com/cms-sw/cmssw/pull/20777){:target="_blank"}  from **@heller3**: Adjust jet eta threshold for offline HT calculation in SUSY Lep+HT trigger DQM module `dqm`  created: 2017-10-06 23:40:21 merged: 2017-10-10 14:32:33

128. [20776](http://github.com/cms-sw/cmssw/pull/20776){:target="_blank"}  from **@bsunanda**: Run2-alca100 Update IsoTrack calibration system to deal with only L1 trigger (no HLT) `alca`  created: 2017-10-06 21:09:50 merged: 2017-10-16 10:59:27

129. [20775](http://github.com/cms-sw/cmssw/pull/20775){:target="_blank"}  from **@jkarancs**: 94X Update phase1 pixel thresholds `simulation`  created: 2017-10-06 16:18:01 merged: 2017-10-09 18:34:09

130. [20774](http://github.com/cms-sw/cmssw/pull/20774){:target="_blank"}  from **@gartung**: FWCore/ParameterSet: Replace Exception in MassSearchReplaceAnyInputTagVisitor.enter() `core`  created: 2017-10-06 15:52:01 merged: 2017-10-07 13:04:58

131. [20773](http://github.com/cms-sw/cmssw/pull/20773){:target="_blank"}  from **@drkovalskyi**: Muon simhit matching `analysis`  `operations`  `pdmv`  `reconstruction`  `simulation`  `upgrade`  created: 2017-10-06 13:55:29 merged: 2017-10-24 06:29:01

132. [20771](http://github.com/cms-sw/cmssw/pull/20771){:target="_blank"}  from **@Sam-Harper**: Disabling high pt trained regression except for saturated E/gammas `reconstruction`  created: 2017-10-06 13:11:45 merged: 2017-10-13 16:16:31

133. [20769](http://github.com/cms-sw/cmssw/pull/20769){:target="_blank"}  from **@mrodozov**: Fix compilation warnings in CalibCalorimetry pkg `alca`  created: 2017-10-06 12:30:36 merged: 2017-10-07 08:05:59

134. [20767](http://github.com/cms-sw/cmssw/pull/20767){:target="_blank"}  from @mtosi: fix TRKDQM **@HLT** `dqm`  `hlt`  created: 2017-10-06 12:00:49 merged: 2017-10-12 13:54:39

135. [20764](http://github.com/cms-sw/cmssw/pull/20764){:target="_blank"}  from **@davidlange6**: remove some divide by 0s and extend blacklist of histograms `dqm`  `reconstruction`  created: 2017-10-06 09:00:12 merged: 2017-10-06 13:58:33

136. [20763](http://github.com/cms-sw/cmssw/pull/20763){:target="_blank"}  from **@smuzaffar**: use ClassDefOverride instead of ClassDef to avoid inconsistent-missing-override warning `core`  created: 2017-10-06 05:14:57 merged: 2017-10-08 18:34:16

137. [20762](http://github.com/cms-sw/cmssw/pull/20762){:target="_blank"}  from **@cms-sw**: Alignment/CocoaFit: use ClassDefOverride to avoid inconsistent-missing-override warning `alca`  created: 2017-10-06 05:05:17 merged: 2017-10-06 10:46:24

138. [20761](http://github.com/cms-sw/cmssw/pull/20761){:target="_blank"}  from **@cms-sw**: Alignment: use ClassDefOverride instead of ClassDef to avoid inconsistent-missing-override warning `alca`  created: 2017-10-06 05:01:47 merged: 2017-10-06 12:45:44

139. [20759](http://github.com/cms-sw/cmssw/pull/20759){:target="_blank"}  from **@bsunanda**: Run2-hcx156 Fix bugs for first layer; active length computation `geometry`  created: 2017-10-05 20:43:52 merged: 2017-10-11 07:31:07

140. [20758](http://github.com/cms-sw/cmssw/pull/20758){:target="_blank"}  from **@arunhep**: GT Updates with inclusion of RPCLink Maps for L1T, HCAL Pedestals and widths, StripBadChannel for MCV2 `alca`  created: 2017-10-05 20:25:20 merged: 2017-10-11 07:53:35

141. [20757](http://github.com/cms-sw/cmssw/pull/20757){:target="_blank"}  from **@davidlange6**: clang-tidy checks for CalibTracker subsystem `alca`  created: 2017-10-05 15:42:20 merged: 2017-10-06 07:28:22

142. [20756](http://github.com/cms-sw/cmssw/pull/20756){:target="_blank"}  from **@davidlange6**: clang checks for CalibMuon subsystem `alca`  created: 2017-10-05 15:42:08 merged: 2017-10-06 07:38:48

143. [20755](http://github.com/cms-sw/cmssw/pull/20755){:target="_blank"}  from **@davidlange6**: clang-tidy checks for CalibCalorimetry subsystem `alca`  `l1`  created: 2017-10-05 14:32:33 merged: 2017-10-06 07:38:34

144. [20754](http://github.com/cms-sw/cmssw/pull/20754){:target="_blank"}  from **@davidlange6**: clang check CalibFormats `alca`  created: 2017-10-05 14:31:59 merged: 2017-10-06 07:29:13

145. [20753](http://github.com/cms-sw/cmssw/pull/20753){:target="_blank"}  from **@davidlange6**: clang-tidy checks for Alignment subsystem `alca`  created: 2017-10-05 13:54:13 merged: 2017-10-05 20:23:16

146. [20752](http://github.com/cms-sw/cmssw/pull/20752){:target="_blank"}  from **@davidlange6**: clang-tidy checks for AnalysisDataFormats subsystem `analysis`  created: 2017-10-05 13:54:04 merged: 2017-10-05 19:42:52

147. [20751](http://github.com/cms-sw/cmssw/pull/20751){:target="_blank"}  from **@davidlange6**: clang-tidy checks for AnalysisAlgos subsystem `analysis`  created: 2017-10-05 13:53:20 merged: 2017-10-05 19:42:32

148. [20750](http://github.com/cms-sw/cmssw/pull/20750){:target="_blank"}  from **@davidlange6**: clang-tidy check for FWCore `core`  created: 2017-10-05 12:51:16 merged: 2017-10-05 19:42:20

149. [20749](http://github.com/cms-sw/cmssw/pull/20749){:target="_blank"}  from **@mandrenguyen**: XeXe collision era and relval workflow `alca`  `analysis`  `dqm`  `generators`  `operations`  `pdmv`  `reconstruction`  `simulation`  `upgrade`  created: 2017-10-05 12:20:28 merged: 2017-10-09 07:42:00

150. [20748](http://github.com/cms-sw/cmssw/pull/20748){:target="_blank"}  from **@mrodozov**: Fix comp warnings from DataFormats HcalDigi `simulation`  created: 2017-10-05 09:11:58 merged: 2017-10-05 19:43:49

151. [20747](http://github.com/cms-sw/cmssw/pull/20747){:target="_blank"}  from **@alberto-sanchez**: updating relval which uses evtgen `generators`  created: 2017-10-04 17:30:38 merged: 2017-10-10 09:48:26

152. [20743](http://github.com/cms-sw/cmssw/pull/20743){:target="_blank"}  from **@ashtipliyski**: Fix typo in handling exclusion of CALOL2 in online DQM `dqm`  created: 2017-10-04 15:31:32 merged: 2017-10-07 13:38:14

153. [20742](http://github.com/cms-sw/cmssw/pull/20742){:target="_blank"}  from **@mrodozov**: Fix xerces xmlparser issue in aarch64 unique_ptr related sigsegv `geometry`  created: 2017-10-04 14:43:30 merged: 2017-10-05 10:35:11

154. [20741](http://github.com/cms-sw/cmssw/pull/20741){:target="_blank"}  from **@ahinzmann**: Protect against missing track info in MiniAOD `reconstruction`  created: 2017-10-04 13:51:21 merged: 2017-10-12 15:18:42

155. [20739](http://github.com/cms-sw/cmssw/pull/20739){:target="_blank"}  from **@cms-tsg-storm**: add HLTScouting event content `hlt`  created: 2017-10-04 13:10:54 merged: 2017-10-23 15:42:58

156. [20736](http://github.com/cms-sw/cmssw/pull/20736){:target="_blank"}  from **@arunhep**: Update of wf1010.0 and run2_data_relval key `alca`  `pdmv`  `upgrade`  created: 2017-10-04 06:31:56 merged: 2017-10-05 07:45:23

157. [20734](http://github.com/cms-sw/cmssw/pull/20734){:target="_blank"}  from **@alberto-sanchez**: fixing typo in tmp filename `generators`  created: 2017-10-03 23:20:50 merged: 2017-10-05 07:45:58

158. [20733](http://github.com/cms-sw/cmssw/pull/20733){:target="_blank"}  from **@mkirsano**: Code to turn on VINCIA plugin version 2 `generators`  created: 2017-10-03 18:16:27 merged: 2017-10-16 11:13:52

159. [20732](http://github.com/cms-sw/cmssw/pull/20732){:target="_blank"}  from **@jfernan2**: DTDQM change to monitor ZS data `dqm`  created: 2017-10-03 17:51:53 merged: 2017-10-05 07:46:57

160. [20731](http://github.com/cms-sw/cmssw/pull/20731){:target="_blank"}  from **@lfinco**: New Hgg low-mass HLT path added to DQM  `dqm`  created: 2017-10-03 16:01:02 merged: 2017-10-11 11:25:36

161. [20730](http://github.com/cms-sw/cmssw/pull/20730){:target="_blank"}  from **@Dr15Jones**: Work around inconsistency in ExternalLHEProducer `core`  `generators`  created: 2017-10-03 14:59:16 merged: 2017-10-04 07:11:39

162. [20729](http://github.com/cms-sw/cmssw/pull/20729){:target="_blank"}  from **@lunik1**: Update quality test limits `dqm`  created: 2017-10-03 13:02:24 merged: 2017-10-05 07:47:33

163. [20727](http://github.com/cms-sw/cmssw/pull/20727){:target="_blank"}  from **@cms-sw**: Fix compiler warning: Removed unused variable `reconstruction`  created: 2017-10-03 10:06:03 merged: 2017-10-03 18:09:06

164. [20726](http://github.com/cms-sw/cmssw/pull/20726){:target="_blank"}  from **@mtosi**: FastTimerServiceClient bug fix `hlt`  created: 2017-10-03 08:58:55 merged: 2017-10-05 08:10:58

165. [20723](http://github.com/cms-sw/cmssw/pull/20723){:target="_blank"}  from **@battibass**: [94X] Make muon HLT (L3/TkMu) work in phaseII scenarios `reconstruction`  `upgrade`  created: 2017-10-02 21:38:15 merged: 2017-10-09 19:07:46

166. [20717](http://github.com/cms-sw/cmssw/pull/20717){:target="_blank"}  from **@fioriNTU**: tuning of Strip QTest for higher PU/track-density `dqm`  created: 2017-10-02 15:45:47 merged: 2017-10-03 18:09:38

167. [20711](http://github.com/cms-sw/cmssw/pull/20711){:target="_blank"}  from **@ggovi**: Fixes for Conddb copy command `db`  created: 2017-10-02 08:12:14 merged: 2017-10-06 07:06:38

168. [20710](http://github.com/cms-sw/cmssw/pull/20710){:target="_blank"}  from **@wmtford**: Trk hit assoc log debug `simulation`  created: 2017-10-02 04:27:27 merged: 2017-10-04 07:15:44

169. [20705](http://github.com/cms-sw/cmssw/pull/20705){:target="_blank"}  from **@drkovalskyi**: Extract timing for tracker-only muons `reconstruction`  created: 2017-10-01 09:11:57 merged: 2017-10-06 08:51:12

170. [20702](http://github.com/cms-sw/cmssw/pull/20702){:target="_blank"}  from **@osschar**: Enable usage of TTreeCache in Fireworks `core`  `visualization`  created: 2017-09-29 22:40:14 merged: 2017-10-05 07:50:43

171. [20699](http://github.com/cms-sw/cmssw/pull/20699){:target="_blank"}  from **@fabozzi**: Update to 2017 data relvals `pdmv`  `upgrade`  created: 2017-09-29 15:01:10 merged: 2017-10-03 14:16:30

172. [20693](http://github.com/cms-sw/cmssw/pull/20693){:target="_blank"}  from **@rvenditti**: Update to the ZMuSkim `pdmv`  created: 2017-09-28 16:07:30 merged: 2017-10-10 11:09:57

173. [20691](http://github.com/cms-sw/cmssw/pull/20691){:target="_blank"}  from **@fabozzi**: Update of data re-miniAOD workflows `pdmv`  `upgrade`  created: 2017-09-28 15:40:46 merged: 2017-10-03 18:15:02

174. [20685](http://github.com/cms-sw/cmssw/pull/20685){:target="_blank"}  from **@antoniovagnerini**: updating trigger names in MssmHbbMonitoring and MssmHbbBtagTriggerMon `dqm`  created: 2017-09-28 09:31:20 merged: 2017-10-03 18:15:42

175. [20680](http://github.com/cms-sw/cmssw/pull/20680){:target="_blank"}  from **@davidcarbonis**: Phase1 pixel validation cluster loop fix `dqm`  created: 2017-09-27 19:52:42 merged: 2017-10-03 18:17:11

176. [20672](http://github.com/cms-sw/cmssw/pull/20672){:target="_blank"}  from **@tstreble**: New Candidate+Point seeded tracking region producer for Tau HLT tracking `hlt`  `reconstruction`  created: 2017-09-27 16:10:22 merged: 2017-10-06 12:47:27

177. [20668](http://github.com/cms-sw/cmssw/pull/20668){:target="_blank"}  from **@mrodozov**: Fix un-init member warnings in DataFormats/SiStripCluster `reconstruction`  created: 2017-09-27 14:07:38 merged: 2017-10-06 07:07:08

178. [20655](http://github.com/cms-sw/cmssw/pull/20655){:target="_blank"}  from **@cms-met**: Adding chsMET and trackMET to miniAOD `analysis`  `reconstruction`  created: 2017-09-26 14:17:15 merged: 2017-10-17 07:08:44

179. [20651](http://github.com/cms-sw/cmssw/pull/20651){:target="_blank"}  from **@capalmer85**: add LumiCorrections records and definitions; adding LumiInfo.h members/methods `alca`  `db`  `reconstruction`  created: 2017-09-25 18:46:01 merged: 2017-10-17 15:49:55

180. [20649](http://github.com/cms-sw/cmssw/pull/20649){:target="_blank"}  from **@astakia**: L1T Muon Offline DQM - Resolution plots & bug fixes `dqm`  `l1`  created: 2017-09-25 16:22:42 merged: 2017-10-20 07:55:21

181. [20643](http://github.com/cms-sw/cmssw/pull/20643){:target="_blank"}  from **@mmusich**: [94X] more Strip conditions supported by Payload Inspector `db`  created: 2017-09-25 09:20:38 merged: 2017-10-16 10:45:30

182. [20642](http://github.com/cms-sw/cmssw/pull/20642){:target="_blank"}  from **@CTPPS**: CTPPS pixel clusterizer: patch in gain calibration call `reconstruction`  created: 2017-09-24 17:21:10 merged: 2017-10-06 08:51:51

183. [20638](http://github.com/cms-sw/cmssw/pull/20638){:target="_blank"}  from **@rappoccio**: Updates to MiniAOD to satisfy JME/SMP/B2G requests for NanoAOD `analysis`  `dqm`  `generators`  `reconstruction`  created: 2017-09-23 21:06:32 merged: 2017-10-05 19:48:57

184. [20635](http://github.com/cms-sw/cmssw/pull/20635){:target="_blank"}  from **@gkaratha**: dqm for triplemuon_5_3_3_dz in master br. `dqm`  created: 2017-09-23 10:46:18 merged: 2017-10-10 06:27:30

185. [20626](http://github.com/cms-sw/cmssw/pull/20626){:target="_blank"}  from **@cms-nanoAOD**: NanoAOD prototype [RFC] `analysis`  `operations`  `reconstruction`  created: 2017-09-22 11:53:03 merged: 2017-10-11 19:37:41

186. [20612](http://github.com/cms-sw/cmssw/pull/20612){:target="_blank"}  from **@drkovalskyi**: Standard muon selectors `analysis`  `reconstruction`  created: 2017-09-21 11:19:39 merged: 2017-10-08 07:53:08

187. [20608](http://github.com/cms-sw/cmssw/pull/20608){:target="_blank"}  from **@bsunanda**: Run2-alca99 Modify all macros used to calibrate Hcal using IsoTracks `alca`  created: 2017-09-20 14:46:09 merged: 2017-10-04 08:26:10

188. [20599](http://github.com/cms-sw/cmssw/pull/20599){:target="_blank"}  from **@depasse**: Upgrade of Ecal and Creation of Preshower Payload Inspector with Plot `db`  created: 2017-09-20 07:15:37 merged: 2017-10-16 10:45:15

189. [20584](http://github.com/cms-sw/cmssw/pull/20584){:target="_blank"}  from **@gkaratha**: dqm for DoubleMu3_DCA_PFMET50_PFMHT60 `dqm`  created: 2017-09-19 14:46:31 merged: 2017-10-10 06:27:42

190. [20567](http://github.com/cms-sw/cmssw/pull/20567){:target="_blank"}  from **@akhatiwa**: Added single module occupancy plots for on track digis and charge Vs  `dqm`  created: 2017-09-18 18:02:40 merged: 2017-10-04 13:37:45

191. [20552](http://github.com/cms-sw/cmssw/pull/20552){:target="_blank"}  from **@bsunanda**: Run2-alca96 Add propagation tool from Hcal to Ecal `alca`  created: 2017-09-17 22:49:37 merged: 2017-10-11 07:37:08

192. [20550](http://github.com/cms-sw/cmssw/pull/20550){:target="_blank"}  from **@Sam-Harper**: electron track isolation producer improvements + reading saturation info from the electron in HEEP V7.0 `reconstruction`  created: 2017-09-17 15:58:00 merged: 2017-10-05 07:58:15

193. [20523](http://github.com/cms-sw/cmssw/pull/20523){:target="_blank"}  from **@bsunanda**: Run2-hcx155 Correct access to HcalGeometry from TauDiscriminationAgainstCaloMuon `reconstruction`  created: 2017-09-14 21:07:45 merged: 2017-10-13 16:18:08

194. [20413](http://github.com/cms-sw/cmssw/pull/20413){:target="_blank"}  from **@popovvp**: CTPPS Pixel DQM add clusters `dqm`  created: 2017-09-07 11:17:50 merged: 2017-10-13 09:32:16

195. [20410](http://github.com/cms-sw/cmssw/pull/20410){:target="_blank"}  from **@bsunanda**: Run2-hcx149 Bug fix for HcalNoiseAlgo and update for HcalHaloAlgo to make C11 compliant `reconstruction`  created: 2017-09-06 22:09:55 merged: 2017-10-10 07:50:12

196. [20286](http://github.com/cms-sw/cmssw/pull/20286){:target="_blank"}  from **@abrinke1**: EMTF 2017 PR #6 - Emulator `alca`  `db`  `dqm`  `l1`  created: 2017-08-28 16:14:08 merged: 2017-10-08 18:42:13

197. [20189](http://github.com/cms-sw/cmssw/pull/20189){:target="_blank"}  from **@Dr15Jones**: LogErrorHarvester depends on  EDProducers `core`  `operations`  `reconstruction`  created: 2017-08-16 17:56:40 merged: 2017-10-14 13:05:20

198. [20000](http://github.com/cms-sw/cmssw/pull/20000){:target="_blank"}  from **@nsmith-**: Modify CaloLayer1 emulator to properly handle saturation in all cases `l1`  created: 2017-08-01 15:30:06 merged: 2017-10-05 08:23:11

199. [19699](http://github.com/cms-sw/cmssw/pull/19699){:target="_blank"}  from **@sushilchauhan**: added hep17 folder, 2d eff plots for egammaHLT DQM and Validation `dqm`  created: 2017-07-12 08:27:54 merged: 2017-10-17 07:19:58

200. [19253](http://github.com/cms-sw/cmssw/pull/19253){:target="_blank"}  from **@chenxvan**: Added scripts to produce Pixel Maps and the Cluster Noise and Size for Strip Maps `dqm`  `reconstruction`  created: 2017-06-15 16:41:29 merged: 2017-10-07 13:32:43

#### CMSDIST Changes between Tags REL/CMSSW_9_4_0_pre2/slc6_amd64_gcc630 and REL/CMSSW_9_4_0_pre3/slc6_amd64_gcc630:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_9_4_0_pre2/slc6_amd64_gcc630...REL/CMSSW_9_4_0_pre3/slc6_amd64_gcc630)



1. [3507](http://github.com/cms-sw/cmsdist/pull/3507){:target="_blank"}  from **@cms-sw**: Update tensorflow-sources.spec created: 2017-10-18 07:40:34 merged: 2017-10-18 12:34:13

2. [3502](http://github.com/cms-sw/cmsdist/pull/3502){:target="_blank"}  from **@cms-sw**: Update root to latest commits from v6-10 patches created: 2017-10-17 10:38:08 merged: 2017-10-18 15:15:15

3. [3501](http://github.com/cms-sw/cmsdist/pull/3501){:target="_blank"}  from **@civanch**: Fixed decay channels or K0 and antiK0 created: 2017-10-16 15:49:34 merged: 2017-10-17 09:53:25

4. [3492](http://github.com/cms-sw/cmsdist/pull/3492){:target="_blank"}  from **@mrodozov**: Update Theano version to 0.9.0 created: 2017-10-12 16:35:02 merged: 2017-10-12 19:36:17

5. [3489](http://github.com/cms-sw/cmsdist/pull/3489){:target="_blank"}  from **@cms-sw**: Updating RecoBTag-Combined to tag V01-00-07 created: 2017-10-10 14:09:00 merged: 2017-10-11 09:45:51

6. [3485](http://github.com/cms-sw/cmsdist/pull/3485){:target="_blank"}  from **@cms-sw**: Update root to latest commits from v6-10 patches created: 2017-10-05 15:53:30 merged: 2017-10-07 07:52:13

7. [3484](http://github.com/cms-sw/cmsdist/pull/3484){:target="_blank"}  from **@fwyzard**: do not include CUDA drivers in the external created: 2017-10-04 16:07:33 merged: 2017-10-12 19:29:10

8. [3480](http://github.com/cms-sw/cmsdist/pull/3480){:target="_blank"}  from **@mkirsano**: upgrade vincia to 2.2.00 created: 2017-10-03 17:49:38 merged: 2017-10-16 11:13:39

9. [3475](http://github.com/cms-sw/cmsdist/pull/3475){:target="_blank"}  from **@fwyzard**: update Intel VTune to version 2017.3.0.510739 created: 2017-10-03 13:43:29 merged: 2017-10-03 19:40:07

10. [3474](http://github.com/cms-sw/cmsdist/pull/3474){:target="_blank"}  from **@fwyzard**: include libcudart_static.a in the distribution created: 2017-10-03 12:44:22 merged: 2017-10-03 19:41:39

11. [3434](http://github.com/cms-sw/cmsdist/pull/3434){:target="_blank"}  from **@gudrutis**: updating vdt to v0.3.9 created: 2017-09-20 12:51:19 merged: 2017-10-17 09:37:10

12. [3407](http://github.com/cms-sw/cmsdist/pull/3407){:target="_blank"}  from **@cms-sw**: Update data-L1Trigger-L1TMuon.spec created: 2017-09-12 22:27:38 merged: 2017-10-08 18:43:23
